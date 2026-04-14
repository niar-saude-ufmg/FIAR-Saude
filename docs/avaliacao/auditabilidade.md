# Avaliação de Auditabilidade

A dimensão de auditabilidade no framework FIAR examina em que medida um sistema de inteligência artificial possui documentação, rastreabilidade e evidências suficientes para permitir análise, verificação e reprodutibilidade ao longo de seu ciclo de vida.

A auditabilidade é um requisito fundamental para a avaliação de sistemas de IA, pois possibilita a reconstrução de decisões técnicas e institucionais, além de sustentar práticas de transparência e governança.

Essa dimensão está alinhada a diretrizes internacionais de IA Responsável, incluindo princípios da OECD, recomendações da Organização Mundial da Saúde (OMS) e normas de gestão de risco em IA (como ISO/IEC 23894), que destacam a importância de documentação, rastreabilidade e prestação de contas.

---

## Objetivo da dimensão

A análise de auditabilidade busca responder perguntas como:

- O sistema possui documentação estruturada?
- É possível rastrear decisões ao longo do desenvolvimento?
- Os dados e modelos são reprodutíveis?
- Existem evidências suficientes para permitir auditoria independente?

---

## Riscos associados

A ausência de auditabilidade pode gerar riscos relevantes, incluindo:

- impossibilidade de verificar decisões do sistema
- falta de transparência sobre dados e modelos
- dificuldade de identificar erros ou falhas
- impossibilidade de reproduzir resultados
- limitação na responsabilização institucional

Esses riscos comprometem a confiabilidade do sistema e dificultam sua governança.

---

## Componentes da auditabilidade

A avaliação considera diferentes componentes que sustentam a auditabilidade do sistema:

### Documentação do sistema

Refere-se à existência de documentação clara sobre:

- objetivo do sistema
- contexto de aplicação
- arquitetura do modelo
- fluxos de dados

### Rastreabilidade

Refere-se à capacidade de reconstruir decisões e processos ao longo do ciclo de vida do sistema, incluindo:

- origem e transformação dos dados
- versões de modelos
- decisões de modelagem
- registros de alterações

### Reprodutibilidade

Refere-se à possibilidade de reproduzir resultados do sistema com base nas informações disponíveis, incluindo:

- acesso a dados (ou suas descrições)
- parâmetros do modelo
- procedimentos de treinamento
- ambientes computacionais

### Disponibilidade de artefatos

Refere-se à existência de artefatos técnicos e documentais que sustentam a avaliação, como:

- Data Cards
- Model Cards
- relatórios técnicos
- logs de execução
- registros de experimentos

---

## Evidências esperadas

A avaliação pode considerar diferentes tipos de evidência fornecida pelo projeto, incluindo:

- documentação inicial do sistema
- Data Cards e Model Cards
- registros de versionamento de dados e modelos
- logs de treinamento e execução
- relatórios técnicos e experimentais
- documentação de decisões relevantes

A ausência de evidências não implica necessariamente falha, mas indica menor maturidade na dimensão.

---

## Critérios de avaliação

A avaliação de auditabilidade considera:

- existência de documentação estruturada
- nível de rastreabilidade de dados e modelos
- capacidade de reproduzir resultados
- disponibilidade e organização de artefatos
- consistência entre evidências fornecidas

Os critérios são operacionalizados por meio do checklist FIAR, sendo classificados como:

- presente
- parcial
- ausente

---

## Exemplos de análise

Exemplos de situações avaliadas incluem:

- verificação da existência de Model Cards e Data Cards
- análise de logs de treinamento e versionamento de modelos
- rastreamento de decisões ao longo do desenvolvimento
- avaliação da capacidade de reproduzir experimentos

---

## Resultado da avaliação

O auditor avalia a dimensão de auditabilidade considerando:

- qualidade e completude da documentação
- nível de rastreabilidade do sistema
- disponibilidade de evidências técnicas
- capacidade de auditoria independente

Os resultados são registrados no relatório final de auditoria, juntamente com justificativas e recomendações para melhoria.

---

## Relação com o processo de auditoria

A auditabilidade sustenta todas as demais dimensões do framework, pois a avaliação de explicabilidade, justiça, privacidade e governança depende da disponibilidade de evidências confiáveis.

Sem auditabilidade, a avaliação das demais dimensões torna-se limitada ou inviável.

Para o processo completo de auditoria, consulte:
→ [Ciclo de Auditoria](../ciclo_auditoria.md)

---
