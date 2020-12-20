# DRE_LSTM_Forecast
Modelo Preditivo para DRE - Rolling Forecasting

## Objetivo do Projeto
O objetivo do trabalho é efetuar a elaboração do Rolling Forecasting de maneira mais assertiva apoiando a tomada de decisão estratégica diante de cenário econômico adverso, com perdas de lucro  no resultado apresentado em sua DRE do 1º TRIM/2020 refletidas pelo efeito da pandemia. A empresa em questão é do setor do Varejo Não Alimentício - Vestuário.

Desta forma, a empresa poderá traçar objetivos de tomada de decisão estratégica, de maneira a desenvolver um plano de ação com alinhamento de todos os seus departamentos, para maximizar seus recursos e efetuar os ajustes necessários para a continuidade e funcionamento da empresa, e cumprir com seus compromissos de curto, médio e longo prazo.

## Métodos Utilizados
A base de dados foi pre processada com análise de valores faltantes, análise exploratória de dados, análise de correlação das variáveis; foi efetuada uma filtragem das empresas pertencentes ao mesmo segmento de negocio da empresa Alvo. 

Como método de modelagem foi utilizado a Regressão Logística e a Árove de Decisão, para predição se a empresa em estudo terá Lucro ou Prejuízo do exercício findo 2020.
Adicionalmente foram utilizados métodos de Deep Learning, sendo Redes Neurais Artificiais - MLP (Multilayer Perceptron), e Redes Neurais Recorrentes - LSTM(Long Short Term Memory).

## Principais Resultados
Os Modelos de Regressão Logística e Árvore de Decisão obtiveram bom desempenho de classificação, porém não conseguiram responder a pergunta de negócio inicial, se a empresa Alvo apresentaria ou não Lucro no final do exercício, prevendo o efeito Pandemia.
No entanto o Modelo LSTM conseguiu realizar uma predição com um Erro Absoluto médio em níveis aceitáveis, para levar em consideração o efeito pandemia.
