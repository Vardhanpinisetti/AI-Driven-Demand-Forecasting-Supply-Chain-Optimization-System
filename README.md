# AI-Driven-Demand-Forecasting-Supply-Chain-Optimization-System ##

Efficient supply chain and inventory planning relies heavily on anticipating customer demand. Stock-outs, excess inventory, and inaccurate procurement decisions can significantly impact profitability and customer satisfaction. Traditional forecasting methods often overlook key real-world factors such as pricing strategies, seasonal effects, promotions, epidemic influences, or regional shopping patterns.

This project solves that by building an **AI-powered demand forecasting system** using historical sales, pricing, and environmental variables. Through **exploratory data analysis, feature engineering, and machine learning modeling**, this system learns complex relationships between business drivers and actual product demand. The model identifies the most influential factors—such as units sold, promotions, pricing, seasonality, and competitor pricing—along with time-based behavioral patterns (monthly cycles, week-seasonality, weekdays/weekends, etc.).

The final trained model generates **future demand predictions for the next 90 days**, enabling organizations to:

* 📦 Optimize stock replenishment and avoid shortages
* 🚚 Improve supply-chain planning and logistics timing
* 💰 Increase revenue using data-driven promotions and pricing
* 🏭 Reduce inventory holding costs and dead stock
* 📊 Strengthen decision-making with predictive insights

By saving the model (`demand_forecasting_model.pkl`) and forecast output (`future_forecast.csv`), the system is **production-ready** and can be used to automate forecasting dashboards, integrate into ERP systems, or power interactive applications like Streamlit or Power BI.

This project demonstrates practical application of:

* Time-series forecasting
* Feature engineering and preprocessing
* Machine learning model comparison (Linear Regression, Decision Tree, Random Forest, XGBoost)
* Real-world dataset handling and evaluation metrics (MAE, RMSE, MAPE)
* Model deployment and automation readiness







