# 🍷 Red Wine Quality Classifier

Este projeto utiliza Machine Learning para classificar vinhos tintos como "bons" ou "ruins" com base em suas propriedades físico-químicas. A base de dados utilizada foi extraída do [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009).

## 📊 Objetivo

O objetivo principal é analisar os fatores que influenciam na qualidade do vinho e desenvolver um modelo preditivo binário, onde:

- **1 = Vinho bom** (qualidade ≥ 7)
- **0 = Vinho ruim** (qualidade < 7)

## 📁 Dados

A base de dados contém 12 colunas com atributos numéricos como:

- `fixed acidity`, `volatile acidity`, `citric acid`
- `residual sugar`, `chlorides`
- `free sulfur dioxide`, `total sulfur dioxide`
- `density`, `pH`, `sulphates`, `alcohol`
- `quality` (alvo da classificação)

## 🔍 Análise Exploratória

- Verificação de valores nulos
- Estatísticas descritivas
- Histograma da variável `quality`
- Matriz de correlação (com destaque para variáveis como `alcohol`, `volatile acidity`, `citric acid`)

## 🧠 Modelo de Machine Learning

Foi utilizado o modelo `RandomForestClassifier` para prever a qualidade do vinho. A base foi dividida em treino e teste (80/20).

### ✅ Acurácia obtida

O modelo obteve uma acurácia de aproximadamente **`92.8`** (substitua com o valor real obtido no seu código).

## 📈 Visualizações

- Histograma da variável `quality`
- Histograma da variável target (após binarização)
- Heatmap de correlação entre as variáveis
