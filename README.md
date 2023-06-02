# analytics_project

Projeto para mostrar uma configuração mínima mas profissional para desenvolvimento web

Neste projeto eu aprendi como criar uma aplicação Django simples e como exibir os dados no client side na forma de um painel de análises. O presente projeto se trata de uma integração do Django com o Flexmonster.

## Tecnologias usadas

1 - Python 3.11.3
2- Django
3 - SQLite
4 - Ambiente virtual
5 - Tabelas e gráficos do Flexmonster (biblioteca do JavaScript)

## Como rodar o programa?

1 - crie um ambiente virtual com o comando "python3 -m venv nome-que-quiser-dar";

2 - Ativo o ambiente virtual:
Linux -> source nome_do_ambriente/bin/activate
Windows -> Linux -> source nome_do_ambriente/script/activate

3 - Com o ambiente ativado, baixo o Django com o comando "pip install django";

4 - Dê o comando "python manage.py runserver";

5 - Com o servidor rodando, acesse o endereço http://127.0.0.1:8000/dashboard

## Considerações

Como o objetivo do estudo era mostrar como construir uma visualização interativa de dados dentro da aplicação, não nos preocupamos com a escolha do banco de dados. Usamos o SQLite – um banco de dados leve que acompanha o servidor de desenvolvimento para a web do Django.

Sabemos que esse banco de dados não é a escolha apropriada para o desenvolvimento em produção. Com o ORM do Django, você pode usar outros bancos de dados que usam a linguagem SQL, como o PostgreSQL ou o MySQL.
