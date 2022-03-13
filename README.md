# Curva_de_Phillips_BR
Obtendo uma série histórica da Curva de Phillips brasileira.

Este repositório é um estudo combinado de um fundamento econômico - A curva de Phillips - e a análise de dados por meio de SQL + Python

A base da PNADC está disponível no BigQuery e pode ser acessada por meio do site https://basedosdados.org
onde os dados estão disponibilizados

Segue SQL utilizado para a consulta dos dados:
`
SELECT 
vd4001,
vd4002,
vd4009,
ano,
trimestre 
FROM basedosdados.br_ibge_pnadc.microdados
WHERE trimestre = 4;
`
