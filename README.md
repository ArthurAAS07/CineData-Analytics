# CineData Analytics

Projeto desenvolvido para a atividade de Engenharia de Dados, com foco na construção de um pipeline de dados utilizando **Databricks, PySpark, Delta Lake e Arquitetura Medalhão**.

O objetivo do projeto é realizar a ingestão, tratamento e organização de dados relacionados a filmes, avaliações, métricas financeiras, métricas de engajamento, gêneros, pessoas e empresas.

---

## Arquitetura

O projeto foi estruturado seguindo a Arquitetura Medalhão:

```text
Arquivos CSV + API Banco Central
              |
              v
           LANDING
              |
              v
           BRONZE
              |
              v
           SILVER
              |
              v
            GOLD
