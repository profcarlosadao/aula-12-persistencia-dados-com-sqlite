# 🗂️ daily_tasks

Aplicativo Flutter com persistência local utilizando SQLite, desenvolvido como parte da **Aula 12 – Persistência de Dados com SQLite**.

---

## 🚀 Funcionalidades

- ✅ Listar tarefas armazenadas localmente
- ➕ Adicionar tarefas com título e data
- 🗑️ Remover tarefas
- 🧠 Separação clara em camadas: Model, ViewModel e Service

---

## 🧱 Estrutura do Projeto

```bash
lib/
├── main.dart
├── task.dart                      # Modelo de dados (Task)
├── task.view_model.dart           # ViewModel com lógica de estado
├── task_database.service.dart     # Serviço de persistência usando sqflite
└── task.screen.dart               # UI principal da aplicação
