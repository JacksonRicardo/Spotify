
# Documentação do Desafio RPA BWA Global
## Configuração do ambiente virtual

A primeira coisa a fazer é clonar o repositório:

```sh
$ git clone https://github.com/JacksonRicardo/spotify.git
```

Crie um ambiente virtual para sistemas ou subsistemas Linux (WSL) instalar as dependências e ative-o:

```sh
$ virtualenv env
$ source env/bin/activate
```
Em caso de erro no ambiente virtual, rode os seguintos comandos:
```sh
$ pip3 uninstall virtualenv
$ sudo pip3 install virtualenv
$ virtualenv .env --always-copy
$ source .env/bin/activate
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
navegue até `http://127.0.0.1:8000/`

## Criar Conta

1. Para criar a conta, clique no botão "Sign up for Spotify"
2. Preencha as informações: What's your name?, What's your email?, Create a password, Confirm your password.
3. Aperte o botão Sign Up.


 


