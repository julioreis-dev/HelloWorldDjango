# Helloworld, Django

Código produzido como parte do artigo sobre Desenvolvimento Web com Django da Python Academy. 
[Acesse aqui](https://pythonacademy.com.br/blog/desenvolvimento-web-com-python-e-django-introducao) 
essa cópia tem por finalidade subsidiar a produção de conteúdo dos alunos que orienta no aprendizado de Django.

## Instalação

Primeiro, recomenda-se a criação de um ambiente virtual. 

_Quer saber mais ambientes virtuais? Acesse [acesse o link para nosso post 
sobre ambientes virtuais no Python](https://pythonacademy.com.br/blog/python-e-virtualenv-como-programar-em-ambientes-virtuais)!_

Com seu ambiente virtual configurado, instale as dependências do projeto com:

Instale o Django
```bash
pip install Django
```

Crie o arquivo requirements.txt, que irá conter as depências do projeto
```bash
pip freeze > requirements.txt
```

Para criar as _Migrations_:

```bash
python manage.py makemigrations
```

Para efetivar as _Migrations_ no banco de dados:

```bash
python manage.py migrate
```

Para criar um super usuário:

```bash
python manage.py createsuperuser
```

## Execução

Para executar o servidor de testes do Django, execute:

```bash
python manage.py runserver
```

## Fique por dentro

Se gostou do conteúdo, siga a Python Academy no nosso blog e redes sociais!

- [Site](https://pythonacademy.com.br)
- [Facebook](https://facebook.com.br/pythonacademy/)
- [Blog](https://pythonacademy.com.br/blog/)

E até a próxima!
