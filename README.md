### Introduction

- The following program is a backend server, that implements REST
  endpoints for authentication, and other operations. 

- It is capable of interacting with `postgresql` database using **Prisma
  ORM**.

### Manual

1. Run `npm install` to install the dependencies.

2. Create a development environment file `.env.development` inside the root
folder with the following attributes:

```
DATABASE_URL=postgresql://_user_:_password_@localhost:5432/_database_name_
JWT_SECRET=_define_a_custom_secret_for_creating_JWT_tokens_
NODE_ENV=development/production
```

3. Setup `postgres` SQL server.

4. Run the backend usign `npm run develop` to start the server in
   development environment,

Scripts provided:

- To update the database in development mode use `npm run migrate:develop`
- To run the development version `npm run develop`.
- To run the production build `npm run start`.
- To test the application `npm test`.
- To build a production version `npm run build`.
