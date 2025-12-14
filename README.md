# Atividade Final - Reconhecimento de Padrões (2025.2)
### Aluno: Iuri Aragão Esmeraldo

Este repositório contém a resolução da lista de exercícios referente à avaliação final da disciplina de Reconhecimento de Padrões. 
O trabalho foca na aplicação prática de algoritmos de Machine Learning, especificamente utilizando a biblioteca XGBoost para resolver problemas de regressão, classificação multiclasse, tratamento de dados desbalanceados e persistência de modelos.

## Estrutura do Repositório

*   **RPAD_FINAL.ipynb**: Jupyter Notebook contendo o código fonte completo para os 5 desafios propostos:
    1.  Regressão com XGBoost (California Housing).
    2.  Classificação Multiclasse (Wine Dataset).
    3.  Detecção de Fraudes e Dados Desbalanceados (Scale Pos Weight).
    4.  Comparativo de Performance (Decision Tree vs. XGBoost).
    5.  Early Stopping e Salvamento de Modelo.

*   **meu_modelo.json**: Arquivo gerado durante a execução do Desafio 5. Contém a estrutura serializada do modelo treinado, demonstrando a funcionalidade de persistência (save/load) do XGBoost.

## Pré-requisitos

O código foi desenvolvido em Python 3. As seguintes bibliotecas são necessárias para a execução:

*   numpy
*   scikit-learn
*   xgboost
*   jupyter (ou ambiente compatível para execução do notebook)

Instalação das dependências:

```bash
pip install numpy scikit-learn xgboost
```

## Como Executar

1.  Clone este repositório ou baixe os arquivos.
2.  Abra o arquivo `RPAD_FINAL.ipynb` em um ambiente Jupyter ou Google Colab.
3.  Execute as células sequencialmente.

Observação: O arquivo `meu_modelo.json` será recriado localmente ao executar a célula correspondente ao Desafio 5.
