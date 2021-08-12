## Predicting Catalog Demand
This project is the part of Udacity's Nanodegree program (Predictive Analytics for Business Nanodgeree)
## Project Overview
In this project, you will analyze a business problem in the mail-order catalog business. You're tasked with predicting how much money your company can expect to earn from sending out a catalog to new customers. This task will involve building the model and applying the results in order to provide a recommendation to management.
## Skills Required
In order to complete this project, you must be able to:
* Build a linear regression model and apply the results to a business problem.

## The Business Problem
You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this year's catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.

Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.

You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

## Details
- The costs of printing and distributing is $6.50 per catalog.
- The average gross margin (price - cost) on all products sold through the catalog is 50%.
- Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

## Steps to Success
### Step 1: Business and Data Understanding
Your project should include:
- A description of the key business decisions that need to be made.
Note: Clean data is provided for this project, so you can skip the data preparation step of the Problem Solving Framework.

### Step 2: Analysis, Modeling, and Validation
Build a linear regression model, then use it to predict sales for the 250 customers. We encourage you to use Alteryx to build the best linear model with your data.

Once you have your linear regression equation, you should use your linear regression equation to predict sales for the individual people in your mailing list.

### Hint
We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

## Data
p1-customers.xlsx - This dataset includes the following information on about 2,300 customers. 

Important: You should build your model on this dataset and not p1-mailinglist.xlsx.

p1-mailinglist.xlsx - This dataset is the 250 customers that you need to predict sales. This is the list of customers that the company would send a catalog to. Use this dataset to estimate how much revenue the company can expect if they send out the catalog. It includes all of the fields from P1_Customers.xlsx except for Responded_to_Last_Catalog so this variable cannot be used in the linear regression model since it could not be applied to the mailing list data set. It also includes two additional variables.
- Score_No: The probability that the customer WILL NOT respond to the catalog and not make a purchase.
- Score_Yes: The probability that the customer WILL respond to the catalog and make a purchase.

## Authors 
[@masabumair](https://github.com/masabumair023)

  