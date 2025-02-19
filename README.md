# Classificação de Distúrbios do Sono

## Sobre o Projeto
Projeto desenvolvido como trabalho da disciplina de Inteligência de Negócios do curso de Bacharelado em Sistemas de Informação. O objetivo é realizar uma análise comparativa entre três técnicas de machine learning (KNN, Árvore de Decisão e Random Forest) para classificação de desordens do sono com base em dados do estilo de vida dos pacientes.

## Dataset
O estudo utiliza o Sleep Health and Lifestyle Data Set (Part 2), disponível em [Figshare](https://figshare.com/articles/dataset/Sleep_Health_and_Lifestyle_Data_Set_Part_2_/24803142?file=43628358).

## Funcionalidades Implementadas
- Pré-processamento de dados
  - Tratamento de valores nulos
  - Codificação de variáveis categóricas
- Implementação e comparação de modelos:
  - K-Nearest Neighbors (KNN)
  - Árvore de Decisão
  - Random Forest
- Avaliação de performance usando:
  - Acurácia
  - Precisão
  - Revocação
  - Matriz de Confusão

## Tecnologias Utilizadas
- Python
- Google Colab
- Bibliotecas:
  - pandas
  - scikit-learn
  - numpy
  - matplotlib
  - seaborn

## Resultados

- Divisão dos dados: 70% treino, 30% teste
- Métricas de avaliação para cada modelo
- Comparação de performance entre as técnicas
- Matrizes de confusão
