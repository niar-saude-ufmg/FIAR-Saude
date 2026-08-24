# Avaliação de Privacidade

A dimensão de **Privacidade** do FIAR-Saúde avalia como os dados utilizados por uma Tarefa de IA são obtidos, tratados, protegidos e governados ao longo de seu ciclo de vida, considerando a natureza dos dados, a finalidade do tratamento e o Contexto de Uso.

Em saúde, podem estar envolvidos dados pessoais, dados pessoais sensíveis, dados anonimizados, dados agregados ou outras formas de informação sujeitas a diferentes condições de acesso e uso. Por isso, a avaliação de Privacidade deve considerar as características concretas dos dados e do tratamento realizado, e não presumir a aplicabilidade uniforme dos mesmos controles a todas as tarefas.

A dimensão busca verificar se o tratamento de dados relevante para a tarefa está adequadamente documentado, se os riscos e limitações de privacidade foram identificados e se existem medidas técnicas, organizacionais e institucionais compatíveis com o contexto avaliado.

O FIAR-Saúde não realiza, por meio desta dimensão, uma certificação de conformidade jurídica com a LGPD. Legislação, políticas institucionais e registros formais de proteção de dados constituem referências e evidências relevantes para a avaliação de governança.

---

## Objetivos da dimensão

A avaliação de Privacidade busca verificar se o projeto:

- identifica e documenta a natureza e a origem dos dados utilizados;
- explicita a finalidade do tratamento e sua relação com a tarefa;
- identifica a presença de dados pessoais ou sensíveis, quando aplicável;
- documenta restrições de uso, acesso, compartilhamento, armazenamento e retenção;
- adota medidas de proteção compatíveis com os riscos e o contexto;
- registra limitações e riscos residuais de privacidade;
- mantém coerência entre o tratamento efetivamente realizado e os registros éticos, institucionais ou regulatórios aplicáveis;
- atualiza essas evidências quando houver mudanças relevantes no tratamento dos dados.

---

## Origem, natureza e finalidade dos dados

A avaliação considera, quando aplicável:

- origem e proveniência dos dados;
- finalidade para a qual os dados são utilizados na tarefa;
- tipo e granularidade dos dados;
- presença de dados pessoais ou dados pessoais sensíveis;
- existência de identificadores diretos ou indiretos;
- uso de dados anonimizados, pseudonimizados ou agregados;
- condições de acesso e compartilhamento;
- restrições éticas, institucionais, contratuais ou regulatórias associadas aos dados;
- compatibilidade entre a finalidade declarada e o tratamento efetivamente realizado.

Nem toda tarefa envolve diretamente dados pessoais. Quando os dados forem públicos, agregados ou previamente anonimizados, a avaliação deve registrar essa condição e considerar os riscos residuais pertinentes, sem presumir automaticamente ausência de questões de privacidade.

---

## Medidas de proteção

A avaliação verifica se as medidas de proteção adotadas são compatíveis com a natureza dos dados, os riscos identificados e o contexto de uso.

Podem ser consideradas, quando aplicáveis:

- anonimização;
- pseudonimização;
- minimização de dados;
- controle de acesso;
- segregação de ambientes;
- criptografia;
- mecanismos de armazenamento seguro;
- políticas de retenção e descarte;
- restrições de compartilhamento;
- registro e revisão de permissões de acesso.

O FIAR-Saúde não exige uma técnica específica de proteção em todas as tarefas. A adequação da medida deve ser analisada em relação ao requisito e ao risco que ela pretende tratar.

---

## Governança dos dados

Também podem ser analisados registros institucionais relacionados ao tratamento dos dados, incluindo:

- políticas ou normas de uso dos dados;
- aprovação ética, quando aplicável;
- termos, autorizações ou condições institucionais de acesso;
- definição de responsabilidades relacionadas ao tratamento;
- documentação de compartilhamento ou transferência;
- consulta ou participação do Encarregado de Proteção de Dados, quando aplicável;
- Relatório de Impacto à Proteção de Dados Pessoais (RIPD), quando aplicável.

A existência desses documentos depende do contexto e das responsabilidades institucionais envolvidas. O NIAR-Saúde verifica sua aplicabilidade e consistência com a tarefa avaliada, sem substituir as instâncias formalmente responsáveis pela proteção de dados ou pela análise jurídica.

---

## Riscos associados

Limitações nas práticas de Privacidade podem contribuir para riscos como:

- exposição ou reidentificação de dados pessoais ou sensíveis;
- acesso, uso ou compartilhamento não autorizado;
- tratamento de dados incompatível com a finalidade declarada;
- conservação de dados além do necessário ou previsto;
- ausência de rastreabilidade sobre acesso ou compartilhamento;
- inconsistência entre o tratamento realizado e aprovações ou restrições institucionais;
- mudanças no tratamento dos dados sem reavaliação dos riscos correspondentes.

---

## Evidências esperadas

Dependendo da tarefa e do contexto, podem constituir evidências relevantes:

- Data Card ou documentação equivalente;
- descrição da origem, natureza e finalidade dos dados;
- documentação de anonimização, pseudonimização ou agregação;
- políticas e procedimentos de controle de acesso;
- registros de permissões ou autorização de acesso;
- documentação de armazenamento, retenção, descarte ou compartilhamento;
- aprovação ética, quando aplicável;
- termos ou registros institucionais de acesso a dados;
- RIPD, quando aplicável;
- registros de consulta ou orientação institucional sobre proteção de dados;
- Registro de Decisão Técnica relacionado ao tratamento dos dados;
- registros de incidentes ou mudanças relevantes, para tarefas em produção.

A ausência de determinada evidência deve ser analisada quanto à sua aplicabilidade ao requisito e ao contexto. Ela não implica automaticamente Não Conformidade nem determina o nível de maturidade do projeto.

---

## Requisitos e mecanismos de verificação

| ID | Requisito ou questão de avaliação | Exemplos de evidências | Mecanismos de verificação |
|---|---|---|---|
| PRI-01 | A origem, a natureza e a finalidade dos dados utilizados na tarefa estão documentadas? | Data Card, documentação de acesso, Formulário de Entrada | Verificação documental; consistência cruzada |
| PRI-02 | Está identificado se a tarefa trata dados pessoais, sensíveis, anonimizados, pseudonimizados ou agregados? | Data Card, documentação técnica | Verificação documental; análise de suficiência |
| PRI-03 | O tratamento dos dados é consistente com a finalidade e o Contexto de Uso declarados? | Data Card, Model Card, aprovação ética, documentação institucional | Consistência cruzada; contextualização |
| PRI-04 | Restrições de acesso, uso, compartilhamento, armazenamento e retenção estão documentadas quando aplicáveis? | políticas, termos, registros de acesso, Data Card | Verificação documental; rastreabilidade |
| PRI-05 | As medidas de proteção adotadas são compatíveis com a natureza dos dados e os riscos identificados? | documentação de anonimização, controle de acesso, segurança dos dados | Revisão documental; revisão metodológica; contextualização |
| PRI-06 | As limitações das medidas de proteção estão documentadas, quando relevantes? | Data Card, documentação técnica, Registro de Decisão Técnica | Verificação documental; consistência |
| PRI-07 | Aprovações éticas, registros institucionais ou outras condições aplicáveis são coerentes com o tratamento realizado? | parecer ético, termos institucionais, Data Card, descrição da tarefa | Verificação institucional; consistência cruzada |
| PRI-08 | Quando aplicável, a necessidade de RIPD ou de consulta à instância institucional responsável por proteção de dados foi considerada? | RIPD, registro de consulta, decisão institucional | Verificação institucional |
| PRI-09 | Riscos residuais ou limitações de privacidade relevantes estão registrados e associados a decisões ou medidas de tratamento? | Registro de Decisão Técnica, documentação de riscos, condicionantes | Rastreabilidade entre risco e decisão |
| PRI-10 | Para tarefas em produção, mudanças relevantes no tratamento dos dados, incidentes ou alterações de acesso são acompanhados e documentados? | registros de incidentes, histórico de versões, monitoramento | Análise de evidências operacionais; rastreabilidade longitudinal |

---

## Análise transversal das evidências

Para cada requisito aplicável, as evidências devem ser analisadas considerando:

- **Suficiência:** há evidência adequada para compreender o tratamento dos dados e os controles relevantes?
- **Consistência:** finalidade, natureza dos dados, condições de uso e registros institucionais são coerentes entre si?
- **Rastreabilidade:** é possível identificar a origem dos dados, as condições de acesso, as versões e as decisões relevantes?
- **Contextualização:** as medidas de proteção são adequadas à natureza dos dados, aos riscos e ao Contexto de Uso?

Essas propriedades apoiam a avaliação das evidências e não constituem, isoladamente, resultados de conformidade.

---

## Resultado da avaliação da dimensão

A avaliação de Privacidade produz **achados, limitações, pendências e, quando aplicável, sinais de governança** que subsidiam a avaliação de conformidade da Tarefa de IA.

A dimensão de Privacidade não recebe um nível de maturidade próprio.

Seus resultados são considerados juntamente com as demais dimensões na consolidação da conformidade da combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade é inferida separadamente no nível do projeto e de forma longitudinal.

