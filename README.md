# 📱 Tellapp

Tellapp is a real-time messenger backend built with Go, Fiber, Bun, and WebSockets, following hexagonal architecture principles.

---

## Stack
- [Go](https://go.dev) Main language
- [Air](https://github.com/air-verse/air) Hot reload for development
- [Bun](https://bun.uptrace.dev/) Bun ORM
- [Godotenv](https://github.com/joho/godotenv) Godotenv
- [Fiber](https://gofiber.io/) Fiber
- [PostgreSQL](https://www.postgresql.org/) PostgreSQL
- [Websocket](https://docs.gofiber.io/contrib/websocket/) Websocket

---

## Requirements

- Go 1.25+
- PostgreSQL 16+

---

## Clone and run in local

```bash
# Clone repo
git clone https://github.com/lautarok/tellapp

# Install deps
go mod tidy

# Install air
go install air

# Run
air
```