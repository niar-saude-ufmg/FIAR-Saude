# Trilhas de Execução do FIAR-Saúde

Toda tarefa avaliada pelo FIAR-Saúde pertence a uma das duas **trilhas de execução**, determinada pela situação de operação da tarefa no contexto avaliado.

A trilha é uma **propriedade da tarefa, não do projeto**: um mesmo projeto pode conter simultaneamente tarefas na Trilha Experimental e tarefas na Trilha Produção.

A trilha orienta a aplicabilidade dos requisitos e a natureza das evidências necessárias. O NIAR-Saúde registra a trilha na delimitação do ciclo.

---

## As duas trilhas

| Trilha                        | Características                                                                                                                                                                                     |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Trilha Experimental** | Tarefa em pesquisa, desenvolvimento ou validação, sem operação ativa. As evidências vêm, em geral, dos artefatos de desenvolvimento.                                                           |
| **Trilha Produção**   | Tarefa em operação ativa, como em plataformas de telemedicina ou sistemas de apoio à decisão clínica. Além dos artefatos de desenvolvimento, podem ser necessárias evidências de operação. |

Avaliar um uso pretendido não altera, por si só, a trilha atual da tarefa nem demonstra atendimento a requisitos que dependam de evidências de operação.

---

## Mudanças relevantes

Mudanças na tarefa são analisadas pelo impacto, conforme a seção Mudanças relevantes de [ciclo_avaliacao.md](ciclo_avaliacao.md). Os tratamentos possíveis são: apenas registrar a mudança, reavaliar os requisitos afetados, abrir novo ciclo ou delimitar nova Tarefa de IA.

Exemplos:

| Tipo de alteração                       | Tratamento usual    |
| ----------------------------------------- | ------------------- |
| Retreinamento com novos dados             | Análise de impacto |
| Mudança de features                      | Análise de impacto |
| Mudança de arquitetura do modelo         | Análise de impacto |
| Mudança de hiperparâmetros críticos    | Análise de impacto |
| Mudança inferencial relevante            | Análise de impacto |
| Correção de bug sem impacto inferencial | Apenas registro     |
| Mudança apenas de infraestrutura         | Apenas registro     |

---

## Migração entre trilhas

Uma tarefa na Trilha Experimental passa à Trilha Produção quando entra em operação ativa. Essa mudança é tratada como mudança relevante e é um dos gatilhos de envio do relatório ao Comitê Gestor.

---

## Encaminhamentos ao Comitê Gestor

Questões que ultrapassam a avaliação técnica, como aceite de risco, restrição de uso, definição de responsabilidades ou conflitos relevantes, são encaminhadas ao Comitê Gestor, conforme [ciclo_avaliacao.md](ciclo_avaliacao.md) e [governanca_avaliacao.md](governanca_avaliacao.md).

---

## Relação com a maturidade (em revisão)

> O conteúdo abaixo vem da versão anterior deste documento. Ele não é aplicado nesta versão do FIAR-Saúde e será revisto junto com o modelo de maturidade.

- Projeto com apenas tarefas na Trilha Experimental: teto de maturidade em N2. Trilha Produção: progressão até N4.
- Critérios previstos para N2: data card completo e consistente com os dados utilizados; model card com finalidade, desempenho, limitações e contexto de uso documentados; fairness report com métricas de disparidade e registro de mitigações adotadas; explainability report com justificativas das decisões de modelagem; registro de decisão técnica rastreável para escolhas metodológicas relevantes.
- Progressão na Trilha Produção: N3 (Desenvolvido) exige recorrência dos mecanismos ao longo de múltiplas versões, histórico de versões documentado e ao menos um ciclo adicional após mudança relevante; N4 (Consolidado) exige monitoramento contínuo institucionalizado, revisão periódica formal documentada e integração com estruturas permanentes de governança.
- Mudanças relevantes contribuem para a progressão de maturidade e não implicam regressão do nível já atribuído.
- Na migração para a Trilha Produção, o nível obtido na Trilha Experimental (N2) é herdado como ponto de partida, sem alteração retroativa da maturidade do projeto.

---

## Relação com a metodologia

Para uma visão conceitual dos princípios do framework:
→ [Metodologia do FIAR](metodologia_fiar.md)

Para o processo operacional de avaliação:
→ [Ciclo de Avaliação](ciclo_avaliacao.md)

Para os níveis e critérios de maturidade:
→ [Modelo de Maturidade](modelo_maturidade.md)
