# **Smart Retention**

**This is the project made for the hackathon Datathon 2025 held in KJSCE on 1-2nd Feb, 2025.**

**In this project we have developed two models to help streaming services reduce the customer churn by offering insights into their uses and providing predictions if the customer might leave the subscription or not.**
**Two models have been created for this project, both have been created using the XGBoost algorithm.**

**We chose XGBoost for this project due to several key advantages that align perfectly with the
requirements of churn prediction:**


  a) High Accuracy: XGBoost consistently outperforms traditional machine learning algorithms due to its advanced
    boosting techniques, making it ideal for detecting subtle patterns in complex customer behavior data.


  b) Handling Complex Relationships: Our dataset involves intricate interactions between features like usage
    patterns, tenure and cost. XGBoost effectively models these relationships, capturing non-linear dependencies.


  c) It’s biggest reason was its class imbalance techniques which was unavailable in adaboost which had promising
    results at start but at the end had massively imbalanced classes causing issues

**The reason we developed 2 models was because both of them have different use cases and the service can use any which suits their given use case at a particular time**
**The use cases are:**
1. **Recall Focused : Used to find as many customers which are at risk of churn, the model will capture most potential churn cases but might also flag customers which are not at risk. It is ideal for proactive customer retention straterfies where retention is more important than reducing churning.**  
2. **Precision Focused : Used to minimize false positives, it ensures that most of the predicted customer are genuinly at risk of churning. It is suitable for cost effective interventions such as offering discounts or premiums only to true churn risks.**
    
