# Classificação de Planos de Telefonia

Neste projeto, utilizamos técnicas de **Machine Learning** para prever qual plano (`is_ultra`) é mais adequado para cada usuário com base em seu comportamento de uso.

---

## 📂 Estrutura
- **Dataset**: `users_behavior.csv`
- **Modelos testados**:
  - Random Forest
  - Decision Tree

---

## 🔎 Etapas do Projeto

1. **Pré-processamento**
   - Separação entre features e target
   - Divisão dos dados em treino, validação e teste (60% / 20% / 20%)

2. **Treinamento e Validação**
   - Ajuste de hiperparâmetros com `RandomForestClassifier`
   - Teste de diferentes profundidades em `DecisionTreeClassifier`
   - Avaliação com `accuracy_score`

3. **Avaliação Final**
   - Teste com conjunto hold-out (`features_test`)
   - Validação cruzada (`cross_val_score` com 5 folds)

---

## 📊 Resultados

- **Random Forest**
  - Melhor acurácia na validação: **≈ 0.79**
  - Acurácia no teste: **≈ 0.79**
  - Média cross-validation: **≈ 0.78**

- **Decision Tree**
  - Melhor acurácia na validação: **≈ 0.74**
  - Acurácia no teste: **≈ 0.73**

---

## ✅ Conclusão

- A **Random Forest** apresentou o melhor desempenho, superando a **Decision Tree** em consistência e precisão.
- O modelo final escolhido foi a **Random Forest**, com acurácia superior a **0.75**, atingindo o requisito mínimo do projeto.
- Esse resultado indica que o modelo é capaz de prever de forma confiável o plano de telefonia ideal para novos clientes.

---
