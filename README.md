### Services WireMock

This project is a basic example for use the wiremock in your stand-alone application.


```bash
java -jar wiremock-jre8-standalone-2.27.2.jar --port=28080
```

for launch the mocks based in JSON files(based in the syntax defined wiremock)

* alone request
* stage the request
* all methods: **POST**, **PUT**, **DELETE**, **GET**

this version include the http://localhost:port/reload.html, that call the process for
reload all definitions in the mock.

### Test api-mock

For test the expose API has been create a collection used insomnia, see the directory :  
**test-api/insonmina-mock-collection**



