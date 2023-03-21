# api-ui testrepository
## REST API Documentation
[Swagger UI](https://trzcode.github.io/api-ui)

Publishing:
1. Add swagger to folder "docs/swaggers"
2. Edit docs/swagger-initializer.js and add in urls array the new swagger file and a name
`urls: [
        { url: "swaggers/petstore.json", name: "Petstore (JSON)"},
        { url: "swaggers/petstore.yaml", name: "Petstore (YAML)"},
        { url: "swaggers/thecodebuzz.json", name: "TheCodeBuzz (JSON)"}
    ]`

## Async API Documentation
[Github action doku](https://github.com/asyncapi/github-action-for-generator)