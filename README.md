In 2022, the outbreak of monkey pox affected many businesses, such as retail, and caused disruptions in the workforce and supply chain management. The downtime for obtaining PCR test results is 48 hours, which is a lot as it can cost a life sometimes. This predictive model is based on the common symptoms that would help the physician take the required course of action promptly.

This repository has dataset and the code.

Results:
For most health-related data, we try to optimize recall value by reducing the false negatives. If I detect monkey-pox positive (false positive) after running the code, I will have to spend money on my treatment which is not required in reality. Keeping this monetary criterion in mind, we felt that reducing False positives in our prediction was essential; therefore, we optimized precision instead.

We trained the data with different algorithms like Decision tree, KNN, Random forest, etc and  hyperparameter tuned Decision Tree with GridSearchCV provided the best precision score.

Our model shows over 68% precision i.e., out of 100 detections, 68 cases are positive for monkeypox. 
