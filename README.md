# Previsão de Remessas
Para melhor entendimento da sequência de passos, leia a modelagem na seguinte ordem:
- [Linear Regression](<Linear Regression.ipynb>)
- [Time Series](<Time Series.ipynb>)
- [Machine Learning ](<Machine Learning.ipynb>)

## Excel com forecasts
O Excel com o forecast para setembro de 2020 de todos os modelos para todos os clusters está no arquivo [forecast-set-2020.xlsx](forecast-set-2020.xlsx).

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

|variable                       |class     |description |
|:------------------------------|:---------|:-----------|
|A                    |double    | Value indicating if the booking was canceled (1) or not (0) |
|B                      |double    | Number of days that elapsed between the entering date of the booking into the PMS and the arrival date |
|C                         |double    | Number of adults|
|D                       |double    | Number of children|
|E                        |character | Country of origin. Categories are represented in the ISO 3155–3:2013 format |
|F              |double    | Value indicating if the booking name was from a repeated guest (1) or not (0) |
|J             |character | Code of room type reserved. Code is presented instead of designation for anonymity reasons |
|K                            |double    | Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights |
|L      |double    | Number of special requests made by the customer (e.g. twin bed or high floor)|
|M      |double    | Number of special requests made by the customer (e.g. twin bed or high floor)|
