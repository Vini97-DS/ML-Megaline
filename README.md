# Projeto de Aprendizado de Máquina: Recomendação de Planos Megaline

**Descrição do Projeto**

Este projeto consiste em um modelo de aprendizado de máquina para a operadora de telecomunicações Megaline. O objetivo é analisar o comportamento de clientes que já migraram para os novos planos — Smart ou Ultra — e, com base nesses dados, desenvolver um modelo de classificação que possa prever o plano mais adequado para novos clientes.
O desafio central é criar um modelo com a maior acurácia possível, com uma meta de acurácia mínima de 0,75, para garantir que as recomendações sejam precisas e úteis para a empresa.

**Metodologia e Análise**

A análise exploratória de dados (EDA) e a modelagem foram realizadas em um Jupyter Notebook. Os passos seguidos incluem:
Análise de Dados: Exploração inicial do conjunto de dados para verificar a integridade, o tipo das variáveis e a presença de dados ausentes.
Análise Exploratória: Investigação do comportamento de clientes nos diferentes planos (Smart e Ultra) através de visualizações, como gráficos de barras e boxplots, para identificar padrões de consumo de minutos, mensagens e dados.
Preparação de Dados: A base de dados já estava pré-processada, permitindo que a etapa de modelagem fosse iniciada diretamente. O conjunto de dados foi dividido em conjuntos de treino, validação e teste para garantir que o modelo seja avaliado de forma imparcial.
Modelagem e Treinamento: Vários modelos de classificação (como Árvore de Decisão, Floresta Aleatória e Regressão Logística) foram treinados e avaliados para encontrar o que melhor se adapta aos dados.
Avaliação do Modelo: O modelo final foi avaliado em um conjunto de teste para verificar se a acurácia atinge a meta de 75% ou mais, validando a eficácia da solução.

**Conjunto de Dados**

O conjunto de dados utilizado, users_behavior.csv, contém informações sobre o comportamento dos clientes, incluindo:
calls: número de chamadas
minutes: duração das chamadas em minutos
messages: número de mensagens de texto
mb_used: volume de dados de internet usados em MB
is_ultra: variável alvo (0 para plano Smart, 1 para plano Ultra)

**Tecnologias e Bibliotecas**

Python 3
Pandas: Para manipulação e análise de dados.
Scikit-learn: Para a construção dos modelos de machine learning.
Matplotlib e Seaborn: Para a visualização dos dados e análise exploratória.

