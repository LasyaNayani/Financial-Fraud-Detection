# Financial Fraud Detection with Machine Learning

**Project Overview**
This project focuses on identifying fraudulent activities in financial transactions using advanced Machine Learning (ML) techniques. Fraud detection is a high-stakes challenge where the goal is to catch as many "thieves" as possible while ensuring legitimate customers aren't inconvenienced by false alarms.

**The Dataset**
The data was sourced from Kaggle (PaySim), a synthetic dataset that simulates mobile money transactions based on real-world financial logs. I specifically focused on TRANSFER and CASH_OUT transaction types, as these are the primary channels where fraudulent behavior occurs.

**The Experiments and Results**

<img width="1202" height="108" alt="image" src="https://github.com/user-attachments/assets/2865c032-fb44-42c0-b3df-08ed96ce5084" />

This Gradient Boosting model was the top performer. It was faster to train than the Random Forest and caught the highest number of fraudsters (1,637 out of 1,643), missing only 6 cases in the entire test set.

**Final Conclusion**
I chose XGBoost as the final model for this project. In a banking environment, the most expensive mistake is missing a thief. XGBoost proved to be the most "alert" model with the highest catch rate, while still maintaining exceptional precision to protect the customer experience.

🚀 **Google Colab Notebook:**  
👉 [Open the full implementation in Colab](https://colab.research.google.com/drive/1PMffh3QkrnyDEnP4U-U-CiEfmvQeNXNf?usp=sharing)


