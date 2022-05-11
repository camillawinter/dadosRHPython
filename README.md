# Análise de Dados de RH com Python
Projeto de análise descritiva, diagnóstica e estatística de dados de RH (Recursos Humanos), utilizando Python no Jupyter Notebook.

Neste projeto foi realizada uma seqüência completa de análise descritiva, diagnóstica e estatística de dados de RH (Recursos Humanos). Foram utilizados dados reais disponíveis publicamente e aplicaremos diversas técnicas de análise de dados.

### Definição do Problema de Negócio:
Uma empresa de consultoria que atua em Big Data e Data Science deseja contratar Cientistas de Dados entre pessoas que obtenham aprovação em alguns cursos ministrados pela empresa.

Muitas pessoas se inscrevem para o treinamento. A empresa quer saber quais desses candidatos realmente querem trabalhar para a empresa após o treinamento ou estão apenas fazendo o treinamento para retornarem ao mercado à procura de um novo emprego.

O objetivo é contratar os profissionais com perfil adequado, a fim de reduzir o custo e o tempo de contratação, bem como a qualidade do treinamento ou planejamento dos cursos e categorização dos candidatos.

*** Descrição fornecida pela Data Science Academy

### Fonte de Dados:

Disponível em: https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists

Este conjunto de dados foi desenvolvido para entender os fatores que levam uma pessoa a deixar o emprego atual.

#### Dicionário:
enrollee_id : Unique ID for candidate

city: City code

city_ development _index : Developement index of the city (scaled)

gender: Gender of candidate

relevent_experience: Relevant experience of candidate

enrolled_university: Type of University course enrolled if any

education_level: Education level of candidate

major_discipline :Education major discipline of candidate

experience: Candidate total experience in years

company_size: No of employees in current employer's company

company_type : Type of current employer

lastnewjob: Difference in years between previous job and current job

training_hours: training hours completed

target: 0 – Not looking for job change, 1 – Looking for a job change

### Abrodagem 
Para esse projeto foi utilizado Python através do Jupyter Notebook com os pacotes: missingno, category_encoders, plotly, pandas, numpy, matplotlib, seaborn, scipy (estatística) e sklearn (engenharia de atributos).
