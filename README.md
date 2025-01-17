# Projeto Curso de Data Science

## Descrição do Projeto

Este projeto aplica técnicas de aprendizado de máquina para prever a qualidade do vinho tinto, utilizando o conjunto de dados público *Wine Quality* disponibilizado pelo UCI Machine Learning Repository. O objetivo principal é desenvolver modelos preditivos capazes de identificar a qualidade do vinho com base em variações químicas e sensoriais. 

## Etapas do Projeto

### 1. Aquisição e Pré-processamento dos Dados

- Normalização das variáveis para melhorar o desempenho dos modelos.
- Divisão dos dados em conjuntos de treino e teste.
- Redução opcional de dimensionalidade com Análise de Componentes Principais (PCA).

### 2. Treinamento de Modelos

Três modelos de aprendizado de máquina foram treinados e avaliados:

- **Regressão Logística**
- **Floresta Aleatória (Random Forest)**
- **XGBoost**

Cada modelo foi avaliado utilizando métricas como acurácia e relatório de classificação, para entender seu desempenho em relação aos dados.

### 3. Melhoria de Modelos de Aprendizado de Máquina

Nesta etapa, realizamos a busca de hiperparâmetros para otimização dos modelos usando **GridSearchCV** e **RandomizedSearchCV**, permitindo:

- Identificação dos melhores hiperparâmetros para cada modelo.
- Avaliação do desempenho do modelo nos conjuntos de treino e teste.
- Análise da matriz de confusão para entender os erros e acertos dos modelos.
