# 📅 Agenda

Projeto de Agenda desenvolvido com Python e Django, permitindo o gerenciamento de contatos de forma simples e eficiente.

---

## 🚀 Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Django**: Framework web utilizado para o desenvolvimento da aplicação.
- **HTML5 & CSS3**: Para estruturação e estilização das páginas.
- **JavaScript**: Para interações dinâmicas no frontend.
- **SQLite**: Banco de dados utilizado para armazenamento local.

---

## ⚙️ Funcionalidades

- **Cadastro de Contatos**: Adicione novos contatos com informações como nome, telefone e email.
- **Edição de Contatos**: Atualize as informações dos contatos existentes.
- **Exclusão de Contatos**: Remova contatos que não são mais necessários.
- **Listagem de Contatos**: Visualize todos os contatos cadastrados em uma lista organizada.
- **Busca de Contatos**: Encontre contatos rapidamente utilizando a funcionalidade de busca.

---

## 🗂️ Estrutura do Projeto

```
Agenda/
├── base_static/
│   └── global/
│       └── css/
├── base_templates/
│   └── global/
├── contact/
│   ├── migrations/
│   ├── templates/
│   │   └── contact/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── project/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── utils/
├── manage.py
└── .gitignore
```

---

## 🛠️ Instalação e Execução

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/RodrigoLudke/Agenda.git
   cd Agenda
   ```

2. **Crie e ative um ambiente virtual:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Aplique as migrações:**

   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento:**

   ```bash
   python manage.py runserver
   ```

6. **Acesse a aplicação:**

   Abra o navegador e vá para [http://localhost:8000](http://localhost:8000)

---

## ✅ Requisitos

- Python 3.8 ou superior
- pip
- Ambiente virtual (recomendado)

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
