# FIAR-Saúde – Framework de Inteligência Artificial Responsável para Saúde

![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-research_framework-orange)
![Domain](https://img.shields.io/badge/domain-public_health_AI-green)
![Version](https://img.shields.io/badge/version-1.0-blue)

O **FIAR-Saúde** é um framework institucional e metodológico de governança de sistemas de inteligência artificial aplicados à saúde. Ele transforma princípios de **IA Responsável (IAR)** em requisitos verificáveis, evidências documentadas, avaliação técnica por requisito e acompanhamento ao longo de ciclos de avaliação, operando no contexto da saúde pública brasileira.

O framework busca reduzir a lacuna entre **princípios normativos de ética em IA** e sua **operacionalização em práticas de governança e auditoria,** uma limitação amplamente discutida na literatura (Floridi et al., 2018; Mittelstadt, 2019).

> O FIAR-Saúde **não** certifica modelos, tarefas ou projetos, **não garante ausência de viés e não substitui** **validação clínica ou mecanismos regulatórios formais**. Seu foco é a governança verificável das práticas, decisões e evidências associadas ao desenvolvimento, avaliação, operação e monitoramento de sistemas de IA.

<!-- busca reduzir a lacuna entre **princípios normativos de ética em IA** e sua **operacionalização em práticas de governança e auditoria**, permitindo avaliações sistemáticas, reprodutíveis e comparáveis entre sistemas.-->

---

## Instâncias Institucionais

A operacionalização do FIAR-Saúde distingue três responsabilidades institucionais:

- **Projetos de IA:** responsáveis pelo desenvolvimento das Tarefas de IA e pela produção, manutenção e atualização das evidências técnicas sob sua responsabilidade.
- **NIAR-Saúde (Núcleo de Inteligência Artificial Responsável para a Saúde):** instância técnico-operacional responsável por operacionalizar o FIAR-Saúde, orientar e padronizar a produção de evidências, delimitar avaliações, verificar a suficiência, consistência e rastreabilidade das evidências, conduzir a avaliação técnica e preparar os relatórios ao Comitê Gestor.
- **Comitê Gestor:** instância de governança responsável por validar os relatórios de avaliação e por deliberar sobre aceite de risco, condicionantes, restrições de uso ou outras decisões que ultrapassem a avaliação técnica.

A **produção de evidências**, a **avaliação técnica** e a **validação e deliberação institucional** são funções distintas.

---

## Ecossistema

Cada projeto avaliado pode utilizar um **repositório próprio criado a partir do FIAR-Audit-Template**.

```mermaid
flowchart TD
    A[FIAR-Saude\nFramework e Metodologia] --> B[FIAR-Audit-Template\nTemplate Base]
    B --> C1[Repositório de Avaliação\nProjeto X]
    B --> C2[Repositório de Avaliação\nProjeto Y]
    B --> C3[Repositório de Avaliação\nProjeto Z]
    C1 --> D[Histórico de Avaliação]
    C2 --> D
    C3 --> D
```

| Repositório                         | Função                                                                                             |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **FIAR-Saude** (este)          | Documentação conceitual e metodologia do framework                                                 |
| **FIAR-Audit-Template**        | Template base para documentação e avaliação dos projetos                                         |
| **Repositórios dos projetos** | Contêm documentação, evidências, comunicações, ciclos de avaliação e relatórios ao Comitê. |
| **ToyExample**                 | Instância de auditoria do PrevisãoRESP-SUS usado como exemplo didático                            |

---

## Dimensões de IAR

O FIAR-Saúde considera **sete dimensões** de IA Responsável. Os requisitos de cada uma estão em [docs/avaliacao/](docs/avaliacao/).

| Dimensão                     | Exemplos de Evidências                                                                                                   |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Governança**         | Escopo aprovado, condicionantes institucionais, mecanismos de supervisão.                                                |
| **Segurança**          | Registros de incidentes, controle de acesso, mecanismos de resposta a falhas.                                             |
| **Privacidade**         | Documentação sobre anonimização, políticas de retenção, controle de acesso aos dados.                              |
| **Responsabilização** | Registros nominais de decisão, aprovação formal de riscos.                                                             |
| **Rastreabilidade**     | Versionamento de dados e modelos, histórico de decisões técnicas.                                                      |
| **Justiça**            | Identificação fundamentada de grupos, resultados por grupo, análise de dados e variáveis-alvo, condições de acesso. |
| **Transparência**      | Relatórios de explicabilidade, justificativas técnicas das decisões de modelagem.                                      |

---

## Maturidade

A maturidade é uma propriedade longitudinal do projeto. Sua definição e a forma de inferi-la serão estabelecidas em revisão posterior. O [modelo anterior](docs/modelo_maturidade.md) está em revisão e não é aplicado nesta versão.

---

## Quickstart

Cada avaliação é um ciclo para uma **Tarefa de IA + Versão Avaliável + Contexto de Uso**:

1. **Entrada:** a equipe do projeto preenche o Formulário de Entrada.
2. **Delimitação:** o NIAR-Saúde define a Tarefa de IA, a Versão Avaliável, o Contexto de Uso, a Trilha, o escopo e as fontes.
3. **Avaliação por requisito:** o NIAR-Saúde determina a aplicabilidade e atribui o resultado de cada requisito (Atendido, Não atendido, Inconclusivo ou Não aplicável).
4. **Rodadas com a equipe:** perguntas ligadas às pendências; as respostas são registradas como fonte.
5. **Fechamento:** registro de resultados, limitações, pendências remanescentes e encaminhamentos.

Quando houver gatilho, o NIAR-Saúde envia o relatório ao Comitê Gestor, que o valida e delibera sobre as questões encaminhadas. Mudanças relevantes são analisadas pelo impacto e podem levar a um novo ciclo. Detalhes em [docs/ciclo_avaliacao.md](docs/ciclo_avaliacao.md).

---

## Documentação Completa

- Metodologia → [docs/metodologia_fiar.md](docs/metodologia_fiar.md)
- Ciclo de Avaliação Técnica → [docs/ciclo_avaliacao.md](docs/ciclo_avaliacao.md)
- Dimensões de IAR → [docs/dimensoes_avaliacao.md](docs/dimensoes_avaliacao.md)
- Trilhas de Execução → [docs/trilhas_execucao.md](docs/trilhas_execucao.md)
- Requisitos por dimensão → [docs/avaliacao/](docs/avaliacao/)
- Governança Institucional  → [docs/governanca_avaliacao.md](https://github.com/niar-saude-ufmg/FIAR-Saude/blob/main/docs/governanca_avaliacao.md)
- Mecanismos de Verificação → [docs/mecanismos_verificacao.md](docs/mecanismos_verificacao.md)
- Modelo de Maturidade (em revisão) → [docs/modelo_maturidade.md](docs/modelo_maturidade.md)
- Mapeamento de Referências (em revisão) → [docs/mapeamento_referencias.md](docs/mapeamento_referencias.md)

---

## Exemplo de Aplicação

👉 [ToyExample — PrevisãoRESP-SUS](https://github.com/niar-saude-ufmg/SBCAS_26_Respiratory_Disease)

Sistema hipotético de previsão de internações respiratórias por hospital utilizando dados do SIH/DataSUS, com avaliação das dimensões de Justiça, Transparência (incluindo Explicabilidade), Auditabilidade e Governança.

---

## Estrutura do Repositório

```
FIAR-Saude/
├── docs/
│   ├── metodologia_fiar.md
│   ├── ciclo_avaliacao.md
│   ├── governanca_avaliacao.md
│   ├── dimensoes_avaliacao.md
│   ├── mecanismos_verificacao.md
│   ├── trilhas_execucao.md
│   ├── modelo_maturidade.md
│   ├── maturidade_fiar.md
│   ├── mapeamento_referencias.md
│   └── avaliacao/
│       ├── governanca.md
│       ├── seguranca.md
│       ├── privacidade.md
│       ├── responsabilizacao.md
│       ├── rastreabilidade.md
│       ├── justica.md
│       └── transparencia.md
├── README.md
├── LICENSE
└── CITATION.cff
```

---

## Público-alvo

- pesquisadores em IA aplicada à saúde pública
- equipes de ciência de dados em instituições públicas de saúde
- projetos vinculados ao CIIA-Saúde/UFMG
- avaliadores técnicos e gestores responsáveis pela governança de sistemas de IA em saúde

---

## Status

Versão 1.0 — Maio de 2026. Framework em validação em projetos de IA em saúde pública no contexto do CIIA-Saúde/UFMG.

---

## Citação

```
Vasconcelos et al. (2026). FIAR-Saúde: Framework de Inteligência Artificial
Responsável para Saúde. CIIA-Saúde, UFMG / NIAR-Saúde.
```

---

## Licença

MIT License

---

## Referências

* Floridi, L., et al. (2018). [AI4People — An Ethical Framework for a Good AI Society](https://ai4people.org/PDF/AI4People_Ethical_Framework_For_A_Good_AI_Society.pdf).
* Mittelstadt, B. D., et al. (2019). [Principles alone cannot guarantee ethical AI](https://doi.org/10.1038/s42256-019-0114-4). *Nature Machine Intelligence, 1*, 501–507.
* Raji, I. D., et al. (2020). [Closing the AI accountability gap: Defining an end-to-end framework for internal algorithmic auditing](https://doi.org/10.1145/3351095.3372873). In *Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (FAccT)*.
* Organisation for Economic Co-operation and Development (2024). [Recommendation of the Council on Artificial Intelligence. OECD/LEGAL/0449](https://legalinstruments.oecd.org/en/instruments/oecd-legal-0449).
* World Health Organization (2021). [Ethics and Governance of Artificial Intelligence for Health](https://www.who.int/publications/i/item/9789240029200)
* International Organization for Standardization (2023). [ISO/IEC 23894: Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
* European Union. (2024). [Artificial Intelligence Act](https://artificialintelligenceact.eu/)
* National Institute of Standards and Technology (2023). [Artificial Intelligence Risk Management Framework (AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
* Brasil (2018). Lei nº 13.709 — Lei Geral de Proteção de Dados Pessoais (LGPD).
