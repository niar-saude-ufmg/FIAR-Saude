# Governança da Auditoria no FIAR

O FIAR estabelece uma separação estruturada entre as responsabilidades do projeto que desenvolve o sistema de IA e as responsabilidades do auditor que conduz a avaliação.

Essa distinção é fundamental para garantir **independência, transparência e credibilidade** no processo de auditoria.

---

## Papel do projeto

A equipe responsável pelo sistema de IA é responsável pela **produção e disponibilização de evidências** necessárias à auditoria.

Suas responsabilidades incluem:

* documentar o sistema de IA
* produzir artefatos técnicos relevantes
* registrar decisões ao longo do desenvolvimento
* fornecer evidências sobre o funcionamento do sistema

O projeto não avalia a si próprio. Ele fornece evidências serão analisadas por um auditor independente.

---

## Papel do auditor

O auditor é responsável por conduzir a avaliação independente do sistema, com base nas evidências fornecidas pelo projeto. Essa separação é fundamental para garantir a credibilidade e a imparcialidade da auditoria.

Suas atividades incluem:

* analisar a documentação disponibilizada
* examinar artefatos técnicos
* avaliar o sistema nas dimensões do framework
* justificar as avaliações realizadas

O auditor também é responsável pela elaboração do **relatório da auditoria**.

---

## Hierarquia institucional

O FIAR-Saúde opera sob três instâncias, em níveis distintos:

- **CIIA-Saúde**: instância decisória externa, responsável pelo enquadramento institucional geral dos projetos submetidos.
- **NIAR**: instância técnico-operacional, responsável pela capacitação, auditoria e atribuição de maturidade.
- **Comitê Gestor**: órgão interno ao NIAR, responsável pela deliberação sobre avaliações escalonadas — validação de aceites de risco residual e definição de condicionantes operacionais.

O auditor mencionado nas seções acima atua no âmbito do NIAR. Casos de médio risco, alto risco ou inconsistências estruturais relevantes são escalonados ao Comitê Gestor.

---

## Independência da auditoria

A independência entre projeto e auditor é um princípio central do FIAR.

A avaliação deve ser conduzida sem interferência direta da equipe responsável pelo sistema, garantindo que os resultados reflitam exclusivamente a análise das evidências disponíveis.

Esse princípio contribui para a confiabilidade e legitimidade do processo de auditoria.

---

## Transparência

A auditoria deve ser baseada em evidências documentadas e, sempre que possível, acessíveis para verificação.

A transparência envolve:

* rastreabilidade das evidências utilizadas
* clareza nas justificativas das avaliações
* possibilidade de revisão por terceiros

Esse princípio fortalece a credibilidade e a auditabilidade do processo.

---

## Reprodutibilidade

As auditorias realizadas com o FIAR devem ser documentadas de forma a permitir sua reavaliação  ao longo do tempo.

Isso inclui:

* organização estruturada das evidências
* registro das avaliações realizadas
* documentação das decisões do auditor

A reprodutibilidade permite revisões futuras, comparações entre versões do sistema e acompanhamento de melhorias.

---

## Uso do template de auditoria

Para operacionalizar o processo de auditoria, o FIAR disponibiliza um template estruturado:

👉 [https://github.com/niar-saude-ufmg/FIAR-Audit-Template](https://github.com/niar-saude-ufmg/FIAR-Audit-Template)

Cada auditoria deve ser conduzida em um **repositório próprio criado a partir desse template**, garantindo padronização, organização e rastreabilidade das informações.

---

## Separação de responsabilidades

| Atividade                 | Projeto | Auditor |
| ------------------------- | ------- | ------- |
| Produção de artefatos   | ✔      | ✖      |
| Avaliação de dimensões | ✖      | ✔      |
| Geração de relatório   | ✖      | ✔      |
