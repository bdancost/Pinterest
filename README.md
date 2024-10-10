
# Pinterest Clone

Este é um projeto de clone do Pinterest, desenvolvido com o framework Flask, que permite aos usuários criar contas, fazer login, enviar fotos e visualizar um feed de imagens. A aplicação utiliza um banco de dados SQLite para armazenar informações sobre usuários e suas fotos.

## Ferramentas e Tecnologias Utilizadas

- **Flask**: Framework web para desenvolvimento de aplicações em Python.
- **Flask-SQLAlchemy**: Extensão Flask que facilita o uso do SQLAlchemy, permitindo a interação com o banco de dados de forma simples.
- **Flask-Login**: Gerencia sessões de usuários e autenticação.
- **Flask-Bcrypt**: Proporciona hashing de senhas, aumentando a segurança das senhas armazenadas.
- **WTForms**: Facilita a criação de formulários em aplicações Flask.
- **SQLite**: Banco de dados leve e embutido utilizado para armazenamento de dados.

## Funcionalidades Principais

- **Cadastro de Usuários**: Os usuários podem criar contas fornecendo um e-mail, nome de usuário e senha.
- **Login de Usuários**: Os usuários podem fazer login usando suas credenciais.
- **Upload de Fotos**: Após o login, os usuários podem fazer o upload de fotos que serão armazenadas no servidor.
- **Feed de Imagens**: Uma página onde todas as fotos enviadas pelos usuários são exibidas.
- **Perfis de Usuários**: Cada usuário tem um perfil onde pode ver suas fotos.

## Estrutura do Projeto

```
pinterest/
│
├── __init__.py           # Inicializa a aplicação Flask e configurações
├── forms.py              # Define os formulários da aplicação
├── models.py             # Define os modelos do banco de dados
├── routes.py             # Define as rotas da aplicação
└── templates/            # Contém os arquivos HTML
```

## Instruções para Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu_usuario/pinterest-clone.git
   ```

2. **Navegue até o diretório do projeto**:
   ```bash
   cd pinterest-clone
   ```

3. **Crie um ambiente virtual** (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Linux/Mac
   venv\Scripts\activate     # Para Windows
   ```

4. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Inicie a aplicação**:
   ```bash
   python -m pinterest
   ```

6. **Acesse a aplicação** no seu navegador:
   ```
   http://127.0.0.1:5000
   ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um *pull request* ou relatar problemas.


## Contato

Para perguntas ou feedback, você pode entrar em contato pelo e-mail: pr.danfc88@gmail.com

---

Sinta-se à vontade para modificar quaisquer seções conforme necessário para refletir com precisão seu projeto!
