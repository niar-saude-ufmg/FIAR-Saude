# Prompts utilizados na revisão metodológica dos requisitos

> Os modelos de linguagem são utilizados como instrumentos auxiliares de busca,
> organização e comparação textual. A fundamentação dos requisitos é estabelecida
> pelas fontes originais e deve ser verificável independentemente da saída do modelo.

## 1. Extração independente a partir das fontes

**Objetivo:** identificar princípios e requisitos candidatos sem expor ao modelo os requisitos atuais do FIAR-Saúde, reduzindo viés de confirmação.

**Prompt:**

> Use exclusivamente as fontes carregadas neste notebook.
>
> Quero identificar quais requisitos metodológicos de **Responsabilização em IA** podem ser extraídos dessas fontes, sem usar nenhuma lista pré-existente de requisitos do FIAR-Saúde.
>
> Extraia das fontes apenas obrigações, recomendações ou princípios operacionalizáveis relacionados a:
>
> - atribuição de responsabilidade;
> - accountability;
> - decisões e tomada de decisão;
> - ações e acompanhamento;
> - distribuição, compartilhamento ou transferência de responsabilidade;
> - clareza de papéis;
> - prestação de contas;
> - consequências, impactos ou resultados;
> - registros necessários para accountability.
>
> Para cada requisito candidato:
>
> 1. formule a ideia em linguagem neutra e curta;
> 2. indique as fontes que a sustentam;
> 3. cite seção/página;
> 4. classifique a sustentação como direta ou conceitual;
> 5. diga se a ideia aparece em uma única fonte ou é recorrente em várias;
> 6. não use nem reproduza requisitos existentes do FIAR-Saúde;
> 7. não tente chegar a um número predeterminado de requisitos;
> 8. agrupe ideias redundantes ou fortemente sobrepostas.
>
> Ao final, produza uma lista consolidada de **princípios/requisitos candidatos de Responsabilização que emergem das fontes**, sem compará-los ainda com o FIAR-Saúde.

**Saída esperada:**

- requisitos/princípios candidatos;
- fontes correspondentes;
- recorrência entre fontes;
- sem comparação com os requisitos existentes.

---

## 2. Consolidação em núcleos conceituais

**Objetivo:** reduzir redundâncias e separar conceitos próprios de Responsabilização de mecanismos pertencentes a outras dimensões.

**Prompt:**

> Com base exclusivamente nos requisitos/princípios candidatos de Responsabilização já extraídos das fontes, faça agora uma etapa de **consolidação conceitual**, sem conhecer ou utilizar os requisitos atuais do FIAR-Saúde.
>
> O objetivo não é manter os candidatos como requisitos separados.
>
> 1. Identifique quais candidatos tratam essencialmente do mesmo núcleo conceitual e podem ser agrupados.
> 2. Diferencie:
>    - atribuição de responsabilidade;
>    - responsabilidade por decisões e ações;
>    - distribuição/compartilhamento de responsabilidade;
>    - prestação de contas;
>    - consequências ou impactos;
>    - responsabilidade humana/institucional;
>    - contestabilidade/reparação.
> 3. Separe conceitos que, embora relacionados a accountability, são principalmente mecanismos ou temas de outras áreas, como:
>    - supervisão humana;
>    - logging/rastreabilidade;
>    - auditoria;
>    - avaliação de impacto;
>    - documentação técnica;
>    - monitoramento;
>    - participação/co-design.
> 4. Não formule ainda requisitos finais.
> 5. Produza apenas um conjunto mínimo de **núcleos conceituais de Responsabilização** sustentados pelas fontes, indicando quais candidatos originais alimentam cada núcleo e quais fontes principais o sustentam.
>
> Não use nem compare com os requisitos FIAR-Saúde nesta etapa.

**Saída esperada:**

- núcleos conceituais consolidados;
- candidatos associados a cada núcleo;
- fontes principais;
- conceitos separados por pertencerem primariamente a outras dimensões;
- sem comparação com os requisitos existentes.
