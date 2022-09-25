# Lab-book-labenu

#### Sobre o projeto

O Labook é uma rede social com o objetivo de promover a conexão e interação entre seus mais diversos usuários. As pessoas poderão criar e curtir publicações.

Ela possui todas as funcionalidades mais comuns em redes sociais:

- **Cadastro**

O usuário pode se cadastrar informando um nome, email, senha. Não é possível criar dois usuários com o mesmo email.

- **Login**

Basta informar o email e a senha corretamente que o usuário poderá se logar na aplicação. Os endpoints de login e cadastro retornam **um** **token.**

- **Criação de um post**

A partir do token de autenticação fornecido no login, o usuário deve ser capaz de criar um post.

- **Deletar um post**

A partir do token de autenticação fornecido no login é feito uma checagem, se o usuário for do tipo 'normal' poderá deletar apenas os posts criados por ele mesmo, caso seja um 'admin' poderá deletar qualquer um.

- **Visualizar todos os posts (feed)** 

A partir do token de autenticação fornecido no login, o usuário pode visualizar todos os posts criados.

- **Dar like em um post**

A partir do token de autenticação fornecido no login, um usuário pode dar um like em um post (apenas um).

- **Dar dislike em um post**

A partir do token de autenticação fornecido no login, um usuário pode remover o seu like de um post. 



### Algumas tecnologias utilizadas

- mySQL
- Typescript

#### Algumas bibliotecas utilizadas:

- Express
- Knex
- Uuid
- JsonWebToken
- Bcryptjs
- mySQL
- Typescript
- Cors
- Dotenv



