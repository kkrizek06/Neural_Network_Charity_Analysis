**Overview of the analysis:**

The purpose of this analysis is to a build model that predicts if an applicant will be successful. We are looking to build a model that can predict success with a 75% (or better) accuracy. We are using deep learning to create this model. 

**Result:**

**o	Data Preprocessing**

**1) What variable(s) are considered the target(s) for your model?**
The target variable is the “Is Successful.” 

**2) What variable(s) are considered to be the features for your model?**
The feature variables where “Application type”, “Affiliation”, “Classification”, “Use Case”, “Status”, “Income amount”, “Special Considerations”, and “Ask amount”

**3) What variable(s) are neither targets nor features, and should be removed from the input data?**
Targets removed where “EIN”, “Name”, and “Organization. 

**o	Compiling, Training, and Evaluating the Model**

**1) How many neurons, layers, and activation functions did you select for your neural network model, and why?**

For attempt 1 I added a single hidden layer. I didn’t change the number of neurons for layer 1 and 2. I picked 10 neurons for layer 3. The reason for 10 was based on using 80 for layer 1, 30 for layer 2, so I wanted to pick an amount that would be using this trend. 

For attempt 2 I changed the activation function. I changed the function to the tanh function. I kept the amount of neurons the same.

For attempt 3 I increased the number of neurons. I kept layer 1 the same but increased layers 2 and 3. Layer 2 I increased to 40, and layer 3 I increased to 25. 

**2) Were you able to achieve the target model performance?**
No. All of my attempts came up short of the 75% goal. 

**3) What steps did you take to try and increase model performance?**
I eliminated the column “ORGANIZATION”, added layers, changed the activation function and increased the number of neurons. 

**Summary:**
Overall, I was unsuccessful in reaching the target accuracy of 75%. I recommend continuing to use the deep learning models. I recommend playing with the functions, neurons or data to increase the model’s proficiency. The reason for this conclusion is that I ran a couple of models (random forest, logistic regression) and the accuracy was far below the 72% that is achieved with my current model. 
