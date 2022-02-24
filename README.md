
<div class="alert alert-info" role="alert">
    <center><h1 style="color:red;"><strong><font color = red>Customer Behavioral Analytics</font></strong></h1></center></div>
<br><br>
Dave Wentzel  

Philadelphia Microsoft Technology Center  

Contact Information:  [LinkedIn](https://linkedin.com/in/dwentzel)

# What is this?

This is a short course/primer on how I do Customer Analytics using a _data-driven_ approach.  This is not meant to be all-inclusive.  This is meant to demonstrate an approach to performing **Prescriptive Analytics** using standard data analytics tools like:

* SQL (every business analyst should understand a _modicum_ of SQL).  
  * We will use `Synapse SQL Serverless` but we could use _any_ SQL tool that supports a SQL abstraction over files in a data lake.  `Databricks` is an excellent choice.  
* python/notebooks/Spark (data professionals use these tools but they are within the grasp of any business analyst)
  * We will use the tooling built into `Synapse`

But the **technology** is much less interesting than understanding a simple repeatable **process** to perform analytics that will actually _work_ for your **people** and their capabilities.  

> You do NOT need to be a python expert or understand advanced SQL.  What I will present is merely the thought processes that will help you on your analytics journey.  I switch between python and SQL a lot -- that is by design -- I choose the best tool for _me_ to accomplish a task, but you could use whatever YOU are comfortable with.  The MTC is here to help.  


<img src="./slides/Prescriptive.png" width="300" align="right">I consider _customer analytics_ to be part of what I call **Prescriptive Analytics**.  This means that the analytics we do are far more advanced than just _predictive_ or _descriptive_ (machine learning and basic BI reporting).  We want to provide our business with ideas regarding _What do we do next?_.  

# Customer Analytics

Without customers, your company is out-of-business.  The most successful companies are using customer behavior data to make key business decisions.  Many companies struggle with things like:

* customer segmentation
* loyalty
* understanding Customer Lifetime Value
* "optimizing" churn.  

I’ll bet your company has the data to tell which customers have churned and which might, but most struggle with “ok, now what do I do?”  As data professionals, we are uncomfortable making opinionated recommendations on what we should do next based on what the data is telling us.  In this session I’ll show you how to use data and analytics processes to understand customer analytics issues and how to help your business leaders interpret their data to answer the question: “What should we do next?”.  


**Customer Analytics** deals with using data and being _data-driven_ to:

* attracting the right customers (promotions)
* satisfying and meeting the needs of your customers
* retaining customers
* set the correct price point to maximize revenue (known as price optimization)

It's been proven (you can go find the links yourself) that if your business gets good at customer analytics it will definitely provide _lift_ to your business, in the form of higher profits and reduced costs.  

>But even more importantly, if you master the _Design Thinking_ and _Rapid Prototyping_ process that I use, and tailor it to YOUR business, these techniques will help you solve _ANY_ analytics problem.  

### So what is it?  

[Customer analytics](https://en.wikipedia.org/wiki/Customer_analytics) is a process where we use data from customer behaviors to help make key business decisions.  We use the outputs to determine how to do better direct marketing, store and warehouse site selection, and customer relationship management.  We want to predict customer behavior and determine how we can shape it.  

Some use cases:  
* marketing
  * increase response rates
  * improve campaign ROI by contacting the right customers with timely and relevant offers
* improve customer loyalty
* decrease attrition/churn by predicting the most likely churners and developing proactive campaigns to retain them.  
* segment customers more effectively to understand their behaviors.  
* come up with a calculation for _Customer Lifetime Value_ (usually abbreviated CLV or LTV) that we can use for tons of different business use cases.


# Today's Use Cases

Here's what we'll look at today:

* Customer Segmentation Analytics

