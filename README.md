# datatran2022

  O dataset contém informações de acidentes nas estradas federais brasileiras em ocorrências registradas no ano de 2022. Os dados podem ser encontrados no link abaixo:

  https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes

O objetivo deste projeto consiste em prever os acidentes fatais.

Neste trabalho, aplicamos técnicas de limpeza e filtragem dos dados.

Explorando os dados, identificamos que havia um grande desbalanceamento na variável target (mortos), o que pode ocasionar no modelo de ML a não generalização.
Para contonar tal situação, aplicamos a técnica undersampling, que consiste em "reduzir" a classe majoritária.
