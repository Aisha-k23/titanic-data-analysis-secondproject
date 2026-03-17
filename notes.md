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


