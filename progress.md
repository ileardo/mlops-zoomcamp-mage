## Module 3: Orchestration and ML Pipelines
*  3.0 Introduction: ML pipelines and Mage
    * 3.0.1 ML Pipelines. Resources: [end-to-end ML lifecycle guide](https://mageai.notion.site/The-definitive-end-to-end-machine-learning-ML-lifecycle-guide-and-tutorial-for-data-engineers-ea24db5e562044c29d7227a67e70fd56)
    * 3.0.2 Running Mage

* 3.1 Data preparation: ETL and feature engineering
    * 3.1.1 Ingestion
        - Creating new project
        - Data preparation - Ingestion
        - Utility helper function
    * 3.1.2 Data preparation
        - Prepare block

    * 3.1.3 Build training sets
        - Encoding function
        - Training set block
    * 3.1.4 Data validation using built-in testing framework
        - Writing data validation

* 3.2 Training: sklearn models and XGBoost
    * 3.2.1 Training pipeline for sklearn models
        - GDP training set
        - Sklearn training GDP
        - Load models
        - Utility helper function for loading models
        - Hyperparameter tuning
        - Train sklearn model
    * 3.2.2 Training pipeline for XGBoost models
        - Hyperparameters tuning
        - Train XGBoost model

* 3.3 Observability: monitoring and alerting  
    * 3.3.1 Pipeline health monitoring  
        - Sklearn training pipeline health  
    * 3.3.2 Explaninability  
        - Customize layout  
        - XBGoost expplainability dashboard  
    * 3.3.3 Model performance dashboard  
        - Overview dashboard for entire project  
        - RMSE and MSE using time series chart  
        - RMSE ditribution using a histogram  
        - Training runs by model using bar chart  
        - Training runs by model using pie chart  
    * 3.3.4 Alerting  
        - Setup email to send alerts
        - Setup pipelines alerting

* 3.4 Triggering; inference and retraining
    * 3.4.1 Retraining pipeline
        - Setup pipeline
        - Trigger pipeline to run 
    * 3.4.2 Inference pipeline
        - Make a prediction
        - Build pipeline
        - Model inference playground part 1
        - Model inference playground part 2
        - Get prediction via API

    