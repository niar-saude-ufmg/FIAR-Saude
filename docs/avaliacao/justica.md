# Avaliação de Justiça (Fairness)

A dimensão de justiça do framework FIAR examina possíveis impactos desiguais de sistemas de inteligência artificial sobre diferentes grupos populacionais.

Em contextos de saúde pública, decisões baseadas em modelos podem afetar grupos de maneira distinta devido a fatores como desigualdades socioeconômicas, acesso desigual a serviços de saúde ou características demográficas da população.

A avaliação busca identificar possíveis **disparidades de desempenho ou impactos discriminatórios** associados ao sistema.

A análise de justiça está alinhada a abordagens de avaliação de fairness em sistemas de IA discutidas na literatura e em diretrizes internacionais de IA Responsável.

---

## Objetivo da dimensão 

A análise de justiça busca avaliar se o sistema:

* apresenta diferenças de desempenho entre grupos relevantes
* utiliza dados representativos da população de interesse
* envolve riscos de reforço de desigualdades estruturais
* possui mecanismos para monitoramento e mitigação de disparidades

A avaliação não pressupõe que todo sistema apresente viés, mas busca identificar **riscos potenciais e evidências disponíveis**.

---

## Identificação de grupos relevantes

A avaliação considera a identificação de subgrupos relevantes no contexto de aplicação do sistema.

Esses grupos dependem do problema analisado e da população afetada.

Exemplos incluem:

* gênero
* faixa etária
* região geográfica
* raça ou etnia (quando disponível e apropriado)
* nível socioeconômico
* presença de comorbidades

Quando não há dados disponíveis para determinados grupos, a avaliação considera as limitações existentes.

---

## Análise de desempenho por subgrupo

Quando possível, o desempenho do modelo deve ser analisado separadamente para diferentes grupos.

Métricas que podem ser consideradas incluem:

* acurácia
* precisão
* recall
* taxa de falsos positivos
* taxa de falsos negativos
* AUC ou outras métricas relevantes

Diferenças significativas entre grupos podem indicar riscos de impacto desigual.

---

## Fontes de viés

A avaliação considera possíveis fontes de viés ao longo do ciclo de desenvolvimento do sistema, como: 

* viés nos dados de treinamento
* sub-representação de determinados grupos
* uso de variáveis correlacionadas com atributos sensíveis
* decisões de modelagem que amplificam desigualdades existentes

A identificação de viés não implica necessariamente discriminação, mas indica necessidade de análise adicional.

---

## Estratégias de mitigação

A avaliação considera se o projeto adota estratégias para lidar com possíveis disparidades.

Exemplos incluem:

* melhoria da representatividade dos dados
* uso de técnicas de balanceamento
* ajuste de thresholds de decisão
* monitoramento contínuo por subgrupo

---

## Riscos associados

A ausência de avaliação de justiça pode gerar riscos como:

* impactos desiguais entre grupos populacionais
* reforço de desigualdades estruturais existentes
* discriminação indireta em decisões automatizadas
* perda de legitimidade institucional do sistema

---

## Evidências esperadas 

O auditor pode considerar evidências como:

* análises de desempenho por subgrupo
* relatórios de avaliação de fairness
* documentação sobre coleta e preparação dos dados
* descrição de limitações relacionadas a representatividade
* registros de estratégias de mitigação adotadas

A ausência de determinadas evidências não implica automaticamente uma falha, mas pode indicar menor maturidade.


---

## Critérios de avaliação

A avaliação da dimensão considera:

* identificação adequada de grupos relevantes
* disponibilidade de análises por subgrupo
* qualidade e transparência das evidências
* reconhecimento de limitações dos dados
* existência de estratégias de mitigação

---

## Exemplos de análise

Exemplos de avaliação incluem:

* comparação de métricas de desempenho entre grupos
* análise da representatividade dos dados utilizados
* verificação da existência de relatórios de fairness
* avaliação de estratégias adotadas para reduzir disparidades

---

## Resultado da avaliação

O auditor avalia a dimensão de justiça com base nas evidências disponíveis e nos critérios definidos pelo framework.

O resultado é expresso em nível de maturidade (L1–L4), acompanhado de justificativas e recomendações para melhoria, sendo registrado no relatório final de auditoria.