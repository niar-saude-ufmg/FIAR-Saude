# Metodologia do FIAR-Saúde

## Contexto e Motivação

Frameworks de IA Responsável frequentemente estabelecem princípios éticos de alto nível — como transparência, justiça e responsabilização (*accountability*) — mas oferecem orientação limitada sobre sua implementação prática.

Essa lacuna entre **princípios normativos e operacionalização** é amplamente discutida na literatura (Floridi et al., 2018; Morley et al., 2020).

O FIAR-Saúde foi desenvolvido para responder a esse problema no contexto específico da saúde pública brasileira, propondo uma abordagem operacional baseada em:

- documentação estruturada do sistema
- evidências verificáveis ao longo do ciclo de vida da tarefa
- avaliação sistemática por dimensões de IA Responsável
- inferência longitudinal de maturidade institucional

Diferentemente de abordagens centradas exclusivamente na avaliação interna de modelos, o FIAR-Saúde concentra-se na **governança verificável das práticas** associadas ao desenvolvimento, operação e monitoramento de sistemas de IA. Seu foco não é inspecionar diretamente as propriedades internas do modelo ou acessar ambientes restritos, mas avaliar a existência, consistência, rastreabilidade e recorrência de evidências técnicas e documentais produzidas ao longo do ciclo de vida do sistema.

Essa perspectiva aproxima o framework de modelos de auditoria regulatória e governança baseada em evidências, nos quais a conformidade é inferida a partir de artefatos verificáveis, consistência operacional e responsabilização institucional.

---

## Diferenciais do FIAR-Saúde

O FIAR-Saúde se diferencia de outros frameworks de IA Responsável por:

- operacionalizar princípios éticos em **critérios verificáveis**
- separar explicitamente **desenvolvimento do sistema e auditoria independente**
- utilizar **evidências documentadas como base da avaliação**, sem necessidade de acesso a dados sensíveis ou ambientes restritos
- adotar um **modelo de maturidade longitudinal e cumulativo**, baseado na recorrência verificável das práticas ao longo do tempo
- distinguir **conformidade pontual** (por versão avaliável) de **maturidade institucional** (por projeto, ao longo do tempo)
- incorporar **trilhas de execução** diferenciadas conforme o destino do modelo (publicação científica ou operação ativa)

Essa abordagem responde a críticas recorrentes na literatura sobre a dificuldade de traduzir princípios de IA Responsável em práticas auditáveis e mensuráveis (Mittelstadt, 2019; Raji et al., 2020).

---

## Princípios Metodológicos

O FIAR-Saúde baseia-se em cinco princípios:

### 1. Documentação estruturada

Sistemas de IA devem possuir documentação clara sobre contexto, dados utilizados, arquitetura do modelo e finalidade, produzida ao longo de todo o ciclo de vida da tarefa — não apenas em momentos isolados.

### 2. Evidências verificáveis

A avaliação de IAR deve ser baseada em evidências documentadas — artefatos técnicos, registros operacionais e documentação institucional — não em autoproclamação. Não há inferência válida sem artefato correspondente.

### 3. Separação entre projeto e auditoria

O framework estabelece uma distinção estrutural entre artefatos produzidos pelo projeto e avaliações conduzidas pelo NIAR. O projeto não avalia a si próprio. Essa separação é fundamental para a credibilidade e imparcialidade do processo (Raji et al., 2020).

### 4. Avaliação multidimensional

A auditoria considera sete dimensões de IA Responsável — Governança, Segurança, Privacidade, Responsabilização, Rastreabilidade, Justiça e Transparência — refletindo diferentes categorias de risco ao longo do ciclo de vida do sistema. As dimensões são avaliadas de forma integrada, não isolada.

### 5. Governança longitudinal

A conformidade é avaliada pontualmente por versão avaliável. A maturidade é inferida longitudinalmente a partir do histórico de conformidades do projeto, refletindo a capacidade institucional de executar práticas de IAR de forma recorrente e verificável ao longo do tempo.

---

## Fundamentação em Referências Internacionais

O framework está alinhado a referências técnicas e normativas internacionais consolidadas para IAR:

- **Princípios da OECD para IA** (2024): destacam transparência, robustez técnica, centralidade humana e responsabilidade ao longo do ciclo de vida dos sistemas de IA.
- **Recomendações da OMS** (2021): orientações sobre gestão sistemática de riscos, validação de modelos, supervisão humana e governança de dados em saúde.
- **ISO/IEC 23894** (2023): propõe abordagem estruturada para identificação, avaliação e mitigação de riscos ao longo do ciclo de vida de sistemas de IA.
- **AI Act da União Europeia** (2024): referências em classificação de riscos, documentação técnica e supervisão de sistemas de IA de alto risco, adotadas como orientação prospectiva de boas práticas.
- **NIST AI RMF 1.0** (2023): framework de gestão de risco em IA que inspira a metodologia operacional de auditoria.
- **LGPD** (2018): o framework incorpora a verificação da consistência entre o escopo aprovado em protocolos éticos e o desenvolvimento efetivo dos sistemas de IA.

No contexto de projetos que utilizam dados de saúde, os projetos desenvolvidos no âmbito do CIIA-Saúde devem ser previamente submetidos à avaliação do CEP-UFMG quando houver necessidade de registros de aprovação ética. O FIAR-Saúde não substitui esse processo regulatório.

---

## Escopo e Não Objetivos

O FIAR-Saúde é um framework de governança e auditoria baseada em evidências. Portanto, o framework **não** possui como objetivo:

- certificar modelos clínicos
- garantir ausência de viés
- substituir validação clínica
- substituir mecanismos regulatórios ou processos formais de certificação
- realizar auditoria forense completa
- verificar diretamente propriedades internas do modelo
- acessar necessariamente dados sensíveis ou ambientes restritos

---

## Fases do Ciclo Operacional

O FIAR-Saúde estrutura a operacionalização da governança em cinco fases longitudinais, que se repetem a cada mudança relevante no sistema:

| Fase | Responsável | Atividades principais |
|---|---|---|
| **1. Entrada** | CIIA + NIAR | Enquadramento institucional, identificação de lacunas de IAR, classificação de risco inicial. |
| **2. Adequação** | NIAR | Capacitação da equipe, fornecimento de templates, estruturação do pipeline de evidências. |
| **3. Execução** | Projeto | Produção dos artefatos (Data Card, Model Card, Fairness Report, Explainability Report, Registro de Decisão Técnica). |
| **4. Avaliação** | NIAR | Auditoria baseada em evidências: verificação de completude, consistência cruzada e amostragem operacional. |
| **5. Governança** | CIIA + NIAR | Classificação de conformidade, atribuição de maturidade, definição de condicionantes e monitoramento contínuo. |

Reavaliações são acionadas sempre que ocorrem mudanças relevantes na tarefa — retreinamento com novos dados, mudança de arquitetura, expansão de escopo clínico, incidentes operacionais ou alterações regulatórias. Essas reexecuções parciais ou integrais das dimensões de IAR constituem a base da inferência longitudinal de maturidade.

---

## Capacitação e Adequação Inicial

O FIAR-Saúde reconhece que muitos projetos de IA em saúde ainda não possuem mecanismos estruturados de IAR. Assim, o framework não opera apenas como mecanismo de verificação de conformidade, mas também como **instrumento de indução e estruturação progressiva de capacidades** sociotécnicas de governança.

Projetos em níveis iniciais de maturidade podem ingressar no framework sem possuir artefatos completos. Nesses casos, o processo pode incluir fases de capacitação e adequação conduzidas pelo NIAR, incluindo:

- treinamento introdutório em IAR
- fornecimento de templates e guias operacionais
- apoio metodológico para produção dos artefatos
- orientação sobre governança e rastreabilidade
- ciclos iterativos de adequação documental e técnica

O objetivo principal nessa etapa não é a reprovação imediata do projeto, mas o desenvolvimento gradual de mecanismos verificáveis de governança.

---

## Navegação da Documentação

- Ciclo de Auditoria → [ciclo_auditoria.md](ciclo_auditoria.md)
- Dimensões de IAR → [dimensoes_avaliacao.md](dimensoes_avaliacao.md)
- Trilhas de Execução → [trilhas_execucao.md](trilhas_execucao.md)
- Modelo de Maturidade → [modelo_maturidade.md](modelo_maturidade.md)
- Governança da Auditoria → [governanca_auditoria.md](governanca_auditoria.md)
- Mapeamento de Referências → [mapeamento_referencias.md](mapeamento_referencias.md)

---

## Referências

- Floridi, L., et al. (2018). AI4People — [An Ethical Framework for a Good AI Society](https://ai4people.org/PDF/AI4People_Ethical_Framework_For_A_Good_AI_Society.pdf).
- Morley, J., Machado, C. C., et al. (2020). [The ethics of AI in health care: A mapping review](https://doi.org/10.1016/j.socscimed.2020.113172). *Social Science & Medicine, 260*, 113172. 
- Mittelstadt, B. D., et al. (2019). [Principles alone cannot guarantee ethical AI](https://doi.org/10.1038/s42256-019-0114-4). *Nature Machine Intelligence, 1*, 501–507.
- Raji, I. D., et al. (2020). [Closing the AI accountability gap: Defining an end-to-end framework for internal algorithmic auditing](https://doi.org/10.1145/3351095.3372873). In *Proceedings of the Conference on Fairness, Accountability, and Transparency (FAccT)*.
- Organisation for Economic Co-operation and Development (2024). [Recommendation of the Council on Artificial Intelligence. OECD/LEGAL/0449](https://legalinstruments.oecd.org/en/instruments/oecd-legal-0449).
- World Health Organization (2021). [Ethics and Governance of Artificial Intelligence for Health](https://www.who.int/publications/i/item/9789240029200)
- International Organization for Standardization (2023). [ISO/IEC 23894: Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
- National Institute of Standards and Technology (2023). [Artificial Intelligence Risk Management Framework (AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
- European Union. (2024). [Artificial Intelligence Act](https://artificialintelligenceact.eu/)
- Brasil (2018). [Lei nº 13.709 — Lei Geral de Proteção de Dados Pessoais (LGPD)](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm). 
- Carvalho, M., et al. (2026). [Quem controla os dados? Governança e responsabilidade na era da inteligência artificial](https://horizontes.sbc.org.br/index.php/2026/04/quem-controla-os-dados-governanca-e-responsabilidade-na-era-da-inteligencia-artificial/). *SBC Horizontes*.


---







