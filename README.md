# Trilha-Microsoft
Respostas dos desafios propostos na trilha Microsoft utilizando o Azure

## Desafio 1: Prever a nota de Ciências da Natureza utilizando a nota de Matemática.

O desafio utiliza os dados do Enem 2019 como base para a realização da previsão. Primeiramente selecionamos apenas as colunas
que iremos utilizar para a previsão, no caso as colunas NU_NOTA_CN, referente as notas de ciencias da natureza, e NU_NOTA_MT,
referente as notas de matematica, após a seleção das colunas, limpamos os dados ausentes da coluna não alvo e a normalizamos.


Após isso separamos 70% dos dados brutos para treinamento e 30% para teste e treinamos um modelo de regressão, por se tratar de
uma previsão de dados numéricos, e avaliamos o modelo.


Criamos um pipeline de inferência para prever uma nota de ciências da natureza utilizando uma nota de matemática inserida 
manualmente. O resultado mostra a previsão feita pelo modelo de inferência.


 
