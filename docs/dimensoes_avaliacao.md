# Dimensões de Avaliação do FIAR

O FIAR-Saúde operacionaliza a avaliação de IA Responsável a partir de **sete dimensões** principais.

Essas dimensões estruturam os requisitos e as evidências consideradas durante a avaliação técnica, permitindo analisar diferentes aspectos das práticas de IA Responsável associadas a uma **Tarefa de IA, Versão Avaliável e Contexto de Uso** específicos.

Cada dimensão é avaliada com base em **evidências documentais, técnicas e, quando aplicável, operacionais**, produzidas ou fornecidas pelo projeto e analisadas pelo **NIAR-Saúde**. A avaliação técnica é realizada de forma independente da equipe responsável pelo desenvolvimento, sem excluir a possibilidade de esclarecimentos, complementações ou correções durante o processo.

A definição dessas dimensões foi inspirada em referências internacionais de IA Responsável, incluindo os princípios da OECD, as diretrizes da Organização Mundial da Saúde (OMS) para IA em saúde e normas de gestão de risco em IA, como a ISO/IEC 23894.

Os aspectos apresentados em cada dimensão são orientadores. Sua aplicabilidade e os mecanismos de verificação utilizados dependem da tarefa, da trilha de execução, do contexto de uso e das evidências disponíveis.

---

## Lógica da avaliação no FIAR-Saúde

A avaliação técnica do FIAR-Saúde pode ser compreendida por meio da seguinte cadeia:

- **Dimensões:** definem **o que avaliamos**.
- **Requisitos ou questões de avaliação:** definem **o que queremos verificar em cada dimensão**.
- **Evidências:** constituem **a base utilizada para fundamentar a análise**.
- **Mecanismos de verificação:** definem **como as evidências são examinadas**.
- **Suficiência, consistência, rastreabilidade e contextualização:** constituem **propriedades transversais consideradas na análise das evidências**.
- **Achados e pendências:** registram **os resultados da análise e as questões ainda não resolvidas**.
- **Conformidade:** constitui o resultado pontual da avaliação de uma **Tarefa de IA + Versão Avaliável + Contexto de Uso**.
- **Maturidade:** constitui uma inferência longitudinal no nível do **projeto**, baseada na recorrência, continuidade e rastreabilidade das práticas de IA Responsável ao longo de sucessivos ciclos de avaliação.


---

## 1. Governança

A dimensão de governança avalia a existência de estruturas institucionais para supervisionar o desenvolvimento e o uso do sistema de IA.

Aspectos considerados incluem:

- definição de responsabilidades institucionais
- mecanismos de supervisão humana
- políticas de uso e operação do sistema
- processos de revisão, atualização e monitoramento

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Governança](avaliacao/governanca.md)

---

## 2. Segurança

A dimensão de segurança avalia a proteção do sistema contra ameaças, ataques e acessos não autorizados, garantindo a integridade e a disponibilidade do sistema.

Aspectos considerados incluem:

- registros de incidentes de segurança
- controle de acesso a dados e ambientes
- mecanismos de resposta a falhas
- mecanismos de proteção, hardening ou isolamento de infraestrutura, quando aplicáveis

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Segurança](avaliacao/seguranca.md) *(arquivo ainda não criado — ver observação no final)*

---

## 3. Privacidade

A dimensão de privacidade avalia como dados sensíveis são coletados, utilizados e protegidos ao longo do ciclo de vida do sistema.

Aspectos considerados incluem:

- origem e sensibilidade dos dados
- práticas de anonimização ou pseudonimização
- mecanismos de controle de acesso
- conformidade com legislações e políticas de proteção de dados (LGPD)

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Privacidade](avaliacao/privacidade.md)

---

## 4. Responsabilização

A dimensão de responsabilização avalia se há identificação clara de quem é responsável pelos resultados e impactos do sistema, com mecanismos de prestação de contas desde o design até a operação.

Aspectos considerados incluem:

- registros nominais de decisão
- registros de aceite de risco e condicionantes institucionais, quando aplicáveis
- atribuição clara de responsabilidades por etapa do ciclo de vida
- rastreabilidade de aprovações institucionais

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Responsabilização](avaliacao/responsabilizacao.md) *(arquivo ainda não criado — ver observação no final)*

---

## 5. Rastreabilidade

A dimensão de rastreabilidade avalia se o sistema possui níveis adequados de documentação e histórico que permitam acompanhamento, verificação e reprodutibilidade ao longo de todo o processo de desenvolvimento.

Aspectos considerados incluem:

- versionamento de dados e modelos
- histórico de decisões técnicas
- registro de execução e logs
- disponibilidade de artefatos técnicos ao longo do tempo

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Rastreabilidade](avaliacao/rastreabilidade.md) *(arquivo ainda não criado — ver observação no final)*

---

## 6. Justiça

A dimensão de justiça avalia potenciais impactos desiguais do sistema sobre diferentes grupos populacionais.

Aspectos considerados incluem:

- presença de vieses nos dados
- diferenças de desempenho entre subgrupos
- riscos de efeitos discriminatórios
- estratégias de mitigação de vieses

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Justiça](avaliacao/justica.md)

---

## 7. Transparência

A dimensão de transparência avalia se o funcionamento do sistema e suas decisões podem ser compreendidos por públicos relevantes, incluindo justificativas técnicas das decisões de modelagem.

Aspectos considerados incluem:

- relatórios de explicabilidade (local e global)
- justificativas e documentação sobre resultados ou decisões apoiadas pelo sistema, quando aplicável
- mecanismos de interpretação do modelo
- comunicação de limitações a públicos não técnicos

Para critérios detalhados de avaliação, consulte:
→ [Avaliação de Transparência](avaliacao/transparencia.md) *(arquivo ainda não criado — ver observação no final)*

---

## Avaliação das Dimensões

A avaliação de cada dimensão é conduzida pelo **NIAR-Saúde** com base nas evidências aplicáveis à Tarefa de IA, à Versão Avaliável e ao Contexto de Uso considerados no ciclo de avaliação.

A avaliação de uma dimensão não se limita à presença de documentos. Para cada requisito ou questão de avaliação, devem ser identificados:

- a evidência esperada;
- as evidências efetivamente disponíveis;
- o mecanismo de verificação aplicável;
- a análise realizada;
- as limitações da evidência;
- eventuais pendências;
- os achados relevantes;
- eventuais recomendações ou sinais de governança.

As evidências são analisadas transversalmente quanto a quatro propriedades:

- **Suficiência:** as evidências disponíveis são adequadas e suficientemente completas para analisar o requisito?
- **Consistência:** as evidências são coerentes entre si e com outras informações relevantes do ciclo de avaliação?
- **Rastreabilidade:** é possível identificar a origem, a versão e a relação da evidência com a tarefa e com as conclusões produzidas?
- **Contextualização:** a evidência e seus resultados foram interpretados considerando o contexto de uso, as limitações, os riscos e as populações ou partes interessadas relevantes?

Essas propriedades apoiam a análise das evidências, mas não constituem, isoladamente, resultados de conformidade.

Os resultados das diferentes dimensões subsidiam a consolidação da avaliação de conformidade da **Tarefa de IA + Versão Avaliável + Contexto de Uso**.

A maturidade não é avaliada dentro de cada dimensão nem resulta da agregação de seus resultados. Ela é inferida longitudinalmente no nível do projeto, a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável ao longo de sucessivos ciclos de avaliação.

---

## Operacionalização e Mecanismos de Verificação

A avaliação das dimensões é operacionalizada por meio de **mecanismos de verificação** adequados ao requisito, à natureza da evidência e ao contexto da tarefa.

Esses mecanismos podem incluir, entre outros:

- verificação documental;
- análise de consistência entre artefatos;
- verificação de versionamento e rastreabilidade;
- revisão de métricas e resultados técnicos;
- análise metodológica;
- execução ou revisão de testes técnicos, quando aplicável;
- análise de registros operacionais;
- esclarecimentos ou entrevistas com a equipe do projeto;
- verificação de registros institucionais.

Checklists padronizados podem ser utilizados como instrumentos de apoio para organizar requisitos, evidências e verificações:

→ [Checklists de Avaliação](avaliacao/checklist.md)

O checklist **não substitui a análise técnica e contextual** e não determina isoladamente o resultado de conformidade.

Cada requisito deve estar associado, sempre que aplicável, a:

1. **questão ou requisito de avaliação**;
2. **evidência esperada**;
3. **mecanismo de verificação**;
4. **critério de suficiência da evidência**;
5. **análise e achados**;
6. **pendências ou limitações**;
7. **eventual sinal de governança**.

Estados administrativos ou documentais, como evidência recebida, incompleta ou ausente, não devem ser automaticamente convertidos em resultados de conformidade.

---

## Relação com a metodologia

As dimensões de IA Responsável representam a estrutura temática da avaliação definida pelo FIAR-Saúde.

Para uma visão conceitual dos princípios e da arquitetura do framework:
→ [Metodologia do FIAR](metodologia_fiar.md)

Para o fluxo operacional da avaliação:
→ [Ciclo de Avaliação Técnica](ciclo_avaliacao.md)

Para os níveis e critérios de maturidade longitudinal:
→ [Modelo de Maturidade](modelo_maturidade.md)

---
