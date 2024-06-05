# Aplicação de Lista de Tarefas

Esta é uma aplicação web de lista de tarefas desenvolvida usando Python, Django e SQLite3.

## Funcionalidades

- Criar uma nova tarefa
- Visualizar a lista de tarefas
- Marcar uma tarefa como concluída
- Editar uma tarefa
- Excluir uma tarefa

## Pré-requisitos

- Python 3.9 ou superior
- Django 5.0.6
- SQLite3

## Instalação

1. Clone o repositório:


~~~
   $   git clone https://github.com/seu-usuario/seu-projeto.git 
~~~


2. Crie e ative o ambiente virtual:


~~~
   $    python -m venv venv
        source venv/bin/activate  # No Windows, use: venv\Scripts\activate
~~~


3. Instale as dependências:


~~~
   $    pip install -r requirements.txt
~~~


4. Aplique as migrações do banco de dados:


~~~
   $    python manage.py migrate
~~~

5. Inicie o servidor de desenvolvimento:


~~~
   $    python manage.py runserver
~~~


6. Acesse a aplicação no navegador:


~~~
   $    http://127.0.0.1:8000/
~~~


## Estrutura do Projeto

- `setup/`: Diretório do projeto Django.
- `todos/`: Aplicação Django responsável pela lista de tarefas.
- `models.py`: Definição dos modelos de dados.
- `views.py`: Implementação das views (funções ou classes).
- `urls.py`: Configuração das URLs da aplicação.
- `templates/`: Diretório com os templates HTML.
- `requirements.txt`: Lista de dependências Python do projeto.

## Contribuição

Sinta-se à vontade para fazer sugestões ou reportar problemas. Contribuições são bem-vindas!


