# 📅 UniAgenda - Sistema de Agendamento de Laboratórios


## 🔍 Visão Geral
O UniAgenda é um sistema web desenvolvido em Flask para gestão de reservas de laboratórios acadêmicos, proporcionando uma solução eficiente para professores e estudantes agendarem espaços de estudo.

## ✨ Funcionalidades
✅ **Autenticação Segura**  
- Cadastro com validação de e-mail e senha
- Login com criptografia bcrypt
- Controle de sessão

📆 **Gestão de Agendamentos**  
- Visualização de disponibilidade em calendário interativo
- Reserva de laboratórios
- Cancelamento de reservas

🎨 **Interface Intuitiva**  
- Design responsivo
- Visualização de agendamentos pessoais
- Navegação por meses

## 🛠️ Tecnologias
**Backend:**
- Python 3
- Flask
- SQLAlchemy
- Flask-Login
- Flask-Bcrypt

**Frontend:**
- HTML5
- CSS3
- JavaScript

**Banco de Dados:**
- SQLite

## 🚀 Como Executar

### Pré-requisitos
- Python 3.8+
- pip

## 📂 Estrutura do Projeto
```
UniAgenda/
├── __init__.py
├── forms.py
├── models.py
├── routes.py
├── teste.py
├── templates/
│   ├── 404.html
│   ├── cadastro.html
│   ├── home.html
│   ├── home2.html
│   ├── home_redirect.html
│   └── login.html
├── static/
│   ├── css/
│   ├── js/
│   └── imgs/
└── uniagenda.db
```

## 🌐 Rotas Principais
| Rota        | Descrição                          |
|-------------|-----------------------------------|
| `/`         | Redireciona para login            |
| `/login`    | Página de autenticação            |
| `/cadastro` | Criação de nova conta             |
| `/sair`     | Encerra sessão                    |
| `/enviar`   | Envio de agendamentos (em dev)    |


> ⚠️ O código-fonte está em repositório privado. Caso tenha interesse técnico, entre em contato.


