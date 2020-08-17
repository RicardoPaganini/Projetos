
# Titanic

O Objetivo deste dataset era utilizar Machine Learning parta prever quais passageiros sobreviveriam ao naufrágio do Titanic.

Poderia ter utilizado PipeLine juntamente com GridSearch para TESTAR vários modelos, porém decidi usar apenas o SVM (Support Vector Machine) juntamente com o GridSearch para encontrar o melhor parâmetro que generalize o modelo.

Fonte do Dataset: [Kaggle](https://www.kaggle.com/c/titanic)

Visão geral:

Os dados estão divididos em 2 datasets principais e um modelo de Deploy:
- test.csv => Representa o conjunto de teste que deverá ser usado para verificar a performance do modelo
- train.csv => Representa o conjunto de treino e deverá ser utilizado para construir o modelo
- gender_submission => É o modelo de Deploy exigido para o desafio

Features / Colunas dos Datasets:

* Survival -> sobreviventes <- Está é a variável Target
Pclass -> Classe dos passageiros
Sex -> Sexo do passageiro
Age -> Idade do passageiro
Sibsp -> Número de irmãos, conjuges a bordo
Parch -> Número de pais, filhos
Ticket -> Número da passagem
Fare -> Tarifa do passageiro
Cabin -> Número da cabine
Embarked -> Porta de embarque
