# Ciclo de Avaliação do FIAR-Saúde

O FIAR-Saúde avalia práticas de IA Responsável a partir de evidências, em ciclos de avaliação. O FIAR-Saúde não é certificação, validação clínica nem autorização de implantação.

Este documento registra as regras gerais. Os campos e as instruções de preenchimento estão no Formulário de Entrada, nos modelos (inclusive os dos relatórios de dimensão) e no guia operacional do repositório FIAR-Audit-Template.

## Papéis

* **Equipe do projeto:** fornece informações sobre a iniciativa, produz e mantém os artefatos sob sua responsabilidade, confere, completa e assina os relatórios de dimensão, responde às lacunas e perguntas do NIAR-Saúde.
* **NIAR-Saúde:** delimita o ciclo, determina a aplicabilidade dos requisitos, verifica os relatórios de dimensão com as demais evidências, aponta lacunas, avalia, faz recomendações e prepara o relatório ao Comitê Gestor. Não edita os artefatos da equipe.
* **Comitê Gestor:** valida os relatórios de avaliação e delibera, no âmbito de sua competência institucional, sobre riscos e questões encaminhadas, inclusive condicionantes e restrições de uso. Pode solicitar esclarecimentos ou revisão ao NIAR-Saúde, sem substituir a avaliação técnica. A aceitação de risco não altera, por si só, os resultados dos requisitos. Lê a síntese da equipe de cada relatório de dimensão, apresentada no relatório do NIAR-Saúde.
* **Agentes:** o agente da sala segura pré-preenche os relatórios de dimensão. Outro agente pode rascunhar a verificação para o NIAR-Saúde. Quem produz e quem verifica são agentes separados. Todo texto de agente é validado pela equipe ou pelo NIAR-Saúde.

## Conceitos

* **Projeto:** iniciativa responsável por uma ou mais Tarefas de IA; guarda o histórico dos ciclos.
* **Tarefa de IA:** modelo, dados e procedimentos orientados a um objetivo específico, que pode ser clínico, assistencial, operacional ou de pesquisa. Mudanças no objetivo, no tipo de resultado ou no escopo essencial podem caracterizar uma nova tarefa, conforme análise justificada do NIAR-Saúde. A delimitação das tarefas cabe ao NIAR-Saúde.  Modelo é um componente cujos parâmetros são ajustados ou aprendidos a partir de dados (por exemplo, aprendizado de máquina ou modelo estatístico, como o pareamento probabilístico de registros). Procedimento só com regras fixas definidas por pessoas não é Tarefa de IA; quando gera dados usados por uma Tarefa de IA, é examinado na avaliação dela (RC03).
* **Versão Avaliável:** estado da tarefa avaliado no ciclo (modelo, dados e procedimentos). A falta de um identificador exato não impede automaticamente a avaliação, mas é preciso haver informação suficiente para relacionar as evidências à tarefa, ao estado avaliado e ao contexto.
* **Contexto de Uso:** condições nas quais a tarefa é desenvolvida, avaliada ou utilizada, incluindo finalidade, usuários, população, ambiente e restrições relevantes. O contexto considerado no ciclo é explicitado. O uso pretendido que não for objeto do ciclo é registrado separadamente.
* **Unidade de avaliação:** Tarefa de IA + Versão Avaliável + Contexto de Uso.
* **Ciclo de avaliação:** uma avaliação de uma unidade, da delimitação ao fechamento.
* **Trilha de Execução:** Experimental (pesquisa, desenvolvimento ou validação, sem operação ativa) ou Produção (em operação ativa). Orienta a aplicabilidade dos requisitos e a natureza das evidências necessárias.
* **Evidência e fonte:** evidência é a informação que responde a um requisito; fonte é onde ela está (artefato ou comunicação registrada).
* **Relatório de dimensão:** artefato da equipe com sua posição formal e assinada sobre os requisitos de uma dimensão. A documentação de cada dimensão define se há relatório obrigatório e qual é o modelo; em Justiça, é o Fairness Report ([justica.md](avaliacao/justica.md)). Tarefa de IA, Versão Avaliável, Contexto de Uso e Trilha são os da delimitação. Cada nova versão lista as lacunas a que responde.
* **Lacuna:** ponto do relatório de dimensão que impede concluir um requisito (ver Lacunas).
* **Maturidade:** propriedade longitudinal do projeto, a ser definida em revisão posterior.

## Etapas do ciclo

### 1. Entrada

O Formulário de Entrada é aberto na entrada do projeto e atualizado quando houver mudanças relevantes, sem exigir novo preenchimento integral a cada ciclo. Reúne informações gerais do projeto e blocos específicos para as Tarefas de IA apresentadas para avaliação.

A equipe descreve as tarefas conforme sua compreensão, com base nas informações disponíveis, sem precisar produzir novas análises. O NIAR-Saúde confirma ou ajusta a delimitação das tarefas e das unidades de avaliação.

Os identificadores usados no formulário relacionam suas informações internas e não definem, por si só, unidades de avaliação.

As respostas da equipe subsidiam a delimitação e a determinação da aplicabilidade dos requisitos, que cabem ao NIAR-Saúde.

### 2. Delimitação

Com base no formulário e nas demais fontes disponíveis, o NIAR-Saúde confirma ou ajusta a delimitação e registra a Tarefa de IA, a Versão Avaliável, o Contexto de Uso avaliado, a Trilha, o escopo e as fontes. O uso pretendido que não for objeto do ciclo é registrado separadamente.

Por padrão, o ciclo considera o contexto atual. Um contexto de uso pretendido pode ser objeto de avaliação antes de sua implementação, desde que isso esteja explicitamente delimitado e justificado. Nesse caso, a análise distingue práticas e condições já existentes daquelas apenas planejadas, sem tratar planos como evidência de execução. A mera indicação de um uso futuro no formulário não o inclui automaticamente no escopo do ciclo.

Avaliar um uso pretendido não altera, por si só, a Trilha de Execução atual da tarefa nem demonstra atendimento a requisitos que dependam de evidências de operação.

A etapa termina com a decisão de que o ciclo está pronto para avaliação. Lacunas na identificação da versão são registradas como limitações, desde que as evidências possam ser relacionadas à tarefa, ao estado avaliado e ao contexto.

Somente fontes localizadas e verificadas quanto à pertinência ao objeto avaliado podem sustentar a avaliação. Fontes de ciclos anteriores podem ser reutilizadas quando permanecerem pertinentes e atuais. Lembranças de conversas ou registros ainda não verificados servem apenas como pistas para localizar evidências.

### 3. Relatório de dimensão

Nas dimensões com relatório obrigatório, o agente da sala segura pré-preenche o relatório com a execução, o Model Card e o Data Card. Sem execução na sala segura, os fatos vêm de publicações ou relatórios técnicos, indicados como fonte. Em cada campo, o agente marca a origem e a versão e aponta as divergências entre as fontes. Os fatos ficam resumidos, com fonte e versão. Campos de julgamento que ele pré-preenche a partir do Model Card vêm marcados "a confirmar". A equipe confere os fatos, confirma ou corrige os campos "a confirmar", completa os julgamentos e assina. O responsável pelo projeto assina a síntese e as decisões. O responsável técnico assina as análises.

### 4. Avaliação por requisito

Para cada requisito das dimensões operacionalizadas, o NIAR-Saúde:

1. determina a aplicabilidade, com justificativa, antes de julgar o atendimento, consultando as informações factuais das fontes;
2. identifica o que precisa ser demonstrado;
3. lê o campo do relatório de dimensão, quando houver, que responde a cada item do checklist e o confere com as evidências nas fontes disponíveis;
4. analisa suficiência, consistência, rastreabilidade e pertinência;
5. atribui o resultado.

O avaliacao.md aponta para os campos do relatório e não reescreve os fatos. Os estados do relatório são da equipe. O resultado do requisito e a situação dos itens são do NIAR-Saúde.

A existência de um template ou tipo de artefato não o torna obrigatório. A necessidade da evidência precede a escolha do artefato. A avaliação responde ao requisito; não verifica apenas a existência de documentos.  A exceção são os relatórios de dimensão definidos como obrigatórios na documentação de cada dimensão. O relatório é a posição formal da equipe e o ponto de partida da verificação, e não substitui a verificação das evidências. As marcações de preenchimento dos modelos (como OBRIGATÓRIO e CONDICIONAL) indicam o que a equipe preenche. Não são resultado nem situação de item.

### 5. Rodadas com a equipe

As lacunas e as pendências destinadas à equipe são enviadas em rodadas, com a versão do relatório de dimensão verificada e o prazo. A equipe responde às lacunas em nova versão do Fairness Report e às pendências pelo canal que preferir. A resposta é registrada como comunicação, analisada pelo NIAR-Saúde e citada como fonte. O NIAR-Saúde reavalia os requisitos afetados.

Não se exige atualizar um artefato apenas para transcrever uma resposta já registrada. A atualização pode ser necessária quando o próprio requisito exigir documentação atualizada ou comunicação a determinado público.

### 6. Fechamento

O NIAR-Saúde registra a unidade avaliada, a cobertura da avaliação, os resultados por requisito e suas justificativas, as fontes utilizadas, as limitações e as pendências e lacunas remanescentes.

O fechamento pode ocorrer com resultados Inconclusivos, desde que seus motivos e as necessidades de acompanhamento estejam explícitos. Encerrar o ciclo não significa encerrar automaticamente as pendências e as lacunas.

As evidências, os resultados e as decisões permanecem vinculados à Tarefa de IA, à Versão Avaliável e ao Contexto de Uso correspondentes. São registrados os encaminhamentos e os gatilhos de reavaliação.

Quando houver gatilho de envio, o NIAR-Saúde prepara o relatório ao Comitê Gestor. A cobertura parcial não autoriza uma conclusão global de atendimento pelo projeto.

## Resultados por requisito

* **Atendido:** a evidência verificada sustenta o atendimento.
* **Não atendido:** a evidência verificada é suficiente para mostrar que o requisito não é cumprido.
* **Inconclusivo:** a evidência disponível não permite concluir se o requisito é ou não atendido. Registra-se o motivo.
* **Não aplicável:** a condição pressuposta pelo requisito não existe na unidade avaliada, com justificativa.

Quando não for possível determinar a aplicabilidade, registra-se Inconclusivo, com o motivo “aplicabilidade não determinada”, e abre-se a pendência necessária para esclarecer a condição objetiva do requisito. Isso não equivale a considerar o requisito aplicável ou não aplicável.

Atendimento parcial ou prática apenas planejada não levam automaticamente a Inconclusivo. Distingue-se insuficiência de evidência (Inconclusivo) de evidência suficiente de não atendimento (Não atendido).

Ausência de artefato não é resultado. Um requisito não é não aplicável apenas porque a evidência está ausente.

Se um relatório de dimensão obrigatório não for entregue no prazo, os requisitos da dimensão ficam Inconclusivos, com o motivo "relatório de dimensão não entregue", salvo evidência suficiente de não atendimento.

## Pendências

* Uma pendência é uma questão que precisa ser resolvida para delimitar a avaliação, determinar a aplicabilidade de um requisito ou concluir sua análise. Está sempre ligada à delimitação ou a um requisito.
* Antes de abrir uma pendência, verifica-se se a questão é necessária, se a informação já está em alguma fonte e se já foi respondida.
* Destinatário: equipe, quando depende dela; NIAR-Saúde, para verificação interna ou decisão metodológica ainda não tomada. Questões internas não são transferidas à equipe. Nas dimensões com relatório, pergunta à equipe sobre o conteúdo de um requisito é lacuna, não pendência. A pendência de requisito fica para verificação interna do NIAR-Saúde e para pedidos que não cabem no relatório, como o acesso a uma fonte. A pendência de delimitação não muda.
* A pendência bloqueia apenas o que depende dela.
* Estados: aberta, respondida, encerrada, cancelada (com motivo). Uma resposta recebida é analisada e não encerra automaticamente a pendência. Só o NIAR-Saúde encerra, citando a fonte.
* Requisito com pendência aberta só fica Inconclusivo quando a pendência impede a conclusão. Se já houver evidência suficiente de não atendimento, esse resultado é registrado.

## Lacunas

* Lacuna é um ponto do relatório de dimensão que impede concluir um requisito: campo vazio, campo que não responde ao item, falta de fonte, julgamento sem fundamento ou sem autor, divergência com outra evidência ou campo que segue marcado "a confirmar" na versão assinada.
* **Quem aponta**: o NIAR-Saúde, ao verificar o relatório. Um agente pode rascunhar, desde que não seja o que preencheu o relatório. O NIAR-Saúde valida.
* **Identificação**: RCxx-Ly, numerada por requisito dentro do ciclo (ex.: RC02-L1). Fora do ciclo, cita-se junto com o ciclo (ex.: C01 RC02-L1).
* **Registro**: na análise do requisito, no avaliacao.md do ciclo. O pedido à equipe é registrado como comunicação e traz as lacunas, a versão do relatório verificada e o prazo.
* **Prazo**: definido pelo NIAR-Saúde no pedido de cada rodada.
* **Resposta**: a equipe responde em nova versão do relatório de dimensão, que lista as lacunas a que responde.
* **Estados**: aberta, respondida, encerrada, cancelada (com motivo). A lacuna fica respondida quando chega a nova versão do relatório. Só o NIAR-Saúde encerra, citando a versão e o campo do relatório.
* Antes de abrir uma lacuna, verifica-se se ela é necessária para concluir o requisito, se a resposta já está no relatório ou em outra fonte e se já foi apontada. Item do checklist não localizado não gera lacuna por si só.
* Lacuna aberta só torna o requisito Inconclusivo quando impede a conclusão. Se já houver evidência suficiente de não atendimento, esse resultado é registrado. Vencido o prazo, o NIAR-Saúde conclui com o que houver. Lacuna aberta no fechamento é registrada entre as lacunas remanescentes.
* Nas dimensões com relatório, pergunta à equipe sobre o conteúdo de um requisito é lacuna. A pendência de requisito fica para verificação interna do NIAR-Saúde e para pedidos que não cabem no relatório, como o acesso a uma fonte. A pendência de delimitação não muda.

## Decisões metodológicas e informações não confirmadas

* Decisões metodológicas já tomadas são registradas no documento que afetam, com justificativa.
* Informações factuais são registradas com suas fontes. Uma informação suficientemente documentada não exige nova confirmação da equipe apenas para repetir o que já consta da fonte.
* Inferências ainda não sustentadas suficientemente são identificadas como hipóteses do NIAR-Saúde, com sua base e limitação. Não substituem fatos demonstrados.
* Responsabilidades técnicas não são estabelecidas por dedução do avaliador. Quando não estiverem documentadas suficientemente, permanecem não confirmadas. Solicita-se esclarecimento somente quando necessário à delimitação ou à análise de um requisito.

## Inconsistências

Inconsistência é uma contradição confirmada dentro de uma fonte ou entre fontes sobre o mesmo fato, versão e contexto. Ausência de informação, dúvida interpretativa ou evidência ainda não fornecida não constituem inconsistência.

A inconsistência é registrada na delimitação ou na análise do requisito afetado. Gera pendência quando exigir esclarecimento necessário à avaliação, com destinatário definido conforme quem pode resolvê-la. Uma inconsistência entre um relatório de dimensão e outra fonte gera lacuna.

Estados: aberta; resolvida (com a fonte que a resolve); cancelada (com motivo, por exemplo quando a revisão mostra que não se tratava do mesmo fato, versão ou contexto). Inconsistência aberta no fechamento é registrada entre as limitações.

## Encaminhamentos

* **Recomendação do NIAR-Saúde:** sugestão à equipe; não é obrigatória e não altera resultados.
* **Questão para o Comitê Gestor:** aceite de risco, restrição de uso, definição de responsabilidades ou conflito que ultrapasse a avaliação técnica.

Condicionantes são definidas apenas pelo Comitê Gestor.

## Relatório ao Comitê Gestor

O relatório é por projeto, em linguagem simples, e descreve a cobertura da avaliação, os resultados, os riscos identificados, as recomendações e a decisão solicitada. Não classifica a aceitabilidade dos riscos. Inclui a síntese da equipe de cada relatório de dimensão, identificada como posição da equipe e separada da análise do NIAR-Saúde.

É enviado quando houver:

1. primeira avaliação concluída;
2. resultado que muda de categoria, ou risco novo ou agravado, mesmo sem mudança de categoria;
3. mudança de contexto para uso real ou entrada na Trilha Produção;
4. questão para o Comitê;
5. revisão periódica, se definida.

Ciclos sem esses efeitos entram no relatório seguinte. Cada emissão do relatório identifica os ciclos e as unidades de avaliação abrangidos. A decisão do Comitê é registrada e vinculada à emissão apreciada.

A aceitação de riscos vale exclusivamente para as tarefas, versões, contextos e condições explicitados na decisão.

## Mudanças relevantes

Mudanças como retreinamento, alteração dos dados, das entradas ou saídas, da arquitetura, da população, do contexto de uso, integração em produção ou incidentes relevantes são analisadas pelo impacto. Uma mudança de uso prevista pode ser avaliada antes de seu início, quando pertinente. Há quatro tratamentos possíveis:

1. apenas registrar a mudança;
2. reavaliar os requisitos afetados;
3. abrir novo ciclo (nova versão ou novo contexto);
4. delimitar nova Tarefa de IA.

A escolha e sua justificativa são registradas. Mudança listada na síntese de um relatório de dimensão como motivo de nova versão exige nova versão desse relatório.

## Visão resumida

```text
Entrada (formulário aberto na entrada e atualizado quando há mudança relevante)
        ↓
Delimitação: Tarefa + Versão + Contexto, Trilha, fontes
        ↓
Relatório de dimensão (em Justiça, Fairness Report): agente da sala segura pré-preenche
        ↓
Avaliação por requisito: NIAR-Saúde verifica o relatório com as evidências; resultados e lacunas
        ↓
Rodadas com a equipe: lacunas respondidas em nova versão do relatório  →  reavaliação
        ↓
Fechamento do ciclo
        ↓
Relatório ao Comitê Gestor, com a síntese da equipe, quando houver gatilho
        ↓
Decisão do Comitê
        ↓
Mudança relevante → registro, reavaliação, novo ciclo, nova tarefa ou nova versão do relatório
```
