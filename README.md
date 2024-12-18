# Repositório do TCC - Classificação de Drogas

Este repositório contém os códigos de aplicação dos métodos de classificação utilizados no meu Trabalho de Conclusão de Curso (TCC) do curso de Graduação em **Matemática Aplicada com Habilitação em Ciências Biológicas** no **Instituto de Matemática e Estatística da Universidade de São Paulo (USP)**.

## Objetivo

Os códigos aqui presentes incluem implementações de modelos de classificação como **Regressão Logística**, **Árvore de Decisão**, **Random Forest** e **KNN**, aplicados a um conjunto de dados. O objetivo é estudar a performance desses métodos em cenários **balanceados** e **desbalanceados**, avaliando suas métricas e eficácia.

Este repositório tem como finalidade compartilhar as implementações dos modelos, oferecendo uma base para replicação e continuidade do estudo. O foco está na **análise de dados** e na **otimização de parâmetros** para melhorar o desempenho dos modelos em cenários práticos.

## Ferramentas e Bibliotecas Utilizadas

Para a aplicação dos métodos de classificação, são utilizadas as seguintes ferramentas e bibliotecas:

- **Pandas**: Biblioteca essencial para manipulação e análise de dados.
- **Scikit-learn**: Biblioteca para aprendizado de máquina que implementa algoritmos de classificação, como os utilizados neste trabalho.
  
### Sobre o Scikit-learn
O **Scikit-learn** é uma biblioteca amplamente utilizada para aprendizado de máquina em Python. Ela oferece simples e eficientes ferramentas para análise de dados e mineração, com implementações de diversos algoritmos de classificação, regressão, clustering, e mais.

### Sobre o SMOTE
O **SMOTE (Synthetic Minority Over-sampling Technique)** é uma técnica de *oversampling* que cria amostras sintéticas da classe minoritária, ajudando a balancear conjuntos de dados desbalanceados. A técnica foi adotada neste trabalho para melhorar a performance dos modelos de classificação em cenários com desbalanceamento de classes.

## Conjunto de Dados

O conjunto de dados utilizado neste estudo foi extraído do Kaggle, com o objetivo de classificar o consumo de **drogas lícitas** com base em várias características de pacientes. A base de dados está disponível em [Drug Classification Dataset - Kaggle](https://www.kaggle.com/datasets/prathamtripathi/drug-classification/data).

### Descrição do Conjunto de Dados
O conjunto de dados contém informações sobre pacientes, como **idade**, **sexo**, **pressão arterial**, **colesterol total**, entre outras variáveis. A variável de resposta é a **droga lícita utilizada** pelos pacientes, categorizada em cinco classes diferentes.

## Estrutura do Repositório

- **`/notebooks`**: Contém os notebooks Jupyter com os experimentos e análises realizadas.
- **`/scripts`**: Contém os scripts em Python para implementação dos modelos.
- **`/data`**: Contém o arquivo de dados (dataset).
- **`README.md`**: Este arquivo de descrição.

## Como Executar

Para rodar os experimentos, basta clonar este repositório e instalar as dependências necessárias:

```bash
git clone <URL do repositório>
cd <diretório do repositório>
pip install -r requirements.txt
