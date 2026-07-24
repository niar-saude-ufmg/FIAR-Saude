# Mapeamento de Referências – FIAR

Este documento apresenta o mapeamento entre os critérios operacionais do checklist FIAR e referências internacionais em IA Responsável.

O objetivo é explicitar a fundamentação teórica e normativa do framework, demonstrando como princípios abstratos são traduzidos em critérios verificáveis de auditoria.

---

## Abordagem de mapeamento

O FIAR adota uma estrutura em três níveis:

1. **Princípios de IA Responsável** (ex: transparência, justiça, accountability)
2. **Dimensões do FIAR** (governança, segurança, privacidade, responsabilização, rastreabilidade, justiça, transparência)
3. **Critérios operacionais**
   (itens do checklist, ex: GOV-01, RAS-04)

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

### Segurança

Relacionada a princípios de:

- proteção contra ameaças e acessos não autorizados
- integridade e disponibilidade de sistemas
- resposta a incidentes

**Critérios:**

- **SEG-01 – Mecanismos de autenticação e autorização**

  - ISO/IEC 23894 – Risk treatment (controle de acesso)
  - NIST – Govern (organizational security practices)
- **SEG-03 – Isolamento do ambiente de processamento de dados sensíveis**

  - WHO – Data governance and security
  - ISO – Information security
- **SEG-06 – Plano de resposta a incidentes de segurança**

  - NIST – Respond function
  - ISO/IEC 23894 – Risk treatment and monitoring
- **SEG-07 – Registros de incidentes de segurança**

  - NIST – Detect and Respond functions

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

### Responsabilização

Relacionada a princípios de:

- accountability
- atribuição de responsabilidade institucional
- prestação de contas

**Critérios:**

- **RESP-01 – Responsáveis técnicos identificados**

  - NIST – Govern (roles and responsibilities)
- **RESP-04 – Registro de decisão técnica com identificação nominal**

  - OECD – Accountability
  - ISO/IEC 23894 – Documentation and traceability of decisions
- **RESP-05 – Aceite de risco residual documentado**

  - NIST – Manage (risk acceptance)
  - ISO/IEC 23894 – Risk treatment
- **RESP-07 – Registro de aprovação institucional para decisões escalonadas**

  - OECD – Accountability
  - WHO – Institutional oversight

---

### Rastreabilidade

Relacionada a princípios de:

- transparência
- accountability
- documentação e reprodutibilidade

**Critérios:**

- **RAS-01 – Documentação do sistema**

  - OECD – Transparency and explainability
  - ISO/IEC 23894 – Documentation and traceability
  - NIST – Govern (documentation practices)
- **RAS-04 – Processo de desenvolvimento documentado**

  - ISO/IEC 23894 – Risk management process documentation
  - NIST – Map function
- **RAS-07 – Rastreabilidade entre dados, modelo e decisões**

  - ISO/IEC 23894 – Traceability
  - NIST – Measure and Manage

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

### Transparência

Relacionada a princípios de:

- transparência
- interpretabilidade
- comunicação de decisões

**Critérios:**

- **TRA-01 – Descrição do modelo**

  - OECD – Explainability
  - WHO – Transparency requirements in health AI
- **TRA-04 – Métodos de interpretação**

  - OECD – Explainability
  - literatura de XAI (ex: SHAP, LIME)
- **TRA-05 – Explicações para decisões individuais**

  - WHO – Decision transparency in clinical AI
- **TRA-08 – Material para usuários não técnicos**

  - WHO – Accessibility and usability

---

## Considerações finais

O mapeamento apresentado demonstra que os critérios do FIAR não são arbitrários, mas derivados de práticas consolidadas em frameworks internacionais de IA Responsável.

Essa abordagem fortalece:

- a validade conceitual do framework
- a consistência entre avaliações
- a possibilidade de comparação com outras abordagens

Além disso, o FIAR contribui ao propor a **operacionalização explícita de princípios**, transformando diretrizes abstratas em critérios auditáveis baseados em evidências.
