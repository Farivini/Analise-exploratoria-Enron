# Analise-exploratoria basica sobre a Empresa Enron


# Análise Exploratória de Dados da Enron

Este repositório contém uma análise exploratória dos dados da Enron realizada por Vinícius Farineli Freire. O objetivo deste projeto é investigar os dados de e-mails da Enron, identificando padrões e insights significativos, utilizando técnicas de análise de dados e aprendizado de máquina.

## Sobre o Dataset

O conjunto de dados utilizado nesta análise contém milhares de e-mails de funcionários da Enron, uma empresa que esteve no centro de um dos maiores escândalos corporativos da história. Os dados foram coletados e disponibilizados para pesquisa e desenvolvimento de técnicas em ciência de dados.

**Fonte do Dataset**: [Enron Email Dataset](https://www.cs.cmu.edu/~enron/)

## Objetivos da Análise

Os principais objetivos desta análise exploratória são:

1. Compreender a estrutura dos dados e realizar a limpeza necessária.
2. Identificar padrões de comunicação entre os funcionários da Enron.
3. Detectar possíveis anomalias ou comportamentos suspeitos nos e-mails.
4. Visualizar as redes de comunicação dentro da empresa.
5. Aplicar técnicas de modelagem para prever e classificar determinados comportamentos.

## Ferramentas Utilizadas

- **Python 3.11**
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib & Seaborn**: Para visualização de dados.
- **NetworkX**: Para análise de grafos.
- **NLTK**: Para processamento de linguagem natural.
- **Scikit-learn**: Para modelagem preditiva.

## Estrutura do Repositório

- `Analise_exploratoria_Enron_Vinicius_farineli_freire.ipynb`: Notebook contendo toda a análise exploratória.
- `data/`: Pasta que contém o conjunto de dados utilizado (não incluído neste repositório por questões de espaço e direitos de uso).
- `img/`: Imagens geradas durante a análise para visualização dos dados.

## Como Utilizar

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/Farivini/Analise-exploratoria-Enron.git
   ```

2. Instale as dependências necessárias:

   ```bash
   pip install -r requirements.txt
   ```

3. Abra o Jupyter Notebook e execute as células para reproduzir a análise:

   ```bash
   jupyter notebook Analise_exploratoria_Enron_Vinicius_farineli_freire.ipynb
   ```

## Resultados

A análise revelou padrões de comunicação que podem indicar as dinâmicas internas da empresa durante o período em que os dados foram coletados. Algumas redes de comunicação entre os funcionários foram destacadas, além de padrões sazonais e anomalias que podem estar relacionadas aos eventos que antecederam o colapso da Enron.
