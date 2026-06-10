# Classificação Binária de Diabetes com Árvore de Decisão

## Contexto do Projeto

O Diabetes Mellitus é uma das doenças crônicas mais prevalentes no mundo, representando um importante desafio para os sistemas de saúde devido às suas complicações e impactos na qualidade de vida dos pacientes.

A utilização de técnicas de Ciência de Dados e Aprendizado de Máquina permite construir modelos capazes de identificar padrões associados ao diagnóstico da doença, auxiliando profissionais da saúde na análise de fatores de risco e na tomada de decisão.

Neste projeto foi desenvolvido um modelo de classificação binária utilizando o algoritmo **Árvore de Decisão (Decision Tree)** para prever a presença ou ausência de diabetes com base em características clínicas e demográficas dos pacientes.

---

## Objetivo do Projeto

Desenvolver um modelo de classificação capaz de prever se um paciente possui ou não diabetes utilizando variáveis clínicas e demográficas.

Os objetivos específicos incluem:

* Realizar análise exploratória dos dados;
* Investigar relações entre as variáveis;
* Construir um modelo de Árvore de Decisão;
* Avaliar o desempenho da classificação;
* Interpretar os fatores mais relevantes para o diagnóstico;
* Utilizar métricas clássicas de avaliação para problemas de classificação binária.

---

## Base de Dados

Foi utilizado o conjunto de dados **Pima Indians Diabetes Database**, amplamente utilizado em estudos de Aprendizado de Máquina aplicados à área da saúde.

A base contém informações clínicas e laboratoriais de pacientes, bem como o diagnóstico de diabetes.

### Características da Base

| Característica    | Valor                                    |
| ----------------- | ---------------------------------------- |
| Tipo de Problema  | Classificação Binária                    |
| Variável Resposta | Diabetes                                 |
| Fonte             | Kaggle / UCI Machine Learning Repository |

### Variáveis da Base

| Variável                   | Descrição                                          |
| -------------------------- | -------------------------------------------------- |
| Gravidez                   | Número de vezes que a paciente engravidou          |
| Glicose                    | Concentração plasmática de glicose após teste oral |
| Pressão Arterial           | Pressão arterial diastólica (mm Hg)                |
| Espessura da Pele          | Espessura da prega cutânea do tríceps (mm)         |
| Insulina                   | Insulina sérica após 2 horas                       |
| IMC                        | Índice de Massa Corporal                           |
| Diabetes Pedigree Function | Histórico familiar associado ao diabetes           |
| Idade                      | Idade do paciente                                  |
| Diabetes                   | Variável resposta (0 = Não, 1 = Sim)               |

---

## Metodologia

O desenvolvimento do projeto seguiu as seguintes etapas.

### 1. Importação dos Dados

* Carregamento da base de dados;
* Verificação da estrutura das variáveis;
* Identificação dos tipos de dados.

### 2. Análise Exploratória dos Dados

Foram realizadas análises descritivas para compreender o comportamento das variáveis.

As análises incluíram:

* Estatísticas descritivas;
* Distribuições das variáveis;
* Identificação de possíveis outliers;
* Matriz de correlação.

### 3. Preparação dos Dados

* Definição das variáveis explicativas;
* Definição da variável resposta;
* Separação em conjuntos de treino e teste.

### 4. Construção do Modelo

Foi utilizado o algoritmo:

* DecisionTreeClassifier (Árvore de Decisão)

O modelo foi treinado utilizando os dados de treinamento e posteriormente avaliado utilizando dados não vistos durante o treinamento.

### 5. Avaliação do Modelo

O desempenho da classificação foi avaliado por meio de:

* Acurácia;
* Matriz de Confusão;
* Precision;
* Recall;
* F1-Score;
* Curva ROC;
* Área sob a Curva (AUC).

### 6. Interpretabilidade

Além da avaliação preditiva, foram analisados:

* Estrutura da árvore gerada;
* Importância das variáveis;
* Principais critérios de decisão do modelo.

---

## Resultados Principais

As análises permitiram:

* Identificar variáveis associadas ao diagnóstico de diabetes;
* Avaliar a capacidade preditiva da Árvore de Decisão;
* Interpretar os caminhos de decisão do modelo;
* Visualizar a importância relativa das variáveis;
* Analisar erros e acertos por meio da matriz de confusão;
* Avaliar o desempenho discriminatório utilizando a Curva ROC e a métrica AUC.

A utilização de Árvores de Decisão oferece uma importante vantagem interpretativa, permitindo compreender de forma transparente como as previsões são realizadas.

---

## Linguagem de Programação

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)

---

## Bibliotecas Utilizadas

### Manipulação e Tratamento de Dados

[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)](https://numpy.org/)

### Visualização de Dados

[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)

### Machine Learning

[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)](https://scikit-learn.org/)

---

## Ambiente de Desenvolvimento

[![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge\&logo=visualstudiocode\&logoColor=white)](https://code.visualstudio.com/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)](https://colab.research.google.com/)

---

## Estrutura do Projeto

```text
Classificacao_Binaria_Diabetes_ArvoreDecisao
│
├── Diabetes.xlsx
│
├── Diabetes_ClassificacaoBinaria_ArvoreDecisao.ipynb
│
└── README.md
```

---

## Fluxo do Projeto

```text
Base de Dados
      │
      ▼
Análise Exploratória
      │
      ▼
Matriz de Correlação
      │
      ▼
Separação Treino/Teste
      │
      ▼
Árvore de Decisão
      │
      ▼
Predições
      │
      ▼
Matriz de Confusão
      │
      ▼
Curva ROC e AUC
      │
      ▼
Importância das Variáveis
      │
      ▼
Interpretação dos Resultados
```

---

## Considerações Finais

Este projeto demonstra a aplicação prática de técnicas de Aprendizado de Máquina Supervisionado para problemas de classificação binária na área da saúde.

A utilização de Árvores de Decisão permite combinar desempenho preditivo e interpretabilidade, tornando possível compreender os fatores que mais influenciam o diagnóstico da doença.

Além disso, a análise das métricas de desempenho fornece uma visão abrangente sobre a qualidade das previsões realizadas pelo modelo.

---

## Referências

* https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
* https://archive.ics.uci.edu/ml/datasets/Pima+Indians+Diabetes
* https://scikit-learn.org/stable/modules/tree.html
* https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html

---

## Autor

**Felipe A. Camargo**

GitHub:
https://github.com/FelipeaACamargo

LinkedIn:
https://www.linkedin.com/in/felipeacamargo
