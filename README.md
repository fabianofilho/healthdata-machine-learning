# healthdata-machine-learning
plano de Estudos para Healthdata e Machine Learning

## tabela de conteúdos
- [x]  [o que é? :interrobang:](#o-que-é)
- [ ]  [por que usar? :interrobang:](#por-que-usar)
- [ ]  [como usar? :interrobang:](#como-usar)
- [ ]  [assuntos introdutórios :interrobang:](#assuntos-introdutórios)
  - [ ] o que é machine learning?
  - [ ] tipos de dados do seu dataset
  - [ ] tipos de aprendizagem
  - [ ] uma breve introdução ao Machine Learning
  - [ ] as 10 principais Aplicações de Machine Learning na saúde
- [ ] dataframes
- [ ] classificação x predição
- [ ] estatística
- [ ] workflow de Machine Learning
- [ ] modelos de Machine Learning
- [ ] [interpretabilidade de modelos](https://christophm.github.io/interpretable-ml-book/)
- [ ] engenharia de características
- [ ] melhoria da performance dos modelos

## o que é?
um plano de estudo desde a estatística até a aplicação de aprendizado de máquina em bases de dados abertas.

## por que usar?
existem, atualmente, muitas formas de se aplicar a ciência de dados e machine learning na sáude.

entretanto, são escassas e descentralizadas as iniciativas e as aplicações para o estudo e desenvolvimento de profissionais da saúde com essa tecnologia.

## como usar?
temos abaixo uma estrutura de tópicos, e você deve enfrentar os itens em ordem de cima para baixo... não precisa ver todos os links, mas você tem que entender cada um dos tópicos.

# assuntos introdutórios
- [O que é machine learning?](https://medium.com/brasil-ai/o-que-%C3%A9-machine-learning-94cc71c2a6e3)
- [Tipos de dados do seu dataset](https://medium.com/brasil-ai/antes-de-come%C3%A7armos-a-falar-sobre-tipos-de-aprendizados-que-veremos-no-pr%C3%B3ximo-artigo-%C3%A9-ea5b04685913)
- [Tipos de aprendizagem](https://medium.com/brasil-ai/tipos-de-aprendizagem-1c1339f73bdf)
- [Inteligência Artificial e Machine Learning aplicados à saúde](https://saudebusiness.com/ti-e-inovacao/inteligencia-artificial-e-machine-learning-aplicados-saude/)
- [Aplicações de inteligência artificial e machine learning em saúde](https://www.youtube.com/watch?v=y8em7JhKwhU)

## estudos brasileiros publicados
- [Machine learning para análises preditivas em saúde: exemplo de aplicação para predizer óbito em idosos de São Paulo, Brasil](http://www.scielo.br/scielo.php?pid=S0102-311X2019000904002&script=sci_arttext)

# dataframes/python
- [Pandas merge dataframes](https://telegra.ph/pandas-merge-10-28)

# [estatística](https://towardsdatascience.com/statistical-modeling-the-full-pragmatic-guide-7aeb56e38b36)
- EDA (Análise de dados exploratória)
- Correlação
- Odds Ratio

# classificação x regressão x predição
- [Classificação x Regressão](https://machinelearningmastery.com/classification-versus-regression-in-machine-learning/)
- [Predição x Classificação no olhar da Probabilidade](https://www.fharrell.com/post/classification/)
- [Modelagem preditiva](https://machinelearningmastery.com/gentle-introduction-to-predictive-modeling/)

# [workflow de Machine Learning](https://towardsdatascience.com/workflow-of-a-machine-learning-project-ec1dba419b94)
1. juntando informação
2. pré-processamento de dados
3. pesquisa do modelo que será melhor para o tipo de dados
4. treinando e testando o modelo
5. avaliação

# aplicação de modelos 
## cancer
### variáveis
- Sexo
### melhor modelo
- XGboost

## diabetes
### variáveis
- Sexo
### melhor modelo
- XGboost

## health disease
### variáveis
- Sexo
### melhor modelo
- XGboost

## stroke
### variáveis
- Sexo
### melhor modelo
- XGboost


------------------------
# modelos

## machine learning supervisionado

### árvores de decisão (_decision trees_)
- [Árvores de Decisão](https://medium.com/machine-learning-beyond-deep-learning/%C3%A1rvores-de-decis%C3%A3o-3f52f6420b69)
- [ÁRVORE DE DECISÃO. EXEMPLO COMPLETO](https://www.youtube.com/watch?v=_ICNdRrl68k)
- [Um tutorial completo sobre modelagem baseada em árvores de decisão (códigos R e Python)](https://www.vooo.pro/insights/um-tutorial-completo-sobre-a-modelagem-baseada-em-tree-arvore-do-zero-em-r-python/)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Decision%20Trees.ipynb)

### árvores aleatórias (_random forest_)
- [Random Forest From Scratch](https://machinelearningmastery.com/implement-random-forest-scratch-python/)
- [Random Forest in Python](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0)

### LR - regressão logística
- [O que é uma regressão logística?](http://carloscollares.blogspot.com/2011/05/o-que-e-uma-regressao-logistica.html)
- [EB - Aula 6 Teórica - Regressão logística](https://www.youtube.com/watch?v=Fs8LhzhEMwI)
- [EB - Aula 6 prática - Regressão Logística](https://www.youtube.com/watch?v=CVL5vj1N1U8)
- [Você sobreviveria no Titanic? Um exemplo de Regressão Logística](http://www.abgconsultoria.com.br/blog/voce-sobreviveria-no-titanic-um-exemplo-de-regressao-logistica/)
- [Regressão Logística na Eleição](https://medium.com/@silviocesar_75950/regress%C3%A3o-log%C3%ADstica-na-elei%C3%A7%C3%A3o-3d8011469712)

 ### adaboost
- [Estudo do algoritmo adaboost de aprendizagem de máquina aplicado a sensores e sistemas embarcados](http://www.teses.usp.br/teses/disponiveis/3/3152/tde-12062012-163740/pt-br.php)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Adaboost.ipynb)

### xgboost
- [Exploring XGBoost](https://towardsdatascience.com/exploring-xgboost-4baf9ace0cf6) 
- [Interpretable Machine Learning with XGBoost](https://towardsdatascience.com/interpretable-machine-learning-with-xgboost-9ec80d148d27)

### KNN - K-Vizinhos Mais Próximos (_K-Nearest Neighbors_)
- [KNN (K-Nearest Neighbors) #1](https://medium.com/brasil-ai/knn-k-nearest-neighbors-1-e140c82e9c4e)
- [KNN (K-Nearest Neighbors) #2](https://medium.com/brasil-ai/knn-k-nearest-neighbors-2-f2ab9e5662b)
- [KNN #3 — Codando nosso classificador de câncer de mama](https://medium.com/brasil-ai/knn-3-codando-nosso-classificador-de-câncer-de-mama-eadd3b41b54b)
- [Machine Learning em Português (Aula 11) - Explicando K-NN (Regressão e Classificação)](https://www.youtube.com/watch?v=bzIsfLgTEQw)
- [Machine Learning em Português (Aula 15) - K-Nearest Neighbors (Regressão - Parte 2)](https://www.youtube.com/watch?v=Cz6NCHSY0Z0)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/KNN.ipynb)

### naive bayes
- [Teorema de Bayes](https://www.youtube.com/watch?v=9OOZf4klOeM)
- [Teorema de Bayes - Aula 1: Características (Probabilidade a Priori, Condicional e Conjunta)](https://www.youtube.com/watch?v=78R1yNVGnSk&t=244s)
- [Teorema de Bayes - Aula 2: a Posteriori](https://www.youtube.com/watch?v=mTfI6ggVNyQ&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J&index=2)
- [Teorema de Bayes (Aula 3) - Usando o teorema para calcular sorteio de uma roleta](https://www.youtube.com/watch?v=Buvp2kFnIbs&index=3&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 4) - Explicando o cálculo do vídeo anterior](https://www.youtube.com/watch?v=WZLf5sSIzAc&index=4&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 5) - Caminho pela raridade do item no Diablo (Parte 1)](https://www.youtube.com/watch?v=dNLqMphjUjw&index=5&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 6) - Caminho pela raridade do item (Parte 2)](https://www.youtube.com/watch?v=X1I29qqXszs&index=6&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 7) Vídeo Correção - Nomenclaturas](https://www.youtube.com/watch?v=Wcb4_pnADEE&index=7&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 8) - Bayes Sequencial](https://www.youtube.com/watch?v=Y1DnDnCYeQU&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J&index=8)
- [Naive Bayes | Carlos Baldove | Papo Reto](https://www.youtube.com/watch?v=3HJVRBEMwoU)
- [Classificador Naive bayes em 50 linhas](https://imasters.com.br/desenvolvimento/classificador-naive-bayes-em-50-linhas)

### SVM - máquina de vetores de suporte (_support vector machine_)
- [Uma Introdução às Support Vector Machines](https://www.mql5.com/pt/articles/584)
- [Explicar o algoritmo SVR](https://pt.stackoverflow.com/a/40149/20728)
- [Máquina de Vetores de Suporte - SVM](https://www.youtube.com/watch?v=4Zh7UeHqHvc)
- [SVM - Support Vector Machine Linear, Não Linear - Teoria](https://www.youtube.com/watch?v=cB__Oa85htg)

### LM - regressão linear
- [Regressão linear simples](https://medium.com/ensina-ai/regress%C3%A3o-linear-simples-4cac67c4488c)
- [Regressão Linear (Parte 1) - Machine Learning em Português (Aula 12)](https://www.youtube.com/watch?v=MgtIdBrf0v8)
- [Regressão Linear (Parte 2) - Machine Learning (Aula 13)](https://www.youtube.com/watch?v=jh4m0WN-n48)
- [Machine Learning (Aula 21) - Regressão Linear no R](https://www.youtube.com/watch?v=Km1HoKVkd6k)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Linear.ipynb)

### regressão multivariada
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Multilinear.ipynb)

### regressão polinomial
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Polinomial.ipynb)

### perceptron
- [Redes neurais roots #1 — introdução](https://medium.com/ensina-ai/redes-neurais-roots-1-introdu%C3%A7%C3%A3o-ffdd6f8b9f01)
- [Redes neurais roots #2— Treinamento](https://medium.com/ensina-ai/redes-neurais-roots-2-treinamento-3161a439c4f3)
- [Redes neurais roots #3 — Show me the code](https://medium.com/ensina-ai/redes-neurais-roots-3-show-me-the-code-e56359310083)
- [Aula - Perceptron e Adaline](https://www.youtube.com/watch?v=6yYUc6nU3Cw&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=2&t=0s)
- [Máquinas de vetores-suporte ](ftp://ftp.dca.fee.unicamp.br/pub/docs/vonzuben/ia353_1s13/topico8_1s2013.pdf)
- [Máquina de vetores de suporte(código)](http://artificiencia.com/aprenda/maquina-de-vetores-de-suporte/)

### função de custo
- [Função de Custo (Regressão Linear) - Machine Learning em Português (Aula 14)](https://www.youtube.com/watch?v=jSaJjshIAUw)
- [Calculando a Função de Custo (Regressão Linear) - Machine Learning (Aula 15)](https://www.youtube.com/watch?v=kHfhMsCoUus)
- [Valor Mínimo da Função de Custo (Regressão Linear) - Machine Learning (Aula 16)](https://www.youtube.com/watch?v=ikmxun1t-HM)

### gradiente descendente (_Gradient Descent_)
- [Gradient Descent (Regressão Linear - Parte 1) - Machine Learning (Aula 17)](https://www.youtube.com/watch?v=xdDL_8Sg6JI&t=404s)
- [Calculando Gradient Descent Parte 1 (Regressão Linear) - Machine Learning (Aula 18)](https://www.youtube.com/watch?v=6lbX-MI5B6M)
- [Como verificar o Gradient Descent (Regressão Linear) - Machine Learning (Aula 20)](https://www.youtube.com/watch?v=yraCrOa3mzk)

### MLP - multilayer perceptron
- [Redes Neurais, Perceptron Multicamadas e o Algoritmo Backpropagation](https://medium.com/ensina-ai/redes-neurais-perceptron-multicamadas-e-o-algoritmo-backpropagation-eaf89778f5b8)

### CNN - redes neurais convolucionais
- [Redes Neurais profundas Convolucionais - Parte I - Fundamentos](https://www.youtube.com/watch?v=n4rmrZg1_58&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=5&t=1s)
- [Redes Neurais profundas Convolucionais - Parte II - Arquiteturas Modernas](https://www.youtube.com/watch?v=0XUrLfQXzcw&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=5)
- [Parametrização de redes neurais profundas](https://www.youtube.com/watch?v=qDmKwmkc4vs&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=7)

- Extra: [Arquiteturas de redes neurais profundas para detecção de objetos](https://www.youtube.com/watch?v=BhwppCyV2iI&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=8)

### rede neurais recorrentes
- [Redes Neurais Recorrentes (RNN) - LSTM, GRU, Seq2seq e Mecanismos de atenção](https://www.youtube.com/watch?v=94hG00EJFNo&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=6)
- [Redes Neurais Recorrentes(tem código)](https://www.youtube.com/watch?v=bDDP0m4jjH0)
- [Keras - Usando redes neurais LSTM para classificar sentimentos](https://www.youtube.com/watch?v=bIcadBu--u8)

## machine learning não-supervisionado

### PCA - análise de componentes principais (_Principal Component Analysis_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/PCA.ipynb)

### LDA - análise discriminante linear (_Linear Discriminant Analysis_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/LDA.ipynb)

### k-Médias (_K-Means_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/K-Means.ipynb)

### DBSCAN
- [DBSCAN Python Example: The Optimal Value For Epsilon (EPS)](https://towardsdatascience.com/machine-learning-clustering-dbscan-determine-the-optimal-value-for-epsilon-eps-python-example-3100091cfbc?source=bookmarks---------1-----------------------)

----------------------
# [interpretabilidade de modelos](https://christophm.github.io/interpretable-ml-book/)
- Feature Importance
- LIME
- SHAP

# engenharia de características (_feature engenieering_)
- Features
- Instances

# melhoria da performance dos modelos
- Grid Search
- Random Search


#### créditos: 

esse plano de estudos foi inspirado em [awesome-machine-learning-portugues](https://github.com/fabianofilho/awesome-machine-learning-portugues).

adiferença é aqui aqui você encontrará conteúdos aplicados a saúde para seus estudos.

_se você gostou deste projeto, por favor me dê uma estrela_ &#9733; _e ajude a divulgar o material._ ;)

<a href="https://twitter.com/intent/tweet?text=Plano%20de%20estudos%20para%20Machine%20Learning%20na%20saude%20https://github.com/fabianofilho/healthdata-machine-learning" target="_blank">
Compartilhe no Twitter</a> :bird:

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
