# PProductions – Análise IMDB

Gerado em: 2025-08-31T15:21:37

## Sumário rápido

- Linhas x colunas: 999 x 45

## Valores ausentes (top 10)

Gross_num            0.169169
Gross                0.169169
Meta_score_num       0.157157
Meta_score           0.157157
Certificate          0.101101
Released_Year_num    0.001001
Unnamed:_0           0.000000
Genre_Film-Noir      0.000000
Genre_Comedy         0.000000
Genre_Crime          0.000000


## Correlações numéricas

                   IMDB_Rating_num  Meta_score_num  Released_Year_num  Runtime_min  No_of_Votes_num  Gross_num
IMDB_Rating_num           1.000000        0.271374          -0.133257     0.242751         0.479308   0.099393
Meta_score_num            0.271374        1.000000          -0.339291    -0.031604        -0.020091  -0.030480
Released_Year_num        -0.133257       -0.339291           1.000000     0.165765         0.246005   0.233270
Runtime_min               0.242751       -0.031604           0.165765     1.000000         0.172483   0.140002
No_of_Votes_num           0.479308       -0.020091           0.246005     0.172483         1.000000   0.589527
Gross_num                 0.099393       -0.030480           0.233270     0.140002         0.589527   1.000000


## Modelagem (previsão de IMDB_Rating)

- Modelo: ElasticNet com TF-IDF do Overview + numéricos + one-hot de categorias
- RMSE (holdout): 0.208
- R² (holdout): 0.342
- RMSE (CV 5-fold): 0.241

## NLP – inferência de gênero a partir do Overview

- F1-micro (holdout): 0.328
- Acurácia (holdout): 0.328


## Previsão para o exemplo (Shawshank): **9.30**
