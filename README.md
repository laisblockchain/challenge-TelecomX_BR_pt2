# 📊 Telecom X — Previsão de Evasão de Clientes (Churn)

## 📌 Descrição

Este projeto tem como objetivo prever a evasão de clientes (churn) na empresa Telecom X utilizando técnicas de **Machine Learning**.

A análise busca identificar padrões que indicam quais clientes possuem maior probabilidade de cancelar seus serviços, permitindo que a empresa desenvolva estratégias para **reduzir a evasão e aumentar a retenção de clientes**.

O projeto faz parte do programa **Oracle Next Education (ONE)** em parceria com a **Alura**, na formação de **Data Science**.

---

# 🎯 Objetivos

- Preparar os dados para modelagem preditiva
- Construir modelos de classificação para prever churn
- Avaliar o desempenho dos modelos
- Identificar as variáveis que mais influenciam a evasão
- Gerar insights estratégicos para retenção de clientes

---


---

# ⚙️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

# 🔄 Etapas do Projeto

## 1️⃣ Preparação dos Dados

- Limpeza e tratamento de dados
- Remoção de variáveis irrelevantes
- Conversão de variáveis categóricas em numéricas (One-Hot Encoding)

---

## 2️⃣ Análise Exploratória

Foram analisadas relações entre churn e variáveis como:

- tempo de contrato
- valor mensal
- valor total gasto
- tipo de contrato
- método de pagamento

---

## 3️⃣ Modelagem Preditiva

Foram treinados dois modelos de Machine Learning:

- **Regressão Logística**
- **Random Forest**

Os modelos foram avaliados com:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

---

# 📊 Principais Resultados

- A **Regressão Logística apresentou melhor desempenho**, com aproximadamente **80% de acurácia**.
- Clientes com **contrato mensal** apresentam maior probabilidade de churn.
- Clientes com **menor tempo de permanência** cancelam mais.
- **Mensalidades mais altas** aumentam o risco de evasão.
- O método de pagamento **Electronic Check** está associado a maior churn.

---

# 💡 Estratégias de Retenção Sugeridas

Com base nos resultados, a empresa pode:

- incentivar **contratos de longo prazo**
- melhorar a experiência de **novos clientes**
- oferecer **benefícios para pagamentos automáticos**
- revisar **planos com mensalidades mais altas**

---

# 🚀 Como Executar o Projeto

1. Clone este repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
