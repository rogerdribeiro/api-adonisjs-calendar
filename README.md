# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

Requisitos funcionais 

O usuário deve poder criar uma conta com nome, e-mail e senha; 
O usuário deve poder se autenticar na aplicação com e-mail e senha; 
O usuário deve poder alterar seu nome e senha informando a senha antiga, a senha nova e a confirmação da senha nova; 
O usuário deve poder cadastrar eventos em seu calendário com título, localização, data e horário; 
O usuário deve poder listar os eventos cadastrados por data; O usuário deve poder excluir um compromisso; 
O uário deve poder compartilhar um compromisso informando o e-mail do destinatário. 
Assim que compartilhado, o destinatário deve receber todas informações do evento por e-mail;
