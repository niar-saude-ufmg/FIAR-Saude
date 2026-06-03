# Mapeamento de Referências – FIAR

Este documento apresenta o mapeamento entre os critérios operacionais do checklist FIAR e referências internacionais em IA Responsável.

O objetivo é explicitar a fundamentação teórica e normativa do framework, demonstrando como princípios abstratos são traduzidos em critérios verificáveis de auditoria.

---

## Abordagem de mapeamento

O FIAR adota uma estrutura em três níveis:

1. **Princípios de IA Responsável**(ex: transparência, justiça, accountability)
2. **Dimensões do FIAR**(auditabilidade, explicabilidade, justiça, privacidade, governança)
3. **Critérios operacionais**
   (itens do checklist, ex: AUD-01, EXP-04)

Esse encadeamento permite rastrear cada critério até sua base conceitual.

---

## Referências utilizadas

As principais referências utilizadas na construção dos critérios incluem:

- OECD (2019) – Principles on Artificial Intelligence
- WHO (2021) – Ethics and Governance of AI for Health
- ISO/IEC 23894 (2023) – Artificial Intelligence Risk Management
- NIST (2023) – AI Risk Management Framework

---

## Mapeamento por dimensão

### Auditabilidade

Relacionada a princípios de:

- transparência
- accountability
- rastreabilidade

**Critérios:**

- **AUD-01 – Documentação do sistema**

  - OECD – Transparency and explainability
  - ISO/IEC 23894 – Documentation and traceability
  - NIST – Govern (documentation practices)
- **AUD-04 – Processo de desenvolvimento documentado**

  - ISO/IEC 23894 – Risk management process documentation
  - NIST – Map function
- **AUD-07 – Rastreabilidade entre dados, modelo e decisões**

  - ISO/IEC 23894 – Traceability
  - NIST – Measure and Manage

---

### Explicabilidade

Relacionada a princípios de:

- transparência
- interpretabilidade
- comunicação de decisões

**Critérios:**

- **EXP-01 – Descrição do modelo**

  - OECD – Explainability
  - WHO – Transparency requirements in health AI
- **EXP-04 – Métodos de interpretação**

  - OECD – Explainability
  - literatura de XAI (ex: SHAP, LIME)
- **EXP-05 – Explicações para decisões individuais**

  - WHO – Decision transparency in clinical AI
- **EXP-08 – Material para usuários não técnicos**

  - WHO – Accessibility and usability

---

### Justiça

Relacionada a princípios de:

- fairness
- não discriminação
- equidade

**Critérios:**

- **JUS-02 – Análise de distribuição dos dados**

  - NIST – Measure (data quality and bias)
- **JUS-03 – Desempenho por subgrupo**

  - NIST – Measure (bias detection)
- **JUS-04 – Métricas de fairness**

  - NIST – Measure
  - literatura de fairness em ML
- **JUS-07 – Mitigação de viés**

  - ISO/IEC 23894 – Risk treatment
  - NIST – Manage

---

### Privacidade

Relacionada a princípios de:

- proteção de dados
- segurança da informação
- uso responsável de dados

**Critérios:**

- **PRI-03 – Anonimização/pseudonimização**

  - WHO – Data governance
  - ISO – Data protection practices
- **PRI-04 – Controle de acesso**

  - ISO – Information security
- **PRI-07 – Conformidade legal**

  - LGPD
  - WHO – Legal compliance

---

### Governança

Relacionada a princípios de:

- accountability
- supervisão humana
- gestão de risco

**Critérios:**

- **GOV-01 – Responsáveis definidos**

  - NIST – Govern
- **GOV-03 – Supervisão humana**

  - OECD – Human-centered values
  - WHO – Human oversight
- **GOV-05 – Monitoramento contínuo**

  - NIST – Manage
- **GOV-08 – Revisão periódica**

  - ISO/IEC 23894 – Continuous risk management

---

## Considerações finais

O mapeamento apresentado demonstra que os critérios do FIAR não são arbitrários, mas derivados de práticas consolidadas em frameworks internacionais de IA Responsável.

Essa abordagem fortalece:

- a validade conceitual do framework
- a consistência entre avaliações
- a possibilidade de comparação com outras abordagens

Além disso, o FIAR contribui ao propor a **operacionalização explícita de princípios**, transformando diretrizes abstratas em critérios auditáveis baseados em evidências.
