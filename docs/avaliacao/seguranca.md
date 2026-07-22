
# Avaliação de Segurança

A dimensão de segurança no framework FIAR examina a proteção do sistema de inteligência artificial contra ameaças, ataques e acessos não autorizados, garantindo a integridade, a confidencialidade e a disponibilidade do sistema ao longo de seu ciclo de vida.

Em contextos de saúde pública, falhas de segurança podem comprometer dados sensíveis de pacientes, a integridade de modelos em produção e a confiabilidade das decisões apoiadas pelo sistema.

Essa dimensão está alinhada a diretrizes internacionais de IA Responsável e gestão de risco, incluindo princípios da OECD, recomendações da OMS para IA em saúde e normas como ISO/IEC 23894 e o NIST AI Risk Management Framework.

---

## Objetivo da dimensão

A análise de segurança busca avaliar se o sistema:

* possui mecanismos de controle de acesso a dados e ambientes computacionais
* está protegido contra acessos não autorizados e ameaças externas
* possui processos de resposta a incidentes de segurança
* garante a integridade e a disponibilidade dos componentes técnicos

---

## Controle de acesso

A avaliação considera os mecanismos que regulam quem pode acessar dados, modelos e ambientes de processamento, incluindo:

* autenticação e autorização de usuários
* segmentação de acessos por perfil (pesquisador, auditor, gestor)
* uso de ambientes isolados para processamento de dados sensíveis (ex.: sala segura)
* registros de acesso e uso

---

## Proteção da infraestrutura

A avaliação considera medidas técnicas de proteção da infraestrutura que sustenta o sistema, como:

* hardening de servidores e ambientes de execução
* isolamento de redes
* armazenamento e sistemas imutáveis, quando aplicável
* mecanismos de defesa contra acessos e usos não autorizados

---

## Resposta a incidentes

A avaliação considera a existência de processos formais para lidar com falhas e incidentes de segurança, incluindo:

* registro estruturado de incidentes
* planos de contingência e resposta
* ações corretivas documentadas
* comunicação institucional em caso de incidente relevante

---

## Riscos associados

A ausência de mecanismos adequados de segurança pode gerar riscos como:

* exposição indevida de dados sensíveis
* acesso não autorizado a modelos ou ambientes de produção
* comprometimento da integridade dos resultados do sistema
* indisponibilidade do sistema em momentos críticos

---

## Evidências esperadas

O auditor pode considerar evidências como:

* documentação de controle de acesso e autenticação
* registros de incidentes de segurança e ações corretivas
* descrição da arquitetura de isolamento de dados e ambientes
* políticas institucionais de segurança da informação
* registros de monitoramento de acessos

A ausência de evidências não implica necessariamente falha, mas indica menor maturidade na dimensão.

---

## Critérios de avaliação

A avaliação de segurança considera:

* existência e adequação de mecanismos de controle de acesso
* nível de isolamento e proteção da infraestrutura
* existência de processos formais de resposta a incidentes
* histórico de incidentes e tratamento dado a eles
* consistência entre políticas declaradas e práticas observadas

---

## Exemplos de análise

Exemplos de situações avaliadas incluem:

* verificação dos mecanismos de autenticação e autorização utilizados
* análise de registros de incidentes de segurança, quando existentes
* avaliação do isolamento do ambiente de processamento de dados sensíveis
* verificação da existência de planos de contingência

---

## Resultado da avaliação

O auditor avalia a dimensão de segurança considerando:

* adequação dos mecanismos de controle de acesso e proteção de infraestrutura
* existência e maturidade dos processos de resposta a incidentes
* histórico de incidentes e efetividade das ações corretivas
* disponibilidade de evidências técnicas e institucionais

O resultado é expresso em nível de maturidade (N1–N4), acompanhado de justificativas e recomendações para melhoria, sendo registrado no relatório final de auditoria.

---

## Relação com o processo de auditoria

Para o processo completo de auditoria, consulte:
→ [Ciclo de Auditoria](../ciclo_auditoria.md)
