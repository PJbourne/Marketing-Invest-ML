# Marketing-Invest-ML
# 💼 Análise de Campanha de Investimento com Machine Learning

Este projeto analisa dados de uma campanha de marketing para prever se os clientes de um banco irão aplicar dinheiro em um investimento ou não. A proposta envolve etapas clássicas de um pipeline de Machine Learning, desde a análise exploratória até a comparação de modelos de classificação.

---

## 🛠️ Etapas do Projeto

1. **Leitura** dos dados [CSV original - marketing_investimento.csv](https://raw.githubusercontent.com/PJbourne/Data_Science_course/refs/heads/main/marketing_investimento%20-%20marketing_investimento.csv)
2. **Análise exploratória** com visualizações (matplotlib, plotly)
3. **Preparação dos dados**:
   - Codificação de variáveis categóricas com `OneHotEncoder` e `LabelEncoder`
   - Normalização com `MinMaxScaler`
4. **Separação** entre treino e teste
5. **Treinamento dos modelos**:
   - DummyClassifier (baseline)
   - DecisionTreeClassifier
   - KNeighborsClassifier
6. **Avaliação e comparação** de desempenho

---

## 🧠 Modelos Avaliados

| Modelo                 | Acurácia |
|------------------------|----------|
| DummyClassifier        | **60%**  |
| KNeighborsClassifier   | **67%**  |
| DecisionTreeClassifier | **73%**  |

---

## 📂 Dados

Os dados estão hospedados em um repositório externo:

🔗 [CSV original - marketing_investimento.csv](https://raw.githubusercontent.com/PJbourne/Data_Science_course/refs/heads/main/marketing_investimento%20-%20marketing_investimento.csv)

> Fonte: Projeto de curso. Os dados são de domínio público e não contêm informações sensíveis.

---

## 📁 Estrutura do Projeto
├── requirements.txt # bibliotecas utilizadas
├── Classificacao_Marketing_Investimento.ipynb # Notebook completo da análise
├── LICENSE
└── README.md
