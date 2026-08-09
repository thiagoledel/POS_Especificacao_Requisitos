# Atividade 4 - Ambiguidades, Inconsistências e Lacunas de Requisitos

# Sistema de Gestão de Eventos - Eventus

## Objetivo

Identificar todas as dúvidas, ambiguidades, inconsistências, conflitos e lacunas de informação que devem ser esclarecidas junto aos stakeholders antes da especificação definitiva dos requisitos.

---

# 1. Ambiguidades Identificadas

## A01 - Prazo para Cancelamento de Inscrição
**Descrição:** Foi identificado que os participantes desejam cancelar inscrições sem contato com a organização, porém não existe definição sobre até quando o cancelamento será permitido.

**Stakeholders envolvidos:** Participantes, Organizadores.

**Pergunta:** Qual o prazo limite para cancelamento da inscrição?

---

## A02 - Critérios para Reembolso
**Descrição:** A equipe financeira informou que algumas situações permitem reembolso e outras não.

**Stakeholders envolvidos:** Equipe Financeira.

**Pergunta:** Quais critérios determinam a concessão ou não do reembolso?

---

## A03 - Liberação de Certificados
**Descrição:** Os participantes desejam emitir certificados após o evento.

**Stakeholders envolvidos:** Participantes, Organizadores.

**Pergunta:** O certificado será emitido automaticamente ou dependerá da confirmação de presença?

---

## A04 - Envio de Comprovantes e Notificações
**Descrição:** Foi solicitado envio de comprovantes e comunicações aos participantes.

**Pergunta:** Qual será o canal utilizado para envio das notificações?

---

## A05 - Reserva de Vagas Durante Pagamento
**Descrição:** Não está claro em qual momento a vaga será reservada.

**Pergunta:** A vaga será reservada no início do pagamento ou apenas após sua confirmação?

---

## A06 - Funcionamento da Lista de Espera
**Descrição:** Existe a necessidade de criar lista de espera para eventos lotados.

**Pergunta:** Como ocorrerá a convocação dos participantes da lista de espera?

---

## A07 - Visualização de Dados por Palestrantes
**Descrição:** Palestrantes desejam consultar participantes inscritos.

**Pergunta:** Quais informações dos participantes poderão ser visualizadas?

---

# 2. Inconsistências e Potenciais Conflitos

## I01 - Workshops no Mesmo Dia
**Descrição:** Participantes desejam inscrever-se em vários workshops no mesmo dia.

**Conflito:** Organizadores informam que workshops podem ocorrer simultaneamente.

**Risco:** Um participante pode tentar se inscrever em atividades com sobreposição de horário.

---

## I02 - Cancelamento Permitido x Cancelamento Bloqueado
**Descrição:** Participantes desejam autonomia para cancelar inscrições.

**Conflito:** Organizadores informam que alguns eventos não permitem cancelamento.

**Ponto a esclarecer:** Quais tipos de evento permitem ou não permitem cancelamento?

---

## I03 - Certificados x Controle de Presença
**Descrição:** Participantes desejam emitir certificados.

**Conflito:** Não está definido se a emissão dependerá da participação efetiva no evento.

---

## I04 - Inscrição x Confirmação de Pagamento
**Descrição:** Participante espera concluir inscrição imediatamente.

**Conflito:** Equipe financeira exige confirmação de pagamento para determinadas inscrições.

---

# 3. Lacunas Funcionais

## L01 - Gestão da Lista de Espera
Não foram definidas:
- Critério de priorização.
- Ordem de convocação.
- Prazo de resposta do participante convocado.
- Processo de substituição de vagas.

---

## L02 - Controle de Presença
Não foi identificado requisito para:
- Registrar presença.
- Validar participação.
- Utilizar presença para emissão de certificados.

---

## L03 - Notificações
Não foram definidos:
- Canais de comunicação.
- Eventos que geram notificações.
- Templates das mensagens.

---

## L04 - Pagamentos
Não foram definidos:
- Métodos de pagamento.
- Integração com meios de pagamento.
- Tratamento de pagamentos recusados.

---

## L05 - Reembolsos
Não foram definidos:
- Motivos válidos.
- Percentuais de devolução.
- Prazo para solicitação.
- Prazo para processamento.

---

## L06 - Gestão de Conflitos de Agenda
Não existe definição sobre o tratamento de inscrições em atividades com horários sobrepostos.

---

# 4. Lacunas Não Funcionais

## NF01 - Segurança
Não foram definidos requisitos relacionados a:
- Autenticação.
- Autorização.
- Criptografia.
- Auditoria.

---

## NF02 - Privacidade de Dados
Não foram levantadas regras relacionadas à LGPD.

---

## NF03 - Desempenho
Não foram definidos:
- Tempo máximo de resposta.
- Volume de usuários simultâneos.
- Crescimento esperado da plataforma.

---

## NF04 - Disponibilidade
Não foi definido o nível de disponibilidade esperado do sistema.

---

## NF05 - Acessibilidade
Não foram definidos critérios de acessibilidade digital.

---

# 5. Perguntas Recomendadas para Próxima Entrevista

1. Até quando uma inscrição pode ser cancelada?
2. Quais condições permitem reembolso?
3. Como funcionará a lista de espera?
4. Como será controlada a presença?
5. Qual a regra para emissão de certificados?
6. Como tratar inscrições em workshops conflitantes?
7. Quais dados dos participantes podem ser vistos pelos palestrantes?
8. Em qual momento a vaga é efetivamente reservada?
9. Quais canais serão utilizados para notificações?
10. Quais requisitos mínimos de segurança devem ser atendidos?
11. Existe necessidade de conformidade com LGPD?
12. Qual volume de usuários simultâneos deve ser suportado?

---

# Resultado da Análise

## Ambiguidades Identificadas
7

## Inconsistências Identificadas
4

## Lacunas Funcionais
6

## Lacunas Não Funcionais
5

A resolução destes pontos é fundamental para reduzir riscos de interpretação incorreta, retrabalho e falhas na especificação dos requisitos do Sistema de Gestão de Eventos da Eventus.
