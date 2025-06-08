## ACTIVITIES:

Week 2 ACTIVITIES B and C:

**Activity B:**




    import pandas as pd


    # Load the dataset
    df = pd.read_csv("athlete_events.csv")


    # Show the first 5 rows
    print(df.head())


    # Show the column names
    print(df.columns)


Using this code we were able to view the first five athletes, their events, their IDs, and Medals for the Olympic Games. The "df.head" function shows the first five athletes and the
"df.tails" function shows the last five athletes.


**Activity C:**


Questions:


1. **How many columns are in the dataset?**

271,117 columns are in the dataset.


2. **Name three of them and explain what they represent.**


The sport they competed in, sex (their gender), and the games they competed in (1992 Summer Olympics.)


3. **What do the first 5 rows show?**


The first five rows show the first five athletes in alphabetical order.

**Activity 2:**

print(df['Sport'].value_counts().head())
print(df['Sex'].value_counts())


Using this code we can answer more questions provided:


1. *What are the top five sports?*


The top five sports include athletics, gymnastics, swimming, shooting, and cycling in order.


2. *How many male versus female athletes are there?*

About 196,594 males and 74,522 females have competed within the Olympic Games.


3. Using the code


[ print(df.describe()) ]


This code gives us the specific averages and percentages which let us answer the following questions:


1. *What is the average age?*


The average age is 25.5 years old.


2. *What is the oldest and youngest athlete?*


The oldest athlete is 97 years old and the youngest athlee is 10 years old.


3. *Are there any columns with missing or strange values?*


The total count of the numbers are incredibly large however it is because of all the values being added.

**Extension:**

The code

This code indicates the number of countries in ascending order. URS (User Requirement Specification) refers to the requirements and expectations of the users within the system. GDR (Generalised Dimensionality Reduction) is a tecnique that reduces the number of variables in a dataset to make it more organised without removing any crucial information. FRG (Feature Ranking and Grouping) is a method for ranking and categorising features.


 






