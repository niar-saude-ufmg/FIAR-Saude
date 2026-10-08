# Metodologia do FIAR-Saúde

## Contexto e Motivação

Frameworks de IA Responsável frequentemente estabelecem princípios éticos de alto nível, como transparência, justiça e responsabilização (*accountability*), mas oferecem orientação limitada sobre sua implementação prática.

Essa lacuna entre **princípios normativos e operacionalização** é amplamente discutida na literatura (Floridi et al., 2018; Morley et al., 2020).

O FIAR-Saúde foi desenvolvido para responder a esse problema no contexto específico da saúde pública brasileira, propondo uma abordagem operacional baseada em:

- documentação estruturada das tarefas de IA
- evidências verificáveis ao longo do ciclo de vida da tarefa
- avaliação sistemática por dimensões de IA Responsável
- acompanhamento das práticas ao longo de sucessivos ciclos de avaliação

Diferentemente de abordagens centradas exclusivamente na avaliação interna de modelos, o FIAR-Saúde concentra-se na **governança verificável das práticas** associadas ao desenvolvimento, operação e monitoramento de sistemas de IA. Seu foco não é inspecionar diretamente as propriedades internas do modelo ou acessar ambientes restritos, mas avaliar a **suficiência, consistência, rastreabilidade e contextualização** das evidências técnicas, documentais e, quando aplicável, operacionais produzidas ao longo do ciclo de vida da tarefa, bem como a recorrência dessas práticas ao longo de sucessivos ciclos de avaliação.

Essa perspectiva aproxima o framework de abordagens de  **avaliação técnica independente, assurance e governança baseada em evidências** , nas quais conclusões são fundamentadas em artefatos verificáveis, consistência entre evidências e responsabilização institucional.

---

## Diferenciais do FIAR-Saúde

O FIAR-Saúde se diferencia de outros frameworks de IA Responsável por:

- operacionalizar princípios éticos em **critérios verificáveis**
- separar explicitamente **produção de evidências pelo projeto, avaliação técnica pelo NIAR-Saúde e validação e deliberação pelo Comitê Gestor.**
- utilizar **evidências documentadas como base da avaliação**, sem necessidade de acesso a dados sensíveis ou ambientes restritos
- avaliar cada **Tarefa de IA + Versão Avaliável + Contexto de Uso** de forma pontual, mantendo o histórico doprojeto ao longo dos ciclos.
- incorporar **trilhas de execução** diferenciadas conforme o destino do modelo (publicação científica ou operação ativa)

Essa abordagem responde a críticas recorrentes na literatura sobre a dificuldade de traduzir princípios de IA Responsável em práticas auditáveis e mensuráveis (Mittelstadt, 2019; Raji et al., 2020).

---

## Princípios Metodológicos

O FIAR-Saúde baseia-se em cinco princípios:

### 1. Documentação estruturada

As tarefas de IA devem possuir documentação clara sobre contexto de uso, dados, modelos, procedimentos, finalidade, limitações e decisões relevantes, produzida e atualizada ao longo de seu ciclo de vida.

### 2. Evidências verificáveis

A avaliação de IAR deve ser baseada em evidências documentadas (artefatos técnicos, registros operacionais e documentação institucional), não em autoproclamação. Não há inferência válida sem artefato correspondente.

### 3. Separação entre produção de evidências e avaliação

O framework estabelece uma distinção estrutural entre a produção das evidências técnicas pelo projeto e sua avaliação pelo NIAR-Saúde.

A equipe do projeto produz, mantém e atualiza os artefatos sob sua responsabilidade. O NIAR-Saúde delimita a avaliação, verifica as evidências e conduz a avaliação técnica de forma independente da equipe responsável pelo desenvolvimento.

O Comitê Gestor valida os relatórios de avaliação e delibera sobre as questões encaminhadas, como aceite de risco, condicionantes e restrições de uso, sem substituir a avaliação técnica.

Essa separação contribui para a credibilidade, rastreabilidade e imparcialidade do processo (Raji et al., 2020).

### 4. Avaliação multidimensional

A avaliação técnica considera sete dimensões de IA Responsável: Governança, Segurança, Privacidade, Responsabilização, Rastreabilidade, Justiça e Transparência. Essas dimensões estruturam diferentes aspectos das práticas de IA Responsável e são analisadas de forma integrada.

### 5. Governança longitudinal

Os requisitos são avaliados pontualmente, para cada Tarefa de IA + Versão Avaliável + Contexto de Uso. O histórico dos ciclos fica registrado no projeto. A forma de inferir a maturidade a partir desse histórico será definida em revisão posterior.

---

## Lógica da Avaliação

A operacionalização da avaliação técnica no FIAR-Saúde segue a seguinte cadeia:

- **Dimensões:** definem o que avaliamos.
- **Requisitos ou questões de avaliação:** definem o que queremos verificar.
- **Evidências:** constituem a base utilizada para fundamentar a análise.
- **Mecanismos de verificação:** definem como as evidências são examinadas.
- **Suficiência, consistência, rastreabilidade e contextualização:** constituem propriedades transversais consideradas na análise das evidências.
- **Pendências:** registram as questões necessárias para delimitar a avaliação, determinar a aplicabilidade de um requisito ou concluir sua análise.
- **Resultado por requisito:** Atendido, Não atendido, Inconclusivo ou Não aplicável, para uma **Tarefa de IA + Versão Avaliável + Contexto de Uso**.
- **Maturidade:** propriedade longitudinal do projeto, a ser definida em revisão posterior.

---

## Fundamentação em Referências Internacionais

O framework está alinhado a referências técnicas e normativas internacionais consolidadas para IAR:

- **Princípios da OECD para IA** (2024): destacam transparência, robustez técnica, centralidade humana e responsabilidade ao longo do ciclo de vida dos sistemas de IA.
- **Recomendações da OMS** (2021): orientações sobre gestão sistemática de riscos, validação de modelos, supervisão humana e governança de dados em saúde.
- **ISO/IEC 23894** (2023): propõe abordagem estruturada para identificação, avaliação e mitigação de riscos ao longo do ciclo de vida de sistemas de IA.
- **AI Act da União Europeia** (2024): referências em classificação de riscos, documentação técnica e supervisão de sistemas de IA de alto risco, adotadas como orientação prospectiva de boas práticas.
- **NIST AI RMF 1.0** (2023): framework de gestão de risco em IA utilizado como uma das referências para a estruturação dos processos de governança, avaliação e acompanhamento do FIAR-Saúde.
- **LGPD** (2018): o framework incorpora a verificação da consistência entre o escopo aprovado em protocolos éticos e o desenvolvimento efetivo dos sistemas de IA.

No contexto de projetos que utilizam dados de saúde, os projetos desenvolvidos no âmbito do CIIA-Saúde devem ser previamente submetidos à avaliação do CEP-UFMG quando houver necessidade de registros de aprovação ética. O FIAR-Saúde não substitui esse processo regulatório.

---

## Escopo e Não Objetivos

O FIAR-Saúde é um framework institucional e metodológico de governança baseada em evidências, apoiado por avaliação técnica independente das equipes responsáveis pelos projetos.

O FIAR-Saúde não tem como objetivo:

- certificar modelos, tarefas ou projetos
- garantir ausência de viés
- substituir validação clínica
- substituir mecanismos regulatórios ou processos formais de certificação
- realizar auditoria forense completa
- verificar diretamente propriedades internas do modelo
- acessar necessariamente dados sensíveis ou ambientes restritos
- autorizar, por si só, o uso ou a implantação de sistemas de IA
- substituir estruturas institucionais existentes de governança, proteção de dados, ética em pesquisa ou regulação

---

## Etapas do Ciclo de Avaliação

O FIAR-Saúde organiza a avaliação em ciclos. Cada ciclo avalia uma Tarefa de IA + Versão Avaliável + Contexto de Uso.

| Etapa                                  | Responsável                 | O que acontece                                                                                                                 |
| -------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **1. Entrada**                   | Equipe do projeto            | Preenche o Formulário de Entrada, atualizado quando houver mudança relevante.                                                |
| **2. Delimitação**             | NIAR-Saúde                  | Define a Tarefa de IA, a Versão Avaliável, o Contexto de Uso, a Trilha, o escopo e as fontes.                                |
| **3. Avaliação por requisito** | NIAR-Saúde                  | Determina a aplicabilidade e atribui o resultado de cada requisito, com base nas evidências.                                  |
| **4. Rodadas com a equipe**      | NIAR-Saúde e equipe         | Perguntas ligadas às pendências; as respostas são registradas como fonte.                                                   |
| **5. Fechamento**                | NIAR-Saúde                  | Registra resultados, limitações, pendências remanescentes e encaminhamentos.                                                |
| **Relatório e decisão**        | NIAR-Saúde e Comitê Gestor | Quando houver gatilho, o NIAR-Saúde envia o relatório; o Comitê Gestor o valida e delibera sobre as questões encaminhadas. |

Mudanças relevantes na tarefa são analisadas pelo impacto e podem levar a apenas registrar a mudança, reavaliar os requisitos afetados, abrir novo ciclo ou delimitar nova Tarefa de IA. Nem toda alteração técnica constitui uma nova Versão Avaliável.

As regras de cada etapa, os resultados, as pendências e os gatilhos do relatório estão em [ciclo_avaliacao.md](ciclo_avaliacao.md).

---

## Capacitação e Adequação Inicial

O FIAR-Saúde reconhece que muitos projetos de IA em saúde ainda não possuem mecanismos estruturados de IAR. Assim, o framework não opera apenas como mecanismo de verificação de conformidade, mas também como **instrumento de indução e estruturação progressiva de capacidades** sociotécnicas de governança.

Projetos que ainda não possuem práticas estruturadas de IA Responsável podem ingressar no framework sem possuir artefatos completos. Nesses casos, o processo pode incluir atividades de capacitação e adequação apoiadas ou conduzidas pelo NIAR-Saúde, incluindo:

- treinamento introdutório em IAR
- fornecimento de templates e guias operacionais
- apoio metodológico para produção dos artefatos
- orientação sobre governança e rastreabilidade
- ciclos iterativos de adequação documental e técnica

O objetivo principal nessa etapa é o desenvolvimento gradual de mecanismos verificáveis de governança.

---

## Navegação da Documentação

- Ciclo de Avaliação Técnica → [ciclo_avaliacao.md](ciclo_avaliacao.md)
- Dimensões de IAR → [dimensoes_avaliacao.md](dimensoes_avaliacao.md)
- Trilhas de Execução → [trilhas_execucao.md](trilhas_execucao.md)
- Modelo de Maturidade → [modelo_maturidade.md](modelo_maturidade.md)
- Governança da Avaliação → [governanca_avaliacao.md](governanca_avaliacao.md)
- Mapeamento de Referências → [mapeamento_referencias.md](mapeamento_referencias.md)
- Mecanismos de Verificação → [mecanismos_verificacao.md](mecanismos_verificacao.md)

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
