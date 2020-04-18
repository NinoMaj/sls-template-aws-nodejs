### Create template

```sh
serverless create --template aws-nodejs
```

### Create test function

```sh
serverless create function -f testFunction --handler src/functions/testFunction.testFunction --path src/tests/
```

### Create createUser function

```sh
serverless create function -f createUser --handler src/functions/createUser.createUser --path src/tests/
```

### Run tests

```sh
npm run test
```

### Creating new service from template

```sh
serverless create --template-path ./template-aws-nodejs --path my-new-service
```

### Connecting service with app

```sh
serverless
```
