# Metodologia do Framework FIAR

## Objetivo do framework

O FIAR (Framework de Auditoria de IA Responsável) foi desenvolvido para apoiar a **documentação, avaliação e auditoria** de sistemas de inteligência artificial aplicados à saúde pública.

Seu objetivo é transformar princípios de IA Responsável em **controles verificáveis**, baseados em evidências documentadas e avaliados por meio de dimensões estruturadas.

O framework busca reduzir a distância entre **princípios normativos de ética em IA** e **práticas operacionais de governança e auditoria** de sistemas de IA.

Essa abordagem está alinhada a diretrizes internacionais de IA Responsável, como os princípios da OECD para IA, recomendações da Organização Mundial da Saúde (OMS) para sistemas de IA em saúde e normas de gestão de risco em IA propostas pela ISO/IEC.

---

## Princípios do framework

O FIAR baseia-se em quatro princípios metodológicos:

### Documentação estruturada

Sistemas de IA devem possuir documentação clara sobre contexto, dados utilizados, arquitetura do modelo e finalidade.

### Evidências verificáveis

A avaliação de IA Responsável deve ser baseada em evidências documentadas, como artefatos técnicos e registros do sistema.

### Separação entre projeto e auditoria

O framework estabelece uma distinção entre:

* **artefatos produzidos pelo projeto**
* **avaliações conduzidas por auditores independentes** 

O projeto não avalia a si próprio, sendo responsável por fornecer evidências que serão analisadas por auditor independente.

### Avaliação multidimensional

A auditoria considera múltiplas dimensões de IA Responsável, refletindo diferentes categorias de risco.

No FIAR, essas dimensões incluem:

* auditabilidade
* explicabilidade
* justiça
* privacidade
* governança

---

## Estrutura da auditoria

A auditoria utilizando o FIAR é organizada em três componentes principais:

1. **Documentação do sistema de IA**
2. **Artefatos técnicos produzidos pelo projeto**
3. **Avaliação independente conduzida pelo auditor**

A documentação e os artefatos são produzidos pela equipe responsável pelo sistema de IA, enquanto a avaliação é conduzida com base em critérios definidos pelo framework.

---

## Evidências e artefatos

A auditoria FIAR baseia-se na análise de evidências documentadas fornecidas pelo projeto.

Entre os principais artefatos estão:

* documentação inicial do sistema
* Data Cards
* Model Cards
* relatórios técnicos
* documentação de governança

Esses artefatos permitem registrar informações relevantes, como:

* fontes de dados
* decisões de modelagem
* limitações do sistema
* potenciais impactos

---

## Avaliação de maturidade

O FIAR avalia o grau de maturidade do sistema em cada dimensão de IA Responsável.

Cada dimensão é analisada com base:

* nas evidências fornecidas pelo projeto
* nos critérios definidos pelo framework

A avaliação considera:

* nível de documentação existente
* presença de práticas de mitigação de riscos
* mecanismos de transparência
* práticas institucionais de governança

Os resultados são expressos por níveis de maturidade (L1-L4), acompanhados de justificativas documentadas.

--- 

## Resultado da auditoria

O processo de auditoria resulta na produção de um **relatório de auditoria**, que inclui:

* avaliação por dimensão
* evidências analisadas
* justificativas das avaliações
* recomendações para melhoria

O relatório apoia processos de **governança, transparência e melhoria contínua**.

---

## Implementação do framework

O FIAR é operacionalizado por meio de um template estruturado:

👉 https://github.com/marisavas/FIAR-Audit-Template

O template fornece suporte para:

* documentação do sistema
* organização de artefatos
* registro das avaliações
* estruturação do relatório final

Cada auditoria deve ser conduzida em um **repositório próprio criado a partir do template**, garantindo padronização e rastreabilidade.

---

## Arquitetura conceitual do framework

O FIAR distingue entre:

- **camada técnica** (avaliação por dimensões)
- **camada institucional** (maturidade e governança)

As dimensões técnicas fornecem evidências para a avaliação institucional do sistema.

## Relação com o processo de auditoria

A operacionalização da metodologia descrita neste documento é detalhada em:

→ [Ciclo de Auditoria](ciclo_auditoria.md)

Para critérios de avaliação por dimensão, consulte:

→ [Dimensões de Avaliação](dimensoes_avaliacao.md)