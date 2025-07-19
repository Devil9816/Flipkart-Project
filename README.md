# 📊 Flipkart Customer Support CSAT Prediction

This project focuses on analyzing Flipkart's customer support interactions to predict customer satisfaction (CSAT) scores using structured data and machine learning. In the competitive e-commerce industry, proactive customer service is essential to ensuring customer loyalty, and this project provides a data-driven approach to optimize support operations.

---

## 🌍 Real-World Applications

- **🎯 CSAT Prediction System**: Predict low satisfaction scores proactively and resolve issues faster.
- **📈 Live Monitoring Dashboard**: Track and visualize support team performance across shifts and channels.
- **⚠️ Flagging Critical Cases**: Automatically highlight at-risk interactions needing urgent attention.
- **🧑‍💻 Agent & Shift Optimization**: Discover patterns in satisfaction by time, agent, or tenure bucket.
- **💡 Data-Driven Strategy**: Use insights to design training programs, escalation workflows, and staffing policies.

---

## 🧠 Business Context

In the highly competitive e-commerce space, delivering excellent customer service is crucial for sustaining growth and customer loyalty. Flipkart, as one of the largest e-commerce platforms, focuses on enhancing customer satisfaction to differentiate itself from competitors.

This project uses real-world customer interaction data to:

- Identify key drivers of customer satisfaction.
- Evaluate performance across service teams and channels.
- Develop predictive models to estimate satisfaction scores.
- Design strategies for enhancing the customer experience and operational efficiency.

---

## 🎯 Objectives

1. Identify key drivers of customer satisfaction based on structured interaction data.
2. Develop a machine learning model to predict the Customer Satisfaction (CSAT) score.
3. Propose strategies to improve the overall customer service experience based on insights.

---

## 📁 Dataset Overview

The dataset, `Customer_support_data.csv`, contains multiple customer service interactions. Each record represents a unique customer issue reported through various support channels and includes metadata about the issue, agent, resolution timeline, and final satisfaction score (CSAT score).

The CSAT score ranges from **1 (very dissatisfied)** to **5 (very satisfied)**.

---

## 🧾 Feature-wise Explanation

| Feature Name             | Description                                                    |
|--------------------------|----------------------------------------------------------------|
| Unique id                | Unique identifier for each record                              |
| Channel name             | Name of the customer service channel                           |
| Category                 | Category of the interaction                                    |
| Sub-category             | Sub-category of the interaction                                |
| Customer Remarks         | Feedback provided by the customer                              |
| Order id                 | Identifier for the order associated with the interaction       |
| Order date time          | Date and time of the order                                     |
| Issue reported at        | Timestamp when the issue was reported                          |
| Issue responded          | Timestamp when the issue was responded to                      |
| Survey response date     | Date of the customer survey response                           |
| Customer city            | City of the customer                                           |
| Product category         | Category of the product                                        |
| Item price               | Price of the item                                              |
| Connected handling time  | Time taken to handle the interaction                           |
| Agent name               | Name of the customer service agent                             |
| Supervisor               | Name of the supervisor                                         |
| Manager                  | Name of the manager                                            |
| Tenure Bucket            | Bucket categorizing agent tenure                               |
| Agent Shift              | Shift timing of the agent                                      |
| CSAT Score               | Customer Satisfaction (CSAT) score                             |

---

## ⚙️ Project Structure

```bash
Flipkart-Project/
├── data/
│   └── Customer_support_data.csv       # Raw dataset
├── notebooks/
│   ├── last_version_EDA.ipynb          # Data analysis and visualization
│   └── last_version_model.ipynb        # Feature engineering and model training
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation
