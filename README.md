# PortfolioHUB

[![Versão](https://img.shields.io/github/v/tag/lucasmalinski/Bootcamp1-Intermediaria?label=vers%C3%A3o)](CHANGELOG.md) [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-065f46)](https://lucasmalinski.github.io/Bootcamp1-Intermediaria/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-lucasmalinski-0a66c2)](https://www.linkedin.com/in/lucasmalinski)

Repositório central do meu portfólio: reúne, organiza e documenta meus projetos acadêmicos e pessoais
em Engenharia e Ciência de Dados. O código de cada projeto vive no seu próprio repositório; aqui ficam
a documentação padronizada e os links.

**Página:** https://lucasmalinski.github.io/Bootcamp1-Intermediaria/
**LinkedIn:** https://www.linkedin.com/in/lucasmalinski
**Currículo:** https://lucasmalinski.dev

## Estrutura

```
PortfolioHUB/
├── academicos/   # projetos de disciplinas da graduação (CEUB)
├── pessoais/     # projetos pessoais, cursos externos e desafios técnicos
└── docs/         # site publicado via GitHub Pages
```

Cada pasta de projeto tem um `README.md` no mesmo formato: resumo, contexto, tecnologias, destaques e links.


## Projetos Acadêmicos

| Projeto | Tecnologias | Documentação |
|---|---|---|
| [Análise Hospitalar SUS-DF](https://github.com/lucasmalinski/analise-hospitalar-sus-df) | Python, GitHub Actions, Azure Blob Storage | [README](academicos/analise-hospitalar-sus-df/README.md) |
| [Warehouse de Risco de Crédito + Machine Learning](https://github.com/lucasmalinski/risco-de-credito) | PostgreSQL, SQL, Python | [README](academicos/risco-de-credito/README.md) |
| [YAHT — Yet Another Habit Tracker](https://github.com/lucasmalinski/yaht) | Python, JSON, unittest | [README](academicos/yaht/README.md) |
| [Modelagem de Dados Avançada — EVG](https://github.com/lucasmalinski/modelagem_dados_EVG) | Power BI, Power Query (M), Modelagem dimensional | [README](academicos/modelagem_dados_EVG/README.md) |
| [Dashboard de Performance Cinematográfica (IMDB)](https://github.com/lucasmalinski/painel_dados_imdb) | Power BI, Power Query (M), DAX | [README](academicos/painel_dados_imdb/README.md) |
| [Bolsa Família — Painel com RLS](https://github.com/lucasmalinski/bolsafamilia-rls) | Power BI, DAX, Row-Level Security | [README](academicos/bolsafamilia-rls/README.md) |
| [Monitoramento de Tráfego](https://github.com/lucasmalinski/monitoramento_trafego) | Python, Estruturas de dados | [README](academicos/monitoramento_trafego/README.md) |
| [Laboratórios de Fundamentos de Big Data](https://github.com/lucasmalinski/ceub-bigdata) | MongoDB, Jupyter, Python | [README](academicos/ceub-bigdata/README.md) |
| [Estruturas de Dados — Ciência de Dados](https://github.com/lucasmalinski/Estruturas_Dados_CD) | Python | [README](academicos/Estruturas_Dados_CD/README.md) |
| [Bootcamp I — PortfolioHUB](https://github.com/lucasmalinski/Bootcamp1-Intermediaria) | Git, GitHub, GitHub Pages | [README](academicos/bootcamp-I/README.md) |

## Projetos Pessoais

| Projeto | Tecnologias | Documentação |
|---|---|---|
| [CVM Extractor](https://github.com/lucasmalinski/cvm_extractor) | Python, Flask, Pandas | [README](pessoais/cvm_extractor/README.md) |
| [Financial Sentiment Pipeline](https://github.com/lucasmalinski/financial-sentiment-pipeline) | Python, BeautifulSoup4, Pandas | [README](pessoais/financial-sentiment-pipeline/README.md) |
| [BanVic — Pipeline de Dados](https://github.com/lucasmalinski/banvic_indicium) | Airflow, Meltano, Docker | [README](pessoais/banvic_indicium/README.md) |
| [Infradata](https://github.com/lucasmalinski/infradata) | Python, Conda, GeoPandas | [README](pessoais/infradata/README.md) |
| [CS50x — Exercícios](https://github.com/lucasmalinski/backup_cs50x) | C, Python, SQL | [README](pessoais/backup_cs50x/README.md) |
| [Currículo Web](https://github.com/lucasmalinski/lucasmalinski.github.io) | HTML, CSS, GitHub Pages | [README](pessoais/curriculo-web/README.md) |

## Versionamento

O repositório segue versionamento semântico com tags Git:

- `v1.0`: estrutura inicial, READMEs por projeto e página no GitHub Pages
- `v1.1`: changelog, badges e versão na página (ver [CHANGELOG.md](CHANGELOG.md))
- `v1.2`: declaração de uso de IA
- `v2.0`: implantação — segurança e fluxo de colaboração

Mensagens de commit seguem o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/) (`feat:`, `docs:`, `fix:`).

## Segurança e colaboração

- A branch `main` é protegida: mudanças só entram por Pull Request.
- Políticas e reporte de vulnerabilidades em [SECURITY.md](SECURITY.md).
- Fluxo de contribuição, padrão de commits e como adicionar projetos em [CONTRIBUTING.md](CONTRIBUTING.md).

## Uso de Inteligência Artificial

Em conformidade com o Código de Ética do UniCEUB (Art. 7º, §2º), declaro que usei o **Claude (Anthropic)**,
via Claude Code, como apoio na montagem deste repositório:

- **Estrutura e redação:** geração da estrutura de pastas, dos READMEs de cada projeto (resumidos a partir
  dos READMEs originais dos meus repositórios) e da página em `docs/`.
- **Versionamento:** apoio na criação dos commits e das tags `v1.0` e `v1.1` (identificados com
  `Co-Authored-By: Claude` no histórico).
- **Implantação (v2.0):** o Claude foi o guia da implantação: plano, políticas de segurança, fluxo de colaboração, documentação do processo e slides
  da apresentação.

Os projetos listados, seu código e sua documentação original são de minha autoria (ou coautoria, quando
indicado).
