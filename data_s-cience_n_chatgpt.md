# Data Science Workflow : Levereging Chatgpt for Productivity in Data Science related Task
## Objectives to document prompts use for data science related tasks
### 1. ChatGpt for Data Processing
* Mask  the sensistive information in the data
* upload to chatgpt or local llms
* Enter the prompt step by step while going through the output
  * can you perform some data preprocessing on this data 
  * can you suggest how we should proceed with this data.
* you can perform data preprocessing such as removal of duplicates value, map categogrical data to numeric data, fill missing value. <br>
... you even tell chatgpt to use and ml algorithm and impute the unknow from the dataset. All this should be capture in your prompt in an iteractive manner.
* However always fact check your result yourself. it should be to guide you.
* It is always good to have a well thought out plan as to what we want to do with the data. chatgpt should not replace out thought process, and it left to us decide and check the results.

### 2. Data Description for Chatgpt task for Data Science
You must be careful of sharing sensitive information with chat gpt, some of the things you can are:
* you can mask the sensitive columns such as the customer names and other personal features.
* The best approach will be to describe the features in your original dataset to chatgpt and allow it create a synthetic data base similar to the data you want to work with.
#### Examples
* __prompt__
<br>
hey chatgpt, I have the following four dataset and columns:
  * customers - customer_id, name
  * products - product_id, product_name, price_category
  * ratings - customers_id, product_id, rating
  * Orders - customer_id, product_id, order_id, date, quantity
Analyze the data and find out the following :
* Top performing products in terms of revenue and in terms of how many unit has been sold
* Identify top client for last month
* provide me with the python code to achieve this.

### Exploratory Analysis Using Chatgpt
* upload the synthetic
* enter the prompt: give me or carryout a description of the data and column and propose some eda in python.
* ask it to carry out the requried steps you wish to see.
* you can request it to reduce the number of bins if you have a large dataset maybe from 30bins  to 10bins
__note__: Always run code to and fact result gotten froom an llms, it can be misleading.
  
