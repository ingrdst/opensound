# OpenSound- Orientação a Objetos (Ruby on Rails)

## Funcionamento

Database open-source colaborativa de sons. As interfaces são distintas para visitante regular, usuário e developer. O visitante regular tem acesso somente à página inicial e pode explorar sons. O usuário cadastrado pode, além disso, fazer upload de sons e ter acesso às postagens privadas de teste (beta!) do aplicativo. Já o admin tem acesso aos outros usuários e à versão (omega!) de teste, podendo também criar, editar e deletar postagens de versões da página com os updates.

## Git Clone

```
    $ git clone https://gitlab.com/ingrdst/opensound.git
```

## Pré-Requisitos

* ruby 2.5.1
* ruby on rails 5.2.0
* rvm/rbenv

## Execução no Terminal

* cd ~ (pasta 'home')
* cd opensound -> project (pasta do projeto)
* bundle install (instala gems)
* rake db:migrate (gera tabela do banco)
* rails s (inicializa server)
* ctrl+c (finaliza server)

## Developers

* Ingrid C. G. S. Soares [Matrícula: 16/0125162]
* Alan Ronison de Lima e Silva [Matrícula: 16/0109256]
