# Previsão de Remessas
Para melhor entendimento da sequência de passos, leia a modelagem na seguinte ordem:
- [Linear Regression](<Linear Regression.ipynb>)
- [Time Series](<Time Series.ipynb>)
- [Machine Learning ](<Machine Learning.ipynb>)

## Excel com forecasts
O Excel com o forecast para setembro de 2020 de todos os modelos para todos os clusters está no arquivo [forecast-set-2020.xlsx](forecast-set-2020.xlsx).

## Acurácia
A acurácia de cada modelo é mostrada na tabela abaixo e foi estimada pelo erro absoluto médio calculado no conjunto de teste (observações não vistas pelo modelo em treinamento). A mediana da série de cada cluster é informada para auxiliar interpretação.
|Cluster                       | reg-model2|reg-model3 |ts-model1 |ts-model2 |ml | mediana|
|:------------------------------|:---------|:-----------|:-----------|:-----------|:-----------|:-----------|
|A|97|	77|	129|	105|	202| 541|
|B|144|	107|	161|	113|	198|713|
|C|98	|116	|121	|110	|134|255|
|D|122	|86	|138|	78	|235|533|
|E|241|	161|	229|	185|	593|968|
|F|241	|172	|824	|925	|1267|3533|
|J|42	|26|	34	|28	|31|184|
|K|63|	42	|49|	53|	63|396|
|L|22|	28	|21	|27	|33|133|
|M|75|	44|	96|	65|	155|567|



## Gráficos de forecast
Ao todo foram treinados 50 modelos: 5 para cada cluster. Nos gráficos abaixo estão comparados os forecasts feitos por cada modelo para cada cluster.

**Clique no gráfico para vê-lo ampliado!**

<img src='graficos/A-comparacao.png'>
<img src='graficos/B-comparacao.png'>
<img src='graficos/C-comparacao.png'>
<img src='graficos/D-comparacao.png'>
<img src='graficos/E-comparacao.png'>
<img src='graficos/F-comparacao.png'>
<img src='graficos/J-comparacao.png'>
<img src='graficos/K-comparacao.png'>
<img src='graficos/L-comparacao.png'>
<img src='graficos/M-comparacao.png'>

