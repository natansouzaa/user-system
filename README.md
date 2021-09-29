## User System

---

### Teste do model

- [x] Should be able to create an user with all props

---

### Testes do repositório

- [x] Should be able to create new users
- [x] Should be able to list all users
- [x] Should be able to find user by ID
- [x] Should be able to find user by e-mail address
- [x] Should be able to turn an user as admin

---

### Testes de useCases

- [x] Should be able to create new users
- [x] Should not be able to create new users when email is already taken
- [x] Should be able to turn an user as admin
- [x] Should not be able to turn a non existing user as admin
- [x] Should be able to get user profile by ID
- [x] Should not be able to show profile of a non existing user
- [x] Should be able to list all users
- [x] Should not be able to a non admin user get list of all users
- [x] Should not be able to a non existing user get list of all users

---

### Testes das rotas

<details>
  <summary>Rota - [POST] /users</summary>

  - [x] Should be able to create new users
  - [x] Should not be able to create new users when email is already taken
</details>
<details>
  <summary>Rota - [PATCH] /users/:user_id/admin</summary>

  - [x] Should be able to turn an user as admin
  - [x] Should not be able to turn a non existing user as admin
</details>
<details>
  <summary>Rota - [GET] /users/:user_id</summary>

  - [x] Should be able to get user profile by ID
  - [x] Should not be able to show profile of a non existing user
</details>
<details>
  <summary>Rota - [GET] /users</summary>

  - [x] Should be able to list all users
  - [x] Should not be able to a non admin user get list of all users
  - [x] Should not be able to a non existing user get list of all users
</details>
