# crud-autenticacao-django

Desenvolvimento de uma API RESTful com interface gráfica utilizando Python e Django. Este sistema permite o login e logout de usuários
cadastrados com todas as checagens de autenticação disponibilizadas pelo Django Admin, também permite o cadastro de clientes utilizando POST, listagem de clientes utilizando GET, update de clientes utilizando POST, e remoção de clientes cadastrados utilizando DELETE.

O frontend consiste em design simples, somente para testar e ver as alterações.




## Tecnologias Utilizadas (Backend)

- Python 3

- Django 2.1

- SQLite

## Tecnologias Utilizadas (Frontend)

- HTML

- CSS

- Bootstrap

- Font Awesome


## Utilização

1. Realizar o clone com `git clone https://github.com/brunoalvaress/crud-autenticacao-django.git`
2. Instalar a dependência Django-Bootstrap-Form com `pip install django-bootstrap-form` (um gerenciador de dependências não foi utilizado devido a possuir apenas uma)
3. Configurar a porta em que deseja, a padrão é 8000
4. Criar um administrador com `python manage.py createsuperuser`
5. Acessar http://localhost:8000/ e realizar o login
