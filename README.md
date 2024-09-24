# Teste Prático - Estágio em Python

## Objetivo

Este teste tem como objetivo avaliar os conhecimentos básicos em Python e programação, incluindo a capacidade de manipular e processar dados, gerar arquivos Parquet e desenvolver dashboards interativos com o Streamlit.

## Descrição

Você deverá realizar as seguintes tarefas:

1. **Leitura e Processamento dos Dados:**
   - Ler o arquivo `vendas.csv` com o pandas ou similar
   - Converter as colunas para os tipos de dados corretos (ex: datas em formato datetime, valores monetários como float).
   - Identificar e tratar dados inválidos (nulos, duplicados ou inconsistentes).
   
2. **Salvar em Formato Parquet:**
   - Após processar os dados, salve-os em um arquivo no formato **Parquet** usando pandas, PySpark ou biblioteca similar.

3. **Criar um Dashboard com Streamlit:**
   - Utilizando o Streamlit, crie um dashboard interativo com as seguintes funcionalidades:
     - Total de vendas por categoria de produto.
     - Evolução das vendas ao longo do tempo.
     - Top 5 produtos mais vendidos.
     - Análise de vendas por cliente.
4. **Faça uma PR do seu código**
   - Utilizar boas práticas de desenvolvimento de código e ambiente virtuais será um plus

## Estrutura Esperada do Projeto

O projeto deve seguir a seguinte estrutura de pastas e arquivos:
├── vendas.csv
├── processar_dados.py
├── dashboard.py
├── requirements.txt
├── README.md
└── data
    └── vendas.parquet

