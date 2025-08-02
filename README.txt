📘 README — Projeto PySpark
Este repositório contém cinco notebooks organizados por etapas de um pipeline de dados com PySpark, desenvolvidos no Google Colab. Cada notebook aborda uma fase específica: da ingestão à otimização de dados.

📂 1. leitura_escrita.ipynb
Objetivo: Leitura e escrita de arquivos com PySpark

Leitura de arquivos CSV e Parquet

Inferência de esquema e tratamento de cabeçalhos

Escrita de dados em formato Parquet

Criação de tabelas temporárias com Spark Catalog

📂 2. preparacao.ipynb
Objetivo: Preparação e transformação de dados para machine learning

Extração de mês e ano a partir de datas

Indexação de variáveis categóricas (StringIndexer)

Vetorização de features numéricas (VectorAssembler)

Normalização (Normalizer) e Redução de dimensionalidade (PCA)

Separação em conjuntos de treino e teste

Regressão linear para prever comentários

📂 3. tratamento.ipynb
Objetivo: Limpeza e pré-processamento de dados

Remoção de valores nulos e duplicados

Conversão de tipos de dados

Renomeação de colunas

Criação de colunas auxiliares como Interaction

Salvamento de dados tratados

📂 4. agragacao.ipynb
Objetivo: Técnicas de agregação e análise exploratória

Contagens, médias, mínimos e máximos por categoria (Keyword)

Cálculo de variância e média acumulativa com Window Functions

Contagem de valores únicos

Análises temporais por ano e mês

📂 5. otimizacao.ipynb
Objetivo: Otimização de joins e queries com particionamento

Uso de repartition e coalesce

Criação de tabelas temporárias e joins com spark.sql

Análise dos planos de execução com .explain()

Filtros e projeções aplicadas antes do join

Salvamento do join otimizado em Parquet

✅ Requisitos
Google Colab ou ambiente com PySpark instalado

Arquivos .csv e .parquet utilizados em cada notebook

Python 3.x