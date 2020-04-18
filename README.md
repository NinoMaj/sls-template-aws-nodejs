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
