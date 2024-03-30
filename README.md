# GraphQL and GO

## References

- [GQLGen](https://gqlgen.com/) - Type-safe GraphQL for Go

## Using gqlgen

To initialize gqlgen config and generate models:

```bash
go run github.com/99designs/gqlgen init

go mod tidy
```

To generate models:

```bash
go run github.com/99designs/gqlgen generate
```

## Run

To run the server, execute the following command:

```bash
go run server.go
```

Then, open the browser and go to `http://localhost:8080/`.
