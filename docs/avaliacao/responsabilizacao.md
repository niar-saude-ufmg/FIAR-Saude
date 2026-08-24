# Avaliação de Responsabilização

A dimensão de **Responsabilização** do FIAR-Saúde avalia se responsabilidades, decisões e mecanismos de prestação de contas relacionados à Tarefa de IA estão claramente definidos e documentados ao longo de seu ciclo de vida.

Em saúde pública, decisões técnicas e institucionais associadas ao desenvolvimento, validação, operação, monitoramento e uso de sistemas de IA podem envolver diferentes pessoas, equipes e instâncias. A avaliação busca verificar se é possível identificar quem possui responsabilidade por cada tipo de decisão relevante, em que contexto essa responsabilidade se aplica e como essas decisões podem ser posteriormente reconstruídas e revisadas.

A responsabilização não deve ser inferida apenas a partir da autoria de documentos ou da participação técnica no projeto. Papéis institucionais, responsabilidades operacionais e competências decisórias devem ser explicitamente documentados quando relevantes.

A dimensão está alinhada a princípios de accountability presentes em referências internacionais de IA Responsável e em abordagens de governança e auditoria algorítmica que enfatizam a atribuição clara de responsabilidades e a rastreabilidade das decisões.


---

## Objetivo da dimensão

A avaliação de Responsabilização busca verificar se o projeto:

- identifica os papéis e responsabilidades relevantes ao longo do ciclo de vida da tarefa;
- distingue responsabilidades técnicas, operacionais e institucionais;
- documenta decisões relevantes e suas justificativas;
- permite reconstruir quem decidiu, em qual papel ou instância, sobre qual questão e com base em quais evidências;
- registra aceite de risco, condicionantes ou decisões institucionais quando aplicáveis;
- mantém coerência entre responsabilidades declaradas e os processos efetivamente documentados;
- atualiza responsabilidades quando mudanças organizacionais ou operacionais relevantes ocorrerem.

---

## Papéis e responsabilidades

A avaliação considera se os papéis necessários à Tarefa de IA estão identificados de forma adequada ao contexto.

Podem incluir, quando aplicáveis:

- responsável pelo projeto;
- responsável técnico pela tarefa ou sistema;
- responsáveis por dados ou infraestrutura;
- responsáveis pela operação e monitoramento;
- responsáveis por validações específicas;
- pontos focais institucionais;
- instâncias responsáveis por decisões escalonadas;
- Comitê Gestor, quando houver deliberação institucional.

A existência de autoria, propriedade ou contribuição em Data Cards, Model Cards ou outros artefatos não deve ser utilizada, isoladamente, para inferir responsabilidade institucional.

---

## Registro e rastreabilidade de decisões

Decisões relevantes devem ser registradas de forma que seja possível reconstruir:

- a decisão tomada;
- o contexto e o problema que motivaram a decisão;
- a pessoa, papel, equipe ou instância responsável;
- a data ou período da decisão;
- as evidências consideradas;
- a justificativa;
- eventuais alternativas avaliadas;
- riscos, limitações ou trade-offs aceitos;
- ações ou condicionantes decorrentes da decisão.

Podem constituir evidências:

- Registros de Decisão Técnica;
- atas ou registros institucionais;
- pareceres;
- registros de aceite de risco;
- decisões sobre mitigação;
- registros de aprovação de mudanças.

O FIAR-Saúde não exige necessariamente assinatura formal em todos os registros. O requisito central é que a responsabilidade e a decisão sejam identificáveis e rastreáveis de forma adequada ao contexto institucional.

---

## Aceite de risco, condicionantes e escalonamento

Quando a avaliação identificar riscos residuais ou questões que exijam decisão institucional, deve ser possível identificar:

- qual risco ou questão foi escalonado;
- quais evidências fundamentaram o escalonamento;
- qual instância possuía competência para decidir;
- qual decisão foi tomada;
- quais condicionantes, restrições ou responsabilidades foram estabelecidas;
- como essa decisão será acompanhada.

Nem toda avaliação exige aceite formal de risco ou condicionantes. Esses mecanismos são aplicáveis quando a natureza do achado exige deliberação institucional.

---

## Riscos associados

Limitações na Responsabilização podem contribuir para riscos como:

- impossibilidade de identificar quem possui competência ou responsabilidade por decisões relevantes;
- decisões técnicas ou institucionais sem justificativa rastreável;
- dificuldade de revisar ou investigar falhas;
- conflitos ou sobreposição de responsabilidades;
- ausência de registro sobre riscos residuais ou trade-offs aceitos;
- condicionantes sem responsável definido para acompanhamento;
- mudanças organizacionais que deixem responsabilidades desatualizadas.

---

## Evidências esperadas

Dependendo da tarefa e do contexto, podem constituir evidências relevantes:

- Formulário de Entrada;
- Identificação da Avaliação;
- definição formal de papéis e responsabilidades;
- Registros de Decisão Técnica;
- atas ou registros de reuniões e comitês;
- registros de validação ou aprovação;
- documentação de aceite de risco residual;
- condicionantes institucionais;
- registros de escalonamento;
- documentação de responsabilidades operacionais;
- histórico de mudanças de responsáveis;
- registros de acompanhamento de decisões.

A ausência de determinada evidência deve ser analisada quanto à sua aplicabilidade ao requisito e ao contexto. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

| ID | Requisito ou questão de avaliação | Exemplos de evidências | Mecanismos de verificação |
|---|---|---|---|
| RES-01 | Os papéis e responsabilidades relevantes para a tarefa estão identificados? | Formulário de Entrada, Identificação da Avaliação, documentação institucional | Verificação documental; análise de suficiência |
| RES-02 | Responsabilidades técnicas, operacionais e institucionais estão diferenciadas quando necessário? | matriz de responsabilidades, documentação do projeto | Verificação documental; consistência cruzada |
| RES-03 | Decisões relevantes estão documentadas com responsável, contexto e justificativa identificáveis? | Registro de Decisão Técnica, atas, pareceres | Verificação documental; rastreabilidade |
| RES-04 | As evidências utilizadas para fundamentar decisões relevantes podem ser reconstruídas? | decisões técnicas, relatórios, avaliações | Consistência cruzada; rastreabilidade entre evidência e decisão |
| RES-05 | Riscos residuais ou trade-offs relevantes foram atribuídos à instância competente para decisão quando necessário? | registro de escalonamento, pareceres, decisões institucionais | Verificação institucional; contextualização |
| RES-06 | Aceites de risco, condicionantes ou restrições estão formalmente registrados quando aplicáveis? | atas, pareceres, registros do Comitê Gestor | Verificação institucional; rastreabilidade |
| RES-07 | Condicionantes ou decisões possuem responsáveis definidos para execução ou acompanhamento? | decisão institucional, plano de ação, registro de pendências | Verificação documental; rastreabilidade |
| RES-08 | Há consistência entre responsabilidades declaradas nos documentos e os papéis efetivamente associados às decisões registradas? | Formulário de Entrada, artefatos, decisões técnicas | Consistência cruzada |
| RES-09 | Mudanças relevantes de equipe, papel ou responsabilidade são registradas quando afetam a tarefa? | histórico de validação, registros institucionais | Verificação de rastreabilidade e versionamento |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** há informação adequada para identificar responsabilidades e reconstruir decisões relevantes?
- **Consistência:** os papéis e responsabilidades declarados são coerentes entre os diferentes documentos e registros?
- **Rastreabilidade:** é possível relacionar decisões, responsáveis, evidências e ações correspondentes?
- **Contextualização:** o nível de formalização das responsabilidades e decisões é adequado ao tipo de tarefa, à Trilha de Execução e ao Contexto de Uso?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Responsabilização produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Responsabilização não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.

---

## Relação com o processo de avaliação

Para o processo completo de avaliação, consulte:

→ [Ciclo de Avaliação Técnica](../ciclo_avaliacao.md)
