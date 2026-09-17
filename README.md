# exotic-fruit-recognition

## Abstract

This project develops an automated classification system to streamline and optimize the fruit grading process. Manual fruit classification is often prone to human error and resource-intensive; this solution addresses the problem by building an accurate machine learning pipeline capable of predicting fruit types based on physical and chemical numerical features.

The project follows a structured data science workflow:
* **Exploratory Data Analysis:** Analyzing feature distributions and class balance to establish data baseline readiness for a distance-based algorithm.
* **Pipeline Design & Tuning:** Integrating `StandardScaler` data normalization and a `KNeighborsClassifier` into a single `Pipeline` to prevent data leakage during hyperparameter optimization via `GridSearchCV`.
* **Model Evaluation:** Conducting 10-fold Cross-Validation to evaluate model stability, computing metrics such as Log Loss and Accuracy, and interpreting confusion matrices to identify feature overlaps between specific fruit classes.

The final model achieves high predictive accuracy and strong generalization stability on unseen data, providing a scalable tool to minimize human error and optimize inventory management.

To see more, extended explanation in the project.
