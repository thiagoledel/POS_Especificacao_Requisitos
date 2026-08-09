# Atividade 5 - Diagramas de Casos de Uso

# Sistema de Gestão de Eventos - Eventus

## Objetivo

Representar graficamente os principais casos de uso identificados durante a elicitação e análise dos requisitos do Sistema de Gestão de Eventos da Eventus.

---

# Diagrama Geral de Casos de Uso

```mermaid
flowchart LR
    Participante([Participante])
    Organizador([Organizador])
    Financeiro([Equipe Financeira])
    Palestrante([Palestrante])
    TI([Equipe de TI])

    UC1((Consultar Eventos))
    UC2((Realizar Inscrição))
    UC3((Consultar Inscrições))
    UC4((Cancelar Inscrição))
    UC5((Emitir Certificado))
    UC6((Criar Evento))
    UC7((Gerenciar Evento))
    UC8((Controlar Vagas))
    UC9((Acompanhar Inscritos))
    UC10((Confirmar Pagamento))
    UC11((Processar Reembolso))
    UC12((Consultar Programação))
    UC13((Consultar Participantes))
    UC14((Gerenciar Usuários))

    Participante --- UC1
    Participante --- UC2
    Participante --- UC3
    Participante --- UC4
    Participante --- UC5

    Organizador --- UC6
    Organizador --- UC7
    Organizador --- UC8
    Organizador --- UC9

    Financeiro --- UC10
    Financeiro --- UC11

    Palestrante --- UC12
    Palestrante --- UC13

    TI --- UC14
```

---

# Diagrama de Casos de Uso - Participante

```mermaid
flowchart LR
    A([Participante])

    UC1((Consultar Eventos))
    UC2((Consultar Detalhes do Evento))
    UC3((Realizar Inscrição))
    UC4((Receber Comprovante))
    UC5((Consultar Inscrições))
    UC6((Cancelar Inscrição))
    UC7((Solicitar Reembolso))
    UC8((Emitir Certificado))

    A --- UC1
    A --- UC2
    A --- UC3
    A --- UC4
    A --- UC5
    A --- UC6
    A --- UC7
    A --- UC8
```

---

# Diagrama de Casos de Uso - Organizador

```mermaid
flowchart LR
    A([Organizador])

    UC1((Criar Evento))
    UC2((Alterar Evento))
    UC3((Gerenciar Programação))
    UC4((Definir Vagas))
    UC5((Controlar Lista de Espera))
    UC6((Gerenciar Participantes))
    UC7((Acompanhar Inscrições))
    UC8((Emitir Relatórios))

    A --- UC1
    A --- UC2
    A --- UC3
    A --- UC4
    A --- UC5
    A --- UC6
    A --- UC7
    A --- UC8
```

---

# Diagrama de Casos de Uso - Equipe Financeira

```mermaid
flowchart LR
    A([Equipe Financeira])

    UC1((Confirmar Pagamento))
    UC2((Liberar Inscrição))
    UC3((Analisar Reembolso))
    UC4((Processar Reembolso))
    UC5((Consultar Situação Financeira))

    A --- UC1
    A --- UC2
    A --- UC3
    A --- UC4
    A --- UC5
```

---

# Diagrama de Casos de Uso - Palestrante

```mermaid
flowchart LR
    A([Palestrante])

    UC1((Consultar Programação))
    UC2((Consultar Participantes das Atividades))

    A --- UC1
    A --- UC2
```

---

# Diagrama de Casos de Uso - Equipe de TI

```mermaid
flowchart LR
    A([Equipe de TI])

    UC1((Gerenciar Usuários))
    UC2((Gerenciar Perfis de Acesso))
    UC3((Manter Sistema))

    A --- UC1
    A --- UC2
    A --- UC3
```

---

# Relacionamento dos Casos de Uso com os Requisitos Funcionais

| Caso de Uso | Requisitos Relacionados |
|-------------|-------------------------|
| Consultar Eventos | RF01, RF02 |
| Realizar Inscrição | RF03, RF04 |
| Emitir Comprovante | RF05 |
| Consultar Inscrições | RF06 |
| Cancelar Inscrição | RF07 |
| Emitir Certificado | RF08 |
| Criar Evento | RF09 |
| Alterar Evento | RF10 |
| Gerenciar Programação | RF11 |
| Controlar Vagas | RF12, RF13, RF14 |
| Lista de Espera | RF15 |
| Configurar Cancelamento | RF16 |
| Acompanhar Inscrições | RF17 |
| Gerenciar Participantes | RF18 |
| Relatórios | RF19 |
| Confirmar Pagamento | RF21, RF22, RF23 |
| Reembolso | RF24, RF25 |
| Situação Financeira | RF26 |
| Consultar Programação | RF27 |
| Consultar Participantes | RF28 |
| Gerenciar Usuários | RF30, RF31, RF32 |

---

# Conclusão

Foram modelados os diagramas de casos de uso para todos os stakeholders identificados no projeto Eventus, permitindo visualizar as principais interações entre usuários e sistema e servindo como base para a próxima etapa de especificação detalhada dos casos de uso.
