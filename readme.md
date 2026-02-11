# 📊 Fintech Analytics Pipeline
## 📌 Objetivo

Construir um pipeline de dados analítico simulando uma fintech digital que oferece:

Conta digital

Cartão de crédito

Empréstimos pessoais

O projeto demonstra habilidades em:

Engenharia de Dados (ETL)

Modelagem Analítica (Star Schema)

SQL avançado

Construção de métricas de negócio

Organização em camadas (Bronze, Silver, Gold)

## 🏗 Arquitetura do Projeto

O pipeline segue uma estrutura simplificada inspirada em arquiteturas modernas de dados:

Bronze → Dados brutos gerados/simulados

Silver → Dados tratados e padronizados

Gold → Camada analítica com métricas de negócio

Fluxo:

Geração de Dados → Transformação (Python) → Modelagem (SQL) → Dashboard

## 🗂 Estrutura do Projeto
fintech-analytics-pipeline/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── src/
│   ├── generate_data.py
│   ├── transform.py
│   ├── load.py
│
├── sql/
│   ├── create_tables.sql
│   ├── analytics_queries.sql
│
├── dashboard/
│
└── README.md

## 🧱 Modelagem de Dados
Tabelas Fato

fact_transactions

fact_loans

fact_payments

Tabelas Dimensão

dim_customer

dim_date

dim_product

dim_risk_profile

A modelagem segue o padrão Star Schema, otimizado para consultas analíticas.

## 📈 Métricas Implementadas

Receita Mensal (MRR)

Volume Transacionado

Ticket Médio

Crescimento de Clientes

Taxa de Inadimplência

Receita por Segmento

## 🛠 Tecnologias Utilizadas

Python (pandas)

SQL

PostgreSQL / DuckDB

Git

Power BI / ferramenta de BI

## 🚀 Como Executar

Gerar os dados:

python src/generate_data.py


Executar transformações:

python src/transform.py


Criar tabelas e rodar queries SQL:

Executar os scripts da pasta /sql

Conectar ferramenta de BI ao banco para visualização.

## 🎯 Objetivo Profissional

Este projeto foi desenvolvido para demonstrar competências em:

Construção de pipelines de dados

Modelagem analítica orientada a negócio

Estruturação de dados para tomada de decisão

Organização e boas práticas em projetos de dados