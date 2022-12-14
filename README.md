## Questão de Negócio


Walmart, Inc., é uma multinacional estadunidense de lojas de
departamento que contratou este estudo para ter alguns apontamentos
e análises de suas lojas , para que chegue a conclusão de quais lojas
valem a pena ser expandidas.
Analisar quanto cada loja vende e realizar comparações entre elas, além disso buscar atributos que tenham certas correlações com as vendas das lojas.




# Entendimento do negócio
Os dados que nos foram disponibilizados (Walmart.cs) são bem relevantes para os apontamentos e conclusões necessárias para chegarmos ao resultado que o cliente deseja, porém é necessário análisar de maneira correta para obter o resultado desejado.



Insights importantes :
- *Qual o preço médio de venda semanal por loja?;*

- *Qual o atributo que tem maior correlação (positiva ou negativa) com o número de vendas? (E que faça sentido);*

- *Da loja com maior venda acumulada (soma de vendas de todo o período), quantas semanas do ano ele ultrapassou a média do período?;*

-  *Faça um gráfico com as vendas máximas, mínimas e médias de todas as lojas ao longo do tempo. Ressalte de alguma forma, o período de feriados mencionados acima.*

-  *Pensando na expansão de uma das lojas, que loja você escolheria e o por que?




# Coleta de dados
Os dados em sua grande maioria estão num formato correto para análise, o que pode ser feito é a formatação do campo Date e a quebra do mesmo em - Dia , Mês e Ano.



# Disponibilidade dos dados
- Store : Número da Loja
- Date : Semana de Venda
- Weekly_Sales : Venda Naquela Semana
- Holiday_Flag: Flag se é ou não semana com feriado (1 -
- Holiday Week :0 - Non-Holiday Week)
- Temperature : Temperatura do dia em °F
- Fuel_Price : Preço do combustível na região da loja
- CPI : Índice de preços ao consumidor
- Unemployment : Taxa de desemprego




# Exploração de dados

Pensando na expansão de uma das lojas, que loja você escolheria e o por que?
- A loja de Id 20, pois além de ser a loja que mais vendeu na somatória total de vendas por loja, a mesma vendeu a cima da média de lojas em todas as semanas,portanto o movimento de pessoas nessa loja é bem grande.





