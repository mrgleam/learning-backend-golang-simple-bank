# Learning Backend

## Get started

macOS

```
brew install golang-migrate
brew install sqlc
```

## DB schema
https://dbdiagram.io/d/62597fb72514c9790339a7ac

## DB Migration

Create migration file

```
migrate create -ext sql -dir db/migration -seq init_schema
```

Ref: https://dev.to/techschoolguru/design-db-schema-and-generate-sql-code-with-dbdiagram-io-4ko5
