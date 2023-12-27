 ### -Para construção do projeto ,foram utilizados dados  do governo federal, disponibilizados no portal da transparência.Utilizei os dados do Orçamento da Despesa do ano de 2022,devido a enorme  quantidade de dados,alimentei o dashboard com 10000 linhas do arquivo.
 

## Modelo dimensional
Para criação do Data Warehouse foi utilizado o Mysql Workbench. O modelo de relacionamento é o  STAR SCHEMA.

A imagem abaixo, exibe as tabelas dimensões e a tabela fato (modelo logíco).
##  ![modelo_dimensional_fisico](https://github.com/guilhermefritz/ModeloDW_orcamento_despesa/assets/126536587/00084f44-5545-4db8-889f-5c8e88345599)

### Load
Com o DW criado, utilizamos a linguagem de programação Python (python 3.6) para ler o conjunto de dados em formato .csv, devido a sua poderosa package de processamento de dados: Pandas.

## Dashboard
 -Para criar o dashboard utilizei o PowerBI.
 
Página 1
![image](https://github.com/guilhermefritz/ModeloDW_orcamento_despesa/assets/126536587/de385ce0-b5e6-4743-8ed9-7435a83169a6)
Página 2 
![image](https://github.com/guilhermefritz/ModeloDW_orcamento_despesa/assets/126536587/5a5fb45a-b977-40cc-b16d-0f0691cb1cdb)



