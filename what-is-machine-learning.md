# What Is Machine Learning?

## 1. Definition

**Machine Learning (ML)** is a branch of Artificial Intelligence (AI) that enables computers to learn from data, identify patterns, and make predictions or decisions without being explicitly programmed for every task.

In simple terms, Machine Learning allows computers to learn from examples and improve their performance through experience.

## 2. How Does Machine Learning Work?

Machine Learning generally follows these steps:

1. **Collect Data:** Gather examples such as images, numbers, text, or customer information.
2. **Prepare Data:** Clean and organize the collected data.
3. **Train the Model:** Feed the data into a learning algorithm so it can identify patterns.
4. **Evaluate the Model:** Test how accurately the model performs.
5. **Make Predictions:** Use the trained model to make predictions or decisions using new data.

### Example: Predicting House Prices

Imagine you want to build a system that predicts house prices.

| Size (m²) | Bedrooms | Price (€) |
|---:|---:|---:|
| 60 | 2 | 150,000 |
| 80 | 3 | 200,000 |
| 100 | 3 | 250,000 |
| 120 | 4 | 300,000 |

The Machine Learning algorithm studies the relationship between house size, bedrooms, and prices.

When you provide information about a new house, the trained model estimates its price.

## 3. Types of Machine Learning

There are three main types of Machine Learning.

### A. Supervised Learning

Supervised Learning trains a model using **labeled data**. This means the training data contains both input information and the correct answers.

Examples:
- Predicting house prices.
- Classifying emails as spam or not spam.
- Predicting whether a customer will leave a service.

Common algorithms:
- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

### B. Unsupervised Learning

Unsupervised Learning trains a model using **unlabeled data**. The algorithm discovers hidden patterns, structures, or groups in the data.

Examples:
- Grouping customers based on purchasing behavior.
- Discovering groups of similar products.
- Identifying unusual transactions.

Common algorithms:
- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- DBSCAN

### C. Reinforcement Learning

Reinforcement Learning involves an agent learning through interaction with an environment.

The agent takes actions and receives rewards or penalties based on its behavior.

Examples:
- Teaching a computer to play chess.
- Training robots to walk.
- Developing autonomous driving systems.

Common algorithms:
- Q-Learning
- Deep Q-Networks (DQN)
- Policy Gradient

## 4. Common Machine Learning Algorithms

| Algorithm | Purpose | Example |
|---|---|---|
| Linear Regression | Predicts numerical values | House prices |
| Logistic Regression | Classifies categories | Spam detection |
| Decision Tree | Makes decisions using rules | Loan approval |
| Random Forest | Combines multiple decision trees | Fraud detection |
| K-Means | Groups similar data | Customer segmentation |
| Neural Network | Learns complex patterns | Image recognition |
| Support Vector Machine | Classifies data | Image classification |

## 5. Real-World Applications

Machine Learning is used in many industries.

- **Healthcare:** Predicting diseases and analyzing medical images.
- **Finance:** Detecting fraudulent transactions and assessing credit risk.
- **Education:** Personalized learning recommendations.
- **Transportation:** Traffic prediction and self-driving vehicles.
- **E-commerce:** Product recommendations and customer analysis.
- **Entertainment:** Movie and music recommendations.
- **Agriculture:** Predicting crop yields and detecting plant diseases.
- **Cybersecurity:** Identifying suspicious activities.

## 6. Important Machine Learning Terminology

| Term | Explanation |
|---|---|
| Data | Information used for learning. |
| Feature | An individual measurable property of the data. |
| Label | The correct answer associated with an example in supervised learning. |
| Algorithm | A method used to learn patterns from data. |
| Model | The result of training a learning algorithm. |
| Training | The process of teaching a model using data. |
| Testing | Evaluating a trained model using unseen data. |
| Prediction | The output produced by a trained model. |
| Accuracy | A measure of how often predictions are correct. |
| Overfitting | When a model learns training data too closely and performs poorly on new data. |
| Underfitting | When a model fails to learn important patterns from the data. |

## 7. Benefits of Machine Learning

- Automates repetitive tasks.
- Identifies patterns in large datasets.
- Makes predictions based on historical data.
- Improves decision-making.
- Personalizes user experiences.
- Helps solve complex real-world problems.

## 8. Challenges of Machine Learning

- Requires sufficient, high-quality data.
- Training can require significant computing resources.
- Models can produce inaccurate predictions.
- Biased training data can lead to biased results.
- Some models are difficult to interpret.
- Models may need regular monitoring and updating.

## 9. Machine Learning vs. Artificial Intelligence vs. Deep Learning

These concepts are related but have different meanings.

- **Artificial Intelligence (AI):** The broader field of creating systems that perform tasks requiring human-like intelligence.
- **Machine Learning (ML):** A branch of AI that enables systems to learn patterns from data.
- **Deep Learning (DL):** A branch of Machine Learning that uses multi-layered neural networks to learn complex patterns.

**Relationship:**

AI → Machine Learning → Deep Learning

## 10. Key Takeaway

Machine Learning enables computers to learn from data instead of relying entirely on manually written instructions.

The basic idea is:

**Data → Learning Algorithm → Trained Model → Prediction**

For example, instead of programming every rule for identifying spam emails, we train a Machine Learning model using examples of spam and legitimate emails. The model learns patterns and uses them to classify new emails.

**Remember:** Machine Learning does not mean computers think exactly like humans. It means they use data and mathematical techniques to recognize patterns and make predictions.
