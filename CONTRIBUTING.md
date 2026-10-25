# Como contribuir

A branch `main` é protegida: mudanças só entram por Pull Request.

1. **Abra uma issue** descrevendo a mudança (novo projeto ou correção).
2. **Crie uma branch** a partir da `main`: `feat/<descricao>`, `fix/<descricao>` ou `docs/<descricao>`.
3. **Faça commits** no padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/):
   `feat: adiciona projeto X`, `fix: corrige link do README`.
4. **Abra o Pull Request** preenchendo o modelo e citando a issue (`Closes #N`).
5. **Aguarde a revisão** do CODEOWNER e faça o merge. O GitHub Pages republica o site sozinho.

## Adicionando um projeto

Crie a pasta em `academicos/<repo>/` ou `pessoais/<repo>/` com um `README.md` no formato padrão
(resumo, contexto, tecnologias, destaques e links), adicione a linha na tabela do `README.md` raiz,
o card em `docs/index.html` e registre a mudança no `CHANGELOG.md`.
