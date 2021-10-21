# Will-It-Rain-Tomorrow
 Case

<img align="right" src="https://imageresizer.static9.net.au/wTyhl1oHYzHksDP61p_NFdoNr24=/750x0/https%3A%2F%2Fvms-network-images-prod.s3-ap-southeast-2.amazonaws.com%2F2020%2F08%2F306244%2F200808-WEATHER.jpg" height='300' width='450'>

## Project Status

Completed

## Project Description

Este case consiste no desenho da construção de um modelo e dos insights extraídos dos dados.

O conjunto de dados contém observações diárias do clima de algumas estações meteorológicas na Austrália.
 
As tabelas estão apartadas, pois são originadas de um outro instrumento e salvas em um sistema apartado.

A descrição das colunas se encontra no arquivo `data_dictionary.md`.

## Objetivo:

The objective of this project is to build a predictive model to determine whether or not it will rain tomorrow.

## The Steps

In this project, I used data cleaning, manipulation and visualization libraries as well as scikit-learn for model development.

During the project, after cleaning and statistical exploration, I observed cases of data leakage, redundancy and behavior patterns of variables.
.
Several iterations of predictive models such as the decision tree with different methods for variable selection were performed.

In this methodology, concepts of tree reducing size, depth analysis and error graph were used.

After that, the LGBM method was used with all numerical variables, with the most important variables using plot importance and with column reduction.

As next steps, I would create new column to add information to the model as a new column called “season of the year”.

## Conclusion

## Data

Os dados estão organizados em duas tabelas:

- `rain_data_aus.csv`: Contém a maior parte das informações de todas as estações.

- `wind_table_01.csv a wind_table_08.csv`: Contém informações sobre velocidade e orientação de ventos.

## Thanks
Raiana Rocha (https://www.linkedin.com/in/raiana-rocha/)


