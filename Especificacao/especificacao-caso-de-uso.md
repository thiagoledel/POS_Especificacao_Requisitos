# Atividade 6 - Especificação dos Casos de Uso

# Sistema de Gestão de Eventos - Eventus

## UC01 - Consultar Eventos
**Atores:** Participante
**Objetivo:** Visualizar eventos disponíveis.
**Pré-condições:** Sistema disponível.
**Fluxo Principal:**
1. Participante acessa catálogo.
2. Sistema exibe eventos disponíveis.
3. Participante consulta detalhes.
**Pós-condição:** Informações visualizadas.

---

## UC02 - Realizar Inscrição
**Atores:** Participante
**Objetivo:** Inscrever-se em evento ou workshop.
**Pré-condições:** Evento disponível.
**Fluxo Principal:**
1. Selecionar evento.
2. Informar dados necessários.
3. Confirmar inscrição.
4. Sistema registra inscrição.
5. Sistema gera comprovante.
**Fluxos Alternativos:** Evento pago exige confirmação financeira.
**Pós-condição:** Inscrição registrada.

---

## UC03 - Consultar Inscrições
**Atores:** Participante
**Objetivo:** Consultar inscrições realizadas.
**Pré-condições:** Usuário autenticado.
**Fluxo Principal:**
1. Acessar área de inscrições.
2. Sistema exibe inscrições.

---

## UC04 - Cancelar Inscrição
**Atores:** Participante
**Objetivo:** Cancelar inscrição.
**Pré-condições:** Evento permite cancelamento.
**Fluxo Principal:**
1. Selecionar inscrição.
2. Solicitar cancelamento.
3. Sistema efetua cancelamento.
**Fluxo Alternativo:** Evento não permite cancelamento.

---

## UC05 - Emitir Certificado
**Atores:** Participante
**Objetivo:** Emitir certificado.
**Pré-condições:** Evento concluído.
**Fluxo Principal:**
1. Selecionar evento.
2. Solicitar certificado.
3. Sistema disponibiliza documento.
**Observação:** Regra ainda pendente de detalhamento.

---

## UC06 - Criar Evento
**Atores:** Organizador
**Objetivo:** Cadastrar evento.
**Fluxo Principal:**
1. Informar dados do evento.
2. Definir programação.
3. Definir vagas.
4. Salvar evento.

---

## UC07 - Alterar Evento
**Atores:** Organizador
**Objetivo:** Atualizar dados do evento.
**Fluxo Principal:**
1. Selecionar evento.
2. Alterar informações.
3. Salvar alterações.

---

## UC08 - Gerenciar Programação
**Atores:** Organizador
**Objetivo:** Manter agenda e workshops.
**Fluxo Principal:**
1. Cadastrar atividades.
2. Definir horários.
3. Publicar programação.

---

## UC09 - Controlar Vagas
**Atores:** Organizador
**Objetivo:** Definir e acompanhar vagas.
**Fluxo Principal:**
1. Configurar limite.
2. Monitorar ocupação.
3. Encerrar inscrições quando lotado.

---

## UC10 - Gerenciar Lista de Espera
**Atores:** Organizador
**Objetivo:** Administrar fila de espera.
**Observação:** Regras pendentes de definição.

---

## UC11 - Gerenciar Participantes
**Atores:** Organizador
**Objetivo:** Consultar e administrar inscritos.
**Fluxo Principal:**
1. Consultar participantes.
2. Aplicar ações administrativas.

---

## UC12 - Acompanhar Inscrições
**Atores:** Organizador
**Objetivo:** Monitorar inscritos em tempo real.
**Fluxo Principal:**
1. Acessar painel.
2. Consultar indicadores.

---

## UC13 - Emitir Relatórios
**Atores:** Organizador
**Objetivo:** Gerar relatórios gerenciais.
**Fluxo Principal:**
1. Selecionar relatório.
2. Gerar documento.

---

## UC14 - Confirmar Pagamento
**Atores:** Equipe Financeira
**Objetivo:** Confirmar pagamento.
**Fluxo Principal:**
1. Consultar pagamento.
2. Validar transação.
3. Confirmar pagamento.

---

## UC15 - Liberar Inscrição
**Atores:** Equipe Financeira
**Objetivo:** Liberar inscrição vinculada a pagamento.
**Pré-condição:** Pagamento confirmado.

---

## UC16 - Analisar Reembolso
**Atores:** Equipe Financeira
**Objetivo:** Avaliar solicitação de reembolso.
**Observação:** Critérios ainda não definidos.

---

## UC17 - Processar Reembolso
**Atores:** Equipe Financeira
**Objetivo:** Executar devolução financeira autorizada.

---

## UC18 - Consultar Situação Financeira
**Atores:** Equipe Financeira
**Objetivo:** Consultar situação financeira das inscrições.

---

## UC19 - Consultar Programação
**Atores:** Palestrante
**Objetivo:** Consultar agenda das atividades.

---

## UC20 - Consultar Participantes das Atividades
**Atores:** Palestrante
**Objetivo:** Consultar inscritos relacionados às suas atividades.
**Observação:** Dados visíveis ainda não definidos.

---

## UC21 - Gerenciar Usuários
**Atores:** Equipe de TI
**Objetivo:** Administrar usuários do sistema.

---

## UC22 - Gerenciar Perfis de Acesso
**Atores:** Equipe de TI
**Objetivo:** Configurar permissões dos perfis.

---

## UC23 - Manter Sistema
**Atores:** Equipe de TI
**Objetivo:** Realizar manutenção operacional da solução.

---

# Resumo

| Indicador | Quantidade |
|------------|------------|
| Casos de Uso Especificados | 23 |
| Atores Identificados | 5 |
| Casos com Regras Pendentes | 4 |

As especificações apresentadas detalham os principais comportamentos do Sistema de Gestão de Eventos da Eventus e servem como base para projeto, desenvolvimento e validação da solução.
