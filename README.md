# EP2 - Previsão de Estágio da Infecção por COVID-19 (Dados do HC)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)

Repositório contendo a solução para o Exercício-Programa 2 da disciplina **MAC0425/5739 - Inteligência Artificial**, que tem como objetivo prever o estágio da infecção por COVID-19 em pacientes com base em dados reais do Hospital das Clínicas da USP.

## Visão Geral

Este projeto implementa uma **rede neural** para classificação binária que prediz se um exame de COVID-19 IgG foi detectado (positivo) ou não (negativo), indicando o estágio da infecção. O trabalho inclui:

- **Pré-processamento** dos dados brutos em CSV (limpeza, tratamento de valores ausentes e codificação)
- **Modelo de rede neural** (arquitetura, treinamento e avaliação)
- **Validação cruzada (k-fold)** para garantir robustez nos resultados
- **Análise de métricas** como acurácia, precisão, sensibilidade e medida-F

## Estrutura do Repositório
