# Food Sales Predictions


# Dataset

For this project, I used a dataset from: Big Mart Outlets which has been collecting its sales data for 1559 products across 10 stores in different cities. There are 8,522 entries and 12 features.

# Data Dictionary

Source:https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement

![Screenshot 2021-10-22 030838](https://user-images.githubusercontent.com/55922514/138436405-5f0dde25-3045-43d9-8841-5099433bd411.png)

# Aim
The aim is to build a predictive model and predict the sales of each product at a particular outlet.



# Observation One: What Is the Relationship Between Sales and Item Visibility?

When looking at the relationship between sales and item visibility, it is interesting that as visibility goes up, then sales go down—not sure what that means: it could be that something is wrong with the data since we see that visibility data has a zero within the data—not sure how to interpret.



![image](https://user-images.githubusercontent.com/55922514/138441941-280737aa-477b-49c1-b0c3-d47563e6022b.png)


# Observation Two: What Is the Relationship Between Sales and Outlet type?

Within the boxplot, we see that sales are better at supermarket type 3 and that grocery store does the worse in terms of sales.


![image](https://user-images.githubusercontent.com/55922514/138442076-f77e64ec-3123-4066-a093-8c291f4b7da5.png)


# Observation Three: What Is the Relationship Between Sales and Outlet type: Including Both Tier Type & Size?

We can see that given outlet type, then sales tend to be better: but two interesting things is that: for supermarket type 2 and type 3, tier 3 is consistent—we also see that outlet size does not play much of a role, except when looking at supermarket type 1.

![image](https://user-images.githubusercontent.com/55922514/138442205-ff06f614-3be0-4d76-bf20-41283de50dc4.png)




# Observation Four: What Is the Relationship Between Sales and Item MRP: Including both item fat content & item weight?

We see that as an item is more expensive, that yields greater sales-moreover; we also see that item fat content does not play much of a role given that it is spread equally same is true with item weight.

![image](https://user-images.githubusercontent.com/55922514/138443199-3c468d5a-721b-49fd-9c80-f7aa70d86225.png)




# Feature Importance


![Screenshot 2021-10-22 035501](https://user-images.githubusercontent.com/55922514/138442652-94a9fadc-1f1b-42fe-bb8e-756788ce2adb.png)

# Model Performance




![Screenshot 2021-10-22 035428](https://user-images.githubusercontent.com/55922514/138442717-94e04ef8-ef74-473a-82e1-9afe8abba4ff.png)



