## Run App

```go
go run .
```
Install dependencies If is required

## Send Book

- -POST http://localhost:3000/book

Exmaple:
```sh
curl --location --request POST 'http://localhost:3000/book' \
--header 'Content-Type: application/json' \
--data-raw '{
    "title": "Brandon",
    "author": "Test 1"
}'
```

Get All Books

```sh
curl http://localhost:3000/allbooks
````
Response
```json
[
  {
    "ID": 2,
    "CreatedAt": "2017-03-14T00:00:00-06:00",
    "UpdatedAt": "2017-03-14T00:00:00-06:00",
    "DeletedAt": null,
    "title": "Brandon",
    "author": "Test 3"
  }
]
````
