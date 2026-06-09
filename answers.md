Part 5 – Linear Regression Answers



1\. What is the slope?



The slope values are:



\* Study\_Hours = 3.4549

\* Attendance = 1.3449

\* Assignments = -2.4027



These values are called coefficients in a multiple linear regression model.



2\. What is the intercept?



The intercept is:



\-48.1006



3\. What do they mean?



The coefficient for Study\_Hours (3.4549) means that for every additional hour studied, the predicted marks increase by approximately 3.45 marks, keeping other factors constant.



The coefficient for Attendance (1.3449) means that for every 1% increase in attendance, the predicted marks increase by approximately 1.34 marks, assuming other factors remain unchanged.



The coefficient for Assignments (-2.4027) means that increasing assignments by one unit decreases the predicted marks by approximately 2.40 marks in this trained model. This negative value occurs because the model learned this relationship from the small dataset used.



The intercept (-48.1006) represents the predicted marks when all feature values are zero. It serves as the starting point of the regression equation.







part 7



Which student had the highest prediction error?



The student with Actual Marks = 35 had the highest prediction error.



Actual Marks = 35

Predicted Marks = 31.24

Difference = 3.76



The highest prediction error was observed for the student whose actual marks were 35. The model predicted 31.24 marks, resulting in an error of approximately 3.76 marks.



Part 8



1\. What is MAE?



MAE (Mean Absolute Error) measures the average difference between the actual values and the predicted values. A lower MAE indicates better model performance.



MAE = 1.3454



This means that, on average, the model's predictions differ from the actual marks by about 1.35 marks.



2\. What is R² Score?



R² Score (Coefficient of Determination) measures how well the model explains the variation in the data. Its value ranges from 0 to 1.



R² Score = 0.9930



This means the model explains approximately 99.3% of the variation in student marks.



3\. Is your model performing well?



Yes, the model is performing very well. The MAE value is low, indicating small prediction errors, and the R² Score is very close to 1, indicating excellent predictive performance.



# Research Answers:



1\. What is Machine Learning?



Machine Learning is a part of Artificial Intelligence that helps computers learn from data and make decisions without being directly programmed. Instead of following fixed rules, the computer finds patterns in the data and uses them to make predictions. For example, a machine learning model can predict a student's marks based on study hours and attendance. Machine learning is widely used because it can handle large amounts of data and improve over time. It is used in many fields such as healthcare, education, banking, shopping, and social media. Machine learning helps solve problems faster and more accurately by learning from previous data and experiences.



2\. What is Linear Regression?



Linear Regression is a machine learning algorithm used to predict numerical values. It finds the relationship between input variables and an output variable. In this assignment, study hours, attendance, and assignments are used to predict marks. Linear Regression draws the best-fit line through the data and uses it to make predictions. It is one of the simplest and most commonly used algorithms because it is easy to understand and implement. It is widely used in prediction tasks such as sales forecasting, salary prediction, and student performance analysis.



3\. What are Features?



Features are the input values used by a machine learning model to make predictions. They provide information that helps the model learn patterns from the data. In the student performance dataset, Study\_Hours, Attendance, and Assignments are the features. Features are important because they directly affect the model's prediction. Choosing relevant features improves the accuracy of the model. Different datasets may have different features depending on the problem being solved.



4\. What are Labels?



Labels are the output values that the machine learning model tries to predict. They are also called target variables. In this assignment, Marks is the label because it is the value we want to predict. During training, the model learns the relationship between features and labels. After learning, it can predict labels for new data. Labels play an important role in supervised learning because they help the model understand the correct output.



5\. What is the Difference Between Training Data and Testing Data?



Training data is used to teach the machine learning model. The model learns patterns and relationships from this data. Testing data is used after training to check how well the model performs on new data. In this assignment, the dataset was split into 80% training data and 20% testing data. Using separate testing data helps us evaluate the model fairly and check whether it can make accurate predictions. Training data is for learning, while testing data is for evaluation.



6\. Where is Machine Learning Used in Real Life?



Machine Learning is used in many areas of daily life. Online shopping websites use it to recommend products. Streaming platforms suggest movies and songs based on user preferences. Banks use machine learning to detect fraud and manage risks. Hospitals use it to help diagnose diseases. Social media platforms use it to show personalized content and advertisements. In education, machine learning helps analyze student performance and provide learning recommendations. These applications make services faster, smarter, and more useful for users.





