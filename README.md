# Risk and Fraud Analytics

This repo comprises of projects completed in the Risk and Fraud Analytics course at IE University.

## Fraud Detection Game

The main purpose of this game was to generate a fraud detection model for Peruvian with anonymized data, whilst obtaining at least a **KS** = **0.4202** and **GINI** = **0.5234** to obtain the maximum possible 10/10 score.

The entire fraud modelling methodology is outlined in `MarangMutloatse_LogBook_RiskGame.pdf` but some noteworthy modelling takeaways are summarised below.

**Noteworthy Modelling Takeaways:**
- Utilizing Population Standard Index **(PSI)** for optimal feature selection rather than genetic algorithms and recursive feature elimination produced the optimal features to obtain the maximum score.
- Employing classical oversampling and undersampling techniques did not prove useful for increasing and subsequently obtaining the maximum score.

The final model was an ensembled model: Voting classifier (soft voting) with a Multi-Layer Perceptron, KNN, Logistic Regression and Random Forest Classifier. The parameters of the model are stated in `MarangMutloatse_LogBook_RiskGame.pdf`. This model obtained a **KS** = **0.4218** and **GINI** = **0.5320** which resulted in a maximum score; 1 of 8/46 class participants. Documented code is outlined in `RiskAndFraudFinalSubmission_MarangMutloatse.ipynb`.

## Fintech Platform: SMME Loans
