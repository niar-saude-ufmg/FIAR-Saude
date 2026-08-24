# Avaliação de Transparência

A dimensão de **Transparência** do FIAR-Saúde avalia se informações relevantes sobre a Tarefa de IA, seu funcionamento, suas limitações e seus resultados podem ser compreendidas pelos públicos pertinentes ao seu Contexto de Uso.

Em saúde, diferentes públicos podem necessitar de diferentes níveis de informação, incluindo equipes técnicas, gestores, profissionais de saúde, instâncias de governança e, quando aplicável, pessoas afetadas pelo uso do sistema.

A Transparência não se limita à explicabilidade algorítmica. Ela envolve documentação adequada da tarefa, comunicação de finalidade e limitações, compreensão do comportamento do modelo e, quando necessário, mecanismos de explicação compatíveis com o tipo de sistema e com o público relevante.

A dimensão está alinhada a referências internacionais de IA Responsável, incluindo os princípios da OECD e recomendações da Organização Mundial da Saúde para IA em saúde.

---

## Objetivo da dimensão

A avaliação de Transparência busca verificar se o projeto:

- documenta a finalidade, o escopo e o contexto de uso da tarefa;
- descreve adequadamente os dados, o modelo e os procedimentos relevantes;
- comunica limitações, pressupostos e condições de uso;
- disponibiliza informações suficientes para revisão técnica e institucional;
- utiliza mecanismos de explicabilidade quando necessários e adequados à tarefa;
- adapta a comunicação aos públicos relevantes;
- documenta as limitações dos próprios métodos de explicação.

---

## Componentes da Transparência

A avaliação considera diferentes níveis de explicabilidade como evidência da dimensão de transparência.

### Transparência técnica

Refere-se à disponibilidade de informações suficientes para compreender e revisar tecnicamente a tarefa, incluindo, quando aplicável:

- arquitetura ou classe do modelo;
- variáveis ou tipos de entradas utilizados;
- origem e preparação dos dados;
- procedimentos de treinamento e validação;
- métricas utilizadas;
- pressupostos relevantes;
- limitações conhecidas;
- versões dos artefatos e componentes.

### Explicabilidade do comportamento

Refere-se à utilização de métodos que auxiliem na compreensão do comportamento do modelo quando isso for necessário e adequado à tarefa.

Pode incluir:

- importância de variáveis;
- análise de sensibilidade;
- métodos de atribuição;
- explicações globais;
- explicações locais;
- visualizações do comportamento do modelo;
- outros métodos apropriados ao tipo de modelo e uso.

Nem toda tarefa exige explicações locais ou métodos pós-hoc. A necessidade deve ser determinada pelo contexto de uso, pela natureza do modelo e pelas decisões que seus resultados apoiam.

### Transparência para públicos relevantes

Refere-se à comunicação de informações em forma adequada aos diferentes públicos envolvidos.

Pode incluir:

- gestores;
- profissionais de saúde;
- equipes técnicas;
- instâncias de governança;
- usuários do sistema;
- pessoas ou grupos afetados, quando aplicável.

O nível e a forma da explicação devem ser compatíveis com as necessidades do público, sem pressupor que uma única forma de comunicação seja adequada para todos.


---

## Métodos de explicação

Quando mecanismos de explicabilidade forem necessários, diferentes métodos podem ser utilizados de acordo com a natureza da tarefa e do modelo.

Exemplos incluem:

- análise de importância de variáveis;
- métodos de explicabilidade pós-hoc;
- explicações globais ou locais;
- visualizações do comportamento do modelo;
- análise de sensibilidade;
- métodos específicos para arquiteturas ou modalidades de dados.

O FIAR-Saúde não prescreve um método específico de explicabilidade.

A avaliação verifica:

- por que o método foi escolhido;
- se ele é adequado ao modelo e à questão analisada;
- se sua aplicação está documentada;
- se suas limitações são reconhecidas;
- se as conclusões produzidas são compatíveis com o que o método realmente permite inferir.

---

## Riscos associados

Limitações de Transparência podem contribuir para riscos como:

- dificuldade de revisão técnica ou institucional;
- interpretação inadequada dos resultados;
- uso da tarefa fora das condições previstas;
- desconhecimento de limitações relevantes;
- dificuldade de reconstruir justificativas técnicas;
- comunicação inadequada de capacidades ou limitações;
- impossibilidade de compreender fatores relevantes para decisões apoiadas pelo sistema, quando essa compreensão for necessária.

---

## Evidências esperadas

Dependendo da tarefa e do contexto de uso, podem constituir evidências relevantes:

- Model Card ou documentação equivalente;
- Data Card ou documentação relacionada aos dados;
- documentação técnica do modelo e do pipeline;
- descrição da finalidade e do contexto de uso;
- registros de limitações e condições de uso;
- Explainability Report ou documentação equivalente;
- justificativa para escolha de métodos de explicabilidade;
- resultados de análises globais ou locais, quando aplicáveis;
- documentação das limitações das explicações;
- materiais destinados a usuários ou gestores;
- Registro de Decisão Técnica;
- documentação de mudanças relevantes entre versões.

A ausência de um método específico de explicabilidade não implica automaticamente Não Conformidade. Deve-se primeiro determinar se esse mecanismo é necessário para a tarefa e para o contexto avaliado.

---

## Requisitos e mecanismos de verificação

| ID | Requisito ou questão de avaliação | Exemplos de evidências | Mecanismos de verificação |
|---|---|---|---|
| TRA-01 | A finalidade, o escopo e o contexto de uso da tarefa estão documentados de forma clara e consistente? | Formulário de Entrada, Identificação da Avaliação, Model Card | Verificação documental; consistência cruzada |
| TRA-02 | Os dados, modelo, procedimentos e resultados relevantes estão documentados em nível suficiente para revisão técnica? | Data Card, Model Card, documentação técnica | Verificação documental; análise de suficiência |
| TRA-03 | Limitações, pressupostos e condições de uso estão explicitamente documentados? | Model Card, Data Card, registros técnicos | Verificação documental; consistência cruzada |
| TRA-04 | O projeto justificou a necessidade ou não de mecanismos de explicabilidade para a tarefa? | Model Card, Explainability Report, Registro de Decisão Técnica | Revisão documental; contextualização |
| TRA-05 | Quando aplicados, os métodos de explicabilidade são adequados ao modelo, à tarefa e à questão analisada? | Explainability Report, documentação metodológica | Revisão metodológica |
| TRA-06 | As conclusões derivadas das explicações respeitam as limitações dos métodos utilizados? | Explainability Report, resultados técnicos | Revisão metodológica; consistência |
| TRA-07 | As limitações dos mecanismos de explicabilidade estão documentadas? | Explainability Report, Model Card | Verificação documental |
| TRA-08 | As informações relevantes são comunicadas em nível adequado aos públicos envolvidos? | documentação de uso, materiais de comunicação, interface, relatórios | Verificação documental; contextualização |
| TRA-09 | Há consistência entre o que a documentação declara sobre o sistema e o comportamento evidenciado pelas análises técnicas? | Model Card, Explainability Report, resultados experimentais | Consistência cruzada |
| TRA-10 | Mudanças relevantes na tarefa e em suas explicações são rastreáveis entre versões, quando aplicável? | histórico de versões, Model Card, Explainability Report | Verificação de rastreabilidade e versionamento |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** existe informação adequada para compreender o aspecto avaliado?
- **Consistência:** as descrições, explicações e resultados são coerentes entre os diferentes artefatos?
- **Rastreabilidade:** é possível relacionar as informações e explicações à Tarefa, à Versão Avaliável e aos resultados correspondentes?
- **Contextualização:** o nível e a forma de transparência são adequados ao Contexto de Uso e aos públicos relevantes?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Transparência produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Transparência não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.
