- [@openapitools/openapi-generator-cli npm package](https://www.npmjs.com/package/@openapitools/openapi-generator-cli)

- Command to generate open api client for dart

    ```bash
    npm ci && npm run gen
    ```

- Command to fix enum values

    ```bash
    cd dart; find . -name "\*\_enum.dart" -exec sed -i "" "s/data.toString()/data/g" {} \;
    ```