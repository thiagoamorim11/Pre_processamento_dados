# PRÉ PROCESSAMENTO DE DADOS

- O objetivo deste Pré procesamento será identificação dos valores fora do padrão e remove-lôs do conjunto.
Com esse valores removidos do dataset, os estudos posteriores serão mais lineares.
- Outra aplicação seria para encontrar os ***outliers*** do conjunto e realizar estudos somente com eles.

## Dados com anomalias:
![projeto](https://github.com/thiagoamorim11/Pre_processamento_dados/blob/main/anomalias.PNG)
- Obs: As anomalias são os pontos que estão fora do range do gráfico.
 
### Procedimentos:

1. Encontrar a ***média*** do conjunto.
2. Encontrar o ***destivo padrão***.
3. Definir a regra que será aplicada para exclusão dos valores discrepantes.
   - Ficou definido as seguintes regras (fronteria de exclusão):
   - Valores acima: ***média + 2 * desvio padrão***.
   - Valores abaixo: ***média - 2 * desvio padrão***.
4. Encontrar os valores que atendem aos critérios das regras.
5. Excluir os valores.
6. Plotar os dados e validar o dataset.

## Dados sem anomalias:
![projeto](https://github.com/thiagoamorim11/Pre_processamento_dados/blob/main/sem_anomalias.PNG)


#### Bibliotecas utilizadas:
- numpy
- matplotlib
- seaborn
