# Project01-SupervisedTraining
Esse repositório teve como objetivo inicial o desenvolvimento de um modelo de classificação para prever se iria chover ou não no próximo dia de acordo com dados históricos de temperatura, umidade e precipitação, utilizando o dataset [usa_rainfall](https://kaggle.com/datasets/waqi786/usa-rainfall-prediction-dataset-2024-2025). O modelo foi desenvolvido utilizando a biblioteca Scikit-learn e o algoritmo Random Forest.


## Projeto inicial [Projeto Rainfall](./rainfall_descontinuado_por_baixa_qualidade_de_dataset/usa_rainfall_classificacao.ipynb)
O projeto inicial foi desenvolvido em Python e utilizou a biblioteca Scikit-learn para o treinamento do modelo. Utilizamos vários algoritmos de classificação, como Decision Tree, Random Forest e Logistic Regression e mais outros, para comparar o desempenho de cada um deles. O modelo foi avaliado utilizando métricas como acurácia, precisão e recall e f1-score.

Porém o projeto foi finalizado mas não foi utilizado para a apresentação do trabalho da disciplina por conta do baixíssimo desempenho dos modelos por conta da baixa qualidade do dataset e a baixa quantidade de dados. A partir deste ponto partimos para outro dataset e outro projeto de classificação.


## Projeto Final [Projeto Satisfação do Cliente em Voos](./fly_satisfaction/fly_satisfaction_final.ipynb)
O projeto final foi feito com um [dataset de avaliação de satisfação de clientes em voos de avião](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/discussion/336813). Nele utilizamos os mesmo algoritmos de classificação, porém adicionamos mais métricas e passos de pré-processamento, validação e análise de desempenho. 

O modelo foi avaliado utilizando as métricas de acurácia, precisão, recall e f1-score, curva ROC-AUC, curva Precisão vs Recall. Além disso, utilizamos a validação cruzada para avaliar o desempenho do modelo e o BayesSearchCV para fazer a busca dos melhores hiperparâmetros. O modelo foi treinado e testado utilizando os algoritmos Classificador Ridge, Regressão Logística, Classificador SGD, Floresta Aleatória, Árvore de Decisão e K Vizinhos Mais Próximos. 

Com os hiperparâmetros otimizados, o modelo que teve o melhor desempenho foi a Árvore de Decisão, com a métrica escolhida de f1-score de 0.9393. O modelo foi salvo em um arquivo pickle para ser utilizado posteriormente. Pelo resultado apresentado o modelo teve um desempenho muito bom.
