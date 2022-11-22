# Relatório análise de dados - Grupo 1 Diabetes 

Sobre o projeto

- Como dividiram o trabalho?
- Dados sobre o que escolheram trabalhar? Base de dados de Diabetes disponível no kangle
- Onde encontro a base de dados original? https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?select=diabetes_binary_5050split_health_indicators_BRFSS2015.csv

## Integrantes

- Quem são os participantes? Beatriz Brito, César Noronha e Julio Oliveira

## Organização do projeto

- Onde estão as bases de dados? Nas pastas main/datasets/raw e main/datasets/processed
- Tem dados processados? Onde? Sim, na pasta main/datasets/processed
- Onde estão os Notebooks com as Análises Exploratórias? na pasta main/notebooks/edas
- Onde está o Notebook com as comparações entre modelos? na pasta main/notebooks

## Setup

- Como instalar as bibliotecas?
    Rodar no terminal:
    conda env create environment.yml
    Caso aconteça algum erro:
    conda env update environment.yml 
- Como baixar os dados? 
pkl_file = open('../../datasets/processed/diabetes_binary_5050split_health_indicators_BRFSS2015.pkl', 'rb')
df = pickle.load(pkl_file)
pkl_file.close()
- Onde armazenar a base de dados?
na pasta main/outputs bem como na pasta main/datasets/processed

## Contribuições

Ressaltar contribuições que julgarem relevantes




