# Avaliação de Segurança

A dimensão de **Segurança** do FIAR-Saúde avalia se a Tarefa de IA e seus componentes relevantes estão protegidos, de forma proporcional ao contexto e aos riscos identificados, contra falhas, uso indevido, acesso ou alteração não autorizados, comprometimento e outras condições capazes de afetar sua integridade, disponibilidade, funcionamento esperado ou confiabilidade.

A Segurança pode envolver dados, modelos, artefatos técnicos, código, configurações, dependências, ambientes computacionais e componentes operacionais relacionados à tarefa.

A dimensão não constitui uma auditoria geral da infraestrutura de tecnologia da informação da organização. Devem ser considerados os componentes, ambientes, ameaças e controles que possuam relação material com a Tarefa de IA, a Versão Avaliável e o Contexto de Uso considerados no ciclo.

A necessidade e o nível de aprofundamento dos mecanismos de segurança dependem da natureza da tarefa, dos riscos relevantes, do Contexto de Uso e da Trilha de Execução. Tarefas experimentais e tarefas integradas a sistemas em operação podem, portanto, exigir controles e evidências diferentes.

O FIAR-Saúde não pressupõe a adoção universal de técnicas específicas como pentest, red teaming, hardening, isolamento, monitoramento contínuo, testes adversariais ou mecanismos de rollback. Esses mecanismos devem ser considerados quando forem pertinentes aos riscos e às condições concretas da tarefa.

---

## Objetivo da dimensão

A avaliação de Segurança busca verificar se o projeto:

- identifica os ativos, componentes e ambientes relevantes para a segurança da Tarefa de IA;
- identifica riscos de segurança compatíveis com a natureza da tarefa, seu Contexto de Uso e sua Trilha de Execução;
- controla o acesso aos componentes relevantes de forma proporcional aos riscos identificados;
- protege a integridade da tarefa e de seus componentes contra alterações, comprometimento ou uso indevido;
- considera disponibilidade, continuidade e recuperação quando forem materialmente relevantes ao Contexto de Uso;
- adota controles de segurança compatíveis com os ambientes de desenvolvimento, avaliação ou execução efetivamente utilizados;
- possui mecanismos proporcionais de detecção e resposta a eventos ou incidentes quando necessários;
- considera riscos específicos de IA quando forem pertinentes à arquitetura, à tarefa ou ao Contexto de Uso.

---

## Ativos, componentes e riscos relevantes

A avaliação de Segurança deve partir da identificação dos elementos da Tarefa de IA cuja proteção seja materialmente relevante.

Conforme a natureza da tarefa, podem ser considerados:

- dados;
- modelos;
- pesos ou parâmetros;
- código;
- configurações;
- pipelines;
- artefatos produzidos durante treinamento, validação ou execução;
- dependências de software;
- interfaces;
- serviços externos;
- ambientes de desenvolvimento;
- ambientes de avaliação;
- ambientes de produção;
- armazenamento;
- credenciais;
- outros componentes técnicos ou operacionais relevantes.

A identificação desses elementos não exige inventário exaustivo de toda a infraestrutura institucional.

Devem ser considerados os componentes cuja perda, alteração, acesso indevido, indisponibilidade ou comprometimento possa afetar materialmente a Tarefa de IA, seu funcionamento ou os resultados relevantes para o escopo avaliado.

Os riscos de segurança devem ser analisados em relação aos ativos e ao contexto efetivamente relevantes para a tarefa.

Conforme aplicável, podem incluir:

- acesso não autorizado;
- uso indevido;
- alteração não autorizada;
- comprometimento de modelos, código ou configurações;
- corrupção ou perda de dados ou artefatos;
- indisponibilidade;
- comprometimento de dependências;
- falhas de configuração;
- exposição de credenciais;
- falhas capazes de produzir comportamento inesperado ou resultados não confiáveis;
- riscos específicos de IA pertinentes à tarefa.

Riscos específicos de IA não devem ser presumidos uniformemente.

Dependendo da arquitetura ou do Contexto de Uso, podem ser relevantes, por exemplo, manipulação adversarial de entradas, comprometimento de dados de treinamento, extração ou alteração de modelos, uso indevido de interfaces ou outros mecanismos capazes de comprometer a tarefa.

A relevância de cada risco deve ser estabelecida antes de determinar quais controles ou testes são necessários.

---

## Controle de acesso

A avaliação considera se o acesso aos componentes relevantes da tarefa é compatível com as funções, necessidades e riscos identificados.

Podem ser considerados, conforme aplicável:

- autenticação;
- autorização;
- segregação de permissões;
- princípio de menor privilégio;
- proteção de credenciais;
- restrição de acesso a modelos, artefatos ou configurações;
- controle de acesso a ambientes de desenvolvimento, avaliação ou produção;
- controle de acesso a interfaces ou serviços;
- revisão de permissões;
- mecanismos adicionais para ativos de maior criticidade.

O FIAR-Saúde não exige uma tecnologia específica de autenticação ou autorização.

O nível de controle necessário deve ser proporcional aos ativos, ao Contexto de Uso e às consequências possíveis de um acesso indevido.

Controles de acesso relacionados a dados pessoais ou sensíveis podem também fornecer evidências para a dimensão de Privacidade. Nesse caso, a mesma evidência pode ser relevante para ambas as dimensões sem que os respectivos requisitos sejam equivalentes.

---

## Integridade da tarefa e de seus componentes

A avaliação considera se existem mecanismos proporcionais para reduzir o risco de alteração, corrupção, comprometimento ou uso indevido dos componentes relevantes da tarefa.

Conforme aplicável, podem ser considerados:

- proteção contra alterações não autorizadas de modelos ou código;
- controle de configurações relevantes;
- mecanismos para verificar integridade de artefatos;
- controle sobre componentes ou dependências utilizados;
- segregação de permissões para alteração;
- validações antes de implantação ou utilização;
- mecanismos para detectar comprometimento;
- proteção dos resultados ou artefatos produzidos pela tarefa.

A exigência de mecanismos específicos depende dos riscos identificados.

Versionamento e histórico de mudanças podem fornecer evidências úteis à análise, mas a reconstrução de versões e alterações ao longo do ciclo de vida pertence principalmente à dimensão de Rastreabilidade.

---

## Disponibilidade, falhas e recuperação

A disponibilidade não possui a mesma relevância para todas as Tarefas de IA.

Quando a indisponibilidade ou falha puder afetar materialmente o Contexto de Uso, a avaliação considera se existem mecanismos proporcionais para lidar com essas situações.

Conforme aplicável, podem ser considerados:

- mecanismos de recuperação;
- backup;
- redundância;
- procedimentos diante de indisponibilidade;
- comportamento seguro diante de falha;
- mecanismos de fallback;
- restauração de componentes;
- contingência;
- rollback, quando apropriado.

A existência de backup, redundância ou rollback não constitui requisito universal.

Por exemplo, uma tarefa exclusivamente experimental e reproduzível a partir de fontes preservadas pode exigir mecanismos de disponibilidade diferentes de uma tarefa integrada a um serviço assistencial em operação.

O nível de proteção deve ser determinado em função das consequências plausíveis da indisponibilidade ou falha.

---

## Segurança dos ambientes e dependências

A avaliação pode considerar controles associados aos ambientes de desenvolvimento, avaliação ou execução quando esses ambientes forem materialmente relevantes para a segurança da tarefa.

Conforme os riscos identificados, podem ser considerados:

- segregação entre ambientes;
- configuração segura;
- isolamento;
- gestão de dependências;
- proteção de serviços ou interfaces;
- atualização de componentes;
- gestão de credenciais;
- proteção de armazenamento;
- segmentação de acesso ou rede;
- outros controles técnicos pertinentes.

A existência de uma infraestrutura institucional ampla não implica que todos os seus controles devam ser avaliados pelo FIAR-Saúde.

A análise deve permanecer limitada aos aspectos capazes de afetar materialmente a segurança da Tarefa de IA e seus componentes relevantes.

Hardening, isolamento, segmentação ou outros mecanismos específicos somente devem ser considerados necessários quando houver relação demonstrável com os riscos da tarefa.

---

## Eventos, incidentes e resposta

Para tarefas na Trilha Produção, ou em outras situações nas quais os riscos identificados justifiquem esse nível de controle, a avaliação considera se existem mecanismos proporcionais para detectar e responder a eventos ou incidentes relevantes de segurança.

Conforme aplicável, podem ser considerados:

- detecção de eventos relevantes;
- monitoramento de acessos ou alterações;
- registro de incidentes;
- mecanismos de alerta;
- procedimentos técnicos de contenção;
- correção ou recuperação;
- revisão dos controles após incidentes;
- preservação das informações necessárias para análise posterior.

Nem todo projeto precisa de monitoramento contínuo ou de um sistema dedicado de gestão de incidentes.

A frequência, o nível de automação e a granularidade desses mecanismos dependem da Trilha de Execução, do Contexto de Uso e dos riscos identificados.

A ausência de histórico de incidentes não demonstra, por si só, que os mecanismos de segurança são adequados.

Quando incidentes ocorrerem, sua rastreabilidade, as responsabilidades associadas e eventuais decisões institucionais podem produzir evidências relevantes também para Rastreabilidade, Responsabilização e Governança.

---

## Relação com outras dimensões

A Segurança possui relação transversal com outras dimensões de IA Responsável, mas seu objeto de avaliação é específico.

Em particular:

- **Privacidade** avalia o tratamento e a proteção de dados pessoais ou sensíveis; Segurança avalia a proteção da tarefa e de seus componentes contra riscos técnicos ou operacionais, inclusive quando os ativos não contêm dados pessoais;
- **Governança** avalia estruturas, competências, processos de decisão, supervisão, tratamento e escalonamento; Segurança avalia os riscos e controles técnicos ou operacionais necessários para proteger a tarefa;
- **Rastreabilidade** avalia se versões, eventos, mudanças e registros relevantes podem ser reconstruídos; Segurança pode utilizar esses registros como evidência para identificar alterações, comprometimentos ou incidentes;
- **Transparência** avalia se informações relevantes sobre riscos, limitações e condições da tarefa estão adequadamente documentadas ou comunicadas; Segurança avalia se os riscos correspondentes possuem proteção compatível;
- **Responsabilização** pode avaliar quem responde por ações ou decisões relacionadas a segurança; Segurança não substitui a atribuição de responsabilidade ou prestação de contas.

Uma mesma evidência pode sustentar requisitos de diferentes dimensões sem que os respectivos requisitos sejam equivalentes.

---

## Riscos associados

Limitações nas práticas de Segurança podem contribuir para riscos como:

- acesso não autorizado a componentes relevantes da tarefa;
- uso indevido de modelos, interfaces ou ambientes;
- alteração não autorizada de modelos, código, configurações ou artefatos;
- comprometimento da integridade de dados ou resultados;
- utilização de componentes ou dependências comprometidos;
- perda ou corrupção de artefatos relevantes;
- indisponibilidade com impacto material no Contexto de Uso;
- comportamento inadequado diante de falhas;
- detecção tardia ou inexistente de comprometimentos;
- resposta insuficiente a incidentes;
- utilização de controles incompatíveis com os riscos concretos da tarefa;
- riscos específicos de IA não considerados quando materialmente pertinentes.

---

## Evidências esperadas

Dependendo da Tarefa de IA, da Versão Avaliável, do Contexto de Uso, da Trilha de Execução e dos riscos identificados, podem constituir evidências relevantes:

- documentação dos ativos e componentes relevantes;
- documentação da arquitetura ou dos ambientes utilizados;
- análise ou registro de riscos de segurança;
- documentação de autenticação e autorização;
- registros ou definições de permissões;
- documentação de proteção de credenciais;
- controles de integridade;
- documentação de dependências;
- registros de configuração;
- documentação de mecanismos de recuperação ou contingência;
- evidências de segregação ou isolamento, quando aplicáveis;
- resultados de verificações ou testes técnicos de segurança, quando necessários;
- registros de incidentes;
- documentação de resposta ou ações corretivas;
- registros de monitoramento, quando aplicáveis;
- Registros de Decisão Técnica relacionados a riscos ou controles de segurança;
- outras evidências capazes de demonstrar os controles pertinentes ao risco analisado.

Pentest, red teaming, testes adversariais, hardening, isolamento, logs operacionais, monitoramento contínuo ou mecanismos de rollback não constituem evidências universalmente obrigatórias.

A necessidade de uma evidência deve ser determinada a partir do requisito e do risco aplicável. Somente então deve ser identificada a fonte ou o artefato adequado.

A ausência de determinado tipo de artefato ou mecanismo não implica, isoladamente, Não Conformidade.

---

## Requisitos e mecanismos de verificação

| ID     | Requisito ou questão de avaliação                                                                                                                                                                                   | Exemplos de evidências                                                                                           | Mecanismos de verificação                                                       |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| SEG-01 | Os ativos, componentes, ambientes e riscos de segurança relevantes para a Tarefa de IA estão identificados e documentados de forma compatível com seu Contexto de Uso e sua Trilha de Execução?                   | documentação técnica, arquitetura, registro de riscos, Model Card ou documentação equivalente                | Verificação documental; análise de suficiência; contextualização            |
| SEG-02 | Existem mecanismos proporcionais para restringir e controlar o acesso aos dados, modelos, artefatos e ambientes relevantes para a tarefa?                                                                              | documentação de acesso, permissões, autenticação, autorização, registros institucionais                    | Verificação documental; revisão técnica; contextualização                   |
| SEG-03 | Existem mecanismos proporcionais para proteger a integridade da tarefa e de seus componentes relevantes contra alteração, comprometimento ou uso indevido?                                                           | controles de integridade, documentação técnica, configurações, registros de validação                      | Revisão documental; revisão técnica; análise de suficiência                  |
| SEG-04 | Quando a disponibilidade ou a continuidade forem relevantes ao Contexto de Uso, existem mecanismos proporcionais para lidar com falhas, indisponibilidade e recuperação da tarefa ou de seus componentes relevantes? | documentação de recuperação, contingência, backup, fallback ou mecanismos equivalentes                       | Verificação documental; contextualização; revisão técnica                   |
| SEG-05 | Os controles de segurança aplicáveis ao ambiente de desenvolvimento, avaliação ou execução são compatíveis com os riscos relevantes da tarefa?                                                                 | documentação dos ambientes, controles técnicos, dependências, configuração e proteção de serviços        | Revisão documental; revisão técnica; contextualização                        |
| SEG-06 | Para tarefas em produção, ou quando o risco identificado justificar, existem mecanismos proporcionais para detectar, registrar e responder a eventos ou incidentes de segurança relevantes?                         | registros de monitoramento, procedimentos de resposta, registros de incidentes, evidências de ações corretivas | Análise de evidências operacionais; verificação documental; revisão técnica |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** as evidências disponíveis permitem compreender os riscos relevantes e demonstrar os controles correspondentes?
- **Consistência:** os riscos, ativos, ambientes e controles descritos são compatíveis entre as diferentes fontes?
- **Rastreabilidade:** é possível relacionar a evidência de segurança à Tarefa de IA, à Versão Avaliável, ao componente e ao período pertinentes?
- **Pertinência:** os controles analisados correspondem efetivamente aos riscos e componentes relevantes para o objeto avaliado?
- **Atualidade:** as evidências de segurança permanecem válidas para a Versão Avaliável e para os ambientes considerados no ciclo?
- **Contextualização:** os mecanismos são proporcionais à natureza da tarefa, aos riscos identificados, ao Contexto de Uso e à Trilha de Execução?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Segurança produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Segurança não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal, a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável observadas ao longo de sucessivos ciclos.
