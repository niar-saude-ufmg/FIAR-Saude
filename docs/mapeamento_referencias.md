# Mapeamento de Referências – FIAR-Saúde

## Escopo e estado da revisão

Este documento registra a fundamentação dos requisitos de Justiça **RC01–RC04**, conforme a reconstrução documentada na planilha [`docs/fontes/derivacao_requisitos_justica.xlsm`](fontes/derivacao_requisitos_justica.xlsm) e as formulações do `guia_requisitos_avaliacao.md` do FIAR-Audit-Template (commit `48fd505`).

O mapeamento anterior, baseado nos códigos do checklist removido, foi substituído. Governança, Segurança, Privacidade, Responsabilização, Rastreabilidade e Transparência permanecem **em revisão metodológica**, sem mapeamento vigente neste documento.

## Método e rastreabilidade

A cadeia de derivação é: **fonte → conceito de Justiça → exigência auditável → requisito candidato → orientação operacional**.

As fontes têm funções distintas:

- **Normativas/recomendatórias substantivas (1a):** sustentam princípios e conteúdo substantivo de Justiça.
- **Governança e técnico-operacionais (1b):** apoiam avaliação, operacionalização e gestão.
- **Literatura de síntese e conceitual:** organiza conceitos, recorrências, pressupostos e limites. Artigos conceituais não são automaticamente revisões de síntese.
- **Literatura técnica, empírica ou aplicada:** exemplifica mecanismos e efeitos ou apoia métodos. Um estudo isolado não cria requisito.

Os IDs NORM, SYN e EMP são os da planilha. O prefixo SYN é um identificador do corpus e não significa que toda fonte dessa série seja uma revisão. Na aba `06_Requisitos_Candidatos`, JUS-RC01 a JUS-RC04 correspondem a RC01 a RC04 no guia.

As relações principais abaixo reproduzem a coluna “Fontes principais” da aba `06_Requisitos_Candidatos`. Apoios complementares e decisões transversais vêm das abas `00_Metodologia`, `04_Extracoes` e `07_Sintese_Corpus_Justica`. Trechos, localizações e status de validação permanecem na aba `04_Extracoes`; este documento não representa nova conferência dos textos originais.

## Mapeamento de Justiça

### RC01 — Grupos e populações

**Requisito:** Identificar, de forma fundamentada, os grupos e populações que podem ser afetados de forma desigual pela Tarefa de IA ou excluídos de seus benefícios.

**Fundamentação:** A literatura normativa e científica converge que os grupos pertinentes não devem ser definidos por lista fixa nem apenas pelos atributos disponíveis nos dados. A identificação depende da Tarefa, do contexto de uso e das formas plausíveis de efeito ou exclusão.

| Papel no mapeamento                      | Fontes principais      |
| ---------------------------------------- | ---------------------- |
| Normativas/recomendatórias substantivas | NORM-01; NORM-03       |
| Consenso técnico-operacional            | NORM-11                |
| Síntese e conceitual                    | SYN-06; SYN-01; SYN-07 |
| Empírica/aplicada                       | EMP-02; EMP-04         |

**Contribuição e limites:** A identificação é contextual e fundamentada, sem lista universal de grupos nem restrição aos atributos disponíveis nos dados. Interseccionalidade integra a orientação de RC01 quando pertinente. STANDING Together, recomendação 2.2a (EXT-051), explicita a identificação contextual de grupos. Mitchell, seção 2.3 (EXT-103–EXT-104), apoia a discussão de grupos e interseções.

### RC02 — Diferenças nos efeitos

**Requisito:** Avaliar se a Tarefa de IA produz, reproduz ou agrava diferenças injustificadas nos efeitos sobre os grupos e populações identificados.

**Fundamentação:** O núcleo mais recorrente do corpus é a preocupação com diferenças injustificadas nos efeitos da IA entre grupos. Os efeitos não se limitam a métricas de desempenho e podem incluir erros, decisões, consequências no cuidado e consequências alocativas produzidas pelas saídas da Tarefa.

| Papel no mapeamento                      | Fontes principais                              |
| ---------------------------------------- | ---------------------------------------------- |
| Normativas/recomendatórias substantivas | NORM-01; NORM-03; NORM-09; NORM-08 (Lei 8.080) |
| Consenso técnico-operacional            | NORM-11                                        |
| Síntese e conceitual                    | SYN-02; SYN-04; SYN-05; SYN-10; SYN-11; SYN-01 |
| Empírica/aplicada                       | EMP-01; EMP-02; EMP-04                         |

**Contribuição e limites:** Os efeitos abrangem desempenho, erros, decisões e consequências observáveis, inclusive alocação de cuidado ou recursos quando influenciada pelas saídas da Tarefa. Diferença numérica não equivale automaticamente a injustiça. STANDING Together, recomendação 2.2d (EXT-054), apoia comparações de desempenho. Paulus & Kent (EXT-147–EXT-149) e Wu et al. (EXT-150–EXT-152) informam a análise de consequências alocativas em RC02, embora tenham entrado no corpus pela investigação da fronteira com RC04.

### RC03 — Dados, variáveis-alvo e padrões de referência

**Requisito:** Avaliar se os dados, as variáveis-alvo e os padrões de referência utilizados no desenvolvimento e na avaliação da Tarefa de IA são adequados para os grupos e populações identificados.

**Fundamentação:** Problemas de Justiça podem decorrer não apenas da composição do dataset, mas também do que é medido, do desfecho usado como alvo, do padrão de referência e de proxies que carregam desigualdades históricas. O corpus sustenta uma noção contextual de adequação, vinculada aos grupos e à finalidade da Tarefa.

| Papel no mapeamento                      | Fontes principais      |
| ---------------------------------------- | ---------------------- |
| Normativas/recomendatórias substantivas | NORM-01; NORM-06       |
| Governança e técnico-operacionais      | NORM-02; NORM-11       |
| Síntese e conceitual                    | SYN-06; SYN-07; SYN-08 |
| Empírica                                | EMP-01                 |

**Contribuição e limites:** A adequação é relativa aos grupos e à finalidade da Tarefa. Abràmoff et al. (EXT-142–EXT-144) relacionam padrões de referência, proxies e desigualdades preexistentes. STANDING Together, recomendações 2.2b, 2.2c e 2.3a (EXT-052–EXT-053; EXT-055), apoia composição dos dados, uso de atributos e limitações com efeitos diferenciados. Problemas gerais de qualidade ou validade pertencem principalmente à Segurança; em Justiça, requerem relação plausível com efeitos diferenciados entre grupos. Como apoio técnico complementar, IMDRF (NORM-07) e AAPM TG 273 (SYN-09; EXT-145–EXT-146) informam a avaliação e os padrões de referência, sem criar exigência autônoma de Justiça.

### RC04 — Acesso e possibilidade de benefício

**Requisito:** Avaliar se a forma de disponibilização da Tarefa de IA produz, reproduz ou agrava desigualdades injustificadas entre os grupos e populações identificados quanto à possibilidade de se beneficiar de seu uso.

**Fundamentação:** A Justiça da Tarefa não depende apenas dos efeitos de suas saídas. A forma como a tecnologia é disponibilizada pode fazer com que certos grupos tenham menor possibilidade de acesso ou benefício, por razões territoriais, infraestruturais, econômicas, digitais ou institucionais.

| Papel no mapeamento                      | Fontes principais                                     |
| ---------------------------------------- | ----------------------------------------------------- |
| Normativas/recomendatórias substantivas | NORM-01; NORM-03; NORM-08 (CF, art. 196, e Lei 8.080) |
| Síntese                                 | SYN-07                                                |

**Contribuição e limites:** O foco é a disponibilização, o acesso e a possibilidade de benefício. A WHO 2021, seção 5.5 (EXT-001), e os fundamentos brasileiros registrados em EXT-038–EXT-040 informam esse núcleo. Consequências alocativas produzidas pelas saídas pertencem a RC02. Na síntese do corpus, a evidência empírica para RC04 é caracterizada como indireta; a fonte Celi oferece contexto geográfico e estrutural. Não se exige igualdade estrita de acesso em qualquer situação: as diferenças precisam ser interpretadas no contexto.

## Apoios e decisões transversais

| Tema                                                                                     | Fontes registradas na planilha                                            | Decisão metodológica                                                                                                                      |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Critérios e métricas contextuais                                                       | NORM-05; NORM-10; SYN-01; SYN-04; SYN-05; SYN-06; EMP-03                  | Não há métrica universal. Justificar critérios em relação à Tarefa, grupos, contexto e efeitos.                                      |
| Tratamento dos achados                                                                   | NORM-01; NORM-03; NORM-06; literatura sociotécnica                       | Regra transversal de RC02–RC04. A identificação de problema requer decisão justificada sobre tratamento; não gera requisito autônomo. |
| Desigualdades estruturais                                                                | NORM-01; NORM-03; NORM-10; SYN-04; SYN-05; SYN-06; SYN-07; EMP-01; EMP-04 | Perspectiva transversal a RC01–RC04.                                                                                                       |
| Participação das pessoas afetadas                                                      | NORM-01; NORM-03; NORM-08; SYN-04; SYN-06                                 | Destino principal: Governança. Pode informar a identificação de grupos em RC01 e o julgamento de diferenças em RC02.                    |
| Justiça individual                                                                      | SYN-03; SYN-01                                                            | Conceito analisado e não incorporado como requisito autônomo nesta versão; depende de definição contextual de similaridade.            |
| Contestação e reparação                                                              | NORM-01; NORM-03                                                          | Destino principal: Responsabilização.                                                                                                     |
| Assimetrias de poder e distribuição de benefícios entre fornecedores e instituições | NORM-01; síntese conceitual do corpus                                    | Direcionamento operacional para Governança. Não se confundem com o acesso dos grupos e populações coberto por RC04.                     |

Esses registros documentam a derivação e as fronteiras conceituais. A aplicabilidade, as evidências e o julgamento de atendimento seguem o guia e as regras do ciclo. A atualização de referências não altera essas regras.

## Referências do corpus utilizado

As referências abaixo foram recuperadas da planilha. Quando a aba de extrações traz identificação bibliográfica mais completa, ela foi utilizada. Não foram acrescentadas fontes externas nesta atualização.

### Fontes normativas, recomendatórias e técnico-institucionais

- **NORM-01:** World Health Organization. Ethics and governance of artificial intelligence for health: WHO guidance. Geneva: WHO; 2021.
- **NORM-02:** World Health Organization. Regulatory considerations on artificial intelligence for health. Geneva: WHO; 2023. ISBN 978-92-4-007887-1.
- **NORM-03:** UNESCO. Recommendation on the Ethics of Artificial Intelligence. Paris: UNESCO; 2021. Publicada em 2022.
- **NORM-05:** NIST. Artificial Intelligence Risk Management Framework (AI RMF 1.0). NIST AI 100-1. 2023.
- **NORM-06:** European Union. Regulation (EU) 2024/1689 — AI Act. 2024.
- **NORM-07:** International Medical Device Regulators Forum. Good machine learning practice for medical device development: Guiding principles. IMDRF/AIML WG/N88 FINAL:2025. 2025.
- **NORM-08:** Brasil. Constituição da República Federativa do Brasil de 1988, art. 196; Lei nº 8.080, de 19 de setembro de 1990, art. 7º.
- **NORM-09:** Brasil. Lei nº 13.709, de 14 de agosto de 2018. Lei Geral de Proteção de Dados Pessoais.
- **NORM-10:** Schwartz R, Vassilev A, Greene KK, Perine L, Burt A, Hall P. Towards a Standard for Identifying and Managing Bias in Artificial Intelligence. NIST SP 1270. 2022.
- **NORM-11:** Alderman JE et al. Tackling algorithmic bias and promoting transparency in health datasets: the STANDING Together consensus recommendations. Lancet Digital Health. 2025;7(1):e64–e88.

### Literatura de síntese, conceitual e técnico-metodológica

- **SYN-01:** Liu M, Ning Y, Teixayavong S, et al. A scoping review and evidence gap analysis of clinical AI fairness. npj Digital Medicine. 2025;8:360.
- **SYN-02:** Chen RJ et al. Algorithmic fairness in artificial intelligence for medicine and healthcare. Nature Biomedical Engineering. 2023.
- **SYN-03:** Anderson JW, Visweswaran S. Algorithmic individual fairness and healthcare: a scoping review. JAMIA Open. 2025;8(1):ooae149.
- **SYN-04:** Rajkomar A, Hardt M, Howell MD, Corrado G, Chin MH. Ensuring Fairness in Machine Learning to Advance Health Equity. Ann Intern Med. 2018;169(12):866–872.
- **SYN-05:** Selbst AD, Boyd D, Friedler SA, Venkatasubramanian S, Vertesi J. Fairness and Abstraction in Sociotechnical Systems. FAT* 2019;59–68.
- **SYN-06:** Mitchell S, Potash E, Barocas S, D’Amour A, Lum K. Algorithmic Fairness: Choices, Assumptions, and Definitions. Annu Rev Stat Appl. 2021;8:141–163.
- **SYN-07:** Celi LA, Cellini J, Charpignon M-L, Dee EC, Dernoncourt F, Eber R, et al. Sources of bias in artificial intelligence that perpetuate healthcare disparities—A global review. PLOS Digit Health. 2022;1(3):e0000022.
- **SYN-08:** Abràmoff MD, Tarver ME, Loyo-Berrios N, et al. Considerations for addressing bias in artificial intelligence for health equity. npj Digit Med. 2023;6:170.
- **SYN-09:** Hadjiiski L, Cha K, Chan H-P, et al. AAPM task group report 273: Recommendations on best practices for AI and machine learning for computer-aided diagnosis in medical imaging. Med Phys. 2023;50:e1–e24.
- **SYN-10:** Paulus JK, Kent DM. Predictably unequal: understanding and addressing concerns that algorithmic clinical prediction may increase health disparities. npj Digit Med. 2020;3:99.
- **SYN-11:** Wu H, Lu X, Wang H. The Application of Artificial Intelligence in Health Care Resource Allocation Before and During the COVID-19 Pandemic: Scoping Review. JMIR AI. 2023;2:e38397.

### Literatura empírica e aplicada

- **EMP-01:** Obermeyer Z, Powers B, Vogeli C, Mullainathan S. Dissecting racial bias in an algorithm used to manage the health of populations. Science. 2019;366(6464):447–453.
- **EMP-02:** Seyyed-Kalantari L, Zhang H, McDermott MBA, Chen IY, Ghassemi M. Underdiagnosis bias of artificial intelligence algorithms applied to chest radiographs in under-served patient populations. Nat Med. 2021;27:2176–2182.
- **EMP-03:** Pfohl SR, Foryciarz A, Shah NH. An empirical characterization of fair machine learning for clinical risk prediction. J Biomed Inform. 2021;113:103621.
- **EMP-04:** Vyas DA, Eisenstein LG, Jones DS. Hidden in Plain Sight — Reconsidering the Use of Race Correction in Clinical Algorithms. N Engl J Med. 2020;383:874–882.

### Fontes fora do núcleo

- **NORM-04 — OECD AI Principles:** excluída após validação por contribuição considerada redundante; possível uso futuro como convergência.
- **AUX-N01 — ISO/IEC TR 24027:2021:** inclusão condicionada a acesso ao texto integral e contribuição adicional.
- **AUX-N02 — ISO/IEC 42001:** complementar, fora do corpus nuclear.
- **AUX-S01 — Vokinger et al., Mitigating bias in machine learning for medicine (2021):** complementar para operacionalização.

O AI Act é utilizado como referência normativa internacional, sem pressupor obrigação legal brasileira. Os fundamentos brasileiros em saúde não geram, isoladamente, requisitos técnicos de IA.

## Limites e pendências da documentação de origem

- A aba de extrações ainda contém registros com transcrição literal ou localização a completar, incluindo EXT-051–EXT-055. A inclusão da fonte neste mapeamento não encerra essas pendências.
- A planilha contém diferença de redação em RC04 e o erro de concordância “os variáveis-alvo” em RC03. Aqui são reproduzidas as formulações do guia de requisitos, sem alteração substantiva dos requisitos.
- Referências jurídicas e versões bibliográficas foram transpostas do corpus, sem nova validação de vigência ou conferência externa.

## Atualização

Quando outra dimensão for consolidada, acrescentar seu mapeamento a partir da respectiva derivação documentada. Não reutilizar correspondências dos códigos antigos sem verificar o conteúdo do requisito e sua sustentação nas fontes.
