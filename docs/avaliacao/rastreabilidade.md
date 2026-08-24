# Avaliação de Rastreabilidade

A dimensão de **Rastreabilidade** do FIAR-Saúde avalia se a Tarefa de IA possui registros, versões e relações documentadas suficientes para permitir a reconstrução de sua evolução técnica e institucional ao longo do ciclo de vida.

A rastreabilidade permite relacionar dados, modelos, configurações, resultados, decisões e mudanças relevantes à versão efetivamente avaliada. Em saúde, essa capacidade é importante para investigar falhas, revisar resultados, compreender alterações entre versões e sustentar decisões de governança.

A dimensão não deve ser confundida com a **rastreabilidade como propriedade transversal da evidência**, utilizada pelo NIAR-Saúde para verificar se uma conclusão da avaliação pode ser relacionada às evidências que a fundamentam. Nesta dimensão, o objeto avaliado são as práticas de rastreamento e versionamento adotadas pela própria tarefa e pelo projeto.

A dimensão está alinhada a referências internacionais de IA Responsável e gestão de riscos que enfatizam documentação, accountability e capacidade de reconstrução das decisões e mudanças ao longo do ciclo de vida.

---

## Objetivo da dimensão

A avaliação de Rastreabilidade busca verificar se o projeto:

- identifica de forma inequívoca a versão da tarefa avaliada;
- mantém relação entre versões de dados, modelos, código, configurações e artefatos relevantes;
- registra mudanças que possam alterar resultados, riscos ou contexto de uso;
- permite reconstruir como resultados técnicos foram produzidos;
- documenta decisões relevantes associadas a mudanças técnicas ou institucionais;
- mantém histórico suficiente para comparar versões ao longo do tempo;
- preserva registros operacionais quando necessários para tarefas em produção.

---

## Riscos associados

Limitações de Rastreabilidade podem contribuir para riscos como:

- impossibilidade de identificar qual versão foi efetivamente avaliada ou utilizada;
- dificuldade de relacionar resultados a dados, modelos ou configurações específicas;
- incapacidade de reconstruir mudanças relevantes;
- dificuldade de investigar falhas ou resultados inesperados;
- perda de histórico sobre decisões técnicas ou institucionais;
- comparação inadequada entre versões;
- alterações em produção sem registro ou reavaliação correspondente.

---

## Componentes da rastreabilidade

A avaliação considera diferentes componentes que sustentam a rastreabilidade da Tarefa de IA ao longo de seu ciclo de vida:

### Identificação da Versão Avaliável

A avaliação verifica se a configuração efetivamente considerada no ciclo pode ser identificada.

Isso pode envolver:

- versão do modelo;
- versão ou recorte dos dados;
- versão do código;
- configuração relevante;
- versão dos artefatos documentais;
- data ou período da avaliação.

### Proveniência e transformação dos dados

Refere-se à possibilidade de reconstruir, quando aplicável:

- origem dos dados;
- versões ou recortes utilizados;
- critérios de seleção;
- transformações e pré-processamentos relevantes;
- relação entre os dados utilizados e os resultados reportados.

### Versionamento de modelos e componentes

Refere-se ao registro das versões e mudanças relevantes em:

- modelos;
- código;
- parâmetros ou configurações;
- dependências;
- pipelines;
- ambientes computacionais, quando necessários para reconstrução dos resultados.

### Rastreamento de decisões e mudanças

Refere-se à capacidade de reconstruir decisões e alterações relevantes ao longo do ciclo de vida, incluindo:

- mudanças metodológicas;
- substituição ou atualização de dados;
- mudanças de modelo;
- alterações de contexto de uso;
- medidas de mitigação;
- condicionantes;
- decisões de implantação ou reavaliação.

### Registros operacionais

Para tarefas em produção, podem ser necessários registros adicionais que permitam acompanhar o comportamento e as mudanças da tarefa ao longo do tempo, como:

- histórico de implantação;
- logs relevantes;
- eventos ou incidentes;
- mudanças de configuração;
- monitoramento;
- rollback ou reimplantação;
- registros de reavaliação.

## Rastreabilidade e reprodutibilidade

A rastreabilidade pode apoiar a reprodução ou reexecução de análises, mas o FIAR-Saúde não pressupõe que todo resultado deva ser integralmente reproduzível pelo NIAR-Saúde.

Restrições relacionadas a dados sensíveis, ambientes protegidos, propriedade intelectual ou infraestrutura podem impedir a reprodução direta.

Nesses casos, a avaliação verifica se existe documentação suficiente para reconstruir:

- quais dados ou versões foram utilizados;
- qual configuração produziu o resultado;
- qual procedimento foi executado;
- quais parâmetros ou condições relevantes foram empregados;
- qual evidência resultou da execução.

Quando a reprodução ou reexecução for necessária para determinado requisito, ela deve ser tratada como mecanismo de verificação específico. 

O nível de detalhe e o período de preservação dos registros devem ser proporcionais à relevância do componente, ao estágio da tarefa, às necessidades de reavaliação e às regras institucionais aplicáveis.

---

## Evidências esperadas

Dependendo da tarefa e da Trilha de Execução, podem constituir evidências relevantes:

- Identificação da Avaliação;
- Data Cards;
- Model Cards;
- histórico de versões;
- registros de experimentos;
- identificadores de datasets, modelos ou código;
- documentação de pipelines e configurações;
- Registros de Decisão Técnica;
- logs ou registros de execução;
- registros de implantação;
- registros de mudanças relevantes;
- histórico de monitoramento e incidentes, quando aplicável.

A ausência de determinada evidência deve ser analisada quanto à sua aplicabilidade ao requisito e ao contexto. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

| ID     | Requisito ou questão de avaliação                                                                                                                                     | Exemplos de evidências                                            | Mecanismos de verificação                               |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------ | --------------------------------------------------------- |
| RAS-01 | A Versão Avaliável da tarefa pode ser identificada de forma inequívoca?                                                                                               | Identificação da Avaliação, Model Card, histórico de versões | Verificação documental; rastreabilidade e versionamento |
| RAS-02 | É possível relacionar a versão avaliada aos dados utilizados?                                                                                                         | Data Card, identificadores de datasets, registros experimentais    | Consistência cruzada; verificação de rastreabilidade   |
| RAS-03 | É possível relacionar a versão avaliada aos modelos, códigos, configurações ou outros componentes técnicos relevantes?                                            | Model Card, repositório, registros experimentais                  | Verificação de rastreabilidade e versionamento          |
| RAS-04 | Transformações e procedimentos relevantes para produção dos resultados estão documentados?                                                                          | pipeline, documentação metodológica, registros de experimentos  | Revisão documental; revisão metodológica               |
| RAS-05 | Resultados técnicos podem ser relacionados à configuração que os produziu?                                                                                           | relatórios, logs, experimentos, identificadores de versão        | Consistência cruzada; rastreabilidade                    |
| RAS-06 | Mudanças relevantes entre versões estão documentadas?                                                                                                                 | histórico de versões, commits, registros técnicos               | Verificação de rastreabilidade e versionamento          |
| RAS-07 | Decisões relevantes associadas a mudanças estão registradas e relacionadas às evidências correspondentes?                                                           | Registros de Decisão Técnica, atas, histórico de mudanças      | Consistência cruzada; rastreabilidade                    |
| RAS-08 | Quando necessário, existe documentação suficiente para reconstruir o procedimento que produziu uma análise técnica e, quando aplicável, permitir sua reexecução? | scripts, configuração, parâmetros, documentação de ambiente   | Revisão metodológica; teste técnico quando aplicável  |
| RAS-09 | Para tarefas em produção, mudanças operacionais, implantações e eventos relevantes são registrados?                                                                | logs de implantação, registros de versão, incidentes            | Análise de evidências operacionais                      |
| RAS-10 | Mudanças que possam alterar riscos, desempenho ou contexto de uso são identificáveis para fins de reavaliação?                                                      | histórico de versões, registros de mudança, TDR                 | Rastreabilidade longitudinal; consistência               |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** existem registros suficientes para reconstruir o aspecto avaliado?
- **Consistência:** versões, identificadores, resultados e mudanças são coerentes entre os diferentes artefatos?
- **Rastreabilidade:** a própria evidência utilizada pelo NIAR pode ser relacionada à Tarefa, à Versão Avaliável e ao requisito analisado?
- **Contextualização:** o nível de rastreamento é adequado à natureza da tarefa, à Trilha de Execução e ao Contexto de Uso?

A terceira propriedade acima refere-se à rastreabilidade da **avaliação realizada pelo NIAR-Saúde**, enquanto a dimensão avalia a rastreabilidade das práticas da **Tarefa de IA e do projeto**.

---

## Resultado da avaliação da dimensão

A avaliação de Rastreabilidade produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Rastreabilidade não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.

---

## Relação com as demais dimensões

A Rastreabilidade oferece suporte à avaliação das demais dimensões ao permitir que evidências, versões, resultados e decisões sejam relacionados à configuração efetivamente avaliada.

Entretanto, uma limitação de rastreabilidade não deve ser automaticamente convertida em falha em todas as demais dimensões.

Seu efeito deve ser analisado requisito a requisito.

Por exemplo, a ausência de identificação da versão de um relatório pode limitar a capacidade de verificar uma evidência de Justiça ou Transparência, gerando uma pendência específica nesses requisitos sem necessariamente invalidar todas as demais evidências disponíveis. Nesses casos, deve-se registrar quais requisitos foram efetivamente afetados e em que medida a limitação compromete a suficiência ou a rastreabilidade da evidência utilizada.

Para o processo completo de avaliação, consulte:

→ [Ciclo de Avaliação Técnica](../ciclo_avaliacao.md)
