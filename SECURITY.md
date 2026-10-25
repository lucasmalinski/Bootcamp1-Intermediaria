# Política de Segurança

O PortfolioHUB é um site estático (HTML e CSS) publicado pelo GitHub Pages. Não tem backend, login nem
coleta de dados pessoais, e o repositório não guarda segredos (tokens, senhas ou chaves).

## Controles adotados

- **Branch `main` protegida** (ruleset): sem push direto, sem force-push e sem exclusão.
  Toda mudança entra por Pull Request.
- **CODEOWNERS**: toda mudança passa pela revisão do mantenedor.
- **Secret scanning e push protection**: o GitHub bloqueia pushes que contenham credenciais.
- **Conta**: autenticação em dois fatores (2FA) na conta do mantenedor.

## Como reportar um problema

Abra uma issue descrevendo o problema. Nunca inclua senhas ou tokens na descrição.
