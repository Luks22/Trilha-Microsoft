# Trilha-Microsoft
Respostas dos desafios propostos na trilha Microsoft utilizando o Azure

## Desafio 1: Prever a nota de Ciências da Natureza utilizando a nota de Matemática.

### Modelo completo
![Modelo completo](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Modelo.jpg)

O desafio utiliza os dados do Enem 2019 como base para a realização da previsão. Primeiramente selecionamos apenas as colunas
que iremos utilizar para a previsão, no caso as colunas NU_NOTA_CN, referente as notas de ciencias da natureza, e NU_NOTA_MT,
referente as notas de matematica, após a seleção das colunas, limpamos os dados ausentes da coluna não alvo e a normalizamos.

### Dados Normalizados
![Tabela normalizada](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Dados%20Normalizados.jpg)

Após isso separamos 70% dos dados brutos para treinamento e 30% para teste e treinamos um modelo de regressão, por se tratar de
uma previsão de dados numéricos, e avaliamos o modelo.

### Modelo de Avaliação
![Modelo de Avaliação](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Modelo%20de%20Avaliacao.jpg)

Criamos um pipeline de inferência para prever uma nota de ciências da natureza utilizando uma nota de matemática inserida 
manualmente. O resultado mostra a previsão feita pelo pipeline de inferência.

### Pipeline de Inferência
![Pipeline de Inferência](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Pipeline_inferencia.jpg)

### Dado inserido manualmente
![Nota de matemática inserida manualmente](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Dado_manual.jpg)

### Resultado da previsão
![Previsão](https://github.com/Luks22/Trilha-Microsoft/blob/screenshots/Resultado_previsao.jpg)


# Desafio 2: mostrar a previsão do cluster de um estudante com base nos dados de Renda Mensal, acesso a internet e nota final da redação informados.

![Modelo de cluster]()

 O desafio utiliza os dados do Enem 2019 como base para a realização da clusterização. Primeiramente selecionamos as colunas
que iremos utilizar, NU_NOTA_REDACAO, referente as notas da redação do enem, Q006, referente as respostas de um formulario 
para a renda mensal, e Q025, referente as respostas de acesso a internet. após a seleção das colunas, limpamos os dados ausentes de
todas as colunas selecionadas e normalizamos as colunas numéricas.

![Dados normalizados]()

 Após isso separamos 70% dos dados brutos para treinamento e 30% para teste e treinamos um modelo de clusterização, para classificar os 
dados em grupos de 3 e avaliamos sua classificação.
 
![Avaliação do modelo]()

 Criamos um pipeline de inferência para classificar um estudante baseado em sua nota da redeção do enem, sua resposta ao formulario
da renda mensal e acesso a internet inserindo esses dados manualmente. O resultado mostra a qual grupo o estudante pertence.

![Pipeline de inferencia do cluster]()

![Dado do estudante]()

![Resultado da clusterização]()

