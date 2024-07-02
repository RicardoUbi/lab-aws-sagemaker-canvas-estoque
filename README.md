# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto Previsão de Estoque Inteligente na AWS com SageMaker Canvas. O objetivo deste desafio é detalhar todo o processo de criação de um Modelo de ML para uma Previsão de Estoque Inteligente.

## Detalhamento Passo a Passo

### 1. Selecionando o Dataset

-   Naveguei até a pasta `datasets` deste repositório. Nesta pasta contém alguns datasets. O dataset escolhido para treinar e testar o modelo de ML, foi o "dataset-1000-com-preco-variavel-e-renovacao-estoque.csv".
-   Carreguei o dataset localmente e realizei uma análise exploratória para entender sua estrutura e características.
-   Após escolher e criar o dataset, fiz o upload do dataset no SageMaker Canvas.

### 2. Treinar ML

-   No SageMaker Canvas, importei o dataset que selecionei.
-   Defini a variável de destino como QUANTIDADE_ESTOQUE e as variáveis preditivas como ID_PRODUTO, DATA_EVENTO e PRECO.
-   Iniciei o treinamento do modelo. O tempo foi de 15 min.

### 3. Analisar e Prever

-   Após o treinamento, examinei as métricas de desempenho do modelo.
-   Alguns produtos (por exemplo, ID 1, ID 5) estão consistentemente em alta demanda e exigem reabastecimento frequente.
-   Outros produtos (por exemplo, ID 18, ID 24) têm menor demanda e podem ser reabastecidos com menos frequência.
-   Outros produtos (por exemplo, ID 1, ID 5, ID 16) experimentam flutuações de preços mais frequentes.

## Divirta-se!
