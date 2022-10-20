# Curl Cheat Sheet

### Post json
```console
$ curl -v -X POST http://localhost:8080/ -H 'Content-Type: application/json' -d '{"key":"value"}'
```

### Delete
```console
$ curl -v -X DELETE http://localhost:8080/
```

### Upload multipart file
```console
$ curl -v -F file=@file.txt http://localhost:8080/
```
