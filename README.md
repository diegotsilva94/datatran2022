# datatran2022

O objetivo deste projeto consiste em prever os acidentes fatais, com base nas ocorrências registradas nas estradas federais brasileiras no ano de 2022. Os dados desse ano e de anos anteriores podem ser encontrados no link abaixo:

https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes

O primeiro passo para este trabalho foi aplicar técnicas de limpeza e filtragem dos dados. Removemos os valores nulos para a coluna BR, que se refere a nomeclatura da rodovia e filtramos apenas as colunas que julgamos ser importantes para esta análise.

Explorando os dados, identificamos que havia um grande desbalanceamento na variável target (mortos), o que pode ocasionar no modelo de ML a não generalização.
Para contonar tal situação, aplicamos a técnica undersampling, que consiste em "reduzir" a classe majoritária.
