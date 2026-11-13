# Avaliação de Justiça

A dimensão de Justiça avalia se a Tarefa de IA pode produzir, reproduzir ou agravar diferenças injustificadas entre grupos e populações relevantes, considerando tanto os efeitos da Tarefa quanto a adequação dos dados, variáveis-alvo, padrões de referência e formas de disponibilização.

A análise não deve presumir que toda diferença observada represente automaticamente injustiça ou discriminação. Também não deve limitar a seleção de grupos aos atributos disponíveis nos dados.

A dimensão está organizada em quatro requisitos: **RC01 a RC04**. Cada requisito é avaliado para a combinação **Tarefa de IA + Versão Avaliável + Contexto de Uso**, considerando a Trilha de Execução, com os resultados definidos em [ciclo_avaliacao.md](../ciclo_avaliacao.md).

A aplicabilidade, o checklist do avaliador, os exemplos de evidências e os mecanismos de verificação de cada requisito estão no [Guia de Requisitos para Avaliação](https://github.com/niar-saude-ufmg/FIAR-Audit-Template/blob/main/documentacao_metodologica/guia_requisitos_avaliacao.md) do FIAR-Audit-Template. Os exemplos de evidências não constituem lista obrigatória de artefatos. O Fairness Report é a exceção: é obrigatório nesta dimensão (ver Fairness Report, abaixo). O modelo do relatório também está no FIAR-Audit-Template.

---

## RC01 — Grupos e populações

**Requisito:** Identificar, de forma fundamentada, os grupos e populações que podem ser afetados de forma desigual pela Tarefa de IA ou excluídos de seus benefícios.

**O que busca verificar:** se os grupos e populações relevantes para a análise de Justiça foram identificados de forma fundamentada a partir da Tarefa de IA, da população pertinente e do Contexto de Uso avaliado. O requisito não busca simplesmente listar atributos existentes nos dados.

---

## RC02 — Diferenças nos efeitos

**Requisito:** Avaliar se a Tarefa de IA produz, reproduz ou agrava diferenças injustificadas nos efeitos sobre os grupos e populações identificados.

**O que busca verificar:** se os efeitos relevantes e observáveis da Tarefa foram examinados entre os grupos identificados em RC01 e, quando diferenças forem encontradas, se elas foram interpretadas de forma contextualizada. A análise não pressupõe uma métrica universal de fairness nem exige necessariamente comparação estatística formal para todos os grupos.

---

## RC03 — Dados, variáveis-alvo e padrões de referência

**Requisito:** Avaliar se os dados, as variáveis-alvo e os padrões de referência utilizados no desenvolvimento e na avaliação da Tarefa de IA são adequados para os grupos e populações identificados.

**O que busca verificar:** se características dos dados, das variáveis-alvo e dos padrões de referência podem produzir ou contribuir para diferenças relevantes entre os grupos identificados em RC01. RC03 não substitui a avaliação geral de qualidade de dados. Em Justiça, o foco é verificar se existe mecanismo plausível de efeito diferenciado entre grupos.

---

## RC04 — Acesso e possibilidade de benefício

**Requisito:** Avaliar se a forma de disponibilização da Tarefa de IA produz, reproduz ou agrava desigualdades injustificadas entre os grupos e populações identificados quanto à possibilidade de se beneficiar de seu uso.

**O que busca verificar:** se a forma concreta pela qual a Tarefa é disponibilizada no Contexto de Uso avaliado cria ou agrava diferenças entre grupos quanto à possibilidade de acessar, utilizar ou se beneficiar da Tarefa. O requisito trata de desigualdades associadas à disponibilização da Tarefa, e não de diferenças de desempenho já analisadas em RC02.

---

## Fairness Report

O Fairness Report é obrigatório nesta dimensão, nas Trilhas Experimental e Produção. É a posição formal da equipe sobre RC01 a RC04. As Seções 1 a 4 correspondem a RC01 a RC04, e cada campo indica o item do checklist a que responde (RCxx.y). O agente da sala segura pré-preenche o relatório a partir da execução, do Model Card e do Data Card. Sem execução na sala segura, os fatos vêm de publicações ou relatórios técnicos, indicados como fonte. Os fatos ficam resumidos no relatório, com fonte e versão de cada um. A equipe confere, completa os julgamentos e assina.

O NIAR-Saúde verifica o relatório com as demais evidências em avaliacao.md e aponta lacunas. A equipe responde em nova versão do relatório. O resultado dos requisitos é do NIAR-Saúde e não consta do relatório. A Seção 5 do relatório, síntese da equipe, é apresentada ao Comitê Gestor no relatório do NIAR-Saúde.

## Fontes de evidência

Informações factuais podem ser recuperadas de Data Card, Model Card, documentação do projeto, resultados experimentais ou outras fontes, que o Fairness Report resume, com fonte e versão.
