# Projeto de Machine Learning Foundations
Este projeto foi desenvolvido como parte da disciplina Machine Learning Foundations do curso de MBA em Data Science & Advanced Analytics. O objetivo principal é explorar e aplicar diferentes algoritmos de aprendizado de máquina utilizando Python, com foco em Clusterização (K-means), Regressão Linear, Árvores de Decisão, e XGBoost.

## Descrição do Projeto
No projeto, realizamos análises e implementações utilizando diversos conjuntos de dados, com ênfase na compreensão do comportamento dos algoritmos em diferentes cenários e configurações. Exploramos o impacto de parâmetros, como ruído em datasets e ajuste de hiperparâmetros, na performance dos modelos.

## Bibliotecas Utilizadas:
  * matplotlib
* numpy
* pandas
* scikit-learn
    * KMeans
    * LinearRegression
    * DecisionTreeRegressor
    * train_test_split
    * StandardScaler
    * mean_squared_error, mean_absolute_error, r2_score
    * plot_tree
    * make_blobs, make_moons, make_circles
* xgboost

## Resultados
* Clusterização: Ao aumentar o ruído no dataset, os pontos tendem a se dispersar mais em torno de seus centroides, tornando mais difícil a formação de clusters claros.
* Regressão Linear: A Regressão Linear demonstrou bons resultados em cenários com relações lineares simples, mas o ajuste fino foi necessário para melhorar a precisão.
* Árvores de Decisão: Observamos que, sem a devida limitação de profundidade, as árvores podem superajustar os dados, criando modelos com baixo poder de generalização.
* XGBoost: O modelo de XGBoost se destacou por sua capacidade de capturar padrões complexos, especialmente quando comparado com a Regressão Linear.

## Contribuições
Este projeto foi realizado em grupo, com foco na exploração prática de algoritmos de aprendizado de máquina e no desenvolvimento de habilidades para análise de dados.
