# Dados de crimes de Los Angeles (LA)

O dataset utilizado nessa EDA é fornecido pelo *Los Angeles Police Department* (LAPD) ([clique aqui e tenha acesso a base](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)) e contém dados relacionados a crime na cidade de Los Angeles (LA) a partir de 2020. Os dados foram transcritos dos *reports* originais e portanto podem haver algumas inconsistências.

O conjunto de dados fornecido pelo LAPD, possui mais de 500.000 linhas e 28 colunas, das quais 6 (colunas relacionadas a código dos crimes cometidos e o tipo de arma utilizado) possuem mais de 50% dos dados como faltantes e portanto foram desconsideradas para as análises.

A partir da análise estatística das idades das vítimas é possível notar algumas anomalias, uma vez que a menor idade é -2 anos e a maior idade é 120 anos, a média e a mediana apresentam valores próximos respectivamente a 29,99 anos e 31 anos, entretanto o desvio padrão calculado é 21,67 anos, um valor relativamente alto quando comparado com a média das idades. Além disso, os dados apresentam uma assimetria de aproximadamente 0,10, um valor muito próximo de zero, indicando um distribuição simétrica, já a curtose possui um valor negativo (indicando uma distribuição platocurtica), mas ainda sim próxima de zero, o que apróxima o perfil dos dados a uma distribuição normal.

[Acesse o notebook](https://github.com/IgorAMorais/crime_data_LA/blob/main/crime_data_LA.ipynb) e tenha acesso a outras análises relacionadas ao perfil das vitimas como idade dos sexos (masculino e feminino) e descendência, evolução de crimes ao longo dos meses, acesso as regiões e locais com maior incidência de crimes, períodos do dia com maior quantidade de crimes e tipos de delito mais cometidos.
