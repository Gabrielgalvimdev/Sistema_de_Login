# Sistema de Login em Python

Este projeto é um sistema simples de cadastro e autenticação de usuários, desenvolvido em Python utilizando SQLAlchemy como ORM e SQLite como banco de dados. Ideal para estudos e projetos que necessitem de um mecanismo básico de login.

## Funcionalidades

- Cadastro de novos usuários com nome, email e senha
- Login com validação de email e senha
- Armazenamento seguro das senhas (hash SHA-256)
- Persistência dos dados em banco SQLite
- Estrutura organizada em Model, View e Controller (MVC)
- Interface simples via terminal

## Requisitos

- Python 3.7 ou superior
- [SQLAlchemy](https://www.sqlalchemy.org/) (instale com `pip install sqlalchemy`)

## Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. (Opcional) Crie e ative um ambiente virtual:
   ```sh
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # Linux/Mac:
   source venv/bin/activate
   ```

3. Instale as dependências:
   ```sh
   pip install sqlalchemy
   ```

## Como executar

No terminal, rode:
```sh
python view.py
```
Siga as instruções no menu para cadastrar ou logar usuários.

## Estrutura do projeto

```
├── model.py        # Definição da tabela Pessoa e conexão com o banco
├── controller.py   # Lógica de cadastro e login
├── view.py         # Interface de interação via terminal
└── README.md       # Este arquivo
```

## Licença

Este projeto é livre para uso educacional e pessoal.
