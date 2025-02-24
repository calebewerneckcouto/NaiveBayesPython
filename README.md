# Análise de Dados com Naive Bayes

Este projeto utiliza o modelo de aprendizado de máquina **Naive Bayes** para prever se um cliente comprou ou não um anúncio oferecido em uma rede social, com base em dados como idade, salário e gênero.

## Descrição

O projeto realiza a importação de dados, a transformação de variáveis categóricas usando **LabelEncoder**, a separação dos dados em treino e teste, o treinamento de um modelo de **Naive Bayes** e a avaliação dos resultados.

Além disso, uma matriz de confusão é gerada para entender o desempenho do modelo, e métricas como **precision**, **recall** e **f1-score** são calculadas.

## Bibliotecas Necessárias

O código utiliza as seguintes bibliotecas:

- **pandas**: Para manipulação de dados.
- **numpy**: Para operações matemáticas.
- **matplotlib**: Para visualização de gráficos.
- **seaborn**: Para visualização de dados (utilizado para matriz de confusão).
- **scikit-learn**: Para a implementação do modelo de **Naive Bayes** e métricas de avaliação.

Para instalar as dependências, utilize o comando abaixo:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
