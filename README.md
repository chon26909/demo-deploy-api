# demo-deploy-api

Simple Go API using Echo with a /health endpoint.

Run locally:

```bash
go mod tidy
go run main.go
```

The server reads PORT from `.env` (use `PORT=8080` as default).
