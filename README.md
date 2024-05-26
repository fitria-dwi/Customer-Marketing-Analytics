# Customer Marketing Analytics: Segmentation and Prediction

_Created by Fitria Dwi Wulandari – February, 2024_

### **Project Background**
iFood is an online food ordering and delivery service in Brazil. The company has had solid revenue over the past three years. However, the profit growth prospects for the next three years are not promising. To overcome this challenge, the company is exploring strategic initiatives to reverse this situation by enhancing its marketing campaign performance. By uncovering valuable insights, the company wants to drive and optimize marketing campaigns for sustained growth.

### **Objectives**
This project seeks to maximize customer value and improve campaign profitability by:
* Performing customer segmentation analysis.
* Developing predictive models to predict customer responses to marketing campaigns.

### **Methodology**
#### <code style="color : darkpurple">Data Preparation</code>
* **Source**: Data obtained from [Kaggle](https://www.kaggle.com/datasets/jackdaoud/marketing-data), which includes various customer attributes and purchasing behaviors.
* **Actions**: Clean and preprocess the data to ensure quality and consistency for analysis.

#### <code style="color : darkpurple">Exploratory Data Analysis (EDA)</code>
* **Purpose**: Discover patterns, spot anomalies, and gain a deeper understanding of the data's characteristics.
* **Techniques**: Use of various visualization techniques to explore and understand the data.

#### <code style="color : darkpurple">Customer Segmentation</code>
* **Principle**: RFM (Recency, Frequency, Monetary) analysis.
* **Method**: K-Means clustering to organize customers into specific groups based on shared characteristics or behavior.

#### <code style="color : darkpurple">\Machine Learning</code>
* **Purpose**: Build models to forecast customer responses to marketing campaigns.
* **Algorithms**: Six different algorithms were evaluated to determine the best model.
  
#### <code style="color : darkpurple">Dashboard Creation</code>
* **Purpose**: Present data in a clear and approachable way, facilitating decision-making processes.

#### <code style="color : darkpurple">Tools</code>
* **Programming Language**: Python.
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
* **Data Analysis and Visualization**: Tableau for creating dashboards and visual representations of the data.

### **Results**
* The results revealed four distinct customer segments based on purchasing behavior. To optimize marketing efforts, iFood needs to develop customized strategies for each segment, addressing their specific needs and preferences.
* The XGBoost model, achieving an accuracy of 94%, was the most effective for predicting customer responses to future campaigns. This model enables more accurate decision-making and efficient resource allocation, enhancing the profitability of marketing campaigns.

### **Future Work**
* **Advanced Analysis**: Explore advanced analytics techniques for deeper insights into customer behavior and market trends.
* **Refinement of Customer Segmentation Strategies**: Explore advanced clustering techniques or alternative segmentation methods to further refine customer groups.
* **Model Improvement**: Further hypertuning the models and exploring advanced algorithms to improve performance.

### Repository Contents
* [**Presentation Deck**](https://github.com/fitria-dwi/Customer-Marketing-Analytics/blob/main/Slide_Customer%20Marketing%20Analytics_Fitria%20Dwi.pdf): Detailed reports on findings, insights, and recommendations.
* [**Script Python**](https://github.com/fitria-dwi/Customer-Marketing-Analytics/blob/main/Code_Script_Customer_Marketing_Analytics_Fitria_Dwi.ipynb): Python scripts for data cleaning, visualization, model building.
* [**Dashboard**](https://public.tableau.com/views/CustomerMarketingAnalytics/Summary?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link): Tableau dashboards visualizing the key insights and metrics.
  
![Preview](https://github.com/fitria-dwi/Customer-Marketing-Analytics/assets/74573342/d0cc7ed4-77a2-4008-95b5-e75bed37b925)

### References
* https://github.com/nailson/ifood-data-business-analyst-test
* https://www.behance.net/gallery/97395037/iFood
