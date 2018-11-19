# Probabilidade e Estatística - ECOM021

# Lab 0

# 1. Quais anos estão incluídos neste conjunto de dados? Quais são as dimensões da base de dados e quais são os nomes das colunas ou variáveis?

De 1940 a 2002. 63 linhas e 3 colunas. year, 'boys' e 'girls'.

# 2. Como estas contagens se comparam aos dados de Arbuthnot? Eles estão numa escala similar?

Não. A quantidade de nascimentos em 'arbuthnot' é bem menor que a de 'present'.

# 3. A observação de Arbuthnot de que os meninos nascem numa proporção maior que as meninas se mantém nos EUA?

Sim.

# 4. Crie um gráfico que mostre a razão de meninos para meninas para cada ano do conjunto de dados. O que você pode verificar?

present-boys-girs-ratio.png
arbuthnot-boys-girls-ratio.png

# 5. Em qual ano se verifica o maior número de nascimentos nos EUA?

> which.max(present$boys + present$girls)
[1] 22
> present$year[22]
[1] 1961
