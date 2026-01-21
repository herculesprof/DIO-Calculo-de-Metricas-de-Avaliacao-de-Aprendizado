# Cálculo de Métricas de Avaliação de Modelos de Classificação

Este projeto automatiza o cálculo das principais métricas de desempenho para modelos de Machine Learning, focado em tarefas de classificação binária.

## 📋 Sobre o Projeto
O objetivo é consolidar o entendimento sobre como interpretar os resultados de uma **Matriz de Confusão**. O projeto calcula indicadores essenciais que ajudam a medir a eficácia de um modelo além da acurácia simples.

## 🧮 Métricas Implementadas
As seguintes fórmulas foram aplicadas conforme as definições técnicas:

* **Acurácia:** Mede a proporção global de acertos (VP + VN) sobre o total.
* **Sensibilidade (Recall):** Avalia a capacidade do modelo em identificar exemplos positivos corretamente.
* **Especificidade:** Mede a eficácia em identificar corretamente os exemplos negativos.
* **Precisão:** Indica a proporção de predições positivas que foram realmente corretas.
* **F-score:** Representa a média harmônica entre Precisão e Sensibilidade, sendo útil para dados desbalanceados.

## 🛠️ Tecnologias
- **Linguagem:** Python 3.
- **Ambiente:** Google Colab.

## 🚀 Como Utilizar
Basta abrir o notebook no Google Colab e alterar os valores de `vp`, `vn`, `fp` e `fn` no início do script para recalcular as métricas com base em qualquer matriz de confusão desejada.
