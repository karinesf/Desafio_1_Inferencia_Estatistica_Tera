# Primeiro desafio proposto pela Tera durante a formação de Data Science e Machine Learning.

## Roteiro para o Desafio

### 1 - Bases de dados

Segue os seguintes bancos de dados em formato csv:

DEMO_PHQ.csv: banco de dados contendo 5334 observações de adultos pesquisados no NHANES 2005-2006, segue PDF com detalhamento das variáveis:

PAG_HEI.csv: banco de dados contendo 9424 observações de crianças e adultos pesquisados no NHANES 2005-2006, segue PDF com detalhamento das variáveis:

### 2 - Tratamento de dados

1. Faça a leitura dos bancos de dados e faça o tratamento que julgar necessário para as variáveis (exemplo: tratamento das categorias 7 = “Se recusou a responder” e 9 = “Não sabe”).

2. Em seguida, combine os dois bancos de dados fornecidos, utilizando a variável SEQN como chave única. O banco de dados final deve conter 5334 observações dos adultos respondentes do NHANES.

3. Crie a variável phq9 - escore Patient Health Questionnaire-9 como a soma das variáveis DPQ010 a DPQ090

4. Crie a variável phq_grp - grupo de sintomas de depressão que assume 0 (“sem sintomas”) se phq9 < 5, 1 (“sintomas leves”) se 5 <= phq9 < 10, 2 (“sintomas moderados”) se 10 <= phq9 < 15, 3 (“sintomas moderadamente severos”) se 15 <= phq9 < 19 e 4 (“sintomas severos”) se phq9 >= 20

### 3 - EDA: Análise Univariada

1. Faça uma análise univariada de todas as variáveis da análise.

2. Julgue como proceder com os casos faltantes nas variáveis

3. Re-agrupe ou re-codifique as variáveis que julgar necessário

### 4 - EDA: Análise Bivariada

1. Faça uma análise bivariada de sintomas de depressão (phq9 ou phq_grp) com as características demográficas. Descreva o perfil com maiores incidências de sintomas de depressão.

2. Faça uma análise bivariada de características demográficas x hábitos saudáveis. Qual perfil possui hábitos mais saudáveis?

3. Faça uma análise bivariada de sintomas de depressão (phq9 ou phq_grp) com os hábitos saudáveis (variáveis de atividade física e healthy eating index). O que podemos observar?

### 5 - Testes de hipóteses

1. Faça o(s) teste(s) de hipóteses adequado(s) para avaliar a significância estatística das diferenças nas características demográficas apontadas na análise bivariada. Quais são as características apresentam diferenças estatisticamente significativas para a frequência de sintomas de depressão?

2. Faça o(s) teste(s) de hipóteses adequado(s) para avaliar se existe associação entre hábitos saudáveis e sintomas de depressão.

### 6 - Aspectos da análise

1. Qual o tipo de estudo está sendo empregado pelo NHANES? experimental ou observacional?

2. Discuta as possíveis fontes de viés presentes na análise

3. A partir da análise realizada, podemos afirmar que hábitos saudáveis possuem um efeito causal na prevenção de depressão?

4. Quais são as fraquezas das análises realizadas? O que pode ser feito para melhorar?

5. Quais outras variáveis/informações poderiam ter sido coletadas para esta análise?
	
