# Trilha-Microsoft
Respostas dos desafios propostos na trilha Microsoft utilizando o Azure

## Desafio 1: Prever a nota de Ciências da Natureza utilizando a nota de Matemática.

![Modelo completo](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Modelo.jpg)

O desafio utiliza os dados do Enem 2019 como base para a realização da previsão. Primeiramente selecionamos apenas as colunas
que iremos utilizar para a previsão, no caso as colunas NU_NOTA_CN, referente as notas de ciencias da natureza, e NU_NOTA_MT,
referente as notas de matematica, após a seleção das colunas, limpamos os dados ausentes da coluna não alvo e a normalizamos.

![Tabela normalizada](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Dados%20Normalizados.jpg)

Após isso separamos 70% dos dados brutos para treinamento e 30% para teste e treinamos um modelo de regressão, por se tratar de
uma previsão de dados numéricos, e avaliamos o modelo.

![Modelo de Avaliação](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Modelo%20de%20Avaliacao.jpg)

Criamos um pipeline de inferência para prever uma nota de ciências da natureza utilizando uma nota de matemática inserida 
manualmente. O resultado mostra a previsão feita pelo pipeline de inferência.

![Pipeline de Inferência]()
![Nota de matemática inserida manualmente]()
![Previsão]()

 
