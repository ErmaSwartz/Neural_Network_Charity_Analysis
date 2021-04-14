# Neural_Network_Charity_Analysis

### Overview of Analysis 
#### Data Preprocessing 
##### Variables considered model targets 
###### Status is our target variable, it is the y value in our model. 
###### All of the other variables are consider our X values, or the data that we use to make the prediction of Status 
###### The EIN and NAME columns are the columns we do not need because the information they provide is only relevant for organization on the side of the charities themselves. They provide no further information to our model and therefore are not neccesary for machine learning or for our analysis. 

#### Compiling, Training, and Evaluating the Model 
##### I added 9 nodes to my first hidden layer and 4 to my second hidden layer. Hidden layers can be understood as the nodes between the input and the output layers. Meaning, within the model there exists the variable we put in, (X values) and our target variable (y). The Hidden layers are the space between where the "thinking" happens. The number of nodes that I chose to use on the MLP occured as a result of experimentation. 
###### We were able to achieve the target performance. The main step that I took to achieve this is by experimenting with the amount of nodes on each level of hidden layers. 
![image](https://github.com/ErmaSwartz/Neural_Network_Charity_Analysis/blob/main/accuracy-99%25.png)
