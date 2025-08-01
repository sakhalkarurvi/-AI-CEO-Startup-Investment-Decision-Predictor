# AI-CEO-Startup-Investment-Decision-Predictor

🎯 Objective:
To build an intelligent machine learning system that acts as an *AI CEO*, automatically deciding whether to invest in a startup based on:

- 🏢 Industry Vertical  
- 🌆 City Location  
- 💰 Investment Type  
- 💵 Requested Funding Amount

---
### 📊 Dataset Overview:
- Source: Indian Startup Funding Data
- Columns: Industry, City, Investment Type, Amount in USD, Decision
- Goal: Predict Invest_Decision (1 = Invest, 0 = Do Not Invest)

---
### ✅ Tools Used:
- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- Jupyter Widgets (ipywidgets)

🧠 How It Works:

1. Dataset is cleaned and encoded.
2. RandomForest model is trained on startup features.
3. You can ask the "AI CEO" to decide based on real-time inputs.
4. The model returns ✅ INVEST or ❌ DO NOT INVEST based on training.

## ✅ Conclusion

This project demonstrates that an AI model can effectively simulate certain aspects of a CEO's decision-making process. By analyzing historical startup funding data, we trained a Random Forest classifier that can predict whether an investment decision is likely to succeed.

With an accuracy of **99%**, the AI CEO can:
- Interpret complex funding patterns
- Make consistent investment decisions based on historical trends
- Help founders or investors gauge startup viability

While this system does not replace human intuition and experience, it shows great potential in **augmenting decision-making** in the startup ecosystem. Future work could include integrating real-time market data, sentiment analysis from news, or even building a full dashboard for investment analytics.

This project marks a strong starting point in exploring how AI could assist in **strategic business leadership**.


