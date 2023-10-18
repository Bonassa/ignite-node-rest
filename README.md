# ignite-node-rest
REST API project made on Rocketseat Ignite course


## Testing with Vitest
This application implements E2E tests, in backend applications E2E is made by simulating the actions of a frontend app interacting with the exposed level

Doc - [https://vitest.dev/]

```bash
  npm install -D vitest
```

### Supertest
Supertest is a library to test the server without need to raise the full server
Doc - [https://www.npmjs.com/package/supertest]

```bash
  npm install -D supertest

  npm install -D @types/supertest
```

## Compiling TS to JS for deploy
To be possible to deploy a node application, we need to compile from TS to JS.

### TSUP
```bash
  npm install -D tsup
```