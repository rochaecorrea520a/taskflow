# 🚀 TaskFlow

![Logótipo do TaskFlow](https://via.placeholder.com/150)

O **TaskFlow** é uma aplicação simples e eficiente concebida para gerir tarefas diárias e acompanhar projetos. 
Esta ferramenta permite organizar fluxos de trabalho através de quadros intuitivos e *listas de controlo*.
Oferece uma interface centralizada para acompanhamento em tempo real do progresso das equipas.

> **Nota Importante:** Instale o Node.js antes de prosseguir.
## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Categoria |
| :---: | :---: | :---: |
| **Node.js** | `v18.16.0` | Backend |
| **Express** | `v4.18.2` | Framework |S
| **SQLite3** | `v5.1.6` | Base de Dados |S

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
