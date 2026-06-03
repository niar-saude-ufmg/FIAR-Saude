# Avaliação de Maturidade – FIAR

A avaliação de maturidade no FIAR tem como objetivo transformar os resultados do checklist em uma interpretação estruturada sobre o grau de desenvolvimento das práticas de IA Responsável em um sistema.

O modelo adota uma abordagem **híbrida**, combinando:

- agregação quantitativa dos critérios
- análise qualitativa das evidências

Essa abordagem permite garantir **consistência entre avaliações**, ao mesmo tempo em que preserva a **capacidade interpretativa do auditor**, especialmente em contextos complexos como a saúde pública.

---

## Objetivo da avaliação de maturidade

A avaliação de maturidade busca:

- sintetizar os resultados do checklist por dimensão
- identificar o nível de desenvolvimento das práticas de IA Responsável
- apoiar recomendações de melhoria
- permitir comparabilidade entre sistemas

A maturidade é avaliada **por dimensão**, e não apenas de forma global, permitindo uma análise mais granular.

---

## Estrutura da avaliação

A avaliação de maturidade é realizada em três etapas:

1. **Pontuação dos critérios (nível operacional)**
2. **Agregação por dimensão**
3. **Classificação do nível de maturidade**

---

## 1. Pontuação dos critérios

Cada critério do checklist é classificado como:

- **Presente** → 1.0
- **Parcial** → 0.5
- **Ausente** → 0.0

Essa pontuação é utilizada como suporte à análise, não como decisão final automática.

---

## 2. Agregação por dimensão

Para cada dimensão, calcula-se uma pontuação agregada com base nos critérios avaliados:

\[
Score_{dimensão} = \frac{\sum pontuação\ dos\ critérios}{número\ de\ critérios}
\]

Esse score representa uma **medida indicativa** do nível de maturidade na dimensão.

---

## 3. Interpretação qualitativa

A classificação final da maturidade não depende exclusivamente do score.

O auditor deve considerar:

### Cobertura dos critérios

- Quantos critérios estão presentes ou parcialmente atendidos

### Qualidade das evidências

- Clareza, consistência e confiabilidade da documentação

### Robustez das práticas

- Se as práticas estão institucionalizadas ou são pontuais

### Consistência interna

- Alinhamento entre diferentes artefatos e evidências

Essa análise evita distorções, como:

- pontuação alta baseada em evidências frágeis
- presença superficial de práticas sem implementação real

---

## Níveis de maturidade

O FIAR utiliza quatro níveis de maturidade:

### L1 – Ad-hoc

- ausência de documentação estruturada
- práticas inexistentes ou informais
- evidências escassas ou inexistentes

### L2 – Inicial

- documentação básica disponível
- algumas práticas implementadas de forma parcial
- evidências limitadas ou inconsistentes

### L3 – Desenvolvido

- práticas estruturadas e documentadas
- evidências consistentes e verificáveis
- aplicação sistemática em partes do sistema

### L4 – Consolidado

- práticas institucionalizadas
- monitoramento contínuo
- governança integrada
- evidências robustas e atualizadas

---

## Relação entre score e maturidade

O score quantitativo pode ser utilizado como referência indicativa:

| Score aproximado | Interpretação sugerida |
| ---------------- | ------------------------ |
| 0.00 – 0.25     | L1 – Ad-hoc             |
| 0.25 – 0.50     | L2 – Inicial            |
| 0.50 – 0.75     | L3 – Desenvolvido       |
| 0.75 – 1.00     | L4 – Consolidado        |

**Importante:**
Esses intervalos são orientativos. A classificação final deve ser validada pela análise qualitativa do auditor.

---

## Papel do auditor

O auditor é responsável por:

- interpretar os resultados do checklist
- avaliar a qualidade das evidências
- justificar a classificação atribuída
- documentar possíveis inconsistências

A decisão final de maturidade deve sempre ser acompanhada de **justificativa explícita**, garantindo transparência e rastreabilidade.

---

## Saída da avaliação

A avaliação de maturidade resulta em:

- nível de maturidade por dimensão
- justificativas documentadas
- identificação de lacunas
- recomendações de melhoria

Esses resultados são consolidados no relatório final de auditoria.

---

## Relação com o checklist

A avaliação de maturidade depende diretamente dos resultados do checklist.

Para critérios operacionais:

→ [Checklist de Avaliação](avaliacao/checklist.md)

---

## Relação com o ciclo de auditoria

A avaliação de maturidade é realizada na etapa de avaliação do ciclo de auditoria.

Para o processo completo:

→ [Ciclo de Auditoria](ciclo_auditoria.md)

---

## Considerações finais

A abordagem híbrida adotada pelo FIAR busca equilibrar:

- **objetividade**, por meio da agregação de critérios
- **flexibilidade**, por meio da interpretação qualitativa

Essa combinação permite aplicar o framework em contextos reais de saúde pública, onde a complexidade dos sistemas exige análises que vão além de métricas puramente quantitativas.
