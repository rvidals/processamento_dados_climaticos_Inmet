# Processamento de dados climáticos obtidos pela base de dados do INMET

Esse projeto traz uma análise de dados simples no intuito de gerar valores médios de temperatura média e temperatura máxima para algumas estações metereológicas (convecional e automáticas) presentes no Distrito Federal.

Essa motivação se deu a partir do módulo Urban Cooling do modelo InVEST, que tem como finalidade avaliar a ilha de calor em áreas urbanas. Nesse módulo, há duas entradas importantes que para tal, foi necessário analisar algumas estaçõe presentes no DF, 
a estação automática presente na Estação Ecológica Águas Emendadas (ESECAE) e as estações convêncionais presentes na sede dp Instituto Nacional de Metereologia (INMET). 

As duas entradas que o módulo Urban Cooling solicita são:
  - Temperatura do Ar de Referência: Temperatura do ar da área rural
  - Efeito UHI: Temperatura máxima na área urbana.

O código está estruturado em algumas funções que possuem regras de negócios específicas para o tratamento dos dados de temperatura. 

As bibliotecas usadas no desenvolvimento desse script são amplamente utilizadas na análise e ciência de dados, utilizando python: 

  - os
  - pandas
  - plotly
