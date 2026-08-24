# Avaliação de Justiça (Fairness)

A dimensão de **Justiça** do FIAR-Saúde examina evidências de possíveis disparidades relevantes na forma como uma Tarefa de IA afeta ou apresenta desempenho entre diferentes grupos, populações, territórios ou unidades pertinentes ao seu contexto de uso.

Em saúde, essas diferenças podem estar relacionadas tanto ao comportamento do modelo quanto às características dos dados e às desigualdades estruturais presentes no contexto em que a tarefa é desenvolvida ou utilizada. Por isso, a análise de Justiça não se limita à comparação de métricas entre atributos demográficos, nem pressupõe que toda diferença observada represente automaticamente injustiça ou discriminação.

A avaliação busca verificar se os grupos e riscos relevantes foram adequadamente identificados, se existem evidências apropriadas para analisar possíveis disparidades, como essas evidências foram interpretadas no contexto de uso e como achados relevantes foram tratados, documentados ou acompanhados.

A análise de Justiça está alinhada à literatura sobre fairness em sistemas de IA e a referências internacionais de IA Responsável, devendo ser adaptada à natureza da tarefa e ao contexto de saúde avaliado.

---

## Objetivo da dimensão

A análise de Justiça busca avaliar se o projeto:

- identifica grupos, populações, territórios ou unidades relevantes para o contexto de uso;
- documenta limitações de cobertura, representação ou qualidade dos dados que possam afetar esses grupos;
- avalia diferenças de desempenho ou impacto quando isso for aplicável à tarefa;
- utiliza métricas e métodos adequados à natureza do problema;
- interpreta disparidades observadas considerando o contexto de uso e as limitações das evidências;
- investiga possíveis causas quando forem identificadas disparidades relevantes;
- considera medidas de mitigação, restrições, monitoramento ou justificativas quando necessário;
- registra riscos residuais e decisões associadas aos achados de Justiça.

A avaliação não pressupõe que todo sistema apresente viés, mas busca identificar **riscos potenciais e evidências disponíveis**.

---

## Identificação de grupos relevantes

A avaliação começa pela identificação dos grupos, populações, territórios ou unidades relevantes para a Tarefa de IA e seu Contexto de Uso.

A seleção não deve decorrer apenas da disponibilidade de atributos no dataset. Ela deve ser justificada considerando, quando aplicável:

- população afetada;
- finalidade clínica ou operacional;
- desigualdades conhecidas no contexto;
- características dos dados;
- consequências potenciais dos erros;
- requisitos éticos, institucionais ou regulatórios aplicáveis.

Exemplos podem incluir:

- sexo ou gênero;
- faixa etária;
- raça ou etnia, quando disponível e apropriado;
- região geográfica;
- condição socioeconômica;
- condições clínicas ou comorbidades;
- unidades territoriais ou institucionais;
- outros grupos relevantes para a tarefa.

Nem todas essas categorias são aplicáveis a todas as tarefas.

Quando informações necessárias não estiverem disponíveis, essa limitação deve ser registrada e considerada na interpretação da evidência.

---

## Análise de desempenho por grupo

Quando aplicável, o desempenho ou os impactos relevantes da tarefa devem ser analisados de forma estratificada entre os grupos identificados.

As métricas utilizadas devem ser adequadas ao tipo de tarefa.

Exemplos incluem:

- classificação: acurácia, precisão, recall, sensibilidade, especificidade, taxas de falsos positivos e falsos negativos, AUC;
- regressão ou previsão: MAE, RMSE, sMAPE ou outras métricas adequadas;
- outros tipos de tarefa: métricas específicas ao domínio e ao objetivo avaliado.

A avaliação não deve se limitar à existência de diferenças numéricas entre grupos. Deve considerar:

- magnitude da diferença;
- incerteza ou estabilidade da estimativa, quando pertinente;
- tamanho e composição dos grupos;
- consequências potenciais da diferença;
- adequação da métrica ao contexto de uso.

A existência de uma disparidade não implica automaticamente uma conclusão de injustiça. Ela constitui um achado que deve ser interpretado no contexto da tarefa.

---

## Possíveis fontes de disparidade ou viés

A avaliação pode considerar possíveis fatores associados às disparidades observadas, como:

- diferenças de representação ou cobertura nos dados;
- diferenças de qualidade, completude ou medição entre grupos;
- sub-representação de determinadas populações;
- decisões de seleção, exclusão ou pré-processamento;
- uso de variáveis associadas a características socialmente relevantes;
- escolhas de modelagem;
- diferenças estruturais ou epidemiológicas entre contextos;
- mudanças de distribuição ao longo do tempo.

A identificação de uma possível fonte de viés não demonstra, isoladamente, discriminação ou causalidade. Quando a evidência disponível não permite estabelecer a origem de uma disparidade, essa limitação deve ser explicitada.

---

## Tratamento de disparidades

Quando forem identificadas disparidades relevantes, a avaliação verifica como o projeto as investigou e tratou.

As respostas possíveis não se limitam à modificação do modelo. Dependendo do contexto, podem incluir:

- investigação adicional das causas;
- melhoria da cobertura ou qualidade dos dados;
- revisão de critérios de inclusão ou exclusão;
- técnicas de reamostragem ou balanceamento;
- ajustes no modelo ou no processo decisório;
- alteração de thresholds, quando aplicável;
- restrições ou condicionantes de uso;
- monitoramento específico por grupo;
- reconhecimento explícito de limitações;
- aceite institucional de risco residual, quando aplicável.

Quando uma estratégia de mitigação for aplicada, devem ser documentados seus efeitos, limitações e eventuais trade-offs.

A ausência de mitigação técnica não implica automaticamente inadequação, desde que a decisão seja compatível com o contexto de uso e adequadamente fundamentada.

---

## Riscos associados

A ausência ou inadequação da avaliação de Justiça pode contribuir para riscos como:

- desempenho sistematicamente inferior para determinados grupos;
- impactos desiguais sobre populações ou territórios;
- reforço de desigualdades existentes;
- decisões inadequadas decorrentes de diferenças de qualidade dos dados;
- desconhecimento de limitações importantes da tarefa;
- uso do sistema em contextos para os quais seu comportamento não foi adequadamente avaliado.

---

## Evidências esperadas

Dependendo da tarefa, podem constituir evidências relevantes:

- Data Cards ou documentação equivalente sobre composição, cobertura, exclusões e limitações dos dados;
- Model Card ou documentação equivalente sobre contexto de uso, população, desempenho e limitações;
- análises de desempenho estratificado;
- Fairness Report ou documentação equivalente;
- justificativa para seleção dos grupos avaliados;
- documentação das métricas utilizadas;
- análise de possíveis causas de disparidade;
- registros de medidas de mitigação;
- Registro de Decisão Técnica;
- registros de riscos residuais, condicionantes ou decisões institucionais;
- evidências de monitoramento por grupo, para tarefas em produção.

A ausência de uma determinada evidência deve ser analisada quanto à sua **aplicabilidade e necessidade para o requisito avaliado**. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

A avaliação da dimensão de Justiça é organizada por requisitos ou questões de avaliação. Para cada requisito, devem ser identificadas as evidências aplicáveis e os mecanismos necessários para examiná-las.

| ID | Requisito ou questão de avaliação | Exemplos de evidências | Mecanismos de verificação |
|---|---|---|---|
| JUS-01 | Os grupos, populações, territórios ou unidades relevantes para o contexto de uso foram identificados e justificados? | Contexto de uso, Formulário de Entrada, Data Card, Model Card | Verificação documental; consistência cruzada; contextualização |
| JUS-02 | Existem limitações de cobertura, representação ou qualidade dos dados relevantes para esses grupos? | Data Card, análises descritivas, documentação de preparação dos dados | Revisão documental; revisão metodológica; consistência cruzada |
| JUS-03 | O desempenho ou impacto foi avaliado entre grupos relevantes quando aplicável? | Fairness Report, métricas estratificadas, resultados experimentais | Revisão metodológica; revisão de métricas e resultados |
| JUS-04 | As métricas e métodos utilizados são adequados à tarefa e aos grupos avaliados? | Fairness Report, protocolo experimental, Model Card | Revisão metodológica |
| JUS-05 | Disparidades identificadas foram adequadamente interpretadas no contexto de uso? | Fairness Report, documentação de limitações, análises contextuais | Contextualização; consistência entre evidências |
| JUS-06 | Quando necessário, possíveis causas das disparidades foram investigadas? | análises adicionais, documentação dos dados, registros técnicos | Revisão metodológica; consistência cruzada |
| JUS-07 | Medidas de mitigação, monitoramento, restrição ou outra resposta foram consideradas quando os achados justificaram ação? | Registro de Decisão Técnica, Fairness Report, condicionantes | Verificação documental; rastreabilidade entre achado e decisão |
| JUS-08 | Riscos residuais, limitações e trade-offs relevantes foram documentados? | Registro de Decisão Técnica, Model Card, relatório de avaliação | Verificação documental; consistência e rastreabilidade |
| JUS-09 | Para tarefas em produção, disparidades relevantes são acompanhadas longitudinalmente quando necessário? | relatórios de monitoramento, histórico de versões | Análise de evidências operacionais; rastreabilidade longitudinal |


---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** há evidência adequada para responder à questão?
- **Consistência:** os resultados e declarações são coerentes entre os diferentes artefatos?
- **Rastreabilidade:** é possível relacionar os resultados aos dados, modelo, versão e decisões correspondentes?
- **Contextualização:** os achados foram interpretados considerando adequadamente o contexto de uso e suas consequências?

Essas propriedades auxiliam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

--- 

## Resultado da avaliação da dimensão

A avaliação de Justiça produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão não recebe um nível de maturidade próprio.

Os resultados da análise de Justiça são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente, no nível do projeto e de forma longitudinal, a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável ao longo de sucessivos ciclos.
