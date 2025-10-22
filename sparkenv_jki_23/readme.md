### Challenge 23 - Predicting Flight Delays with Big Data

****Level:**** Medium  
****Description:**** You are a data scientist working at a regional airport authority that’s grappling with a familiar problem: unpredictable flight delays. Every week, thousands of flight records are logged, containing valuable insights about scheduling, departures, arrivals, and delays. However, with such massive volumes of data (> 1 million rows), relying on local data processing struggles to scale. You are then tasked with building a predictive system powered by distributed computing. For example, by creating a local big data environment to handle the heavy data lifting. With the environment in place, load the Parquet dataset of historical flight status records into the Spark context and perform the data cleaning operations that you deem relevant within the Spark context. With the cleaned and transformed data, train and apply two classification models in parallel—a Decision Tree and a Random Forest—to predict delays. Score both models visually and using scoring metrics. Make sure that model training and the computation of scoring metrics are performed within the Spark context. Finally, save the best model for future use. Can you help the regional airport authority predict flight delays with an accuracy above 80%?  
_Beginner-friendly objectives:_ 1. Set up a local big data environment and load the flight status data from the Parquet file into the Spark context. 2. Clean and pre-process the data directly within the Spark context, ensuring each step enhances data quality to support effective classifier training.  
  
_Intermediate-friendly objectives:_  1. Within the Spark context, train in parallel a Decision Tree model and a Random Forest model to predict flight delays, ensuring reproducibility and model robustness. 2. Apply the models and evaluate them using scoring metrics. 3. Evaluate the models also visually, balancing execution efficiency and informativeness. 4. Save the best model for future use in the local big data environment.  
**  
Author:**  [Roberto Cadili](https://hub.knime.com/roberto_cadili)  
  
**Dataset:**  [Flight delay data on KNIME Community Hub](https://hub.knime.com/just%20knime%20it/spaces/Solutions/Season%204/Challenge%2023/Challenge%2023%20-%20Dataset~fnTHQyRmKkLqKVr3/)  
  
Remember to upload your solution with tag **JKISeason4-23** to your public space on KNIME Community Hub. To increase the visibility of your solution, also post it to [**this challenge thread**](https://forum.knime.com/t/solutions-to-just-knime-it-challenge-23-season-4/90211) on KNIME Forum.

[Solution by KNIME](https://hub.knime.com/s/iV-Ock4gGixCi4U6)

> Written with [StackEdit](https://stackedit.io/).
