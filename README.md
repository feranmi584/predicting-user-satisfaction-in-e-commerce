# predicting-user-satisfaction-in-e-commerce
## predicting and improving user satisfaction in e-commerce platforms using machine learning
The aim of this project work is to predict and improve user satisfaction in an e-commerce platform using machine learning.
The objectives are:
1. To predict the level of satisfaction of customers and users based on feedback data
2. Developing a deployable machine learning model, trained and the accuracy and efficiency of the model will be tested to predict user satisfaction
3. Understanding the factors that are significant to user satisfaction and looking to improve on those factors 
# System Description
Our system was created using python language and was deployed using streamlit and ngrok as our tunnel to visualize our model.
# What The System Does
This system classes user satisfaction which is our target variable with other sufficient variables from our data that can help to improve predicting user satisfaction.
Our goal of creating the system as explained in our aims and objectives above is to be able to predict user satisfaction and to note on areas where we can improve user satisfaction with the system created.

For this system, we used Customer Review and Customer Rating as our variables to predict user satisfaction.
An algorithm called a vectorizer which is able to separate positive comment from negative comment was used to analyse the customers review written comment when it was inputted.
  Then, the score of the customer rating also determined for the customer rating score. Two other algorithms where then used and tested which were the DecisionTreeClassifier and the RandomForestClassifier.
For the customer rating variable, it has indicated that if the rating is greater than or equals to 3, then it is a good rating and shows us that the customer is satisified which then solves the 50 percent of the puzzle for user satisfaction. The other 50 percent is to be covered by the customer review variable.
  After variables are inputted, we click on the predict/go button  for the machine learning model to do its work. The model then combines the variables and classifies them into 0’s and 1’s. In this scenario, 0 interprets to not satisfied while 1s interprets to the user being satisfied based on the customers review and customer rating which are the factors that were used to determine user satisfaction. 
  For example, if a customer review says ‘It is a bad product’ and the rating is gauged as ‘2’ out of ‘5’, the output will be 0 which then indicate and means ‘not satisfied’ and It concludes that the customer was not satisfied.
# Benefit Of The Model 
1.	User-Friendly & Accessible – The model is simple and integrated into a Streamlit app, allowing non-technical users to analyze customer reviews without coding knowledge.
2.	Efficient Deployment – Streamlit enables quick and seamless integration of machine learning models into web applications without requiring web development expertise.
3.	Scalability & Security – The model can be deployed on cloud platforms (AWS, Google Cloud, Azure) to handle large user volumes while maintaining performance and data security.
# How Our Prediction Model Improves Customer Satisfaction on Jumia
1. Enhancing Checkout Experience – Identifies pain points in the checkout process through customer reviews, helping Jumia streamline and optimize it.  
2. Refining Product Catalog – Analyzes reviews to detect trends in preferences and complaints, enabling Jumia to improve product quality and selection.   
3. Automating Satisfaction Analysis – Uses machine learning to assign satisfaction scores, allowing Jumia to quickly address customer concerns proactively.

# Recommendations
 1. Integrate Satisfaction Model – Use machine learning to predict customer satisfaction and detect dissatisfaction based on real-time user data.
 2. Continuous Model Improvement – Regularly update the model by comparing predictions with actual customer feedback. 
 3. Personalized Engagement – Leverage insights to tailor loyalty programs and marketing campaigns for high-value or dissatisfied customers.    
 4. Measure Impact – Track key metrics like satisfaction scores, NPS, and retention rates to assess the model’s effectiveness.

