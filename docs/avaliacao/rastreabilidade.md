# Avaliação de Rastreabilidade

A dimensão de **Rastreabilidade** do FIAR-Saúde avalia se é possível reconstruir, de forma verificável e proporcional ao contexto, os estados relevantes de uma Tarefa de IA e as relações entre versões, dados, modelos, procedimentos, evidências, mudanças e registros produzidos ao longo de seu ciclo de vida.

A rastreabilidade permite identificar a que Tarefa de IA, Versão Avaliável, Contexto de Uso e período determinada evidência ou resultado se refere, bem como compreender mudanças relevantes ocorridas entre diferentes estados da tarefa.

Em sistemas de IA, dados, modelos, procedimentos, dependências, parâmetros, documentos e condições de uso podem mudar ao longo do tempo. Sem registros adequados dessas mudanças, evidências produzidas em momentos diferentes podem ser indevidamente associadas a versões distintas da tarefa, dificultando a avaliação técnica, a investigação de inconsistências, a revisão de decisões e o acompanhamento longitudinal.

A dimensão não pressupõe que toda tarefa possua rastreamento completo de cada dado individual até cada resultado produzido pelo modelo. O nível de rastreabilidade necessário depende da natureza da tarefa, da Versão Avaliável, do Contexto de Uso, da Trilha de Execução e dos requisitos cuja análise depende dessas relações.

**A rastreabilidade também não deve ser confundida com Transparência, Responsabilização ou Governança.** Transparência trata da disponibilidade e compreensão das informações relevantes; Responsabilização trata da atribuição de responsabilidades e da prestação de contas; Governança trata das estruturas e processos institucionais de decisão e supervisão. A Rastreabilidade verifica se os objetos, registros, evidências e mudanças relevantes podem ser relacionados e reconstruídos ao longo do ciclo de vida da tarefa.

---

## Objetivo da dimensão

A avaliação de Rastreabilidade busca verificar se o projeto:

- identifica de forma inequívoca o estado da Tarefa de IA ao qual as evidências se referem;
- mantém registros suficientes das versões relevantes de dados, modelos, procedimentos e outros componentes associados à tarefa;
- permite identificar a origem, a versão, a data ou o período e a pertinência das evidências utilizadas na avaliação;
- documenta mudanças relevantes de modo que seja possível reconstruir a evolução da tarefa;
- preserva relações entre evidências, achados, decisões e ações quando necessárias para compreender o ciclo avaliado;
- mantém histórico suficiente de substituições, correções e atualizações relevantes;
- permite reconstruir, quando necessário, relações entre dados, modelos, procedimentos e resultados;
- mantém rastreabilidade longitudinal de eventos e mudanças operacionais quando aplicável à Trilha de Execução.

---

## Identificação da tarefa e de seus componentes

A rastreabilidade começa pela possibilidade de identificar de forma inequívoca o estado da tarefa considerado em determinado ciclo de avaliação.

Devem ser identificáveis, conforme aplicável:

- Tarefa de IA;
- Versão Avaliável;
- Contexto de Uso;
- Trilha de Execução;
- versão ou estado do modelo;
- dados ou versões de conjuntos de dados utilizados;
- procedimentos relevantes de preparação, treinamento, validação ou avaliação;
- configurações ou parâmetros relevantes;
- componentes técnicos que possam afetar as evidências analisadas;
- período ao qual os resultados ou evidências se referem.

Nem toda alteração técnica caracteriza uma nova Versão Avaliável. A determinação de uma nova Versão Avaliável depende da relevância da mudança para o objeto avaliado e para os requisitos de IAR aplicáveis.

Entretanto, alterações que não produzam uma nova Versão Avaliável podem ainda precisar ser registradas quando forem necessárias para compreender evidências, resultados ou mudanças relevantes na tarefa.

---

## Proveniência e associação das evidências

As evidências utilizadas no FIAR-Saúde devem poder ser associadas ao objeto efetivamente avaliado.

Quando relevante, deve ser possível identificar:

- origem da evidência;
- documento, sistema ou processo que a produziu;
- data ou período de produção;
- versão do artefato;
- versão dos dados ou modelo aos quais se refere;
- relação com a Tarefa de IA e com a Versão Avaliável;
- eventual substituição ou atualização posterior.

Uma evidência não deve ser considerada pertinente apenas porque está presente no repositório ou foi produzida pelo projeto. Deve ser possível determinar se ela corresponde ao estado da tarefa considerado no ciclo.

A rastreabilidade da evidência não exige um formato documental único. Diferentes mecanismos de registro podem ser utilizados desde que permitam estabelecer de forma verificável sua origem, versão e relação com o objeto avaliado.

---

## Versionamento e mudanças relevantes

A avaliação considera se mudanças relevantes são registradas de maneira suficiente para reconstruir a evolução da tarefa.

Conforme aplicável, podem ser consideradas mudanças em:

- dados utilizados;
- critérios de inclusão ou exclusão;
- preparação ou transformação dos dados;
- modelo ou arquitetura;
- parâmetros relevantes;
- procedimentos de treinamento ou validação;
- métricas;
- thresholds;
- componentes de software;
- dependências relevantes;
- interfaces ou fluxos operacionais;
- Contexto de Uso;
- condições ou restrições de utilização.

O objetivo não é registrar indiscriminadamente toda alteração realizada durante o desenvolvimento. Devem ser preservadas as mudanças necessárias para compreender o estado da tarefa, interpretar corretamente as evidências e identificar possíveis impactos sobre requisitos ou conclusões anteriores.

Mudanças relevantes devem poder ser relacionadas, quando pertinente, às evidências, análises ou decisões que motivaram ou resultaram da alteração.

---

## Relações entre dados, modelo, procedimentos e resultados

Quando necessário para a avaliação, deve ser possível reconstruir as relações entre os principais elementos técnicos que produziram uma evidência ou resultado.

Dependendo da natureza da tarefa, isso pode envolver:

- conjunto ou versão dos dados utilizados;
- procedimentos de preparação ou seleção dos dados;
- versão do modelo;
- configuração ou parâmetros relevantes;
- procedimento experimental ou operacional;
- métricas utilizadas;
- resultados obtidos;
- artefatos ou relatórios nos quais esses resultados foram registrados.

O nível de detalhamento necessário depende do requisito analisado e do Contexto de Uso.

O FIAR-Saúde não exige, como regra geral, rastreamento individual de cada registro de entrada até cada resultado produzido pelo sistema, nem reprodução integral do ambiente computacional. Esses mecanismos podem ser necessários em situações específicas quando sua ausência impedir a verificação de requisito aplicável ou quando forem exigidos pelo contexto técnico, institucional ou regulatório.

---

## Preservação do histórico

A atualização de documentos, modelos, dados ou registros não deve eliminar informações necessárias para distinguir estados anteriores e atuais da tarefa.

Quando relevante, deve ser possível identificar:

- qual registro ou versão foi substituído;
- qual versão o substituiu;
- quando ocorreu a alteração;
- qual foi a natureza da mudança;
- quais evidências ou análises podem ter sido afetadas.

Correções documentais também podem exigir preservação de histórico quando alterarem informações utilizadas na avaliação.

A preservação do histórico não implica manutenção indefinida de todos os arquivos ou versões produzidos durante o desenvolvimento. O nível de retenção deve ser suficiente para reconstruir os estados e mudanças relevantes ao processo de avaliação e ao acompanhamento da tarefa.

---

## Rastreabilidade longitudinal e operação

Para tarefas na Trilha Produção, podem ser necessárias evidências adicionais que permitam relacionar eventos operacionais ao estado da tarefa correspondente.

Conforme aplicável, podem ser considerados:

- versões implantadas;
- datas ou períodos de implantação;
- atualizações ou substituições;
- registros de monitoramento;
- incidentes ou eventos relevantes;
- ações corretivas;
- rollback ou suspensão;
- alterações de configuração;
- reavaliações realizadas;
- mudanças relevantes no Contexto de Uso.

Esses registros devem permitir, quando necessário, determinar qual versão estava em uso, quais evidências estavam vigentes e quais mudanças ocorreram antes ou após determinado evento.

Tarefas na Trilha Experimental podem requerer níveis diferentes de rastreabilidade, concentrados principalmente nos dados, modelos, procedimentos experimentais, resultados e versões utilizadas na avaliação.

---

## Relação com outras dimensões

A Rastreabilidade possui relação transversal com as demais dimensões de IA Responsável, mas seu objeto de avaliação é específico.

Em particular:

- **Governança** avalia se processos, competências e mecanismos institucionais adequados estão definidos; a Rastreabilidade verifica se os registros desses processos e mudanças podem ser associados ao estado correspondente da tarefa;
- **Responsabilização** avalia quem possui responsabilidade e competência para determinadas decisões; a Rastreabilidade permite relacionar decisões e registros às evidências e versões correspondentes;
- **Transparência** avalia se informações relevantes estão adequadamente documentadas e comunicadas; a Rastreabilidade verifica se essas informações podem ser associadas ao objeto e à versão corretos;
- **Privacidade** avalia o tratamento e a proteção dos dados; a Rastreabilidade pode apoiar a identificação de origem, versão e condições de utilização dos dados;
- **Segurança** avalia mecanismos de proteção e resposta a riscos técnicos e operacionais; registros de acesso, alteração ou incidentes podem também constituir evidências de Rastreabilidade;
- **Justiça** avalia disparidades relevantes e seu tratamento; a Rastreabilidade permite associar análises e resultados de Justiça aos dados, modelos e versões correspondentes.

Uma mesma evidência pode, portanto, contribuir para diferentes dimensões sem que os respectivos requisitos sejam equivalentes.

---

## Riscos associados

Limitações de Rastreabilidade podem contribuir para riscos como:

- utilização de evidências produzidas para uma versão diferente daquela avaliada;
- impossibilidade de determinar quais dados, modelos ou procedimentos produziram determinado resultado;
- perda do histórico de alterações relevantes;
- mudanças relevantes sem identificação de seus possíveis impactos sobre evidências anteriores;
- dificuldade de investigar inconsistências, falhas ou incidentes;
- impossibilidade de relacionar decisões ou ações às evidências que as motivaram;
- confusão entre documentos ou resultados referentes a diferentes estados da tarefa;
- reavaliações conduzidas com base em evidências desatualizadas;
- dificuldade de reconstruir a evolução da tarefa ao longo de sucessivos ciclos.

---

## Evidências esperadas

Dependendo da Tarefa de IA, da Versão Avaliável, do Contexto de Uso e da Trilha de Execução, podem constituir evidências relevantes:

- Identificação da Avaliação;
- Data Card ou documentação equivalente;
- Model Card ou documentação equivalente;
- documentação técnica dos dados, modelos ou pipelines;
- identificadores ou registros de versões;
- histórico de alterações;
- registros de experimentos;
- documentação de treinamento e validação;
- registros de resultados e métricas;
- Registros de Decisão Técnica;
- histórico de validação;
- Controle de Artefatos;
- documentação de mudanças relevantes;
- registros de substituição ou correção documental;
- sistemas de versionamento;
- logs ou registros operacionais, quando aplicáveis;
- registros de implantação ou rollback;
- relatórios de monitoramento;
- registros de incidentes;
- documentação de reavaliações anteriores.

A existência de um sistema específico de versionamento, de logs automatizados ou de uma ferramenta dedicada de linhagem não constitui requisito universal do FIAR-Saúde.

A ausência de determinado artefato deve ser analisada quanto à sua necessidade para o requisito, à natureza da tarefa e à Trilha de Execução. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

| ID     | Requisito ou questão de avaliação                                                                                                                               | Exemplos de evidências                                                                                       | Mecanismos de verificação                                                         |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| RAS-01 | A Tarefa de IA e os componentes ou versões relevantes ao estado avaliado podem ser identificados de forma inequívoca?                                            | Identificação da Avaliação, Model Card, Data Card, documentação técnica, registros de versão          | Verificação documental; consistência cruzada; versionamento                      |
| RAS-02 | A origem, versão, data ou período e relação das evidências com a unidade de avaliação podem ser identificadas?                                              | Controle de Artefatos, histórico de validação, artefatos versionados, registros técnicos                  | Verificação documental; rastreabilidade entre evidência e unidade de avaliação |
| RAS-03 | Mudanças relevantes na tarefa ou em seus componentes estão registradas de forma que sua evolução possa ser reconstruída?                                      | histórico de versões, registros de mudanças, Registro de Decisão Técnica, documentação técnica        | Comparação entre versões; verificação documental; rastreabilidade longitudinal |
| RAS-04 | Evidências, achados, decisões e ações relacionadas podem ser vinculados quando essa relação for necessária para reconstruir o ciclo avaliado?               | Registros de Decisão Técnica, relatórios de avaliação, registro de pendências, decisões institucionais | Rastreamento entre registros; consistência cruzada                                 |
| RAS-05 | Quando necessário à avaliação, é possível reconstruir a relação entre dados, modelo, procedimentos e resultados relevantes?                                | Data Card, Model Card, registros de experimentos, documentação de pipeline, resultados técnicos            | Revisão documental; revisão metodológica; rastreabilidade técnica               |
| RAS-06 | Substituições, correções ou atualizações relevantes preservam histórico suficiente para distinguir estados anteriores e atuais da tarefa e das evidências? | histórico de versões, controle de artefatos, histórico de validação, registros de mudanças              | Comparação entre versões; verificação de histórico                            |
| RAS-07 | Para tarefas em produção, eventos operacionais relevantes podem ser associados à versão da tarefa e ao período correspondentes?                               | registros de implantação, monitoramento, incidentes, logs, histórico de versões, registros de rollback    | Análise de evidências operacionais; rastreabilidade longitudinal                  |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** os registros disponíveis permitem reconstruir adequadamente o estado, a origem, as relações ou as mudanças relevantes para o requisito?
- **Consistência:** versões, datas, identificadores, resultados e relações entre registros são compatíveis entre as diferentes fontes?
- **Rastreabilidade:** é possível estabelecer uma cadeia verificável entre a evidência, o objeto avaliado, as versões e as mudanças relevantes?
- **Pertinência:** os registros reconstruídos correspondem efetivamente à Tarefa de IA, à Versão Avaliável e ao Contexto de Uso considerados?
- **Atualidade:** a evidência permanece válida para o estado da tarefa considerado no ciclo?
- **Contextualização:** o nível de rastreabilidade é proporcional à natureza da tarefa, ao requisito analisado, ao Contexto de Uso e à Trilha de Execução?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Rastreabilidade produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Rastreabilidade não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal, a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável observadas ao longo de sucessivos ciclos.

---
