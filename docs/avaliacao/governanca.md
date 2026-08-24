# Avaliação de Governança

A dimensão de **Governança** do FIAR-Saúde avalia se a Tarefa de IA está inserida em estruturas, processos e responsabilidades institucionais adequados ao seu desenvolvimento, avaliação, uso, monitoramento e eventual operação.

A governança da tarefa envolve a definição de papéis, processos decisórios, mecanismos de supervisão, condições de uso, critérios de acompanhamento e formas de resposta a mudanças, riscos ou limitações relevantes.

Esta dimensão não deve ser confundida com a governança do próprio processo FIAR-Saúde. O objeto da avaliação é a governança associada à Tarefa de IA e ao seu Contexto de Uso. O NIAR-Saúde realiza a avaliação técnica e, quando necessário, questões relevantes podem ser escalonadas às instâncias institucionais competentes.

A dimensão está alinhada a referências internacionais de IA Responsável e gestão de riscos que enfatizam governança institucional, supervisão humana, gestão de riscos e acompanhamento ao longo do ciclo de vida.

---

## Objetivo da dimensão

A avaliação de Governança busca verificar se o projeto:

- identifica as estruturas e responsabilidades institucionais relevantes para a tarefa;
- define processos de decisão compatíveis com o estágio e o Contexto de Uso;
- estabelece condições e limites para o uso da tarefa;
- define mecanismos de supervisão humana quando necessários;
- estabelece processos de monitoramento, revisão e atualização quando aplicáveis;
- identifica como riscos, limitações e mudanças relevantes são tratados ou escalonados;
- mantém coerência entre as práticas declaradas e as decisões institucionais relacionadas à tarefa.

---

## Estruturas e processos institucionais

A avaliação considera, quando aplicável:

- responsáveis pelo desenvolvimento e manutenção da tarefa;
- responsáveis pelo uso ou operação;
- instâncias responsáveis por aprovação, validação ou decisão institucional;
- processos de escalonamento;
- regras ou condições de uso;
- processos de revisão;
- relação entre decisões técnicas e institucionais.

A existência de uma estrutura formal específica, como um comitê dedicado exclusivamente à IA, não constitui requisito universal do FIAR-Saúde. O foco é verificar se as responsabilidades e competências necessárias estão adequadamente atribuídas no contexto institucional existente.

O FIAR-Saúde não prescreve uma estrutura organizacional única. O requisito é que as competências, responsabilidades, processos decisórios e mecanismos de supervisão necessários ao contexto estejam adequadamente definidos e rastreáveis.

---

## Supervisão humana

A avaliação considera se o papel da supervisão humana foi definido de forma compatível com a natureza da tarefa e com o contexto de uso.

Quando aplicável, podem ser considerados:

- finalidade da supervisão humana;
- pessoas ou papéis responsáveis pela supervisão;
- informações disponíveis para apoiar a revisão;
- possibilidade de questionar, interromper ou substituir a recomendação do sistema;
- procedimentos para situações de incerteza, erro ou comportamento inesperado;
- limitações da própria supervisão humana.

Nem toda Tarefa de IA produz decisões automatizadas individuais. Por isso, a necessidade e a forma de supervisão humana devem ser determinadas a partir do contexto de uso, e não presumidas de forma uniforme.

---

## Monitoramento, revisão e mudança

A avaliação considera se existem processos adequados para acompanhar a tarefa e responder a mudanças relevantes ao longo de seu ciclo de vida.

Dependendo da Trilha de Execução, podem ser considerados:

- monitoramento de desempenho;
- monitoramento de riscos ou disparidades relevantes;
- revisão periódica;
- atualização de dados ou modelos;
- critérios para reavaliação;
- gestão de mudanças;
- registro de incidentes ou eventos relevantes;
- suspensão, restrição ou descontinuação do uso, quando necessário.

Tarefas experimentais e tarefas em produção podem exigir diferentes níveis de formalização e acompanhamento.

---

## Condições e limites de uso

A avaliação verifica se o uso pretendido da tarefa, suas limitações e eventuais restrições estão suficientemente definidos.

Podem ser considerados:

- finalidade autorizada ou prevista;
- população ou contexto ao qual a tarefa se destina;
- usos não recomendados ou não avaliados;
- necessidade de supervisão humana;
- condicionantes técnicos ou institucionais;
- circunstâncias que exigem interrupção, revisão ou reavaliação.

Mudanças relevantes na finalidade ou no Contexto de Uso podem exigir nova avaliação, mesmo quando o modelo técnico permanece inalterado.

---

## Riscos associados

Limitações de Governança podem contribuir para riscos como:

- uso da tarefa fora das condições avaliadas;
- ausência de definição sobre quem possui competência para determinadas decisões;
- supervisão humana inadequada ou meramente formal;
- riscos ou limitações identificados sem resposta definida;
- mudanças relevantes sem revisão ou reavaliação;
- ausência de critérios para suspensão ou restrição de uso;
- desalinhamento entre práticas operacionais e decisões institucionais.

---

## Evidências esperadas

Dependendo da tarefa, do Contexto de Uso e da Trilha de Execução, podem constituir evidências relevantes:

- Formulário de Entrada;
- Identificação da Avaliação;
- Model Card;
- definição de papéis e responsabilidades;
- políticas ou procedimentos institucionais aplicáveis;
- documentação do fluxo de decisão;
- documentação da supervisão humana;
- Registros de Decisão Técnica;
- atas ou decisões institucionais;
- condicionantes ou restrições de uso;
- registros de escalonamento;
- planos ou relatórios de monitoramento;
- registros de revisão e reavaliação;
- documentação de mudanças relevantes;
- registros de suspensão, rollback ou descontinuação, quando aplicáveis.

A ausência de determinada evidência deve ser analisada quanto à sua aplicabilidade ao requisito, ao contexto e à Trilha de Execução. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

| ID     | Requisito ou questão de avaliação                                                                                                        | Exemplos de evidências                                                              | Mecanismos de verificação                                          |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | -------------------------------------------------------------------- |
| GOV-01 | As estruturas, papéis e competências institucionais relevantes para a tarefa estão identificados?                                        | Formulário de Entrada, Identificação da Avaliação, documentação institucional | Verificação documental; consistência cruzada                      |
| GOV-02 | Existem processos definidos para decisões técnicas, operacionais ou institucionais relevantes à tarefa?                                  | fluxos de decisão, Registros de Decisão Técnica, procedimentos                    | Verificação documental; rastreabilidade                            |
| GOV-03 | A finalidade, as condições e os limites de uso da tarefa estão definidos?                                                                | Model Card, documentação de uso, decisões institucionais                          | Verificação documental; contextualização                         |
| GOV-04 | A necessidade e a forma de supervisão humana foram determinadas de acordo com a natureza da tarefa e o Contexto de Uso?                    | Model Card, procedimento operacional, documentação institucional                   | Contextualização; verificação documental                         |
| GOV-05 | Quando aplicável, os responsáveis pela supervisão possuem informações e mecanismos adequados para intervir ou revisar o uso da tarefa? | procedimentos, interfaces, materiais de uso                                          | Revisão documental; análise contextual                             |
| GOV-06 | Riscos, limitações ou achados relevantes possuem processo definido de tratamento ou escalonamento?                                        | registros de risco, TDR, fluxo de escalonamento                                      | Rastreabilidade entre achado e decisão; verificação institucional |
| GOV-07 | Condicionantes, restrições ou decisões institucionais estão documentados e associados à tarefa quando aplicáveis?                     | atas, pareceres, decisões do Comitê Gestor                                         | Verificação institucional; rastreabilidade                         |
| GOV-08 | Existem mecanismos adequados de monitoramento, revisão e atualização para o estágio da tarefa?                                          | planos de monitoramento, registros de revisão                                       | Análise de evidências operacionais; contextualização             |
| GOV-09 | Existem critérios ou gatilhos para reavaliação quando mudanças relevantes ocorrerem?                                                    | política de mudanças, histórico de versões, registros de decisão                | Verificação documental; rastreabilidade longitudinal               |
| GOV-10 | Para tarefas em produção, existem mecanismos para restringir, suspender, corrigir ou descontinuar o uso quando necessário?               | procedimentos operacionais, planos de contingência, decisões institucionais        | Análise de evidências operacionais; verificação institucional    |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** existem informações adequadas para compreender as estruturas, processos e decisões de governança relevantes?
- **Consistência:** papéis, condições de uso, processos e decisões são coerentes entre os diferentes registros?
- **Rastreabilidade:** é possível relacionar riscos, decisões, responsáveis, condicionantes e ações correspondentes?
- **Contextualização:** os mecanismos de governança são proporcionais à natureza da tarefa, à Trilha de Execução e ao Contexto de Uso?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Governança produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Governança não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.

---
