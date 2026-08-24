# Ciclo de Avaliação Técnica do FIAR-Saúde

O FIAR-Saúde operacionaliza a Inteligência Artificial Responsável por meio de um ciclo estruturado de produção, organização, verificação e avaliação de evidências ao longo do ciclo de vida das tarefas de IA.

O processo distingue três responsabilidades institucionais:

* **Equipe do projeto:** fornece informações sobre a iniciativa e produz, mantém e atualiza as evidências técnicas sob sua responsabilidade;
* **NIAR-Saúde:** delimita a avaliação, orienta a produção de evidências, verifica sua suficiência, consistência e rastreabilidade e conduz a avaliação técnica;
* **Instância de governança:** delibera quando a avaliação exige decisão institucional, como aceite de risco, definição de condicionantes ou restrições de uso.

A avaliação de conformidade não recai sobre o projeto ou sobre o modelo isoladamente. Sua unidade é a combinação entre:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

A maturidade, por sua vez, é uma propriedade longitudinal do projeto e é inferida a partir da recorrência, continuidade e rastreabilidade das práticas de IA Responsável observadas ao longo de sucessivos ciclos de avaliação.

---

## 1. Entrada do projeto

O ciclo inicia-se com o fornecimento, pela equipe do projeto, de informações básicas necessárias para compreender a iniciativa.

O Formulário de Entrada registra, entre outros elementos:

* identificação do projeto;
* descrição da solução;
* problema ou objetivo que orienta seu desenvolvimento;
* uso atual e uso pretendido;
* estágio de desenvolvimento ou operação;
* dados e modelos envolvidos;
* pessoas ou grupos potencialmente afetados;
* responsáveis e pontos de contato conhecidos;
* documentos e aprovações já existentes;
* limitações ou riscos já identificados.

O objetivo dessa etapa é fornecer ao NIAR-Saúde informações suficientes para iniciar a delimitação da avaliação, sem exigir que a equipe produza antecipadamente novas análises técnicas.

---

## 2. Triagem e identificação da avaliação

O NIAR-Saúde analisa as informações iniciais para determinar o objeto da avaliação.

São definidos:

* o projeto ao qual a avaliação pertence;
* a Tarefa de IA;
* a Versão Avaliável;
* o Contexto de Uso;
* a Trilha de Execução;
* o escopo da avaliação;
* os artefatos e evidências inicialmente necessários.

Uma **Tarefa de IA** é definida pela combinação de modelo, dados, procedimentos e objetivo clínico ou operacional situada em determinado contexto de uso.

A **Versão Avaliável** corresponde a uma configuração da tarefa que introduz mudança relevante no modelo, nos dados, nos procedimentos ou no contexto de uso e que, por isso, requer nova avaliação integral ou parcial.

A tarefa é classificada em uma das seguintes trilhas:

* **Trilha Experimental:** pesquisa, experimentação, desenvolvimento ou validação metodológica sem integração ativa a um sistema em operação;
* **Trilha Produção:** tarefa integrada a um sistema em operação ativa.

Quando as informações disponíveis forem insuficientes ou contraditórias, o NIAR-Saúde poderá solicitar esclarecimentos adicionais ou realizar entrevista com a equipe do projeto.

---

## 3. Solicitação e produção de evidências

Com o objeto da avaliação delimitado, o NIAR-Saúde identifica as evidências necessárias para aquele ciclo.

Os projetos permanecem responsáveis pela produção e manutenção dos artefatos técnicos sob sua responsabilidade.

Entre os artefatos de desenvolvimento podem estar:

* Data Card;
* Model Card;
* Fairness Report;
* Explainability Report;
* Registro de Decisão Técnica;
* documentação de privacidade;
* aprovação ética, quando aplicável;
* outros registros técnicos ou institucionais necessários ao contexto da tarefa.

Tarefas na Trilha Produção podem demandar também artefatos operacionais, como:

* relatórios de monitoramento;
* registros de incidentes;
* histórico de versões;
* logs operacionais;
* registros de reimplantação;
* evidências de revisão periódica formal.

O FIAR-Saúde não pressupõe um conjunto universal e rígido de artefatos. As evidências exigidas devem ser proporcionais à tarefa, à trilha, ao contexto de uso e às dimensões de IA Responsável aplicáveis.

---

## 4. Controle e pré-avaliação documental

Os artefatos recebidos são registrados e submetidos a uma pré-avaliação documental.

Essa etapa verifica se a documentação permite iniciar a avaliação técnica e identifica eventuais necessidades de complementação.

A pré-avaliação considera, entre outros aspectos:

* presença das evidências solicitadas;
* suficiência mínima das informações;
* coerência entre tarefa, dados, modelo e contexto de uso;
* consistência entre diferentes artefatos;
* identificação de versões;
* riscos e limitações declarados;
* rastreabilidade documental;
* necessidade de evidências adicionais.

A ausência ou insuficiência de uma informação não deve ser automaticamente interpretada como não conformidade.

A pré-avaliação pode concluir que:

* a avaliação técnica pode prosseguir;
* parte da avaliação pode prosseguir com pendências;
* são necessárias complementações documentais;
* é necessário esclarecer novamente o objeto ou o contexto da avaliação.

---

## 5. Registro e tratamento de pendências

Lacunas ou dúvidas identificadas durante a pré-avaliação são registradas de maneira rastreável.

As pendências podem envolver:

* informação;
* evidência;
* análise;
* inconsistência documental;
* enquadramento metodológico;
* decisão institucional.

Somente as pendências que dependem da equipe do projeto devem ser encaminhadas ao projeto para complementação.

Uma inconsistência deve ser registrada como tal somente quando houver divergência efetiva entre fontes ou evidências. Ausência de informação, dúvida interpretativa ou evidência ainda não fornecida não constituem, isoladamente, inconsistência.

Após a complementação, os registros de evidências e pendências são atualizados.

---

## 6. Avaliação técnica por dimensão

Quando houver evidências suficientes para análise, o NIAR-Saúde conduz a avaliação das dimensões de IA Responsável aplicáveis:

* Governança;
* Segurança;
* Privacidade;
* Responsabilização;
* Rastreabilidade;
* Justiça;
* Transparência.

Para cada dimensão, a avaliação deve explicitar:

* requisito ou questão avaliada;
* evidências utilizadas;
* mecanismo de verificação aplicado;
* análise realizada;
* limitações da evidência;
* pendências remanescentes;
* achados relevantes;
* recomendações;
* eventual necessidade de escalonamento.

A avaliação não se limita à verificação da existência de documentos. As evidências são analisadas quanto à sua **suficiência, consistência, rastreabilidade e adequação ao contexto de uso**.

Diferentes requisitos podem exigir diferentes mecanismos de verificação, incluindo análise documental, consistência cruzada entre artefatos, métricas, testes técnicos, revisão metodológica, esclarecimentos com a equipe ou análise institucional.

---

## 7. Consolidação do resultado de conformidade

Os resultados das avaliações por dimensão são consolidados pelo NIAR-Saúde.

O resultado refere-se exclusivamente à combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

Os estados de conformidade são:

* **Conforme:** as evidências disponíveis sustentam o atendimento dos requisitos aplicáveis ao ciclo avaliado;
* **Pendente:** existem questões, evidências ou ações ainda necessárias para concluir ou sustentar a avaliação;
* **Não Conforme:** existem requisitos aplicáveis não atendidos ou evidências suficientes de inadequação relevante em relação aos critérios estabelecidos.

A conformidade é pontual e não deve ser confundida com a maturidade do projeto.

Uma versão não conforme não implica, por si só, regressão da maturidade do projeto.

---

## 8. Sinais de governança e escalonamento

Achados identificados durante a avaliação podem produzir sinais de governança.

Esses sinais podem indicar, por exemplo:

* necessidade de mitigação;
* necessidade de monitoramento adicional;
* risco residual significativo;
* necessidade de restrição de uso;
* necessidade de revisão técnica;
* necessidade de aceite institucional de risco;
* necessidade de definição de condicionantes.

Quando a questão ultrapassar o escopo da avaliação técnica de rotina, ela deverá ser encaminhada à instância de governança responsável pela deliberação institucional.

O NIAR-Saúde subsidia essa decisão por meio das evidências e análises produzidas, mas não substitui a instância deliberativa.

---

## 9. Encerramento do ciclo

O ciclo é encerrado com o registro de:

* objeto avaliado;
* evidências consideradas;
* avaliações por dimensão;
* resultado de conformidade;
* pendências remanescentes;
* condicionantes, quando houver;
* decisões institucionais associadas;
* próximos gatilhos de reavaliação.

Toda evidência e decisão relevante deve permanecer vinculada à Tarefa, à Versão Avaliável e ao Contexto de Uso correspondentes.

---

## 10. Reavaliação e acompanhamento longitudinal

O FIAR-Saúde acompanha a evolução das tarefas ao longo do tempo.

Mudanças relevantes podem iniciar novo ciclo de avaliação, integral ou parcial. Entre os possíveis gatilhos estão:

* retreinamento do modelo;
* alteração relevante do conjunto de dados;
* mudança de arquitetura;
* alteração das entradas ou saídas;
* expansão do contexto de uso;
* mudança da população afetada;
* incidentes relevantes;
* integração da tarefa em ambiente de produção.

A recorrência das práticas de documentação, avaliação, decisão e monitoramento ao longo de sucessivas versões avaliáveis constitui a base para a inferência longitudinal da maturidade do projeto.

A maturidade não é obtida pela agregação de resultados de checklist nem representa a qualidade de uma versão isolada.

---

## Visão resumida do ciclo

```text
Entrada do projeto
        ↓
Triagem pelo NIAR-Saúde
        ↓
Identificação da Tarefa + Versão Avaliável + Contexto de Uso
        ↓
Definição das evidências necessárias
        ↓
Produção e envio de artefatos pelo projeto
        ↓
Pré-avaliação documental
        ↓
Pendências e complementações, quando necessárias
        ↓
Avaliação técnica por dimensão
        ↓
Resultado de conformidade
        ↓
Sinais de governança
        ↓
Deliberação institucional, quando necessária
        ↓
Encerramento e acompanhamento longitudinal
        ↓
Nova versão avaliável / novo ciclo, quando aplicável
```

O ciclo de avaliação técnica constitui, portanto, o mecanismo pelo qual o FIAR-Saúde transforma dimensões de IA Responsável em evidências verificáveis, avaliações estruturadas, sinais de governança e acompanhamento ao longo do ciclo de vida.
