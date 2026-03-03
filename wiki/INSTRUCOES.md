# Wiki do Assignment - API com Gin

## Objetivo

Completar e evoluir uma API REST simples usando Go + Gin, garantindo que todos os testes passem no GitHub Actions.

---

## Passo a passo para o aluno

1. Faça o clone do repositório gerado pelo GitHub Classroom.
2. Instale Go (versão 1.22 ou superior).
3. Baixe dependências:

```bash
go mod tidy
```

4. Rode os testes:

```bash
go test ./... -v
```

5. Implemente as mudanças pedidas no assignment.
6. Crie novos testes para validar os novos comportamentos.
7. Faça commit e push para o repositório.

---

## Como funciona a correção automática

- A cada `push` na branch `main` ou em um `pull request`, o GitHub Actions executa:

```bash
go mod tidy
go test ./... -v
```

- Se algum teste falhar, o check ficará vermelho.
- Se todos passarem, o check ficará verde.

---

## Critérios sugeridos de avaliação

- Implementação correta dos endpoints solicitados.
- Cobertura por testes automatizados.
- Código organizado e legível.
- Pipeline do GitHub Actions passando.

---

## Dica para depuração

Use `go test` com verbose para identificar rapidamente o teste que falhou:

```bash
go test ./... -v
```
