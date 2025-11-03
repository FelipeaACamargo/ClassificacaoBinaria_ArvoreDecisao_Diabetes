# Classificação Binária de Diabetes com Árvore de Decisão

Este projeto apresenta uma solução completa de Machine Learning para classificação binária de diabetes, utilizando um algoritmo de Árvore de Decisão. O objetivo é prever se um paciente possui ou não diabetes, com base em medidas clínicas e demográficas extraídas de um banco de dados real do Instituto Nacional de Diabetes e Doenças Digestivas e Renais.

## Sobre o Projeto

- **Notebook principal:** Diabetes_Classificacao_ArvoreDecisao.ipynb
- **Base de dados:** Diabetes.xlsx (contendo variáveis explicativas e o rótulo)
- **Algoritmo:** DecisionTreeClassifier (Árvore de Decisão)
- **Tarefa:** Classificação binária (0 = não possui diabetes, 1 = possui diabetes)

## Dados
No arquivo Diabetes.xlsx, contém as seguintes informações:
    - **Gravidez:** Número de vezes que engravidaram
    - **Glicose:** Concentração plasmática de glicose em 2 horas em um teste oral
    - **Pressão Arterial:** Pressão arterial diastólica (mm Hg)
    - **Espessura da Pele:** Espessura da prega cutânea do tríceps (mm)
    - **Insulina:** Insulina sérica de 2 horas
    - **IMC:** Índice de massa corporal (peso em kg/(altura em m)$^2$)
    - **Diabetes-Pedigree:** Função de pedigree do diabetes
    - **Idade:** Idade (anos)
    - **Diabetes:** Variável rótulo (0 = não, 1 = sim)

## Principais Etapas

1. Importação das bibliotecas e dados.
2. Análise descritiva das variáveis.
3. Matriz de correlação para identificar relações relevantes.
4. Separação dos dados em treino e teste.
5. Treinamento do modelo de árvore de decisão.
6. Avaliação das previsões (acurácia, matriz de confusão, relatório de classificação).
7. Construção da curva ROC e cálculo da AUC.
8. Visualização gráfica da árvore gerada.
9. Gráfico de importância das variáveis.

## Como Executar

1. Clone este repositório e baixe o arquivo Diabetes.xlsx.
2. Recomenda-se um ambiente com Python 3.7+.
3. Instale os requisitos do projeto:
    ```
    pip install pandas matplotlib seaborn scikit-learn
    ```
4. Execute o notebook Diabetes_Classificacao_ArvoreDecisao.ipynb no Jupyter, Google Colab ou VSCode.

## Resultados Esperados

- Identificação das variáveis mais correlacionadas com o diagnóstico.
- Acurácia do modelo reportada ao final.
- Interpretação da matriz de confusão.
- Análise da curva ROC e valor AUC.
- Visualização das variáveis com maior impacto na decisão.

## Referências

- [Instituto Nacional de Diabetes e Doenças Digestivas e Renais - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- [Documentação Scikit-learn - Árvore de Decisão](https://scikit-learn.org/stable/modules/tree.html)

---

Sinta-se à vontade para copiar, adaptar, compartilhar e contribuir com sugestões ou melhorias
