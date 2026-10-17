# Análise Hospitalar SUS-DF

> Painel analítico do desempenho da rede hospitalar do SUS no Distrito Federal (2022–2025), pensado como instrumento de vigilância para o Conselho de Saúde do DF.

**Contexto:** Projeto final — Business Intelligence II (CEUB), em dupla com Erick Cardoso Mendes

## Tecnologias

- Python
- GitHub Actions
- Azure Blob Storage
- Parquet
- Power BI

## Destaques

- Pipeline ETL idempotente em Python consumindo a API da Saúde-DF (~985 mil AIHs)
- Orquestração agendada via GitHub Actions e data lake em Azure (Parquet, ~30 MB vs ~300 MB em CSV)
- 11 KPIs em cinco eixos: produção, qualidade, financeiro, equidade e resolutividade

## Links

- **Repositório:** [https://github.com/lucasmalinski/analise-hospitalar-sus-df](https://github.com/lucasmalinski/analise-hospitalar-sus-df)

---

[← Voltar ao PortfolioHUB](../../README.md)
