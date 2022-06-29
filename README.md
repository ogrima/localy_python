

### Running Cloud-functions locally

<h4> </h4>

> Instalar localmente o cloud-functions-framework

```shelscript
pip install functions-framework
```

#### Startando o listener

> functions_framework --target=${NOME_DA_FUNCAO}

```shelscript
 functions_framework --target=hello_http
```
##### Testando via terminal ou postman
```shelscript
 curl -X POST http://localhost:8080 -H "Content-Type:application/json"  -d '{"name":"Grima"}'
```
 

