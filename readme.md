[Pt-Br]

Esse projeto busca selecionar os filmes oferecidos no Imdb, analisá-los através da compreensão de seu dataset e, em sua etapa final, disponibilizar um algoritmo de recomendação.

O projeto é dividido em 3 etapas:
---------------------

1- Coleta e limpeza de dados:
---------------------


Parte responsável pelo acesso via API do repertório de filmes da IMBD. O dataset utilizado foi feito pelo kaggle, no entanto, ele está desatualizado. Resolvi atualizá-lo com o acesso via API dos últimos filmes lançados (2020/2021).

No fim, reuno o dataset em um único arquivo CSV

2- Análise e exploração dos dados (EDA):
---------------------

Nesta parte, isolo cada coluna para analisar suas possíveis relações e o que exatamente podemos inferir a partir disso. É importante essa parte para a compreensão devida do algoritmo de machine learning. Também aqui se encontram as visualizações.

3- Implementação do algoritmo de Machine Learning:
---------------------

O algoritmo utilizado é o de filtragem demográfica, recomandado pela propria IMDB. 


