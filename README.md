# Análise de Risco de Crédito
Análise de Risco de Crédito e Aprendizado de Máquina 

# Resumo do Repositório:
Este repositório explora diferentes técnicas de aprendizado de máquina supervisionado para analisar o risco de crédito, com foco em prever quais características têm maior correlação com empréstimos de alto risco. O autor utiliza um conjunto de dados desequilibrado, onde o número de bons empréstimos é muito maior que o número de empréstimos arriscados, e aplica métodos como regressão logística com diferentes técnicas de amostragem (sobreamostragem, subamostragem e amostragem combinada), florestas aleatórias e boosting.

A análise inclui uma avaliação do impacto financeiro de um empréstimo com base no custo médio e nas taxas médias de hipoteca de 30 anos de uma casa na Califórnia, considerando o cenário de empréstimos concedidos a candidatos de alto risco. O autor compara a performance dos diferentes modelos de aprendizado de máquina, utilizando métricas como precisão balanceada, precisão, recall e F1-score, e discute os resultados em termos de rejeição de bons candidatos e aceitação de candidatos ruins.

# Descrição do que o código faz:
## O código realiza as seguintes etapas:

    Limpeza de dados: remove colunas irrelevantes, trata valores ausentes, converte a taxa de juros para formato numérico, codifica variáveis categóricas e transforma dados de texto em numéricos.
    
    Preparação dos dados: divide os dados em conjuntos de treinamento e teste.
    
    Aplicação de diferentes técnicas de amostragem: utiliza sobreamostragem (Random Oversampling e SMOTE), subamostragem (Cluster Centroids) e amostragem combinada (SMOTEENN) para lidar com o desbalanceamento dos dados.
    
    Treinamento e avaliação de modelos de regressão logística: aplica a regressão logística aos dados amostrados e avalia o desempenho dos modelos usando métricas como precisão balanceada, precisão, recall e F1-score.
    
    Treinamento e avaliação de modelos de aprendizado de conjunto: utiliza Florestas Aleatórias Balanceadas e Easy Ensemble AdaBoosting para classificar os candidatos e avalia o desempenho dos modelos.

    Análise dos resultados: compara o desempenho dos diferentes modelos, discute as implicações de rejeitar bons candidatos e aceitar candidatos ruins, e avalia o impacto financeiro no contexto de empréstimos hipotecários na Califórnia.

    O código demonstra como diferentes técnicas de aprendizado de máquina podem ser aplicadas para analisar o risco de crédito e como a escolha do modelo pode impactar os resultados financeiros de uma empresa de empréstimos.






