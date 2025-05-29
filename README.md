# 📦 Previsão de Qualidade de Produtos com Machine Learning

## 📄 Descrição do Projeto
Este projeto aplica técnicas de aprendizado de máquina para prever a qualidade de produtos (originalmente vinho tinto), utilizando o conjunto de dados público Wine Quality disponibilizado pelo UCI Machine Learning Repository.

O objetivo principal é desenvolver modelos preditivos capazes de identificar a qualidade de produtos com base em variações químicas e sensoriais, ajudando empresas na garantia da qualidade, controle de processos e tomada de decisões.

---

## 🔍 Etapas do Projeto

### 1. Aquisição e Pré-processamento dos Dados
- Importação e exploração do conjunto de dados
- Normalização das variáveis para melhorar o desempenho dos modelos
- Divisão dos dados em conjuntos de treino e teste
- Redução opcional de dimensionalidade com Análise de Componentes Principais (PCA)

### 2. Treinamento de Modelos
Três modelos de aprendizado de máquina foram treinados e avaliados:

- ✅ Regressão Logística  
- ✅ Random Forest
- ✅ XGBoost  

Cada modelo foi avaliado utilizando métricas como:
- Acurácia
- Relatório de classificação
- Matriz de confusão

### 3. Melhoria de Modelos de Aprendizado de Máquina
- Busca de hiperparâmetros com **GridSearchCV** e **RandomizedSearchCV**
- Identificação dos melhores parâmetros para cada modelo
- Avaliação de desempenho nos conjuntos de treino e teste
- Análise da matriz de confusão para entender erros e acertos

---

## 📈 Resultados
- O modelo Random Forest teve o melhor desempenho, com acurácia aproximada de 78%
- As variáveis mais relevantes para previsão foram: acidez volátil, teor alcoólico e dióxido de enxofre

---

## 🧰 Tecnologias Utilizadas
- Python (Jupyter Notebook)
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn

---

## 📎 Arquivos Incluídos
- `Trabalho_Final.ipynb`: Notebook com todo o pipeline do projeto
- Apresentacao_Wine_Quality.pptx: Apresentação resumida dos resultados.
- Dataset utilizado (público da UCI)

---

## 📷 Visualização
![image](https://github.com/user-attachments/assets/61d6601b-5ed5-4ba3-ad14-601b02c0ba87)
![image](https://github.com/user-attachments/assets/0fb770bd-cf58-4243-862f-f6a214ee9c45)
![image](https://github.com/user-attachments/assets/71329c8f-74d6-457b-9ada-807c669a285e)

---

## 🔗 Fonte dos Dados
- [Wine Quality Data Set - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)

---

## 👨‍💻 Autor
João Vicente 
[LinkedIn](https://www.linkedin.com/in/joaovita)  
