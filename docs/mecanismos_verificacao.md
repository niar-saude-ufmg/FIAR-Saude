# Mecanismos de Verificação do FIAR-Saúde

## 1. Objetivo

Os mecanismos de verificação definem **como o NIAR-Saúde examina as evidências utilizadas na avaliação técnica do FIAR-Saúde**.

Eles operacionalizam a passagem entre os requisitos das dimensões de IA Responsável e os resultados da avaliação, permitindo que conclusões sejam fundamentadas em evidências identificáveis, verificáveis e contextualizadas.

Os mecanismos de verificação não constituem uma lista universal de testes aplicável indistintamente a todos os projetos. Sua seleção depende da **Tarefa de IA**, da **Versão Avaliável**, do **Contexto de Uso**, da **Trilha de Execução**, do requisito avaliado e da natureza das evidências disponíveis.

---

## 2. Posição dos mecanismos na lógica do FIAR-Saúde

A avaliação técnica segue a seguinte cadeia:

* **Dimensões:** definem **o que avaliamos**.
* **Requisitos ou questões de avaliação:** definem **o que queremos verificar**.
* **Evidências:** constituem **a base utilizada para fundamentar a análise**.
* **Mecanismos de verificação:** definem **como as evidências são examinadas**.
* **Suficiência, consistência, rastreabilidade e contextualização:** constituem **propriedades transversais consideradas na análise das evidências**.
* **Achados e pendências:** registram **os resultados da análise e as questões ainda não resolvidas**.
* **Conformidade:** constitui o resultado pontual da avaliação de uma **Tarefa de IA + Versão Avaliável + Contexto de Uso**.
* **Maturidade:** constitui uma inferência longitudinal no nível do **projeto**, baseada na recorrência, continuidade e rastreabilidade das práticas de IA Responsável ao longo de sucessivos ciclos de avaliação.

Os mecanismos de verificação, portanto, ocupam a camada operacional entre a existência da evidência e a conclusão da avaliação.

---

## 3. Princípios dos mecanismos de verificação

### 3.1 Proporcionalidade

Nem toda tarefa exige os mesmos mecanismos de verificação.

A seleção deve considerar, entre outros elementos:

* finalidade da tarefa;
* estágio de desenvolvimento ou operação;
* Trilha de Execução;
* contexto de uso;
* pessoas, grupos ou instituições potencialmente afetados;
* natureza dos dados;
* riscos e limitações conhecidos;
* evidências disponíveis.

A inexistência de determinado teste ou artefato não constitui automaticamente uma não conformidade. Deve-se primeiro determinar se aquela evidência é aplicável ao requisito e ao contexto avaliado.

A aplicabilidade de uma dimensão não implica a obrigatoriedade de um mecanismo técnico específico. Os mecanismos devem ser selecionados em função do requisito, da tarefa, das evidências e do contexto de uso.

Da mesma forma, a existência de um template ou diretório no FIAR-Audit-Template não implica que o artefato correspondente seja obrigatório para todas as tarefas.

Os artefatos constituem formas possíveis de produzir ou registrar evidências. Sua necessidade deve decorrer dos requisitos aplicáveis, das evidências já disponíveis e das lacunas identificadas durante a avaliação.

Quando a evidência necessária já estiver suficientemente documentada em outro artefato ou registro rastreável, não é necessário exigir duplicação documental apenas para preencher um template específico.

### 3.2 Fundamentação em evidências

Toda conclusão deve poder ser relacionada às evidências utilizadas.

O avaliador deve distinguir claramente:

* informações declaradas pelo projeto;
* evidências documentais ou técnicas apresentadas;
* resultados de verificações realizadas;
* análise do NIAR-Saúde;
* pendências;
* decisões institucionais.

Inferências sem suporte documental ou técnico devem ser explicitamente identificadas como limitações ou questões pendentes.

Uma deficiência, ausência ou limitação identificada em determinada evidência não deve ser automaticamente propagada como falha para todas as dimensões ou requisitos que possam depender dela.

Seu impacto deve ser analisado no nível dos requisitos efetivamente afetados, considerando se as demais evidências disponíveis ainda permitem uma conclusão suficientemente fundamentada.

Informações sobre autoria, propriedade, contribuição ou contato registradas em artefatos não devem ser utilizadas, isoladamente, para inferir responsabilidades técnicas, operacionais ou institucionais.

Quando a atribuição de responsabilidade for relevante para um requisito, ela deve estar sustentada por evidência específica sobre o papel, competência ou responsabilidade correspondente.

### 3.3 Independência da avaliação

Os mecanismos são aplicados pelo NIAR-Saúde de forma independente da equipe responsável pelo desenvolvimento.

Isso não impede interação com o projeto para:

* esclarecimentos;
* complementação de informações;
* correção de documentação;
* explicação de decisões técnicas;
* fornecimento de evidências adicionais.

A equipe do projeto fornece e explica as evidências, mas não determina o resultado da avaliação.

### 3.4 Análise contextual

A evidência não deve ser interpretada isoladamente.

Um resultado técnico pode assumir significados diferentes dependendo do contexto de uso, da população afetada, das limitações conhecidas, dos riscos envolvidos e das condições operacionais da tarefa.

Por isso, a aplicação de um mecanismo de verificação deve considerar tanto o resultado observado quanto sua relevância para o contexto específico da avaliação.

### 3.5 Rastreabilidade

Toda verificação relevante deve registrar, quando aplicável:

* requisito avaliado;
* evidência utilizada;
* identificação ou versão do artefato;
* mecanismo aplicado;
* resultado obtido;
* interpretação do resultado;
* limitações;
* pendências;
* relação com outros artefatos ou decisões.
* identificador do requisito;
* data da verificação;
* responsável pela avaliação;

Essa estrutura permite reconstruir posteriormente como uma conclusão foi produzida.

### 3.6 Critérios de interpretação

Sempre que um mecanismo de verificação depender de métricas, thresholds, tolerâncias ou critérios qualitativos de decisão, esses critérios devem ser explicitados e justificados.

O FIAR-Saúde não pressupõe thresholds universais para todas as tarefas ou dimensões.

Os critérios de interpretação devem considerar, quando aplicável:

- natureza da tarefa;
- contexto de uso;
- consequências potenciais dos erros;
- população ou grupos afetados;
- referências técnicas ou normativas aplicáveis;
- tolerância institucional ao risco;
- limitações da evidência.

Sempre que possível, critérios e thresholds devem ser definidos antes da interpretação dos resultados, evitando sua seleção retrospectiva apenas para justificar o resultado observado.

---

## 4. Tipos de mecanismos de verificação

Os mecanismos utilizados pelo FIAR-Saúde podem assumir diferentes formas.

### 4.1 Verificação documental

Examina a existência, completude e adequação de informações registradas em documentos e artefatos.

Exemplos:

* existência de finalidade e contexto de uso no Model Card;
* documentação da origem dos dados no Data Card;
* registro de limitações conhecidas;
* existência de responsáveis ou procedimentos definidos.

A existência de um campo preenchido não implica, por si só, evidência suficiente.

### 4.2 Consistência cruzada entre artefatos

Compara informações relacionadas presentes em diferentes evidências.

Exemplos:

* datasets mencionados no Model Card correspondem aos Data Cards disponíveis;
* população descrita nos dados corresponde à população considerada na avaliação de Justiça;
* limitações identificadas em um artefato aparecem refletidas nas análises e decisões subsequentes;
* uso pretendido é consistente entre os documentos do ciclo.

Divergências confirmadas devem ser registradas como inconsistências. Ausência de informação em apenas um dos documentos não deve ser automaticamente classificada como inconsistência.

### 4.3 Verificação de rastreabilidade e versionamento

Avalia se é possível reconstruir a relação entre evidências, versões e decisões.

Pode verificar:

* versões de datasets;
* versões de modelos;
* versões dos artefatos;
* histórico de mudanças;
* relação entre resultado experimental e configuração avaliada;
* registros de decisões técnicas;
* relação entre achados, mitigação e decisão.

### 4.4 Revisão metodológica

Examina se o procedimento utilizado para produzir determinada evidência é adequado à questão avaliada.

Exemplos:

* estratégia de divisão treino/teste;
* definição dos subgrupos utilizados em uma análise de Justiça;
* escolha de métricas;
* protocolo de validação;
* método de explicabilidade empregado.

O NIAR-Saúde pode avaliar a adequação metodológica a partir das evidências disponibilizadas sem necessariamente reproduzir integralmente os experimentos.

### 4.5 Revisão de métricas e resultados técnicos

Analisa resultados quantitativos produzidos pelo projeto ou por ferramentas de avaliação.

Pode envolver:

* desempenho global;
* desempenho estratificado;
* métricas de disparidade;
* indicadores de robustez;
* medidas de drift;
* resultados de explicabilidade;
* métricas de segurança ou privacidade, quando aplicáveis.

Uma métrica isolada não determina automaticamente conformidade. Seu significado depende do requisito e do contexto de uso.

### 4.6 Testes técnicos

Quando necessários e viáveis, mecanismos de verificação podem envolver execução ou reexecução de testes técnicos.

Esses testes devem ter:

* objetivo claramente definido;
* relação explícita com um requisito de avaliação;
* método documentado;
* entradas e versões identificadas;
* resultado registrado;
* critérios de interpretação definidos.

O FIAR-Saúde não pressupõe que toda avaliação exija acesso direto ao código, dados sensíveis, pesos ou ambiente operacional.

### 4.7 Análise de evidências operacionais

Para tarefas em produção, podem ser examinadas evidências como:

* relatórios de monitoramento;
* registros de incidentes;
* logs;
* indicadores de drift;
* histórico de reimplantação;
* registros de resposta a falhas;
* revisões periódicas.

Esses mecanismos são especialmente relevantes para a avaliação longitudinal e para tarefas na Trilha Produção.

### 4.8 Esclarecimentos e entrevistas

Entrevistas e solicitações de esclarecimento são mecanismos complementares de obtenção ou interpretação de informações.

Podem ser utilizadas quando:

* a documentação é ambígua;
* existem informações aparentemente contraditórias;
* decisões relevantes não estão suficientemente explicadas;
* o contexto de uso não pode ser compreendido apenas pelos documentos.

Informações obtidas por entrevista que sejam relevantes para a avaliação devem ser registradas de maneira rastreável.

A entrevista não substitui evidências técnicas que devam existir formalmente.

### 4.9 Verificação institucional

Alguns requisitos dependem de registros ou decisões institucionais, como:

* aprovação ética;
* definição de responsabilidades;
* condicionantes;
* aceite de risco;
* políticas de uso;
* procedimentos de supervisão;
* decisões do Comitê Gestor.

Nesses casos, o mecanismo de verificação consiste na análise da existência, aplicabilidade, vigência e relação desses registros com a tarefa avaliada.

A verificação de registros normativos, éticos ou institucionais no FIAR-Saúde não equivale, por si só, à certificação de conformidade legal, regulatória ou ética. O mecanismo verifica sua existência, aplicabilidade, vigência e consistência com a tarefa avaliada.

---

## 5. Aplicabilidade do requisito

Antes da análise das evidências, o NIAR-Saúde deve determinar se cada requisito é aplicável à **Tarefa de IA, Versão Avaliável, Contexto de Uso e Trilha de Execução** considerados.

Para cada requisito deve ser registrado:

- **Aplicabilidade:** Aplicável | Não aplicável
- **Justificativa:** fundamento para a determinação de aplicabilidade.

A classificação como **Não aplicável** deve ser justificada e não equivale a atendimento do requisito.

A aplicabilidade pode variar entre tarefas e versões. Um requisito não aplicável em uma tarefa experimental pode tornar-se aplicável após mudança de contexto, integração em produção ou outra alteração relevante.

Somente os requisitos classificados como aplicáveis seguem para a análise de suficiência, consistência, rastreabilidade e contextualização das evidências.

---

## 6. Propriedades transversais da análise das evidências

Independentemente do mecanismo utilizado, a avaliação deve considerar quatro propriedades transversais.

### 6.1 Suficiência

Pergunta central:

> **As evidências disponíveis são adequadas e suficientemente completas para analisar o requisito?**

A suficiência não significa quantidade máxima de documentação. Significa que há evidência adequada para sustentar uma análise tecnicamente fundamentada.

Possíveis situações incluem:

* evidência suficiente;
* evidência parcial;
* evidência insuficiente;
* evidência não disponível;

Esses estados descrevem a condição da evidência e não equivalem automaticamente a resultados de conformidade.

### 6.2 Consistência

Pergunta central:

> **As evidências disponíveis são coerentes entre si?**

A análise pode considerar:

* consistência entre Data Card e Model Card;
* consistência entre finalidade declarada e avaliação realizada;
* consistência entre limitações identificadas e decisões posteriores;
* consistência entre versões dos documentos;
* consistência entre resultados técnicos e conclusões registradas.

Uma inconsistência deve ser sustentada por evidências de divergência efetiva.

### 6.3 Rastreabilidade

Pergunta central:

> **É possível identificar a origem da evidência e reconstruir sua relação com a tarefa, a versão e a conclusão produzida?**

A rastreabilidade pode envolver:

* identificação da versão;
* origem dos dados;
* configuração do modelo;
* registro da análise;
* relação entre achado e decisão;
* histórico temporal da evidência.

Esta propriedade transversal não deve ser confundida com a **dimensão de Rastreabilidade**, que avalia as práticas de versionamento, documentação e acompanhamento adotadas pela própria tarefa e pelo projeto.

### 6.4 Contextualização

Pergunta central:

> **A evidência foi interpretada considerando adequadamente o contexto em que a tarefa será utilizada?**

A contextualização pode considerar:

* finalidade;
* contexto clínico ou operacional;
* população afetada;
* estágio experimental ou produtivo;
* riscos conhecidos;
* limitações;
* consequências de erros;
* supervisão humana;
* condições institucionais de uso.

O mesmo resultado técnico pode ser aceitável, insuficiente ou relevante de maneiras diferentes em contextos distintos.

---

## 7. Sequência de avaliação de um requisito

A avaliação requisito a requisito ocorre após a pré-avaliação documental do ciclo, conforme o [Protocolo de Pré-Avaliação Documental](protocolo_pre_avaliacao_documental.md).

A pré-avaliação organiza e verifica inicialmente as fontes disponíveis; os mecanismos descritos neste documento são utilizados posteriormente para analisar as evidências em relação aos requisitos aplicáveis.

Para cada requisito das dimensões do FIAR-Saúde, a avaliação segue a seguinte sequência:

1. **Determinar a aplicabilidade**

   - verificar se o requisito é aplicável à tarefa, versão, contexto e trilha;
   - registrar a justificativa.
2. **Identificar as evidências esperadas**

   - determinar quais evidências seriam adequadas para responder ao requisito.
3. **Identificar as evidências disponíveis**

   - registrar quais artefatos, resultados ou registros estão efetivamente disponíveis.
4. **Selecionar o mecanismo de verificação**

   - definir como as evidências serão examinadas.
5. **Analisar as propriedades transversais**

   - suficiência;
   - consistência;
   - rastreabilidade;
   - contextualização.
6. **Registrar o resultado da análise**

   - achados;
   - limitações;
   - pendências;
   - recomendações, quando pertinentes.
7. **Avaliar a existência de sinal de governança**

   - determinar se o achado requer mitigação, monitoramento, restrição, escalonamento ou decisão institucional.

Essa sequência impede que presença, ausência ou preenchimento de um artefato sejam convertidos automaticamente em resultado de conformidade.

---

## 8. Sinais de governança

Um achado pode produzir um **sinal de governança** quando sua relevância exige uma resposta que ultrapassa o tratamento ordinário de pendências documentais ou técnicas.

Possíveis sinais incluem:

- necessidade de mitigação;
- necessidade de monitoramento específico;
- necessidade de revisão em versão futura;
- necessidade de restrição ou condicionamento de uso;
- risco residual que requer avaliação institucional;
- necessidade de escalonamento ao Comitê Gestor.

Pendências de informação, complementação documental ou esclarecimento são tratadas pelo fluxo ordinário da avaliação e não constituem, por si só, sinais de governança.

Nem todo achado produz um sinal de governança.

Quando houver sinal, deve ser possível rastrear:

**evidência → mecanismo de verificação → achado → sinal de governança → ação ou decisão correspondente.**

---

## 9. Estados da evidência, achados e conformidade

É necessário distinguir três níveis diferentes de resultado.

### 9.1 Estado da evidência

### Estado documental

Descreve a disponibilidade administrativa da evidência:

- recebida;
- parcialmente recebida;
- não recebida;
- substituída ou desatualizada, quando aplicável.

### Estado analítico da evidência

A condição analítica da evidência é registrada segundo propriedades independentes, quando aplicáveis.

Por exemplo:

**Suficiência**

- suficiente;
- parcialmente suficiente;
- insuficiente.

**Consistência**

- consistente;
- inconsistente;
- consistência ainda não determinável.

Podem também ser registrados estados auxiliares, como:

- requer esclarecimento;
- requer evidência adicional;
- requer análise adicional.

Essas classificações não constituem resultados de conformidade.

### 9.2 Resultado da verificação

O **resultado da verificação** corresponde ao resultado diretamente produzido pela aplicação de um mecanismo de verificação.

Pode assumir forma:

- documental;
- quantitativa;
- qualitativa;
- técnica;
- institucional.

Exemplos incluem uma divergência identificada entre dois artefatos, o valor de uma métrica, o resultado de um teste técnico ou a confirmação da existência e vigência de um registro institucional.

O resultado da verificação deve ser distinguido de sua interpretação.

Um **achado** corresponde à conclusão produzida pelo NIAR-Saúde a partir da análise e contextualização de um ou mais resultados de verificação.

### 9.3 Achado ou pendência

Um **achado** é uma conclusão sustentada pela análise de uma ou mais evidências.

Uma **pendência** representa uma questão que ainda impede ou limita a conclusão sobre determinado requisito.

Exemplos de pendência incluem:

* informação ausente;
* evidência insuficiente;
* análise adicional necessária;
* inconsistência ainda não esclarecida;
* decisão institucional necessária.

### 9.4 Resultado de conformidade

O resultado de conformidade é produzido somente após a análise dos requisitos aplicáveis à avaliação.

Ele se refere à combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

Os estados de evidência não devem ser convertidos mecanicamente em resultados de conformidade.

Por exemplo:

* um documento ausente pode gerar inicialmente uma pendência;
* uma evidência incompleta pode requerer complementação;
* uma inconsistência pode ser esclarecida ou confirmada;
* uma limitação técnica conhecida pode ser compatível com uso condicionado, dependendo do contexto e da decisão institucional aplicável.

A conformidade resulta da análise fundamentada do conjunto de requisitos e evidências, e não da simples contagem de itens presentes ou ausentes.

---

## 10. Relação com a maturidade

Os mecanismos de verificação produzem evidências sobre um ciclo específico de avaliação e não atribuem diretamente o nível de maturidade do projeto.

A maturidade é inferida longitudinalmente a partir da recorrência, continuidade e rastreabilidade das práticas observadas ao longo de sucessivos ciclos.

Portanto:

- a aplicação de um mecanismo em uma única versão não demonstra recorrência;
- um requisito não atendido em uma versão não implica automaticamente regressão de maturidade;
- a maturidade não resulta da soma ou agregação dos resultados dos requisitos.
