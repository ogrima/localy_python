

### Run Cloud-functions locally

> pip install functions-framework

> curl -X POST http://localhost:8080 -H "Content-Type:application/json"  -d '{"name":"Jane"}'

> curl --location --request POST 'http://localhost:8080/' --header 'Content-Type: application/json' --data-raw '{"name":"Jane"}'

> functions_framework --target=hello_http