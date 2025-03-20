# 🔍 Comparação de Modelos para Predição de Falhas em Máquinas
Este repositório contém uma análise comparativa de diferentes modelos de aprendizado de máquina para prever falhas em máquinas com base em dados coletados de sensores. O objetivo é avaliar o desempenho de cada modelo e identificar a melhor abordagem para prever falhas com antecedência, possibilitando manutenção preditiva eficiente.

## 📊 Conjunto de Dados
O conjunto de dados utilizado é composto por diversas variáveis que representam as condições operacionais e ambientais das máquinas monitoradas. As variáveis disponíveis podem incluir temperatura, vibração, pressão, entre outras características relevantes para a predição de falhas.

## 🔎 Modelos Avaliados
* Decision Tree
* Random Forest
* AdaBoost
* Gradient Boosting
* SGB
* SVM

#### Instruções Repassadas para este projeto

1) Realize o processo de gridsearch para classificação do dataset para  arvore de decisão, random forest, adaboost, gradientBoost, SGB e SVM e retorne a melhor parametrização de cada modelo.
2) Você realizou um gridsearch da melhor parametrização possível para os modelos da questão 1, utilizando a a função GridSearchCV.
Em um unico script faça uma implementação que, em vez de um gridseach para parametrização de modelos, seja um gridsearch que retorne o melhor 
modelo por meio de um método Best_Model que você vai implementar, com base no desempenho de todos os modelos. Utilize a acurácia como
fator de decisão para retorno do modelo de melhor desempenho. Crie também uma função auxiliar que retorna o classification report e matriz de confusão de todos os modelos.
Crie uma estrutura de projeto encapsulada e organizada para que seja executáda pelo avaliador, com tutorial de execução. 
No relatório, discuta sobre os resultados.
