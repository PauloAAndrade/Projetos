# 🛢️ Predição de Lucro em Regiões Petrolíferas com Machine Learning

Este projeto tem como objetivo **estimar o lucro esperado na exploração de petróleo em diferentes regiões geográficas**, utilizando **modelagem preditiva (Regressão Linear)** e **simulações estatísticas (Bootstrap)**.  
A análise busca determinar **qual região apresenta o melhor potencial de retorno financeiro** considerando o risco e o investimento.

---

## 📊 Contexto

A empresa de energia precisa decidir **em qual região deve investir** para a perfuração de poços.  
Para isso, são disponibilizados três conjuntos de dados (`geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`), cada um representando uma região com **parâmetros de poços e volume de produção esperado**.

O desafio é:
1. Treinar um modelo de predição da produção (`product`).
2. Selecionar os poços mais promissores.
3. Calcular o lucro potencial.
4. Avaliar o **risco de prejuízo** via **Bootstrap**.

---

## ⚙️ Tecnologias Utilizadas

- **Python 3.10+**
- **Bibliotecas:**
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`
  - `typing`

---

## 🧩 Estrutura do Projeto

