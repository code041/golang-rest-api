# Projeto simples de API com Gin (GitHub Classroom)

Este repositório é um template de assignment para GitHub Classroom com:

- API REST em Go usando Gin.
- Testes automatizados com `go test`.
- Workflow do GitHub Actions para validar os testes automaticamente.

## Como executar localmente

```bash
go mod tidy
go run .
```

A API sobe em `http://localhost:8080`.

## Endpoints

- `GET /health` → `{ "status": "ok" }`
- `GET /hello` → `{ "message": "Olá, mundo!" }`
- `GET /hello?name=Ana` → `{ "message": "Olá, Ana!" }`

## Rodar testes

```bash
go test ./... -v
```

## GitHub Actions

O workflow está em `.github/workflows/test.yml` e roda em pushes para `main` e em pull requests.
