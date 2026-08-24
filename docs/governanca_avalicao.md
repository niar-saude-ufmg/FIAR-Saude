# Governança da Avaliação no FIAR-Saúde

O FIAR-Saúde estabelece uma separação estruturada entre a  **produção de evidências** , a **avaliação técnica** e a  **deliberação institucional**.

Essa separação busca preservar a **independência** da avaliação sem eliminar a interação necessária entre o NIAR-Saúde e as equipes dos projetos para esclarecimento, complementação e atualização das evidências.

---

## Papel do projeto

A equipe responsável pelo sistema de IA é responsável pela desenvolvimento dos modelos e pela **produção, manutenção e atualização** das evidências técnicas sob sua responsabilidade.

Suas responsabilidades incluem:

* documentar a tarefa de IA e seu contexto de uso;
* produzir e manter os artefatos técnicos aplicáveis;
* registrar decisões relevantes ao longo do desenvolvimento;
* fornecer evidências sobre dados, modelos, procedimentos e avaliações realizadas;
* responder a solicitações de esclarecimento ou complementação;
* atualizar os artefatos quando houver mudanças relevantes.

A equipe do projeto **não atribui a conformidade da própria tarefa no âmbito do FIAR-Saúde**. As evidências produzidas pelo projeto constituem entradas para a avaliação conduzida pelo NIAR-Saúde.

---

## Papel do NIAR-Saúde

O **NIAR-Saúde** constitui a instância técnico-operacional responsável por operacionalizar o FIAR-Saúde.

Entre suas responsabilidades estão:

* orientar e padronizar a produção de evidências;
* delimitar o objeto da avaliação;
* identificar a  **Tarefa de IA** , a  **Versão Avaliável** , o **Contexto de Uso** e a  **Trilha** ;
* verificar a suficiência, consistência e rastreabilidade das evidências apresentadas;
* solicitar esclarecimentos ou complementações quando necessário;
* conduzir a avaliação técnica das dimensões de IA Responsável;
* documentar os fundamentos das avaliações realizadas;
* registrar pendências, achados e sinais de governança;
* consolidar o resultado de conformidade;
* acompanhar longitudinalmente o histórico de avaliações das tarefas do projeto;
* inferir a maturidade do projeto segundo os critérios definidos pelo FIAR-Saúde.

O NIAR-Saúde não substitui a equipe técnica do projeto na produção das análises e artefatos sob responsabilidade do projeto e não constitui, por si só, instância de certificação clínica ou regulatória.

---

## Papel do Comitê Gestor

O **Comitê Gestor** constitui a instância de governança responsável pelas deliberações institucionais previstas na arquitetura do NIAR-Saúde.

Sua atuação ocorre especialmente quando a avaliação identifica questões que exigem decisão institucional, incluindo:

* aceite explícito de risco residual;
* definição de condicionantes;
* restrição ou limitação de uso;
* necessidade de adequações institucionais;
* conflitos relevantes entre benefícios, riscos e condições de uso;
* outras situações que ultrapassem a avaliação técnica de rotina.

O Comitê Gestor não substitui a avaliação técnica conduzida pelo NIAR-Saúde. Suas decisões devem ser fundamentadas nas evidências, análises e sinais de governança produzidos durante o processo.

---

## Independência da avaliação

A avaliação técnica deve ser realizada de forma  **independente da equipe responsável pelo desenvolvimento da tarefa avaliada** .

Independência não significa ausência de interação entre avaliador e projeto.

Durante o processo, o NIAR-Saúde pode:

* solicitar informações adicionais;
* esclarecer inconsistências ou ambiguidades;
* solicitar complementação de evidências;
* discutir o contexto técnico e operacional da tarefa;
* solicitar correções documentais.

A equipe do projeto pode explicar ou complementar suas evidências, mas não determina o resultado da avaliação.

A independência refere-se, portanto, à separação entre **quem produz as evidências e desenvolve a solução** e  **quem avalia a suficiência e consistência dessas evidências segundo os critérios do FIAR-Saúde** .

---

## Transparência e fundamentação

Toda avaliação deve ser baseada em evidências identificáveis e em justificativas explicitamente registradas.

A transparência do processo envolve:

* identificação das evidências utilizadas;
* indicação da versão dos artefatos considerados;
* registro dos mecanismos de verificação aplicados;
* explicitação dos fundamentos das conclusões;
* registro das limitações da avaliação;
* preservação das pendências e divergências relevantes;
* possibilidade de revisão posterior do processo.

Uma conclusão não deve ser sustentada por inferências que não possam ser vinculadas às evidências disponíveis.

---

## Rastreabilidade da avaliação

As avaliações realizadas com o FIAR-Saúde devem ser documentadas de forma que seja possível reconstruir:

* qual tarefa foi avaliada;
* qual versão avaliável foi considerada;
* qual era o contexto de uso;
* quais evidências estavam disponíveis;
* quais verificações foram realizadas;
* quais pendências foram identificadas;
* quais resultados foram obtidos;
* quais sinais de governança foram produzidos;
* quais decisões institucionais foram tomadas, quando aplicável.

Essa rastreabilidade permite revisões futuras, comparação entre versões avaliáveis e acompanhamento longitudinal das práticas de IA Responsável.

---

## Relação entre avaliação e maturidade

A avaliação de conformidade e a avaliação de maturidade operam em níveis distintos.

A **conformidade** refere-se a uma combinação específica de:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A **maturidade** pertence ao projeto e é inferida longitudinalmente a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável observadas ao longo de sucessivos ciclos de avaliação.

Por isso:

* uma avaliação isolada não demonstra maturidade longitudinal;
* uma versão não conforme não implica automaticamente regressão da maturidade;
* a maturidade não é calculada pela simples agregação dos resultados das dimensões de uma única avaliação.

---

## Uso do template de avaliação

Para apoiar a operacionalizaçao do processo, o FIAR-Saúde disponibiliza uma estrutura padronizada:

👉 [https://github.com/niar-saude-ufmg/FIAR-Audit-Template](https://github.com/niar-saude-ufmg/FIAR-Audit-Template)

Os repositórios dos projetos organizam:

* documentação de entrada;
* artefatos produzidos pelo projeto;
* registros da avaliação do NIAR-Saúde;
* pendências e complementações;
* eventuais decisões institucionais;
* histórico longitudinal.

O template organiza o processo documental, mas não substitui os critérios metodológicos definidos pelo FIAR-Saúde.

---

## Separação de responsabilidades

| Atividade                                                   |                               Projeto |        NIAR-Saúde | Comitê Gestor |
| ----------------------------------------------------------- | ------------------------------------: | ----------------: | ------------: |
| Fornecimento das informações iniciais                       |                                     ✓ |           orienta |             — |
| Produção dos artefatos técnicos do projeto                  |                                     ✓ | orienta/padroniza |             — |
| Delimitação da avaliação                                    |             contribui com informações |                 ✓ |             — |
| Pré-avaliação documental                                    |                 responde a pendências |                 ✓ |             — |
| Avaliação técnica das dimensões                             |  fornece evidências e esclarecimentos |                 ✓ |             — |
| Resultado de conformidade                                   |                                     — |                 ✓ |             — |
| Inferência longitudinal de maturidade                       |                                     — |                 ✓ |             — |
| Deliberação institucional escalonada                        | fornece informações quando necessário |          subsidia |             ✓ |
| Produção de condicionantes ou aceite institucional de risco |                                     — |          subsidia |             ✓ |
