
# Trilhas de Execução do FIAR-Saúde

Toda tarefa avaliada pelo FIAR-Saúde pertence a uma das duas **trilhas de execução**, determinada pelo destino previsto do modelo.

A trilha é uma **propriedade da tarefa, não do projeto**: um mesmo projeto pode conter simultaneamente tarefas na Trilha Experimental e tarefas na Trilha Produção.

---

## As duas trilhas

| Trilha                        | Características                                                                                                                                                                                                                                                              |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Trilha Experimental** | Tarefa orientada à publicação científica, com número limitado de versões avaliáveis. A avaliação de conformidade é pontual. O projeto que contém apenas tarefas nessa trilha tem **teto de maturidade em N2**.                                              |
| **Trilha Produção**   | Tarefa integrada a um sistema em operação ativa, como plataformas de telemedicina ou sistemas de apoio à decisão clínica. Admite múltiplas versões avaliáveis ao longo do tempo, permitindo que o projeto acumule evidências operacionais e avance**até N4**. |

---

## 1. Trilha Experimental

Na Trilha Experimental, a avaliação é **pontual**: a tarefa é avaliada uma única vez, com base nos artefatos de desenvolvimento produzidos. O nível máximo alcançável é **N2**.

Para atingir N2, a tarefa deve apresentar:

- data card completo e consistente com os dados utilizados;
- model card com finalidade, desempenho, limitações e contexto de uso documentados;
- fairness report com métricas de disparidade e registro de mitigações adotadas;
- explainability report com justificativas das decisões de modelagem;
- registro de decisão técnica rastreável para escolhas metodológicas relevantes.

---

## 2. Trilha Produção

Na Trilha Produção, a maturidade é **acumulativa** e evolui ao longo do tempo conforme o sistema acumula versões, evidências operacionais e estruturas de governança. O ponto de partida é N2, obtido com os mesmos critérios da Trilha Arti aplicados à versão inicial do sistema.

A progressão para N3 e N4 depende de evidências operacionais adicionais:

| Nível       | Nome         | Critérios adicionais para progressão                                                                                                                                                                                                               |
| ------------ | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **N2** | Inicial      | Artefatos de desenvolvimento completos e verificáveis em pelo menos um ciclo de auditoria.                                                                                                                                                          |
| **N3** | Desenvolvido | Recorrência dos mecanismos ao longo de múltiplas versões do sistema, com rastreabilidade longitudinal verificável entre versões. Requer histórico de versões documentado e ao menos um ciclo adicional de auditoria após mudança relevante. |
| **N4** | Consolidado  | Monitoramento contínuo institucionalizado, revisão periódica formal documentada e integração com estruturas permanentes de governança. Requer relatórios de monitoramento e evidência de revisão periódica formal.                         |

Para os critérios completos de cada nível, consulte → [Modelo de Maturidade](modelo_maturidade.md).

---

## 3. Mudanças Relevantes na Trilha Produção

Mudanças no sistema que afetem propriedades avaliadas nas dimensões de IAR requerem novo ciclo de produção de artefatos. Essas mudanças **contribuem para a progressão de maturidade** — não implicam regressão do nível já atribuído.

| Tipo de alteração                       | Exige novo ciclo de artefatos? |
| ----------------------------------------- | ------------------------------ |
| Retreinamento com novos dados             | Sim                            |
| Mudança de features                      | Sim                            |
| Mudança de arquitetura do modelo         | Sim                            |
| Mudança de hiperparâmetros críticos    | Sim                            |
| Mudança inferencial relevante            | Sim                            |
| Correção de bug sem impacto inferencial | Não                           |
| Mudança apenas de infraestrutura         | Não                           |

---

## 4. Migração entre Trilhas

Uma tarefa inicialmente classificada na Trilha Experimental pode migrar para a Trilha Produção quando o modelo é posteriormente integrado a um sistema em operação ativa. Nesse caso:

- o nível de maturidade obtido na Trilha Experimental (N2) é **herdado como ponto de partida**;
- a tarefa passa a ser avaliada sob os critérios adicionais da Trilha Produção;
- a progressão para N3 e N4 requer a produção dos artefatos operacionais correspondentes.

A migração não altera a maturidade do projeto de forma retroativa — ela amplia o conjunto de evidências que o NIAR pode considerar na inferência longitudinal.

---

## 5. Escalonamento

Em tarefas de médio risco, alto risco ou em presença de inconsistências estruturais relevantes, o processo de avaliação pode ser escalonado ao **Comitê Gestor** (órgão interno ao NIAR responsável por deliberações escalonadas). O Comitê Gestor é responsável pela validação de aceites de risco residual significativos, especialmente em cenários com impacto potencial em decisões clínicas, distributivas ou institucionais.

> **Nota para revisão:** este trecho foi ajustado para refletir a hierarquia CIIA → NIAR → Comitê Gestor confirmada internamente — o Relatório Meta 1 (fonte original deste conteúdo) ainda atribui essa função diretamente ao CIIA. Confirmem se esta formulação está correta antes de publicar.

---

## Relação com a metodologia

Para uma visão conceitual dos princípios do framework:
→ [Metodologia do FIAR](metodologia_fiar.md)

Para o processo operacional de auditoria:
→ [Ciclo de Auditoria](ciclo_auditoria.md)

Para os níveis e critérios de maturidade:
→ [Modelo de Maturidade](modelo_maturidade.md)
