# GoHubAPI
A hub rest api written in golang for all my personal projects to interact with

# Usage 

```shell
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

```shell
curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET"
```




