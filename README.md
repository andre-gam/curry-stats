# Análise Curry Stats

Análise descritiva e preditiva das estatísticas de Stephen Curry da temporada 2015-2016 até 2022-2023.

Foram obtidos a base de dados de todas as partidas que Curry jogou em temporada regular da temporada 2015-2016 até a temporada atual 2022-2023.
Nessa base temos as seguintes informações:

- Data da Partida
- Adversário
- Mandante ou visitante
- Resultado da partida
- Número de pontos
- Número de bolas de 3 convertidas
- Número de lance livres convertidos
- Turnovers
- Assistências
- Roubos de Bola

Em paralelo foram obtidas bases com as informações de classificação de cada time na temporada para considerar a força dos adversários. Também foi obtida as estatísticas avançadas de cada time na temporada para obter o deFG% (Rating defensivo) de cada time. 

Com essas informações, foram obtidas as métricas de cada estatística de curry por temporada e na carreira, podendo ser considerado apenas para jogos mandantes, visitantes, adversários com aproveitamento acima de 50%, etc.

Por fim, um modelo de classificação preditiva é utilizado utilizando redes neurais, para avaliar a probabilidade dele performar um valor acima da média em determinada estatística do jogo. 
