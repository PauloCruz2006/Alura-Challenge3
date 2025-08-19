# 📊 Prevendo Evasão de Clientes (Churn) — Telecom X  

Projeto desenvolvido como parte do **Alura Challenge — Machine Learning**.  
O objetivo é **prever clientes com maior risco de cancelamento** e propor estratégias de retenção baseadas em dados.  

---

## 🎯 Objetivos  
- Preparar os dados para modelagem (tratamento, encoding, normalização).  
- Treinar e avaliar modelos preditivos de classificação.  
- Interpretar os principais fatores que influenciam a evasão.  
- Entregar recomendações estratégicas para retenção de clientes.  

---

## 🛠️ Metodologia  
1. **Pré-processamento dos dados**: limpeza, padronização, tratamento de valores nulos.  
2. **Modelagem**: treinamento de classificadores (Regressão Logística, Random Forest, etc).  
3. **Avaliação**: métricas como AUC, precisão e recall.  
4. **Interpretação**: análise de importância das variáveis e dos coeficientes.  

---

## 🔑 Principais Achados  
- **Clientes novos e em planos mensais** apresentam maior risco de churn.  
- **Contratos de longo prazo e múltiplos serviços** reduzem a probabilidade de evasão.  
- **Problemas de suporte e cobrança** são gatilhos imediatos para saída.  

---

## 🚀 Conclusão  
A combinação de modelos permitiu equilibrar **explicabilidade** (Regressão Logística) e **performance preditiva** (Random Forest).  
Com isso, a empresa pode **atuar preventivamente**, ajustando onboarding, ofertas de fidelização e resolução rápida de atritos.  

---

## 📂 Estrutura  
- `Alura_Challenge3.ipynb` → notebook principal com todo o pipeline de dados e modelagem.  

---

## ✅ Próximos Passos  
- Integrar métricas quantitativas (AUC, recall, F1-score) ao relatório.  
- Implementar o **score de risco híbrido** em ambiente operacional.  
- Criar rotina de monitoramento e re-treino periódico dos modelos.  
