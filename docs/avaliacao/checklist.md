# Checklist de Avaliação – FIAR

O checklist do FIAR é o principal instrumento operacional utilizado para avaliar sistemas de inteligência artificial no contexto de IA Responsável.

Ele transforma princípios e dimensões do framework em **critérios verificáveis**, permitindo uma avaliação estruturada, comparável e baseada em evidências documentadas.

---


## Como usar este checklist

Este checklist deve ser utilizado como instrumento único de avaliação durante a auditoria FIAR.

O auditor deve:

1. Coletar a documentação e artefatos do sistema
2. Avaliar cada critério com base em evidências disponíveis
3. Classificar cada item como: presente, parcial ou ausente
4. Registrar evidências que justifiquem a avaliação

A avaliação deve ser baseada exclusivamente em evidências documentadas.

---

## Objetivo do checklist

O checklist tem como objetivo:

- padronizar o processo de auditoria
- garantir consistência entre avaliações
- conectar evidências documentais a critérios objetivos
- apoiar a atribuição de níveis de maturidade

Cada item do checklist corresponde a um critério verificável associado a uma dimensão de IA Responsável.

---

## Estrutura do checklist

Cada item do checklist é definido por:

- **Código do critério** (ex: AUD-01, EXP-02)
- **Descrição do critério**
- **Evidência esperada**

Os critérios estão organizados por dimensão:

- Auditabilidade (AUD)
- Explicabilidade (EXP)
- Justiça (JUS)
- Privacidade (PRI)
- Governança (GOV)

---

## Escala de avaliação

Cada critério é avaliado pelo auditor com base nas evidências disponíveis, utilizando a seguinte escala:

| Classificação | Descrição                                                           |
| --------------- | --------------------------------------------------------------------- |
| Presente        | O critério é plenamente atendido com evidência clara e documentada |
| Parcial         | O critério é parcialmente atendido ou a evidência é incompleta    |
| Ausente         | Não há evidência suficiente para atender ao critério              |

A avaliação deve ser sempre baseada em **evidências verificáveis**, e não em suposições.

A avaliação deve ser conduzida por auditor independente, com base exclusivamente nas evidências fornecidas pelo projeto.

---

## Papel do checklist na auditoria

O processo de avaliação segue as etapas:

1. Coleta de artefatos e documentação do sistema
2. Análise das evidências disponíveis
3. Preenchimento do checklist por dimensão
4. Consolidação dos resultados

Os resultados do checklist são utilizados para:

- identificar lacunas
- documentar práticas existentes
- apoiar recomendações
- calcular níveis de maturidade

---

## Relação com níveis de maturidade

Os resultados do checklist são agregados por dimensão e utilizados para determinar o nível de maturidade do sistema.

A atribuição de maturidade considera:

- número de critérios atendidos
- qualidade e robustez das evidências
- consistência das práticas ao longo do sistema

Os níveis seguem o modelo do FIAR:

- L1 – Ad-hoc
- L2 – Inicial
- L3 – Desenvolvido
- L4 – Consolidado

---

## Estrutura dos critérios por dimensão

### Auditabilidade (AUD)

| Código | Critério                                              | Evidência esperada        |
| ------- | ------------------------------------------------------ | -------------------------- |
| AUD-01  | O sistema possui documentação geral                  | documentação do sistema  |
| AUD-02  | Existe descrição das fontes de dados                 | Data Card                  |
| AUD-03  | Existe documentação do modelo                        | Model Card                 |
| AUD-04  | O processo de desenvolvimento está documentado        | relatórios técnicos      |
| AUD-05  | Existem registros de decisões relevantes              | logs / documentação      |
| AUD-06  | Os artefatos técnicos estão disponíveis             | repositórios / documentos |
| AUD-07  | Existe rastreabilidade entre dados, modelo e decisões | documentação integrada   |
| AUD-08  | A documentação permite reprodutibilidade básica     | documentação técnica    |

---

### Explicabilidade (EXP)

| Código | Critério                                          | Evidência esperada          |
| ------- | -------------------------------------------------- | ---------------------------- |
| EXP-01  | O modelo possui descrição geral documentada      | Model Card                   |
| EXP-02  | As variáveis utilizadas são descritas            | documentação               |
| EXP-03  | O processo de treinamento é documentado           | relatório técnico          |
| EXP-04  | Existem métodos de interpretação do modelo      | SHAP, LIME etc.              |
| EXP-05  | Existem explicações para decisões individuais   | exemplos documentados        |
| EXP-06  | As explicações são adequadas ao contexto de uso | documentação               |
| EXP-07  | Limitações das explicações são documentadas   | Model Card                   |
| EXP-08  | Existe material para usuários não técnicos      | documentação institucional |

---

### Justiça (JUS)

| Código | Critério                                               | Evidência esperada |
| ------- | ------------------------------------------------------- | ------------------- |
| JUS-01  | Grupos relevantes foram identificados                   | documentação      |
| JUS-02  | Existe análise de distribuição dos dados             | Data Card           |
| JUS-03  | Existe análise de desempenho por subgrupo              | relatório          |
| JUS-04  | Métricas de fairness foram utilizadas                  | relatório          |
| JUS-05  | Possíveis fontes de viés foram analisadas             | documentação      |
| JUS-06  | Limitações relacionadas à justiça são documentadas | Model Card          |
| JUS-07  | Existem estratégias de mitigação de viés            | relatório          |
| JUS-08  | Existe monitoramento por subgrupo                       | documentação      |

---

### Privacidade (PRI)

| Código | Critério                               | Evidência esperada |
| ------- | --------------------------------------- | ------------------- |
| PRI-01  | A origem dos dados é documentada       | Data Card           |
| PRI-02  | Dados sensíveis são identificados     | documentação      |
| PRI-03  | Existe anonimização/pseudonimização | documentação      |
| PRI-04  | Existem controles de acesso             | políticas          |
| PRI-05  | Existe armazenamento seguro             | documentação      |
| PRI-06  | Existe política de retenção de dados | documentação      |
| PRI-07  | Existe conformidade legal (ex: LGPD)    | documentação      |
| PRI-08  | Existe governança de dados             | políticas          |

---

### Governança (GOV)

| Código | Critério                          | Evidência esperada |
| ------- | ---------------------------------- | ------------------- |
| GOV-01  | Existem responsáveis definidos    | documentação      |
| GOV-02  | Papéis estão documentados        | organograma         |
| GOV-03  | Existe supervisão humana          | processos           |
| GOV-04  | Existem políticas de uso          | documentação      |
| GOV-05  | Existe monitoramento contínuo     | relatórios         |
| GOV-06  | Existem processos de atualização | documentação      |
| GOV-07  | Existem registros de decisão      | logs                |
| GOV-08  | Existe revisão periódica         | documentação      |

---

## Considerações finais

O checklist é um instrumento central do FIAR, permitindo a tradução de princípios de IA Responsável em critérios operacionais verificáveis.

Seu uso sistemático garante:

- transparência na avaliação
- rastreabilidade das decisões
- consistência entre auditorias
- suporte à melhoria contínua


