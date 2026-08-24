# Avaliação de Segurança

A dimensão de **Segurança** do FIAR-Saúde avalia se os riscos técnicos e operacionais relevantes para uma Tarefa de IA são identificados, tratados e acompanhados de forma compatível com seu Contexto de Uso e sua Trilha de Execução.

A avaliação pode envolver a proteção de dados, modelos, componentes de software, ambientes computacionais e fluxos operacionais contra acessos não autorizados, alterações indevidas, falhas ou outros eventos capazes de comprometer a integridade, a disponibilidade ou o funcionamento esperado da tarefa.

Em saúde, a relevância e a natureza dos mecanismos de segurança dependem do estágio da tarefa. Tarefas experimentais podem exigir principalmente controles relacionados ao acesso e à integridade dos artefatos e ambientes de desenvolvimento, enquanto tarefas em produção podem demandar evidências adicionais de monitoramento, resposta a incidentes, continuidade e proteção da infraestrutura operacional.

A dimensão está alinhada a referências internacionais de IA Responsável e gestão de riscos, incluindo princípios da OECD, recomendações da Organização Mundial da Saúde, ISO/IEC 23894 e o NIST AI Risk Management Framework.

---

## Objetivo da dimensão

A avaliação de Segurança busca verificar se o projeto:

- identifica os ativos, componentes e ambientes relevantes para a tarefa;
- documenta riscos de segurança compatíveis com o contexto e o estágio de uso;
- adota controles de acesso e proteção adequados aos ativos relevantes;
- preserva, quando aplicável, a integridade e a disponibilidade dos componentes técnicos;
- possui mecanismos proporcionais de prevenção, detecção e resposta a falhas ou incidentes;
- registra limitações e riscos residuais de segurança;
- atualiza as evidências de segurança quando mudanças relevantes alteram a superfície de risco da tarefa.

---

## Controle de acesso e proteção dos ativos

A avaliação considera, quando aplicável, os mecanismos que regulam o acesso a dados, modelos, códigos, ambientes de processamento e outros ativos relevantes para a tarefa.

Podem ser consideradas evidências sobre:

- autenticação e autorização;
- segregação de permissões por função;
- restrição de acesso a dados sensíveis;
- controle de acesso a ambientes de desenvolvimento ou produção;
- registros de acesso e uso;
- proteção de credenciais;
- mecanismos de isolamento, quando necessários.

A adoção de ambientes isolados, salas seguras ou outros controles específicos depende do contexto e não constitui requisito universal do FIAR-Saúde.

---

## Proteção de componentes e infraestrutura

Quando a tarefa depender de infraestrutura computacional específica, a avaliação pode considerar medidas destinadas a preservar a integridade, a disponibilidade e o funcionamento esperado de seus componentes.

Exemplos incluem:

- configuração e hardening de ambientes;
- isolamento de redes ou serviços;
- proteção contra alteração não autorizada de modelos ou código;
- gestão de dependências e componentes;
- mecanismos de backup e recuperação;
- segregação entre ambientes de desenvolvimento, teste e produção;
- proteção de armazenamento e serviços críticos.

Esses mecanismos são avaliados de forma proporcional ao estágio da tarefa e à infraestrutura efetivamente utilizada.

---

## Monitoramento e resposta a incidentes

Para tarefas em produção, ou quando o risco justificar, a avaliação considera a existência de mecanismos para detectar, registrar e responder a eventos de segurança.

Podem ser consideradas evidências como:

- registros estruturados de incidentes;
- procedimentos de resposta;
- planos de contingência;
- definição de responsabilidades;
- ações corretivas documentadas;
- registros de comunicação institucional;
- monitoramento de eventos ou acessos relevantes;
- revisão de controles após incidentes.

A ausência de histórico de incidentes não demonstra, por si só, que os mecanismos de segurança são adequados. O foco da avaliação é verificar se os processos necessários estão definidos e se, quando acionados, deixam evidências rastreáveis.

---

## Riscos associados

Limitações nas práticas de Segurança podem contribuir para riscos como:

- acesso não autorizado a dados, modelos ou ambientes;
- alteração indevida de modelos, parâmetros, códigos ou resultados;
- comprometimento da integridade dos resultados;
- indisponibilidade de componentes relevantes;
- perda de rastreabilidade sobre alterações ou acessos;
- continuidade inadequada do serviço em tarefas operacionais;
- ausência de resposta estruturada a incidentes;
- mudanças na infraestrutura ou na operação sem reavaliação dos riscos correspondentes.

---

## Evidências esperadas

Dependendo da tarefa, da Trilha de Execução e do Contexto de Uso, podem constituir evidências relevantes:

- documentação dos ativos e ambientes utilizados;
- descrição de mecanismos de autenticação e autorização;
- políticas ou procedimentos de controle de acesso;
- registros de permissões;
- documentação de isolamento ou proteção de ambientes;
- registros de versões e mudanças em componentes técnicos;
- procedimentos de backup ou recuperação, quando aplicáveis;
- documentação de riscos de segurança;
- registros de incidentes e ações corretivas;
- planos de contingência ou resposta;
- evidências de monitoramento para tarefas em produção;
- Registro de Decisão Técnica relacionado a riscos ou controles de segurança.

A ausência de determinada evidência deve ser analisada quanto à sua aplicabilidade ao requisito, à Trilha de Execução e ao Contexto de Uso. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.


---

## Requisitos e mecanismos de verificação

| ID | Requisito ou questão de avaliação | Exemplos de evidências | Mecanismos de verificação |
|---|---|---|---|
| SEG-01 | Os ativos, componentes e ambientes relevantes para a tarefa estão identificados? | Model Card, documentação técnica, arquitetura do sistema | Verificação documental; análise de suficiência |
| SEG-02 | Os riscos de segurança relevantes para o contexto e o estágio da tarefa foram identificados e documentados? | documentação de riscos, Model Card, Registro de Decisão Técnica | Verificação documental; contextualização |
| SEG-03 | Os mecanismos de controle de acesso são adequados aos dados, modelos e ambientes relevantes? | políticas de acesso, permissões, documentação técnica | Verificação documental; verificação institucional; contextualização |
| SEG-04 | Existem mecanismos proporcionais para preservar a integridade dos componentes e resultados da tarefa? | documentação de infraestrutura, versionamento, controles técnicos | Revisão documental; rastreabilidade; revisão técnica |
| SEG-05 | Quando a disponibilidade for relevante ao contexto de uso, existem mecanismos adequados de continuidade, backup ou recuperação? | planos de contingência, documentação de infraestrutura | Verificação documental; contextualização |
| SEG-06 | Mudanças relevantes em componentes, ambientes ou dependências são rastreáveis? | histórico de versões, logs de implantação, registros técnicos | Verificação de rastreabilidade e versionamento |
| SEG-07 | Para tarefas em produção, existem mecanismos definidos de monitoramento e resposta a incidentes? | plano de resposta, registros de monitoramento, documentação operacional | Análise de evidências operacionais; verificação documental |
| SEG-08 | Incidentes relevantes, quando existentes, são registrados e associados a ações corretivas? | registros de incidentes, Registro de Decisão Técnica, ações corretivas | Rastreabilidade entre incidente e resposta |
| SEG-09 | Limitações e riscos residuais de segurança estão documentados e associados a decisões ou condicionantes quando necessário? | documentação de riscos, decisões técnicas, condicionantes | Verificação documental; rastreabilidade |
| SEG-10 | A tarefa é reavaliada quando mudanças relevantes alteram seu perfil de risco de segurança? | histórico de versões, registros de reavaliação | Rastreabilidade longitudinal |


---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** existem evidências adequadas sobre os riscos e controles relevantes?
- **Consistência:** os controles declarados são coerentes com os ativos, ambientes e riscos descritos?
- **Rastreabilidade:** é possível relacionar controles, mudanças, incidentes e respostas às versões e componentes correspondentes?
- **Contextualização:** os mecanismos de segurança são proporcionais ao estágio, à Trilha de Execução, aos riscos e ao Contexto de Uso?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Segurança produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Segurança não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.

---

## Relação com o processo de avaliação

Para o processo completo de avaliação, consulte:

→ [Ciclo de Avaliação Técnica](../ciclo_avaliacao.md)
