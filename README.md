🧠 Stroke Prediction using Artificial Neural Networks (ANN)
This project implements a Deep Learning model to predict stroke risk using a highly imbalanced medical dataset. The primary focus is to maximize Recall for the minority stroke class, ensuring early detection for at-risk patients.

🚀 Key Performance Highlights
Recall (Stroke Detection): 0.82 – The model successfully identifies 82% of all actual stroke cases in the test set.

3.75x Lift over Baseline: With an Average Precision (AP) of 0.18, this model is nearly 4 times more effective than random guessing (Baseline AP: 0.048) in a dataset with only 4.8% stroke prevalence.

Safety-First Trade-off: The model minimizes life-threatening False Negatives (only 9 missed cases) by accepting a higher number of False Positives, prioritizing patient safety in a diagnostic setting.
