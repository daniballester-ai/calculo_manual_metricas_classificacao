# Cálculo Manual de Métricas de Classificação ✨📊

## Objetivo do Projeto 🎉

Este projeto tem como objetivo demonstrar o cálculo manual das principais métricas de avaliação para modelos de classificação (Acurácia, Sensibilidade, Especificidade, Precisão e F-score), sem a utilização de bibliotecas específicas para este fim, como Scikit-learn. 🤓 O cálculo é baseado nas fórmulas tradicionais e utiliza uma matriz de confusão gerada a partir de um modelo de exemplo. No final iremos fazer a curva AUC-ROC para cada classe.

## Fórmulas das Métricas de Avaliação 📝

As fórmulas utilizadas para o cálculo das métricas, baseadas na imagem "metricas.png", são as seguintes:

*   **Acurácia:**
    Acurácia = {VP + VN}/{VP + VN + FP + FN} 
*   **Sensibilidade (Recall):**
    Sensibilidade = {VP}/{VP + FN}
*   **Especificidade:**
    Especificidade = {VN}/{VN + FP}
*   **Precisão:**
    Precisão = {VP}/{VP + FP}
*   **F-score:**
    F-score = 2 * (Precisão * Sensibilidade) / (Precisão + Sensibilidade)

Onde:
*   **VP:** Verdadeiros Positivos
*   **VN:** Verdadeiros Negativos
*   **FP:** Falsos Positivos
*   **FN:** Falsos Negativos

## Passo a Passo do Projeto 👣

O projeto foi desenvolvido seguindo os seguintes passos no notebook:

1.  **Carregamento e Pré-processamento dos Dados:** Carregamento do conjunto de dados MNIST e pré-processamento das imagens. 📥
2.  **Definição e Treinamento do Modelo:** Definição de uma arquitetura de rede neural convolucional (CNN) e treinamento do modelo com os dados de treinamento. 🧠
3.  **Geração da Matriz de Confusão:** Utilização das previsões do modelo nos dados de teste para gerar a matriz de confusão. 📉
4.  **Extração dos Valores da Matriz de Confusão:** Extração manual dos valores de VP, VN, FP e FN para cada classe a partir da matriz de confusão. ✨
5.  **Cálculo Manual das Métricas:** Implementação das fórmulas de Acurácia, Sensibilidade, Especificidade, Precisão e F-score utilizando os valores extraídos da matriz de confusão, sem o uso de bibliotecas de métricas. ✍️
6.  **Exibição dos Resultados:** Impressão dos valores calculados para cada métrica, por classe. 📊
7.  **Análise da Curva AUC-ROC:** Cálculo e visualização da curva AUC-ROC para cada classe como uma análise complementar do desempenho do modelo. 📈
8.  **Resumo e Conclusão:** Apresentação de um resumo das descobertas e possíveis próximos passos. 📝

Este projeto demonstra o entendimento fundamental de como as métricas de avaliação de classificação são derivadas diretamente da matriz de confusão. 😊
