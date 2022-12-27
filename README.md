
# Documentação do Desafio RPA BWA Global
## Configuração do ambiente virtual

A primeira coisa a fazer é clonar o repositório:

```sh
$ git clone https://github.com/JacksonRicardo/spotify.git
```

Crie um ambiente virtual para instalar as dependências e ative-o:

```sh
$ virtualenv env
$ source env/bin/activate
```

Em seguida, instale as dependências:

```sh
(env)$ pip install -r requirements.txt
```
Observe o `(env)` na frente do prompt. Isso indica que este terminal
sessão opera em um ambiente virtual configurado por `virtualenv2`.

Assim que o `pip` terminar de baixar as dependências:
```sh
(env)$ python manage.py runserver
```
E navegue até `http://127.0.0.1:8000/`.
