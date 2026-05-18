# Análise de Risco de Crédito com PySpark

Projeto desenvolvido com foco em análise de dados e machine learning para previsão de inadimplência utilizando dados financeiros, cadastrais e comportamentais.
O objetivo do projeto foi simular um pipeline de análise de risco de crédito semelhante aos utilizados em ambientes corporativos, aplicando conceitos de engenharia de dados, análise exploratória e modelagem preditiva utilizando PySpark.

---

# Objetivo

Desenvolver um modelo de classificação capaz de prever a probabilidade de inadimplência de clientes a partir de informações históricas de crédito.

Além da modelagem, o projeto também teve como foco:

- construção de pipelines de dados
- tratamento e transformação de dados
- análise exploratória (EDA)
- engenharia de atributos
- preparação de dados para machine learning
- análise de performance dos modelos

---

# Tecnologias Utilizadas

- Python
- PySpark
- SQL
- Jupyter Notebook
- Machine Learning
- ETL
- Git/GitHub

---

# Dataset

Dataset utilizado:
Home Credit Default Risk - Kaggle

Bases trabalhadas no projeto:

- application_train.csv
- bureau.csv
- previous_application.csv

O dataset contém informações:

- financeiras
- cadastrais
- comportamentais
- histórico de crédito

Variável alvo:
- TARGET
    - 0 → Adimplente
    - 1 → Inadimplente

---

# Pipeline do Projeto

O desenvolvimento foi dividido nas seguintes etapas:

1. Ingestão e entendimento dos dados
2. Análise exploratória (EDA)
3. Limpeza e tratamento de dados
4. Seleção de variáveis
5. Engenharia de atributos
6. Agregações e joins entre tabelas
7. Preparação para modelagem
8. Treinamento de modelos
9. Avaliação de métricas
10. Geração de insights

---

# Etapas Desenvolvidas

## Ingestão e Tratamento de Dados

- Leitura de arquivos CSV com PySpark
- Seleção de colunas relevantes
- Tratamento de valores nulos
- Padronização de dados
- Transformação de variáveis categóricas

## Análise Exploratória (EDA)

- Distribuição da variável alvo
- Identificação de outliers
- Análise de correlação
- Análise de variáveis financeiras e comportamentais
- Avaliação do desbalanceamento dos dados

## Engenharia de Atributos

Criação de variáveis derivadas para melhorar o poder preditivo do modelo, como:

- relação crédito/renda
- relação parcela/renda
- quantidade de créditos anteriores
- indicadores de atraso
- agregações históricas de crédito

## Modelagem

Modelos utilizados:

- Regressão Logística
- Árvore de Decisão
- Random Forest

Métricas avaliadas:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

# Competências e Conceitos Trabalhados

Durante o desenvolvimento do projeto foram aplicados conceitos relacionados a:

## Engenharia de Dados
- ETL
- Manipulação de grandes volumes de dados
- Processamento distribuído com PySpark
- Organização de pipelines

## Ciência de Dados
- EDA
- Feature Engineering
- Machine Learning
- Avaliação de modelos
- Classificação supervisionada

## Análise de Dados
- Geração de insights
- Qualidade de dados
- Tratamento de inconsistências
- Visualização e interpretação de métricas

---

# Resultados e Aprendizados

O projeto permitiu aprofundar conhecimentos em:

- análise de dados financeiros
- construção de pipelines de dados
- machine learning aplicado a risco de crédito
- processamento distribuído utilizando PySpark
- tratamento e preparação de dados para modelagem

Além da parte técnica, o projeto também contribuiu para o desenvolvimento de uma visão mais estruturada sobre fluxo analítico e tomada de decisão orientada a dados.

---

# Contato

LinkedIn: https://www.linkedin.com/in/isabelle-silva-severino-91b533261/
