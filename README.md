# Gin starter

A minimal [Gin](https://gin-gonic.com) server in Go.

## Run it locally

```sh
go run .
```

Then open http://localhost:8080. `GET /health` answers `ok` for health checks.

## Deploying

| Step | Command |
| --- | --- |
| Build | go build -o out . |
| Start | ./out |

## Environment variables

| Variable | Meaning |
| --- | --- |
| `PORT` | Port to listen on. Default: 8080. |

## License

MIT
