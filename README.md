# Daily Diet API

API RESTful completa para **controle de dieta diária**, desenvolvida em **Flask**.  

O sistema permite que os usuários registrem suas refeições com informações detalhadas, como nome, descrição, data/hora e se a refeição está dentro da dieta. A aplicação oferece funcionalidades completas de **CRUD (Criar, Ler, Atualizar, Deletar)** e **autenticação de usuários** com **Flask-Login**, garantindo gerenciamento seguro das informações.

---

## Funcionalidades

- **Registro de refeições** com dados detalhados:
  - Nome da refeição
  - Descrição
  - Data e hora
  - Status (dentro ou fora da dieta)
- **CRUD completo** para gerenciamento das refeições:
  - Criar
  - Listar
  - Atualizar
  - Deletar
- **Autenticação de usuários**:
  - Registro e login com **Flask-Login**
  - Proteção de rotas
- **Persistência em banco de dados**:
  - SQLite para desenvolvimento rápido (pode ser adaptado para PostgreSQL ou MySQL)
- Estrutura RESTful clara e organizada
- Possibilidade de extensões futuras, como relatórios de dieta ou filtros de refeições



## Tecnologias Utilizadas

- **Python 3.11+**
- **Flask**
- **Flask-Login** (autenticação de usuários)
- **SQLite** (banco de dados para desenvolvimento)