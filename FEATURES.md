# 📌 FEATURES — Voll Med

## 🎯 Visão Geral
Sistema de gestão médica com foco em cadastro, edição, listagem e controle de médicos e pacientes, incluindo validações de dados e controle de status.

---

## ✅ Requisitos Funcionais

### 🏠 Navegação / Home

- [ ] O sistema deve possuir uma tela inicial (Home).
- [ ] A Home deve apresentar atalhos para:
  - [ ] Gestão de Médicos
  - [ ] Gestão de Pacientes
- [ ] A Home deve exibir indicadores/resumo (ex: quantidade de registros).

---

### 👨‍⚕️ Gerenciamento de Médicos

#### 📋 Listagem

- [ ] O usuário poderá visualizar a lista de médicos cadastrados.
- [ ] A listagem deve exibir:
  - [ ] Nome
  - [ ] Especialidade
  - [ ] Contato
- [ ] O usuário poderá pesquisar médicos.
- [ ] O usuário poderá acessar ações de:
  - [ ] Editar
  - [ ] Visualizar detalhes

---

#### ➕ Criação de Médico

- [ ] O usuário poderá cadastrar um novo médico.
- [ ] O formulário deve conter:
  - [ ] Nome completo
  - [ ] Especialidade
  - [ ] CRM
  - [ ] Email
  - [ ] Telefone
  - [ ] Endereço completo:
    - [ ] Logradouro
    - [ ] Número
    - [ ] Complemento
    - [ ] Bairro
    - [ ] Cidade
    - [ ] UF
    - [ ] CEP

---

#### ✏️ Edição de Médico

- [ ] O usuário poderá editar dados de um médico.
- [ ] O sistema deve permitir alteração de todos os campos cadastrados.

---

#### ⚠️ Validação de Campos

- [ ] O sistema deve validar campos obrigatórios:
  - [ ] Nome
  - [ ] CRM
  - [ ] Especialidade
  - [ ] Email
- [ ] O sistema deve validar formato:
  - [ ] Email válido
  - [ ] CRM válido
  - [ ] CEP válido
- [ ] Campos inválidos devem ser destacados visualmente.

---

#### 🚫 Desativação de Médico

- [ ] O usuário poderá desativar um médico.
- [ ] O sistema deve solicitar confirmação antes da ação.
- [ ] O sistema deve informar regras para desativação (ex: vínculo ativo).
- [ ] Um médico desativado não deve aparecer em listagens ativas.

---

### 🧑‍🤝‍🧑 Gerenciamento de Pacientes

#### 📋 Listagem

- [ ] O usuário poderá visualizar a lista de pacientes cadastrados.
- [ ] A listagem deve exibir:
  - [ ] Nome
  - [ ] CPF
  - [ ] Contato
- [ ] O usuário poderá pesquisar pacientes.
- [ ] O usuário poderá acessar:
  - [ ] Editar
  - [ ] Visualizar detalhes

---

#### ➕ Criação de Paciente

- [ ] O usuário poderá cadastrar um novo paciente.
- [ ] O formulário deve conter:
  - [ ] Nome completo
  - [ ] CPF
  - [ ] Email
  - [ ] Telefone
  - [ ] Endereço completo:
    - [ ] Logradouro
    - [ ] Número
    - [ ] Complemento
    - [ ] Bairro
    - [ ] Cidade
    - [ ] UF
    - [ ] CEP

---

#### ✏️ Edição de Paciente

- [ ] O usuário poderá editar os dados de um paciente.
- [ ] O sistema deve permitir atualização de todos os campos.

---

#### ⚠️ Validação de Campos

- [ ] O sistema deve validar campos obrigatórios:
  - [ ] Nome
  - [ ] CPF
  - [ ] Email
- [ ] O sistema deve validar formato:
  - [ ] CPF válido
  - [ ] Email válido
  - [ ] CEP válido
- [ ] Campos inválidos devem ser destacados visualmente.

---

#### 🚫 Desativação de Paciente

- [ ] O usuário poderá desativar um paciente.
- [ ] O sistema deve solicitar confirmação.
- [ ] O sistema deve impedir desativação em casos inválidos (ex: vínculo ativo).
- [ ] Pacientes desativados não devem aparecer em listagens ativas.

---

### 🔒 Estados e Feedback do Sistema

- [ ] O sistema deve exibir mensagens de sucesso ao salvar dados.
- [ ] O sistema deve exibir mensagens de erro ao falhar validações.
- [ ] O sistema deve exibir modais de confirmação para ações críticas.
- [ ] O sistema deve bloquear ações inválidas com feedback claro.

---

### 📱 Interface e Experiência

- [ ] O sistema deve ser responsivo (mobile-first).
- [ ] Os formulários devem ser organizados por seções:
  - [ ] Dados pessoais
  - [ ] Contato
  - [ ] Endereço
- [ ] O sistema deve ter navegação intuitiva e consistente.

---

## 🚧 Backlog (Sugestões Evolutivas)

- [ ] Sistema de agendamento de consultas
- [ ] Integração com calendário
- [ ] Histórico médico do paciente
- [ ] Dashboard com métricas avançadas
- [ ] Sistema de autenticação (login)
- [ ] Controle de permissões (admin, recepção, médico)
- [ ] Upload de documentos médicos
- [ ] Notificações (email/SMS)
