# Atividade 2 - Identificação dos Requisitos Não Funcionais

# Sistema de Gestão de Eventos - Eventus

## Objetivo

Identificar os requisitos não funcionais do sistema com base nas necessidades do negócio, nos stakeholders envolvidos e nas lacunas identificadas durante a elicitação de requisitos.

---

# Requisitos de Usabilidade

## RNF01 - Interface Intuitiva
**Descrição:** O sistema deve possuir interface amigável e intuitiva para usuários com conhecimentos básicos de informática.

## RNF02 - Facilidade de Navegação
**Descrição:** As funcionalidades mais utilizadas devem estar acessíveis com no máximo três interações a partir da página principal.

## RNF03 - Design Responsivo
**Descrição:** O sistema deve adaptar sua interface para computadores, tablets e smartphones.

## RNF04 - Clareza das Mensagens
**Descrição:** O sistema deve apresentar mensagens de erro, confirmação e alerta em linguagem clara e compreensível.

---

# Requisitos de Desempenho

## RNF05 - Tempo de Resposta
**Descrição:** As operações de consulta de eventos e inscrições devem responder em até 3 segundos em condições normais de uso.

## RNF06 - Processamento Simultâneo
**Descrição:** O sistema deve suportar múltiplos acessos simultâneos sem degradação perceptível da experiência do usuário.

## RNF07 - Atualização de Dados em Tempo Real
**Descrição:** O número de vagas disponíveis deve ser atualizado imediatamente após confirmação de inscrições ou cancelamentos.

---

# Requisitos de Disponibilidade

## RNF08 - Disponibilidade do Serviço
**Descrição:** O sistema deve estar disponível 24 horas por dia, 7 dias por semana, exceto durante janelas programadas de manutenção.

## RNF09 - Recuperação de Falhas
**Descrição:** O sistema deve permitir recuperação dos dados em caso de falhas operacionais.

---

# Requisitos de Segurança

## RNF10 - Autenticação de Usuários
**Descrição:** O acesso ao sistema deve exigir autenticação por usuário e senha.

## RNF11 - Controle de Acesso por Perfil
**Descrição:** O sistema deve restringir funcionalidades conforme o perfil do usuário.

## RNF12 - Proteção de Dados Sensíveis
**Descrição:** Os dados pessoais dos participantes devem ser armazenados de forma segura.

## RNF13 - Registro de Auditoria
**Descrição:** O sistema deve registrar operações críticas, incluindo inscrições, cancelamentos, pagamentos e reembolsos.

## RNF14 - Comunicação Segura
**Descrição:** A comunicação entre usuários e sistema deve ocorrer por conexões seguras e criptografadas.

---

# Requisitos de Privacidade e LGPD

## RNF15 - Conformidade com a LGPD
**Descrição:** O sistema deve atender aos requisitos da Lei Geral de Proteção de Dados (LGPD).

## RNF16 - Consentimento para Uso de Dados
**Descrição:** O sistema deve obter consentimento do participante para tratamento de seus dados pessoais quando necessário.

## RNF17 - Restrição de Visualização de Dados
**Descrição:** O sistema deve permitir acesso apenas às informações autorizadas para cada perfil de usuário.

---

# Requisitos de Confiabilidade

## RNF18 - Integridade dos Dados
**Descrição:** O sistema deve garantir a consistência das informações de inscrições, vagas e pagamentos.

## RNF19 - Controle de Concorrência
**Descrição:** O sistema deve evitar que duas pessoas ocupem simultaneamente a mesma vaga.

## RNF20 - Tolerância a Falhas de Processo
**Descrição:** O sistema deve preservar registros mesmo em falhas durante inscrições ou pagamentos.

---

# Requisitos de Manutenibilidade

## RNF21 - Facilidade de Manutenção
**Descrição:** O sistema deve possuir arquitetura que facilite correções e evoluções futuras.

## RNF22 - Documentação Técnica
**Descrição:** O sistema deve possuir documentação técnica atualizada para apoiar a equipe de TI.

## RNF23 - Padronização de Código
**Descrição:** O software deve seguir padrões de desenvolvimento definidos pela organização.

---

# Requisitos de Compatibilidade

## RNF24 - Compatibilidade com Navegadores
**Descrição:** O sistema deve ser compatível com os principais navegadores modernos.

## RNF25 - Compatibilidade com Dispositivos Móveis
**Descrição:** O sistema deve funcionar adequadamente em dispositivos móveis.

---

# Requisitos de Acessibilidade

## RNF26 - Acessibilidade Digital
**Descrição:** O sistema deve seguir boas práticas de acessibilidade digital para usuários com deficiência.

## RNF27 - Contraste e Legibilidade
**Descrição:** A interface deve garantir leitura adequada por meio de contraste e tamanho apropriado de fontes.

---

# Requisitos de Escalabilidade

## RNF28 - Crescimento de Eventos
**Descrição:** O sistema deve suportar aumento gradual da quantidade de eventos sem necessidade de reestruturação completa.

## RNF29 - Crescimento de Usuários
**Descrição:** O sistema deve suportar aumento da quantidade de participantes cadastrados.

---

# Requisitos Não Funcionais Pendentes de Refinamento

| ID | Tema | Pendência |
|----|-------|------------|
| RNF08 | Disponibilidade | Não foi definido o nível mínimo de SLA esperado. |
| RNF05 | Desempenho | Não foi informado o volume esperado de usuários simultâneos. |
| RNF15 | LGPD | Não foram detalhadas políticas de retenção e descarte dos dados. |
| RNF26 | Acessibilidade | Não foi definido o padrão de acessibilidade a ser adotado. |
| RNF13 | Auditoria | Não foi definido o prazo de retenção dos logs. |
| RNF14 | Segurança | Não foram definidos requisitos específicos de criptografia. |

---

# Resultado da Análise

**Total de Requisitos Não Funcionais Identificados:** 29

**Categorias Cobertas:**
- Usabilidade
- Desempenho
- Disponibilidade
- Segurança
- Privacidade
- Confiabilidade
- Manutenibilidade
- Compatibilidade
- Acessibilidade
- Escalabilidade

Os requisitos acima complementam os requisitos funcionais identificados na Atividade 1 e servem como base para a especificação completa do Sistema de Gestão de Eventos da Eventus.
