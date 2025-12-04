# Churn de Clientes em Telecom 📊

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)

## 📄 Descrição do Projeto

Este projeto foca em um problema clássico e de alto valor para empresas: a **previsão de Churn de clientes**. Utilizando um dataset de uma empresa de telecomunicações, o objetivo foi construir um modelo de Machine Learning (Regressão Logística) capaz de identificar clientes com alta probabilidade de cancelar seus serviços.

## 📊 Dataset

O dataset utilizado foi o "Telco Customer Churn", obtido na plataforma Kaggle. Ele pode ser encontrado neste [link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

O arquivo contém informações sobre os serviços contratados por cada cliente, tempo de contrato, forma de pagamento e a variável alvo, `Churn`.

## 🛠️ Ferramentas Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
*   **Ambiente:** Jupyter Notebook

## 📈 Análise e Resultados do Modelo

Após a análise exploratória e um rigoroso pré-processamento dos dados, foi treinado um modelo de **Regressão Logística**. A avaliação no conjunto de teste revelou os seguintes resultados:

*   **Acurácia Geral:** O modelo alcançou **79%** de acurácia, mostrando um bom desempenho geral.
*   **Performance na Detecção de Churn (`Churn = True`):**
    *   🎯 **Precisão (Precision): 62%** - Quando o modelo prevê que um cliente vai cancelar, ele está correto 62% das vezes.
    *   🎣 **Recall (Revocação): 51%** - O modelo conseguiu identificar 51% de todos os clientes que de fato cancelaram.

## 💼 Conclusões e Próximos Passos

O modelo atual já serve como uma ferramenta valiosa para iniciar ações de retenção. Ele fornece uma lista de clientes com 62% de chance de churn, permitindo que a equipe de marketing atue de forma proativa.

Para evoluir este projeto, os próximos passos seriam:
1.  **Otimizar para Recall:** Modificar o modelo para aumentar sua capacidade de "encontrar" mais clientes que vão cancelar, pois reter um cliente é geralmente mais barato do que adquirir um novo.
2.  **Testar Modelos Avançados:** Implementar algoritmos como Random Forest ou Gradient Boosting para capturar padrões mais complexos e melhorar a performance.

## 🚀 Como Executar

1.  Clone este repositório.
2.  Certifique-se de ter as bibliotecas listadas acima instaladas.
3.  Abra o arquivo `analise_churn.ipynb` em um ambiente Jupyter.
