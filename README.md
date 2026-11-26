Projeto: Detecção de Fraudes em Cartões de Crédito

Sobre o projeto

Este projeto utiliza Machine Learning para identificar transações fraudulentas em cartões de crédito.

O principal desafio é o desbalanceamento dos dados: aproximadamente 99,83% das transações são normais e 0,17% são fraudulentas.

Por isso, utilizamos principalmente Recall, Precisão e F1-score para avaliar os modelos.

Dataset

Base utilizada: Credit Card Fraud Detection.

Link: https://storage.googleapis.com/download.tensorflow.org/data/creditcard.csv

O dataset contém informações sobre transações, incluindo:

- Time: momento da transação.
- Amount: valor da transação.
- V1 até V28: variáveis transformadas por PCA.
- Class: classificação (0 = normal, 1 = fraude).

Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- SHAP
- Google Colab

Modelos utilizados

- Regressão Logística
- Random Forest
- XGBoost

Etapas do projeto

1. Exploração dos dados.
2. Preparação e padronização.
3. Separação entre treino e teste.
4. Treinamento dos modelos.
5. Comparação das métricas.
6. Curvas ROC e Precision-Recall.
7. Ajuste do limiar de decisão.
8. Otimização com GridSearchCV.
9. Explicabilidade com SHAP.

Conclusão

O projeto demonstra como utilizar Machine Learning para detectar fraudes em cartões de crédito, considerando o desbalanceamento dos dados e a importância de avaliar corretamente os modelos.

Também utiliza SHAP para compreender quais variáveis influenciam as previsões.

Autor

Projeto desenvolvido como estudo de Machine Learning e análise de dados.
