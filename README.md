# BOOTCAMP ATLÂNTICO AVANTI

Equipe: HYOZAN SQUAD 11

Cientistas de dados:
- Airan Rejane Conceição Dos Santos
- João Volney Grangeiro Dos Santos
- Juvenal Da Costa Lavres Da Conceição
- Natalia Ligabo Dos Santos

Dataset: Diabetes Prediction Dataset


# Análise de Dados e Modelagem — Diabetes

Projeto desenvolvido em equipe durante o bootcamp Atlântico Avanti, utilizando o Diabetes Prediction Dataset.

O trabalho foi dividido em duas etapas: primeiro realizamos a análise exploratória dos dados para entender as características da base e identificar padrões; depois utilizamos os resultados dessa etapa para preparar os dados e realizar uma comparação entre diferentes modelos de classificação.

## Sobre o dataset

O dataset possui 100.000 registros e 9 variáveis relacionadas a características demográficas e clínicas dos pacientes.

Entre as variáveis analisadas estão:

- gênero;
- idade;
- hipertensão;
- doença cardíaca;
- histórico de tabagismo;
- IMC;
- nível de HbA1c;
- nível de glicose no sangue;
- diagnóstico de diabetes.

A variável `diabetes` foi utilizada como variável-alvo na etapa de modelagem.

## Etapa 1 — Análise exploratória

A primeira etapa teve como objetivo conhecer melhor os dados antes de partir para a modelagem.

Foram realizadas análises sobre a distribuição das variáveis, seus tipos e características, além da investigação de possíveis relações entre elas.

### Análise bivariada

Minha participação nessa etapa foi principalmente na análise bivariada.

A ideia foi observar como duas variáveis se comportavam em conjunto e verificar se existiam padrões ou diferenças relevantes entre os grupos.

Foram analisadas relações envolvendo variáveis quantitativas e qualitativas, incluindo características como:

- idade;
- IMC;
- HbA1c;
- glicose;
- hipertensão;
- doença cardíaca;
- histórico de tabagismo;
- diabetes.

As visualizações foram utilizadas para facilitar a identificação desses padrões e ajudar a equipe na interpretação dos dados.

### Alguns insights encontrados

Durante a exploração da base, observamos alguns padrões que chamaram a atenção:

- A quantidade de pessoas sem diabetes é muito maior que a quantidade de pessoas com diabetes, caracterizando um desbalanceamento da variável-alvo.
- Os níveis de HbA1c e glicose apresentam diferenças importantes entre os grupos de pacientes com e sem diabetes.
- A presença de hipertensão e doença cardíaca aparece associada a uma maior proporção de casos de diabetes.
- Foram encontrados valores extremos de IMC que precisavam ser avaliados antes da utilização dos dados em modelos.
- A variável 'smoking_history' possui uma quantidade significativa de registros classificados como 'No Info', o que precisava ser considerado durante o tratamento dos dados.

Esses resultados ajudaram a orientar as decisões tomadas na etapa seguinte.

## Etapa 2 — Pré-processamento e modelagem

Na segunda etapa, o objetivo foi preparar os dados para a construção e comparação de modelos de classificação.

Minha participação foi principalmente na definição da metodologia e no pré-processamento dos dados.

### Pré-processamento

Antes de utilizar os dados nos modelos, foi necessário adequar as variáveis de acordo com suas características.

Entre os procedimentos utilizados estão:

- separação das variáveis de acordo com seus tipos;
- codificação de variáveis categóricas;
- transformação de variáveis ordinais;
- normalização das variáveis numéricas;
- preparação dos dados para utilização nos modelos;
- tratamento do desbalanceamento das classes.

Foram utilizados recursos do Scikit-learn, como OneHotEncoder, OrdinalEncoder, StandardScaler, RobustScaler, MinMaxScaler, Pipeline e ColumnTransformer.


## Comparação de modelos

Depois do pré-processamento, diferentes algoritmos de classificação foram avaliados e comparados.

A comparação foi feita utilizando métricas de avaliação de classificação, permitindo observar o desempenho dos diferentes modelos sobre o problema proposto.


## O que aprendi com o projeto

O projeto foi uma oportunidade de passar por diferentes etapas de um trabalho de dados, desde o entendimento inicial da base até a preparação dos dados para modelagem.

Uma das partes que achei mais interessante foi perceber que a modelagem não começa simplesmente escolhendo um algoritmo. Antes disso, é necessário entender os dados, identificar problemas, decidir como tratar cada tipo de variável e preparar a base de uma forma adequada.

Também pude trabalhar em equipe e dividir responsabilidades dentro de um projeto maior.

## Minha contribuição

Minha participação esteve concentrada em três partes principais:

**1. Dicionário dos dados**

Organização e descrição das variáveis presentes no dataset, buscando entender o significado e o tipo de cada informação.

**2. Análise bivariada**

Investigação das relações entre diferentes variáveis para identificar padrões e diferenças relevantes nos dados.

**3. Metodologia e pré-processamento**

Participação na definição da metodologia da segunda etapa e na preparação dos dados para a modelagem, incluindo a adequação das variáveis, codificação e normalização.

## Estrutura do projeto

- 01_analise_exploratoria_de_dados.ipynb

Contém a primeira etapa do projeto, com a exploração e análise dos dados.

- 02_analise_comparativa_de_modelos.ipynb

Contém a segunda etapa, com a metodologia, preparação dos dados e comparação dos modelos.

## Observação

ATENÇÃO: Este foi um projeto acadêmico desenvolvido em equipe durante o bootcamp Atlântico Avanti. Os resultados apresentados representam os padrões encontrados no dataset utilizado no projeto e não devem ser interpretados como conclusões clínicas!!!
