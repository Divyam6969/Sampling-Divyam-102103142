# Sampling Assignment - Divyam
## Data Sampling and Model Evaluation
Name: Divyam Malik<br>
Roll No. 102103142<br>
Group: 3CO5<br>

From the table I can conclude that Random forest is best model and if we consider 1 as overfitting then Decision trees will be the best

Subsequent to the creation of five distinct samples utilizing these techniques, each sample underwent evaluation using five different models. The accuracies of each model for a given sample are summarized in the following table:

| Sampling Technique      | Random Forest | Logistic Regression | SVM    | Decision Trees | AdaBoost |
|-------------------------|---------------|---------------------|--------|----------------|----------|
| Simple Random Sampling   | 0.9870        | 0.8926              | 0.9664 | 1.0000         | 0.9933   |
| Systematic Sampling      | 1.0000        | 0.9579              | 1.0000 | 0.9789         | 1.0000   |
| Cluster Sampling         | 1.0000        | 0.8955              | 0.9701 | 0.9925         | 0.9851   |
| Stratified Sampling      | 1.0000        | 0.9250              | 0.9750 | 0.9625         | 1.0000   |
| Bootstrap Sampling       | 1.0000        | 0.9250              | 0.9750 | 0.9625         | 1.0000   |




Data sampling is a crucial method employed to extract meaningful insights about a population by analyzing statistics from a representative subset, eliminating the necessity to scrutinize each individual record. In addressing an initial dataset imbalance — with 763 non-fraudulent cases and only 9 fraudulent cases — an oversampling approach was adopted. This entailed generating additional instances of the minority class (fraudulent cases) to align with the majority class (non-fraudulent cases), resulting in a well-balanced dataset consolidated into a single data frame.

Various sampling techniques were employed to create diverse subsets for analysis:

- **Simple Random Sampling:** Involves the random selection of samples from the entire population.
- **Systematic Sampling:** Selects samples at regular intervals after a random starting point.
- **Cluster Sampling:** Randomly selects entire clusters from the population.
- **Stratified Sampling:** Divides the population into subgroups based on specific criteria for sampling.
- **Bootstrap Sampling:** Resamples with replacement to generate multiple samples from the original dataset.

