# mba-usp-esalq-tcc-dsa232
Coletânea de arquivos utilizados para gerar dados sintéticos e realizar um ajuste binominal neles.
1. sintese_dados.ipynb: código para gerar o dataset e salvar como "df_rmn.csv".
2. df_rmn.csv: dataset exportado de sintese_dados.ipynb e a ser importado por RegLogBinom_stepwise_rmn.ipynb.
3. RegLogBinom_stepwise_rmn.ipynb: carregamento do dataset df_rmn.csv, análise exploratória e seleção de variáveis independentes.
4. RegLogBin_eesentials_rmn.ipynb: carregamento do dataset df_rmn.csv, ajuste binomial, matriz de confusão e curva ROC.
