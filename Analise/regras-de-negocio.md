# Atividade 3 - Identificação das Regras de Negócio

# Sistema de Gestão de Eventos - Eventus

## Objetivo

Identificar as regras de negócio derivadas das entrevistas realizadas com os stakeholders e das restrições operacionais do processo de gestão de eventos.

---

# Regras de Negócio Identificadas

## RN01 - Limite de Vagas
**Descrição:** Cada evento ou workshop deve possuir uma quantidade máxima de vagas definida pelo organizador.

**Origem:** Organizadores

---

## RN02 - Controle Automático de Vagas
**Descrição:** A quantidade de vagas disponíveis deve ser reduzida automaticamente conforme novas inscrições forem confirmadas.

**Origem:** Organizadores

---

## RN03 - Bloqueio por Lotação
**Descrição:** Não devem ser aceitas novas inscrições quando o limite de vagas do evento for atingido.

**Origem:** Organizadores

---

## RN04 - Lista de Espera para Eventos Lotados
**Descrição:** Quando um evento atingir sua capacidade máxima, participantes podem ser direcionados para uma lista de espera.

**Origem:** Organizadores

**Status:** Necessita detalhamento.

---

## RN05 - Eventos Gratuitos e Pagos
**Descrição:** Um evento pode ser classificado como gratuito ou pago.

**Origem:** Equipe Financeira

---

## RN06 - Confirmação de Pagamento
**Descrição:** Determinadas inscrições somente poderão ser efetivadas após a confirmação do pagamento.

**Origem:** Equipe Financeira

---

## RN07 - Existência de Política de Reembolso
**Descrição:** O sistema deve considerar que existem situações em que o participante possui direito ao reembolso e situações em que não possui.

**Origem:** Equipe Financeira

**Status:** Critérios não definidos.

---

## RN08 - Cancelamento Condicional
**Descrição:** Nem todos os eventos permitirão o cancelamento da inscrição.

**Origem:** Organizadores

---

## RN09 - Configuração de Cancelamento por Evento
**Descrição:** A permissão de cancelamento deve ser configurada individualmente para cada evento.

**Origem:** Organizadores

---

## RN10 - Comprovante de Inscrição
**Descrição:** Após a conclusão da inscrição, o participante deve receber um comprovante.

**Origem:** Participantes

---

## RN11 - Emissão de Certificados
**Descrição:** Participantes devem poder obter certificado após a realização do evento.

**Origem:** Participantes

**Status:** Forma de liberação não definida.

---

## RN12 - Consulta de Eventos Disponíveis
**Descrição:** Os participantes devem conseguir visualizar os eventos disponíveis para inscrição.

**Origem:** Participantes

---

## RN13 - Consulta das Próprias Inscrições
**Descrição:** Os participantes devem conseguir acompanhar suas inscrições realizadas.

**Origem:** Participantes

---

## RN14 - Gestão de Eventos
**Descrição:** Somente organizadores podem criar e administrar eventos.

**Origem:** Organizadores

---

## RN15 - Acompanhamento em Tempo Real
**Descrição:** Organizadores devem possuir acesso às informações atualizadas de inscrições e vagas.

**Origem:** Organizadores

---

## RN16 - Consulta de Participantes por Palestrantes
**Descrição:** Palestrantes podem consultar participantes inscritos em suas atividades.

**Origem:** Palestrantes

**Status:** Dados visíveis ainda não definidos.

---

## RN17 - Consulta de Programação por Palestrantes
**Descrição:** Palestrantes podem visualizar a programação relacionada às suas atividades.

**Origem:** Palestrantes

---

## RN18 - Workshops Simultâneos
**Descrição:** Workshops planejados para o mesmo horário devem ocorrer simultaneamente.

**Origem:** Organizadores

---

## RN19 - Múltiplas Inscrições em Workshops
**Descrição:** Um participante pode desejar inscrever-se em vários workshops do mesmo dia.

**Origem:** Participantes

**Status:** Necessita definição das regras para conflitos de horário.

---

## RN20 - Perfis de Usuário
**Descrição:** O sistema deve operar considerando perfis distintos de acesso: Participante, Organizador, Financeiro, Palestrante e TI.

**Origem:** Stakeholders identificados.

---

# Regras de Negócio Pendentes de Definição

| ID | Regra | Pendência Identificada |
|----|--------|-----------------------|
| RN04 | Lista de Espera | Não foi definida a ordem de convocação e reserva de vagas. |
| RN07 | Reembolso | Não existem critérios definidos para concessão. |
| RN08 | Cancelamento | Não foi definido o prazo limite para cancelamento. |
| RN11 | Certificados | Não foi definida a necessidade de confirmação de presença. |
| RN16 | Consulta de Participantes | Não foram definidos os dados visíveis aos palestrantes. |
| RN19 | Conflito de Horários | Não foi definida a regra para inscrições simultâneas em workshops conflitantes. |
| RN06 | Pagamentos | Não foi definido o momento exato da reserva da vaga durante o pagamento. |
| RN10 | Comprovantes e Notificações | Não foi definido o canal de comunicação utilizado. |

---

# Resultado da Análise

**Total de Regras de Negócio Identificadas:** 20

**Regras com Necessidade de Refinamento:** 8

As regras de negócio documentadas representam restrições, políticas e decisões organizacionais que orientam o comportamento esperado do Sistema de Gestão de Eventos da Eventus. Elas complementam os requisitos funcionais e não funcionais levantados nas atividades anteriores.
