# PySpark
For an **interactive preview**:<br><br>
1 - You can edit and run the notebook by importing it into your Databricks account. After clicking `Workspace` select Import from any folder's menu and paste the URL that shows up → [here](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1199654668581148/4023091891084761/7048844156867682/latest.html)

2.1 - If you don't have a Databricks account, set up your Databricks account and create a workspace → [<img src="https://go.granicus.com/rs/231-DWB-776/images/databricks.png" width="10%">](https://databricks.com/)</br> 

2.2 - If you want a previous detailed explation of how it works → [click here](https://docs.databricks.com/getting-started/account-setup.html)
- - - 
 > - PySpark is the ‘product’ of the collaboration beteween `Apache Spark` and `Python`.
 > - PySpark is the `Python API` for Apache Spark, an open source distributed computing framework that provides some of the most popular tools used to carry out common Big Data related tasks.
- - - 
<br>

###	Aim: To create a ML model with PySpark that predicts which passengers survived the sinking of the Titanic. 

→	**Considering** that the **Titanic ML competition is almost legendary** and that **almost everyone** (competitor or non-competitor) that **tried to tackle the challenge** did it either with **python or R**, I decided to use **Pyspark, having run a notebook in Databricks** to **show how easy can be to work with PySpark**, namely regarding:<br>

> -	EDA
> -	Feature Selection
> -	Feature Engineering
> -	Train-Test Split (within the training set)
> -	Pipelines
> -	Classification: a baseline model and hyperparameter tuning with Crossvalidator
