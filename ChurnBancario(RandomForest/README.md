# 🔍 Predição de Churn Bancário com Random Forest

Este projeto tem como objetivo prever a evasão de clientes (*Churn*) em um banco, utilizando técnicas de **aprendizado de máquina supervisionado**.  
O modelo desenvolvido busca identificar quais clientes têm maior probabilidade de encerrar sua conta, ajudando a empresa a **tomar decisões preventivas** e **reduzir perdas**.

---

## 📊 Contexto

O conjunto de dados (`Churn.csv`) contém informações de clientes, incluindo idade, saldo bancário, produtos utilizados, histórico de crédito e status de saída do banco (`Exited`).  
O desafio é prever a variável `Exited` (0 = permaneceu, 1 = saiu) a partir das demais características.

---

## ⚙️ Tecnologias Utilizadas

- **Python 3.10+**
- **Bibliotecas principais:**
  - `pandas`, `numpy` — manipulação e análise de dados  
  - `scikit-learn` — modelagem e métricas de desempenho  
  - `matplotlib` — visualizações  
  - `imbalanced-learn` (opcional, caso queira usar SMOTE)

---

## 🧩 Estrutura do Projeto

```bash
.
├── datasets/
│   └── Churn.csv
├── churn_model.py
├── README.md
└── requirements.txt
