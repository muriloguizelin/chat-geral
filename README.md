# 💬 Chat em Tempo Real — Requisitos (MVP)

## 🎯 Objetivo
Aplicação web para troca de mensagens em tempo real entre usuários.

---

## 🧱 Funcionalidades

### 👤 Usuário
- Entrar com nome (sem login)
- Ver usuários online

### 💬 Mensagens
- Enviar mensagem
- Receber em tempo real
- Exibir histórico da sessão

### 🟢 Status
- Mostrar quem está online
- Atualizar ao entrar/sair

### 🧪 Regras
- Nome obrigatório
- Mensagem não vazia

---

## ⚙️ Requisitos Técnicos

### Frontend
- React
- Tela com:
  - lista de mensagens
  - input
  - botão enviar

### Backend
- Node.js + Express
- WebSocket (Socket.io)

---

## 🔌 Eventos (Socket)
- `join` → usuário entrou  
- `message` → nova mensagem  
- `users` → lista de usuários  
- `disconnect` → usuário saiu  

---

## 🧩 Divisão de Tarefas

### Backend
- Servidor + WebSocket
- Lógica de mensagens
- Gerenciar usuários online

### Frontend
- UI do chat (input + lista)
- Conexão socket
- Exibir mensagens e usuários

---

## 🗓️ Sprints

### Sprint 1
- Conexão funcionando
- Envio/recebimento de mensagens

### Sprint 2
- Lista de mensagens
- Nome do usuário

### Sprint 3
- Usuários online
- Ajustes de UI

---

## 🧠 Regras do Sistema
- Mensagens → broadcast para todos
- Usuário entra → adiciona na lista
- Usuário sai → remove da lista

---

## 🚀 Extras (opcional)
- Salas (rooms)
- Mensagem privada
- Persistência (banco)
- Autenticação

---

## ⚠️ Fora do Escopo (MVP)
- Login complexo
- Banco de dados inicial
- UI avançada
