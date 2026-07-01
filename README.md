Code: https://github.com/GLV-10IADT/FASE1_FINAL/blob/main/README.md

# Predição de óbito por COVID-19

Este repositório reúne o trabalho desenvolvido para prever a probabilidade de óbito em pacientes com COVID-19 a partir de variáveis clínicas estruturadas. O objetivo é construir um pipeline de Machine Learning capaz de comparar diferentes classificadores, avaliar o desempenho com métricas relevantes e salvar um modelo final para uso posterior.

## Objetivo do projeto

- Construir um classificador binário para prever se um paciente provavelmente evolui para óbito.
- Explorar o conjunto de dados, tratar valores ausentes e preparar as variáveis para treinamento.
- Comparar modelos clássicos e de boosting, buscando um equilíbrio entre desempenho e custo computacional.
- Gerar um modelo final organizado, reprodutível e pronto para inferência.

## Integrantes

- Gabriel Sant Ana - RM375211
- Lucas Faria Polaquini - RM375345
- Victor Luiz Domingues - RM375278

## Estrutura do repositório

- data/ - arquivos de dados utilizados no projeto.
- models/ - modelos treinados e pipelines salvos.
- videos/ - materiais complementares da apresentação.
- covid.ipynb - notebook inicial, com a exploração do dataset e a primeira versão do fluxo de análise.
- covid-workbook.ipynb - notebook final, com o pipeline refinado, experimentos e resultados consolidados.
- requirements.txt - dependências do projeto.

## Descrição dos notebooks

- covid.ipynb: versão inicial do projeto, usada para entender o dataset, realizar a análise exploratória e definir os primeiros passos do pipeline de classificação.
- covid-workbook.ipynb: versão final e mais completa do trabalho, contendo tratamento de dados, treinamento de modelos, avaliação e organização dos resultados.

## Materiais de apresentação

Os vídeos e demais materiais da apresentação podem ser armazenados na pasta videos/ na raiz do repositório para facilitar o acesso e a organização do projeto.

Links disponibilizados:
- https://drive.google.com/file/d/1-eHzTPM8hlbsk-mlMVVKhhN9tv5giCV4/view?usp=drive_link
- https://drive.google.com/file/d/1Vn5tzEOScwvSedqxVX9DuAkbM8gs0Etp/view?usp=drive_link

## Como executar

1. Coloque o dataset em data/.
2. Crie um ambiente virtual e instale as dependências:

```bash
python -m venv .venv
source .venv/bin/activate  # no Windows, use .venv\Scripts\activate
python -m pip install -r requirements.txt
```

3. Abra um dos notebooks no Jupyter e execute as células na ordem apresentada.

## Recursos implementados

- Análise exploratória de dados (EDA)
- Tratamento de valores ausentes
- Pré-processamento com imputação, codificação e normalização
- Treinamento e comparação de modelos de Machine Learning
- Avaliação com métricas como acurácia, precisão, recall, F1-score e AUC-ROC
- Salvamento do modelo final para uso posterior

## Ambiente recomendado

- Python 3.10+
- Jupyter Notebook ou JupyterLab
- Extensões recomendadas no VS Code: Python, Pylance, Jupyter e Python Debugger
