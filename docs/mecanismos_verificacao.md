
# Mecanismos de Verificação do FIAR-Saúde

## 1. Objetivo

Os mecanismos de verificação definem **como o NIAR-Saúde examina as evidências utilizadas na avaliação técnica do FIAR-Saúde**.

Eles operacionalizam a passagem entre os requisitos das dimensões de IA Responsável e os resultados da avaliação, permitindo que conclusões sejam fundamentadas em evidências identificáveis, verificáveis e contextualizadas.

Os mecanismos de verificação não constituem uma lista universal de testes aplicável indistintamente a todos os projetos. Sua seleção depende da **Tarefa de IA**, da **Versão Avaliável**, do **Contexto de Uso**, da **Trilha de Execução**, do requisito avaliado e da natureza das evidências disponíveis.

---

## 2. Posição dos mecanismos na lógica do FIAR-Saúde

A avaliação técnica segue a seguinte cadeia:

* **Dimensões:** definem **o que avaliamos**.
* **Requisitos ou questões de avaliação:** definem **o que queremos verificar**.
* **Evidências:** constituem **a base utilizada para fundamentar a análise**.
* **Mecanismos de verificação:** definem **como as evidências são examinadas**.
* **Suficiência, consistência, rastreabilidade e contextualização:** constituem **propriedades transversais consideradas na análise das evidências**.
* **Achados e pendências:** registram **os resultados da análise e as questões ainda não resolvidas**.
* **Conformidade:** constitui o resultado pontual da avaliação de uma **Tarefa de IA + Versão Avaliável + Contexto de Uso**.
* **Maturidade:** constitui uma inferência longitudinal no nível do **projeto**, baseada na recorrência, continuidade e rastreabilidade das práticas de IA Responsável ao longo de sucessivos ciclos de avaliação.

Os mecanismos de verificação, portanto, ocupam a camada operacional entre a existência da evidência e a conclusão da avaliação.

---

## 3. Princípios dos mecanismos de verificação

### 3.1 Proporcionalidade

Nem toda tarefa exige os mesmos mecanismos de verificação.

A seleção deve considerar, entre outros elementos:

* finalidade da tarefa;
* estágio de desenvolvimento ou operação;
* Trilha de Execução;
* contexto de uso;
* pessoas, grupos ou instituições potencialmente afetados;
* natureza dos dados;
* riscos e limitações conhecidos;
* evidências disponíveis.

A inexistência de determinado teste ou artefato não constitui automaticamente uma não conformidade. Deve-se primeiro determinar se aquela evidência é aplicável ao requisito e ao contexto avaliado.

### 3.2 Fundamentação em evidências

Toda conclusão deve poder ser relacionada às evidências utilizadas.

O avaliador deve distinguir claramente:

* informações declaradas pelo projeto;
* evidências documentais ou técnicas apresentadas;
* resultados de verificações realizadas;
* análise do NIAR-Saúde;
* pendências;
* decisões institucionais.

Inferências sem suporte documental ou técnico devem ser explicitamente identificadas como limitações ou questões pendentes.

### 3.3 Independência da avaliação

Os mecanismos são aplicados pelo NIAR-Saúde de forma independente da equipe responsável pelo desenvolvimento.

Isso não impede interação com o projeto para:

* esclarecimentos;
* complementação de informações;
* correção de documentação;
* explicação de decisões técnicas;
* fornecimento de evidências adicionais.

A equipe do projeto fornece e explica as evidências, mas não determina o resultado da avaliação.

### 3.4 Análise contextual

A evidência não deve ser interpretada isoladamente.

Um resultado técnico pode assumir significados diferentes dependendo do contexto de uso, da população afetada, das limitações conhecidas, dos riscos envolvidos e das condições operacionais da tarefa.

Por isso, a aplicação de um mecanismo de verificação deve considerar tanto o resultado observado quanto sua relevância para o contexto específico da avaliação.

### 3.5 Rastreabilidade

Toda verificação relevante deve registrar, quando aplicável:

* requisito avaliado;
* evidência utilizada;
* identificação ou versão do artefato;
* mecanismo aplicado;
* resultado obtido;
* interpretação do resultado;
* limitações;
* pendências;
* relação com outros artefatos ou decisões.

Essa estrutura permite reconstruir posteriormente como uma conclusão foi produzida.

---

## 4. Tipos de mecanismos de verificação

Os mecanismos utilizados pelo FIAR-Saúde podem assumir diferentes formas.

### 4.1 Verificação documental

Examina a existência, completude e adequação de informações registradas em documentos e artefatos.

Exemplos:

* existência de finalidade e contexto de uso no Model Card;
* documentação da origem dos dados no Data Card;
* registro de limitações conhecidas;
* existência de responsáveis ou procedimentos definidos.

A existência de um campo preenchido não implica, por si só, evidência suficiente.

### 4.2 Consistência cruzada entre artefatos

Compara informações relacionadas presentes em diferentes evidências.

Exemplos:

* datasets mencionados no Model Card correspondem aos Data Cards disponíveis;
* população descrita nos dados corresponde à população considerada na avaliação de Justiça;
* limitações identificadas em um artefato aparecem refletidas nas análises e decisões subsequentes;
* uso pretendido é consistente entre os documentos do ciclo.

Divergências confirmadas devem ser registradas como inconsistências. Ausência de informação em apenas um dos documentos não deve ser automaticamente classificada como inconsistência.

### 4.3 Verificação de rastreabilidade e versionamento

Avalia se é possível reconstruir a relação entre evidências, versões e decisões.

Pode verificar:

* versões de datasets;
* versões de modelos;
* versões dos artefatos;
* histórico de mudanças;
* relação entre resultado experimental e configuração avaliada;
* registros de decisões técnicas;
* relação entre achados, mitigação e decisão.

### 4.4 Revisão metodológica

Examina se o procedimento utilizado para produzir determinada evidência é adequado à questão avaliada.

Exemplos:

* estratégia de divisão treino/teste;
* definição dos subgrupos utilizados em uma análise de Justiça;
* escolha de métricas;
* protocolo de validação;
* método de explicabilidade empregado.

O NIAR-Saúde pode avaliar a adequação metodológica a partir das evidências disponibilizadas sem necessariamente reproduzir integralmente os experimentos.

### 4.5 Revisão de métricas e resultados técnicos

Analisa resultados quantitativos produzidos pelo projeto ou por ferramentas de avaliação.

Pode envolver:

* desempenho global;
* desempenho estratificado;
* métricas de disparidade;
* indicadores de robustez;
* medidas de drift;
* resultados de explicabilidade;
* métricas de segurança ou privacidade, quando aplicáveis.

Uma métrica isolada não determina automaticamente conformidade. Seu significado depende do requisito e do contexto de uso.

### 4.6 Testes técnicos

Quando necessários e viáveis, mecanismos de verificação podem envolver execução ou reexecução de testes técnicos.

Esses testes devem ter:

* objetivo claramente definido;
* relação explícita com um requisito de avaliação;
* método documentado;
* entradas e versões identificadas;
* resultado registrado;
* critérios de interpretação definidos.

O FIAR-Saúde não pressupõe que toda avaliação exija acesso direto ao código, dados sensíveis, pesos ou ambiente operacional.

### 4.7 Análise de evidências operacionais

Para tarefas em produção, podem ser examinadas evidências como:

* relatórios de monitoramento;
* registros de incidentes;
* logs;
* indicadores de drift;
* histórico de reimplantação;
* registros de resposta a falhas;
* revisões periódicas.

Esses mecanismos são especialmente relevantes para a avaliação longitudinal e para tarefas na Trilha Produção.

### 4.8 Esclarecimentos e entrevistas

Entrevistas e solicitações de esclarecimento são mecanismos complementares de obtenção ou interpretação de informações.

Podem ser utilizadas quando:

* a documentação é ambígua;
* existem informações aparentemente contraditórias;
* decisões relevantes não estão suficientemente explicadas;
* o contexto de uso não pode ser compreendido apenas pelos documentos.

Informações obtidas por entrevista que sejam relevantes para a avaliação devem ser registradas de maneira rastreável.

A entrevista não substitui evidências técnicas que devam existir formalmente.

### 4.9 Verificação institucional

Alguns requisitos dependem de registros ou decisões institucionais, como:

* aprovação ética;
* definição de responsabilidades;
* condicionantes;
* aceite de risco;
* políticas de uso;
* procedimentos de supervisão;
* decisões do Comitê Gestor.

Nesses casos, o mecanismo de verificação consiste na análise da existência, aplicabilidade, vigência e relação desses registros com a tarefa avaliada.

---

## 5. Propriedades transversais da análise das evidências

Independentemente do mecanismo utilizado, a avaliação deve considerar quatro propriedades transversais.

### 5.1 Suficiência

Pergunta central:

> **As evidências disponíveis são adequadas e suficientemente completas para analisar o requisito?**

A suficiência não significa quantidade máxima de documentação. Significa que há evidência adequada para sustentar uma análise tecnicamente fundamentada.

Possíveis situações incluem:

* evidência suficiente;
* evidência parcial;
* evidência insuficiente;
* evidência não disponível;
* evidência não aplicável ao requisito.

Esses estados descrevem a condição da evidência e não equivalem automaticamente a resultados de conformidade.

### 5.2 Consistência

Pergunta central:

> **As evidências disponíveis são coerentes entre si?**

A análise pode considerar:

* consistência entre Data Card e Model Card;
* consistência entre finalidade declarada e avaliação realizada;
* consistência entre limitações identificadas e decisões posteriores;
* consistência entre versões dos documentos;
* consistência entre resultados técnicos e conclusões registradas.

Uma inconsistência deve ser sustentada por evidências de divergência efetiva.

### 5.3 Rastreabilidade

Pergunta central:

> **É possível identificar a origem da evidência e reconstruir sua relação com a tarefa, a versão e a conclusão produzida?**

A rastreabilidade pode envolver:

* identificação da versão;
* origem dos dados;
* configuração do modelo;
* registro da análise;
* relação entre achado e decisão;
* histórico temporal da evidência.

Esta propriedade transversal não deve ser confundida com a **dimensão de Rastreabilidade**, que avalia as práticas de versionamento, documentação e acompanhamento adotadas pela própria tarefa e pelo projeto.

### 5.4 Contextualização

Pergunta central:

> **A evidência foi interpretada considerando adequadamente o contexto em que a tarefa será utilizada?**

A contextualização pode considerar:

* finalidade;
* contexto clínico ou operacional;
* população afetada;
* estágio experimental ou produtivo;
* riscos conhecidos;
* limitações;
* consequências de erros;
* supervisão humana;
* condições institucionais de uso.

O mesmo resultado técnico pode ser aceitável, insuficiente ou relevante de maneiras diferentes em contextos distintos.

---

## 6. Estados da evidência, achados e conformidade

É necessário distinguir três níveis diferentes de resultado.

### 6.1 Estado da evidência

Descreve a condição da evidência disponível.

Exemplos:

* recebida;
* completa;
* parcial;
* ausente;
* insuficiente;
* inconsistente;
* não aplicável;
* requer esclarecimento.

Esses estados são utilizados para organizar a avaliação e identificar necessidades de complementação.

### 6.2 Achado ou pendência

Um **achado** é uma conclusão sustentada pela análise de uma ou mais evidências.

Uma **pendência** representa uma questão que ainda impede ou limita a conclusão sobre determinado requisito.

Exemplos de pendência incluem:

* informação ausente;
* evidência insuficiente;
* análise adicional necessária;
* inconsistência ainda não esclarecida;
* decisão institucional necessária.

### 6.3 Resultado de conformidade

O resultado de conformidade é produzido somente após a análise dos requisitos aplicáveis à avaliação.

Ele se refere à combinação:

**Tarefa de IA + Versão Avaliável + Contexto de Uso.**

Os estados de evidência não devem ser convertidos mecanicamente em resultados de conformidade.

Por exemplo:

* um documento ausente pode gerar inicialmente uma pendência;
* uma evidência incompleta pode requerer complementação;
* uma inconsistência pode ser esclarecida ou confirmada;
* uma limitação técnica conhecida pode ser compatível com uso condicionado, dependendo do contexto e da decisão institucional aplicável.

A conformidade resulta da análise fundamentada do conjunto de requisitos e evidências, e não da simples contagem de itens presentes ou ausentes.
