# 🧠 Machine Learning: Projeto de Credit Score com Árvore de Decisão

Este projeto faz parte do Módulo Árvore de Decisão do curso de Cientista de Dados da EBAC e tem como objetivo aplicar o algoritmo de Árvore de Decisão para prever o score de crédito dos clientes (baixo, médio e alto).

A base de dados já havia sido previamente tratada nos módulos anteriores, incluindo limpeza, codificação de variáveis categóricas, balanceamento das classes e separação entre treino e teste, permitindo foco direto na modelagem e avaliação.

## 🧩 Etapas Desenvolvidas

**1. Validação das bases:** Verificação da consistência entre X e y, garantindo correta separação das variáveis e ausência de inconsistências.

**2. Preparação dos dados:** Utilização das bases previamente tratadas, assegurando que apenas variáveis independentes fossem utilizadas no modelo.

**3. Treinamento do modelo:** Aplicação do algoritmo Árvore de Decisão para classificação do score de crédito.

**4. Avaliação do modelo:** Análise de desempenho utilizando métricas como acurácia, classification report e matriz de confusão.

**4. Comparação de modelos:** Comparação dos resultados com o modelo anterior (Naive Bayes).

## 📊 Resultados e Insights

- Acurácia próxima de 100% na base de treino e entre 97% e 98% na base de teste.

- Matrizes de confusão com erros mínimos e pontuais, distribuídos entre classes próximas.

- Desempenho semelhante ao modelo Naive Bayes, com pequenas diferenças na distribuição dos erros.

- A Árvore de Decisão apresentou melhor ajuste na base de treino, com possível leve ´*overfitting*.

- Naive Bayes demonstrou maior consistência entre treino e teste, indicando maior estabilidade.

- Ambos os modelos mostraram alta capacidade preditiva, sendo adequados para o problema.

## ✅ Conclusão

A comparação entre a Árvore de Decisão e o modelo Naive Bayes mostrou que ambos apresentam desempenho elevado e bastante semelhante na base de teste, com acurácia próxima de 98% e poucos erros nas matrizes de confusão. As diferenças observadas concentram-se na distribuição dos erros entre as classes, sendo pontuais em ambos os modelos.

A principal distinção está no comportamento durante o treinamento: a Árvore de Decisão apresentou melhor ajuste à base de treino, chegando a 100% de acurácia, o que pode indicar leve *overfitting*, enquanto o Naive Bayes demonstrou maior consistência entre treino e teste.

Dessa forma, ambos os modelos se mostraram adequados para o problema, sendo a Árvore de Decisão ligeiramente superior em capacidade de ajuste, enquanto o Naive Bayes se destaca pela simplicidade e estabilidade.
