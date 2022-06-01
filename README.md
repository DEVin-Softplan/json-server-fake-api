# Projeto contendo umplementação de uma FakeAPI utilizando [json-server](https://www.npmjs.com/package/json-server)

## Para implementação foi utilizado como base os artigos [Simulando uma API REST com JSON Server de maneira simples](https://www.fabricadecodigo.com/json-server/) e [Building a Fake and JWT Protected REST API with json-server](https://www.techiediaries.com/fake-api-jwt-json-server/)

## Para instalar as depenencias do projeto deve ser executado o comando:

```
npm install
```

## Para inicializar o servidor deve ser executado o comando:

```
npm run start:auth
```

## Rotas

| Request | URL        | Detalhes                          |
| ------- | ---------- | --------------------------------- |
| GET     | /foruns    | Busca todos os fóruns             |
| GET     | /foruns/1  | Busca um forum                    |
| POST    | /foruns    | Salva um forum                    |
| PUT     | /forun/1   | Atualiza dos os dados do forum    |
| PATCH   | /forun/1   | Atualiza parte dos dados do forum |
| DELETE  | /forun/1   | Remove um forum                   |
| GET     | auth/login | Efetua o login                    |

### As rotas vão ser compostas pelo endereço base (localhost:3001) mais o recurso que dev ser acessado com por exemplo foruns.
