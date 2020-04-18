### Create template

```sh
serverless create --template aws-nodejs
```

### Create test function

```sh
serverless create function -f testFunction --handler src/functions/testFunction.testFunction --path src/tests/
```

### Run tests

```sh
npm run test
```

### Creating new service from templates

```sh
serverless create --template-path ./template-aws-nodejs --path my-new-service
```
