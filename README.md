# Non-profit donations investment analysis

### How many neurons and layers did you select for your neural network model?
   Based on the analysis selected 5 layers and each layer with varying neurons
   
   Layer 1 - 250
   Layer 2 - 125
   Layer 3 - 60
   Layer 4 - 30
   Layer 5 - 10


### Were you able to achieve target model performance?

   No, acheived accuracy of close to 74. 
   
### What steps did you take to try and increase model performance?

   To improve the model performance following transformation of features were added
   1. Bucketed ASK_AMT
   2. Filtered the row by classification if the value exists more than once to reduce noisy data
   3. Use OneHotEncoder to change Categorical value to Numerical value
   4. Use StandardScaler to scale the values
   
### If you were to implement a different model to solve this classification problem, which would you choose and why

   I would choose logistic regression classification which is good for probability.
