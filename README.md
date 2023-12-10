# Dados - TCC _(em atualização)_
Bases de dados criadas para o meu trabalho de conclusão de curso "Dez anos de cobertura racial do jornal Folha de São Paulo: uma análise de títulos com Jornalismo de Dados". São bases contendo

## materias.csv

Coluna   | Descrição
--------- | ------
`datas` | Data de publicação da matéria
`editoria` | Editoria em que a matéria foi publicada
`url` | Endereço da matéria publicada
`titulos` | Título da matéria publicada

## palavras.csv

Coluna   | Descrição
--------- | ------
`datas` | Data de publicação da matéria
`editoria_limpo` | Editoria em que a matéria foi publicada, em letra minúscula e sem pontuações
`url` | Endereço da matéria publicada
`titulos` | Título da matéria publicada
`palavra` | Uma palavra do título
`racial` | O título contém palavras do dicionário de palavras raciais? (`TRUE` ou `FALSE`)


## bigramas.csv

Coluna   | Descrição
--------- | ------
`datas` | Data de publicação da matéria
`editoria_limpo` | Editoria em que a matéria foi publicada, em letra minúscula e sem pontuações
`url` | Endereço da matéria publicada
`titulos` | Título da matéria publicada
`word 1` | Primeira palavra do bigrama
`word 2` | Primeira palavra do bigrama
`bigrama` | Bigrama identificado `word 1` + `word 2`

