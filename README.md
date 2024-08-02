# Try the model here :
https://huggingface.co/spaces/varshaa08/Product_Categorization    

## Objective    
A wide variety of goods are frequently added on e-commerce sites. With this, a need of classification arises. Description of products are useful and can help figure out the category they belong to.   
With the same aim, a model has been built to automate the process. It categorizes them into 11 different categories :    
Baby Care    
Bakery, Cakes & Dairy     
Beauty & Hygiene     
Beverages     
Cleaning & Household     
Eggs, Meat & Fish     
Foodgrains, Oil & Masala      
Fruits & Vegetables              
Gourmet & World Food      
Kitchen, Garden & Pets      
Snacks & Branded Foods      

**Dataset** : https://www.kaggle.com/datasets/surajjha101/bigbasket-entire-product-list-28k-datapoints

## Approach    
Data was cleaned, converted into proper input format, divided into training and testing set.    
Several algorithms (Naive bayes, logistic regression, random forest, Support vector machine) were tried and evaluated through cross validation. Hyper-parameter tuning was done using GridSearchCV. At last the most reliable model was picked.    
Selected model (Support Vector Classifier) was trained on training data and evaluated using test set.    
Lasted it was deployed in hugging-face space using gradio.

##### Environment : Jupyter Notebook
##### language : Python
##### Libraries : Pandas, Numpy, matplotlib, seaborn, scikit-learn, nltk, joblib

#### Evaluation metrics :   
f1-score, precision, recall, Confusion matrix, accuracy
