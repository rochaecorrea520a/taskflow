# TASKFLOWW - GESTOR DE TAREFAS PESSOAL

<!-- TEXTO DE COMENTÁRIO -->

O **TaskFlow** é uma aplicação web intuitiva para organizar rotinas diárias e projetos com *eficiência máxima*. A ferramenta permite categorizar tarefas e acompanhar o progresso. É a solução ideal para simplificar a gestão de tempo.

> **Nota Importante:** Instale o Node.js antes de prosseguir.
## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Categoria |
| :---: | :---: | :---: |
| **Node.js** | `v18.16.0` | Backend |
| **Express** | `v4.18.2` | Framework |
| **SQLite3** | `v5.1.6` | Base de Dados |

## 📦 Instalação

1. Clona o repositório.
2. Abre a pasta no terminal.
3. Executa `npm install`.
4. Configura o ficheiro `config.txt`.
5. Executa `npm start`.

### ⚙️ Configuração da Base de Dados

```sql
CREATE TABLE tarefas (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    titulo VARCHAR(100) NOT NULL
);
✨ Funcionalidades
    • Criar e editar tarefas.
    • Categorizar por prioridade.
    • Exportar dados em JSON.
📋 Roadmap
    • [x] Estrutura baseM DIA
    • [ ] Autenticação
    • [ ] Modo escuro (Dark Mode)

    Projeto por RENATA.
    • GitHub: rochaecorrea520a
    • Docs: Node.js
