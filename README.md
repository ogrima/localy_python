

### Running Cloud-functions locally

<h4> </h4>

> Locally install the cloud-functions-framework

```shelscript
pip install functions-framework
```

#### Listener startup

> functions_framework --target=${NOME_DA_FUNCAO}

```shelscript
 functions_framework --target=hello_http
```
##### Test from the Command Line or Postman
```shelscript
 curl -X POST http://localhost:8080 -H "Content-Type:application/json"  -d '{"name":"Grima"}'
```
 

