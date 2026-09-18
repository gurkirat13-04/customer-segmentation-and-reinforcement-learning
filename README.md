# Customer Intelligence & Reinforcement Learning

A practical machine learning project demonstrating **Unsupervised Learning** through customer segmentation and the fundamental concepts of **Reinforcement Learning** through a delivery-route optimization example.

The project focuses on understanding how machine learning techniques can support business decision-making without requiring complex model implementation.

## Overview

This project is divided into two core components:

### Part A — Customer Segmentation

An online retailer wants to identify different customer groups using two behavioral features:

* Monthly Spending
* App Visits

**K-Means Clustering** is used to divide customers into three groups and visualize the resulting segments.

The clusters can then be interpreted from a business perspective to support actions such as:

* Loyalty programs
* Personalized recommendations
* Customer engagement strategies
* Re-engagement campaigns

### Part B — Reinforcement Learning

A simple delivery-route scenario is used to introduce the fundamental concepts of Reinforcement Learning.

Two possible routes are evaluated using historical reward values:

* Route A
* Route B

The project demonstrates how an agent can use rewards to learn which actions tend to produce better outcomes.

Key Reinforcement Learning concepts covered include:

* Agent
* Environment
* Action
* Reward
* Exploration
* Exploitation

## Machine Learning Concepts

| Concept                | Application                               |
| ---------------------- | ----------------------------------------- |
| Unsupervised Learning  | Discovering patterns in customer behavior |
| K-Means Clustering     | Customer segmentation                     |
| Data Visualization     | Understanding customer groups             |
| Reinforcement Learning | Learning from actions and rewards         |
| Exploration            | Trying different available actions        |
| Exploitation           | Selecting an action known to perform well |

## Dataset

The customer dataset is a small illustrative dataset created specifically for the practical.

| Customer | Monthly Spending | App Visits |
| -------- | ---------------: | ---------: |
| A        |            9,000 |         20 |
| B        |            8,500 |         18 |
| C        |            1,200 |          3 |
| D        |            1,500 |          4 |
| E        |            5,000 |         10 |
| F        |            5,500 |         12 |
| G        |            8,800 |         19 |
| H        |            1,800 |          5 |

The clustering model uses **Monthly Spending** and **App Visits** as its features.

## Methodology

### Customer Segmentation

The workflow follows these steps:

1. Create the customer dataset.
2. Select relevant clustering features.
3. Configure K-Means with `K = 3`.
4. Assign each customer to a cluster.
5. Visualize the resulting groups.
6. Interpret the clusters from a business perspective.

```text
Customer Data
      ↓
Feature Selection
      ↓
Monthly Spending + App Visits
      ↓
K-Means Clustering
      ↓
3 Customer Groups
      ↓
Visualization
      ↓
Business Interpretation
```

### Reinforcement Learning

The delivery-route example follows:

```text
Agent
  ↓
Choose Action
  ↓
Route A / Route B
  ↓
Environment
  ↓
Delivery Outcome
  ↓
Reward
  ↓
Learn From Feedback
```

The example also demonstrates the difference between:

**Exploration** — trying a new or less-used option.

**Exploitation** — choosing the option currently known to provide better rewards.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Jupyter Notebook

## Project Structure

```text
customer-intelligence-ml/
│
├── part-a/
│   └── unsupervised-learning/
│       └── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│
├── screenshots/
│   └── customer-segmentation.png
│
└── README.md
```

## Key Business Insights

Customer segmentation demonstrates how businesses can move beyond treating every customer the same.

Different behavioral groups can receive different strategies based on their spending and engagement patterns.

The Reinforcement Learning example demonstrates another approach to business decision-making: instead of simply identifying patterns, a system can learn from the outcomes of its actions through rewards.

Together, the two approaches demonstrate different ways AI can support business decisions:

```text
Unsupervised Learning
        ↓
Discover Hidden Patterns
        ↓
Understand Customer Groups


Reinforcement Learning
        ↓
Take Actions
        ↓
Observe Rewards
        ↓
Improve Future Decisions
```

## Limitations

This project is designed as an educational practical and uses simplified examples.

* The customer dataset is small and illustrative.
* Only two customer features are used.
* The number of clusters is predefined as `K = 3`.
* The Reinforcement Learning section uses a simplified reward-based example rather than a trained RL algorithm.
* Real-world applications would require larger datasets, additional features, validation, and more sophisticated modeling.

## Learning Outcomes

After completing this project, the following concepts are demonstrated:

* Understanding Unsupervised Learning
* Applying K-Means Clustering
* Identifying customer segments
* Interpreting clusters from a business perspective
* Understanding the Agent–Action–Reward framework
* Differentiating Exploration from Exploitation
* Connecting machine learning techniques with business decision-making

## Author

**Gurkirat Singh Brar**

BBA FinTech & AI
Chitkara University

---

*This repository was developed as part of a practical exploration of Unsupervised Learning and Reinforcement Learning for business applications.*
