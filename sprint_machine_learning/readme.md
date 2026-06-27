# Predição de Diagnóstico em Saúde Mental com Machine Learning

## Sobre o projeto

Este projeto foi desenvolvido como MVP da sprint de Machine Learning & Analytics da Pós-Graduação em Ciência de Dados.

O objetivo é desenvolver um modelo de Machine Learning capaz de prever se um indivíduo possui diagnóstico relacionado à saúde mental utilizando informações pessoais, profissionais, organizacionais e de hábitos de vida.

Durante o desenvolvimento foram aplicadas todas as etapas de um projeto de Machine Learning, desde a análise exploratória dos dados até a seleção e avaliação do modelo final.

---

## Objetivos

- Realizar análise exploratória dos dados (EDA);
- Preparar e pré-processar os dados;
- Comparar diferentes algoritmos de classificação;
- Otimizar hiperparâmetros;
- Avaliar o desempenho dos modelos;
- Selecionar a melhor solução para o problema.

---

## Dataset

**Fonte:**
Mental Health in the Tech Workplace Dataset (Kaggle)

O dataset contém informações relacionadas a características demográficas, ambiente de trabalho, hábitos de vida e indicadores de saúde mental.

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Modelos avaliados

- DummyClassifier (Baseline)
- Regressão Logística
- Random Forest
- Regressão Logística Otimizada
- Random Forest Otimizado

---

## Modelo selecionado

Após a comparação entre os modelos e a otimização de hiperparâmetros, a **Regressão Logística Otimizada** foi escolhida como modelo final por apresentar o melhor equilíbrio entre desempenho, simplicidade e custo computacional.

Resultados obtidos no conjunto de teste:

- Accuracy: **97%**
- Precision: **95% (No) / 97% (Yes)**
- Recall: **94% (No) / 98% (Yes)**
- F1-Score ponderado: **97%**

---

## Estrutura do projeto

- Definição do problema
- Descrição do dataset
- Análise exploratória dos dados (EDA)
- Preparação dos dados
- Pré-processamento
- Baseline
- Comparação entre modelos
- Otimização de hiperparâmetros
- Avaliação final
- Conclusões

---

## Notebook

O notebook completo pode ser acessado no Google Colab, disponível dentro desta pasta do Github

---

## Como executar

1. Clone este repositório.
2. Abra o notebook no Google Colab.
3. Execute as células em sequência.

---

## Autor

Décio Amaral
decioamaral@gmail.com

