**df.groupby(["Sex", "Pclass"])["Survived"].mean()**

What this shows:
*df.groupby("Sex")*  
Split the Titanic dataset into two groups: all rows where Sex == "male" and all rows where Sex == "female".
*["Survived"]*  
From each group, select the Survived column (0 = died, 1 = survived).
*.mean()*  
Calculate the average of that column within each group.
Since the column is 0/1, the mean becomes the survival rate.

**df["column_name"].value_counts().plot(kind="bar")**
This gives you a bar chart

**df["column_name"].plot(kind="hist", bins=30)**
This gives you a histogram where you can customise the number 30 to give u a different number of bars

**df["column_name"].plot(kind="line")**
This gives you a line graph

**import os
os.listdir()**
if you cant find something in github run this to find out whats saved in your notebook and under what name cause it could be your refercing the wrong name 


Titanic Data Analysis

Key Insights:

1. Female passengers had a much higher survival rate than male passengers.

2. First-class passengers had the highest survival rate.

3. Most passengers travelled in third class.

4. Ticket prices were significantly higher in first class.

5. Most passengers were between 20 and 40 years old.
