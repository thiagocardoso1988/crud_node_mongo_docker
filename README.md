# crud_node_mongo_docker
Estudo simples sobre como utilizar mongodb

Para inserir dados no banco, pode-se usar esse curl:
````
curl -H "Content-Type: application/json" -d '{"marca":"ferrari", "modelo":812 }' -X POST http://localhost:9000/api/carros/novo
```

ou então fazer via Postman
