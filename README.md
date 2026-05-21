# ai-sales-prediction
AI Sales Prediction using Python & Machine Learning

This project focuses on analyzing retail sales data from the Superstore dataset and building a machine learning model to predict future sales. The main idea of the project is to help understand how business data can be used to make better decisions and forecast future performance.

In this project, I first imported all the required Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. These libraries were used for data handling, visualization, and building the prediction model. After that, I loaded the dataset from an Excel file using Pandas and explored it by checking its structure, column details, and statistical summary. This helped me understand what kind of data I was working with.

Then I moved on to data cleaning. I checked for missing values and removed duplicate records to ensure the dataset was clean and reliable. I also converted the order date and ship date columns into proper date format so that they could be used for time-based analysis. From the order date, I extracted new useful features like year, month, day, and weekday. These new features helped in analyzing sales patterns over time in a better way.

After preparing the data, I performed exploratory data analysis to understand how sales were behaving. I analyzed yearly sales trends by grouping data based on year and visualized it using a line graph. This helped in understanding whether the business was growing over time. I also studied monthly sales trends to see which months had higher or lower sales, which can help businesses plan their marketing and stock management.

I further analyzed the top 10 products based on total sales to identify which products were performing best in the market. Along with that, I examined region-wise sales to understand which geographical areas were generating more revenue. These insights helped in identifying strong and weak areas in the business.

After completing data analysis, I moved to the machine learning part of the project. I selected year and month as input features and sales as the target variable. The dataset was then split into training and testing sets so that the model could be trained and evaluated properly. I used the Linear Regression algorithm to train the model on historical sales data so it could learn patterns and relationships in the data.

Once the model was trained, I used it to predict sales values for the test data. To evaluate the performance of the model, I calculated errors using Mean Absolute Error and Root Mean Squared Error. I also created a scatter plot to compare actual sales values with predicted values to visually understand how well the model was performing.

Finally, I used the trained model to predict future sales for the year 2026 for different months. This shows how the model can be used for forecasting future business performance, which is useful for planning inventory, improving marketing strategies, and making data-driven decisions.

Overall, this project helped me understand the complete workflow of a data science project starting from data cleaning, analysis, visualization, to building a machine learning model. It also improved my understanding of how real-world businesses can use data to predict future outcomes and improve decision-making.