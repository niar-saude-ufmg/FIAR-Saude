# Protocolo de Pré-Avaliação Documental

## 1. Objetivo

Este protocolo orienta a verificação inicial dos artefatos e evidências de um projeto antes da avaliação por requisito e por dimensão no FIAR-Saúde.

A pré-avaliação documental tem como objetivos:

- identificar os artefatos efetivamente disponíveis no ciclo atual;
- verificar se a unidade de avaliação está suficientemente delimitada;
- identificar as evidências relevantes contidas nos artefatos;
- realizar verificações cruzadas entre documentos;
- identificar lacunas, ambiguidades e divergências;
- evitar solicitações desnecessárias à equipe do projeto;
- preparar a avaliação técnica posterior.

A pré-avaliação documental não produz, por si só, resultado de conformidade.

Somente fontes verificadas no ciclo atual podem ser tratadas como evidência da avaliação. Informações provenientes de conversas anteriores, memória do sistema ou registros históricos não verificados podem ser utilizadas como pistas para localização de evidências, mas não devem ser tratadas como evidências do ciclo atual.

---

## 2. Confirmar a unidade de avaliação

Antes da análise documental, verificar se estão suficientemente definidos:

- **Tarefa de IA**;
- **Versão Avaliável**;
- **Contexto de Uso**;
- **Trilha de Execução da tarefa:** Experimental | Produção.

Se houver pendência material na delimitação de qualquer desses elementos, ela deve ser registrada antes do início da avaliação requisito a requisito.

A avaliação por requisito não deve ser iniciada enquanto a unidade de avaliação não estiver suficientemente delimitada.

---

## 3. Inventário dos artefatos

Registrar os artefatos efetivamente disponíveis no ciclo atual.

| Artefato | Arquivo / referência | Versão | Data | Estado documental | Observação |
|---|---|---|---|---|---|
| | | | | | |

### Estados documentais

- recebido;
- parcialmente recebido;
- não recebido;
- desatualizado;
- substituído.

O estado documental descreve a disponibilidade administrativa do artefato e não constitui avaliação de sua suficiência.

---

## 4. Identificação das evidências

Para cada artefato disponível, registrar as informações relevantes para a avaliação.

Podem incluir, quando aplicáveis:

- identificação da tarefa;
- finalidade;
- Contexto de Uso;
- Trilha de Execução;
- datasets utilizados;
- versões dos dados;
- modelo e versão;
- população;
- entradas e saídas;
- procedimentos de treinamento ou validação;
- métricas e resultados;
- limitações;
- decisões técnicas;
- papéis ou responsabilidades explicitamente declarados;
- registros éticos, regulatórios ou institucionais;
- informações sobre monitoramento ou operação.

A existência de uma informação em um artefato não implica, por si só, que ela seja evidência suficiente para um requisito.

---

## 5. Verificações cruzadas

Realizar, quando aplicável, verificações entre os diferentes artefatos.

Podem incluir:

- coerência da Tarefa de IA entre documentos;
- coerência da Versão Avaliável;
- coerência do Contexto de Uso;
- coerência da Trilha de Execução;
- correspondência entre datasets citados;
- correspondência entre versões de dados e modelo;
- correspondência entre população descrita e população analisada;
- coerência entre entradas e saídas declaradas;
- correspondência entre métricas e resultados reportados;
- consistência entre limitações documentadas;
- relação entre decisões técnicas e evidências disponíveis;
- consistência entre responsabilidades explicitamente declaradas.

A ausência de determinada informação em apenas um artefato não deve ser automaticamente classificada como inconsistência.

---

## 6. Resultado das verificações

Cada verificação deve ser registrada, quando aplicável, como:

- **Consistente:** as evidências examinadas são compatíveis entre si;
- **Informação ausente:** a informação necessária não foi localizada;
- **Requer esclarecimento:** as evidências disponíveis não permitem conclusão;
- **Divergência confirmada:** existem informações incompatíveis entre evidências identificadas;
- **Não aplicável:** a verificação não se aplica ao ciclo considerado.

Uma divergência somente deve ser registrada como confirmada quando existirem evidências suficientes de incompatibilidade.

---

## 7. Registro de pendências

Questões não resolvidas devem ser registradas de forma rastreável.

| ID | Questão | Evidência relacionada | Tipo | Ação necessária | Responsável | Status |
|---|---|---|---|---|---|---|
| | | | | | | |

### Tipos de pendência

Podem incluir:

- complementação documental;
- esclarecimento;
- confirmação factual;
- verificação pelo NIAR-Saúde;
- análise técnica adicional;
- decisão institucional.

Antes de solicitar nova evidência ao projeto, o NIAR-Saúde deve verificar se a questão pode ser resolvida a partir dos documentos já disponíveis.

---

## 8. Resultado da pré-avaliação

**Unidade de avaliação suficientemente delimitada:** Sim | Não

**Inventário documental concluído:** Sim | Não

**Verificações cruzadas concluídas:** Sim | Não

**Existem divergências confirmadas:** Sim | Não

**Existem pendências materiais:** Sim | Não

**A avaliação por requisito pode ser iniciada:** Sim | Não

### Questões resolvidas

-

### Pendências que permanecem

-

### Evidências adicionais necessárias

-

### Verificações adicionais pelo NIAR-Saúde

-

### Itens a solicitar à equipe do projeto

-

### Justificativa para iniciar ou não a avaliação por requisito

-