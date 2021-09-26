# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

- _The purpose for the analysis of this project it was to create a binary classifier that could predict an applicant for alphebet soup will be succesfull if the funds were provided_.

## Results: Using bulleted lists and images to support your answers, address the following questions.

- _"EIN" and "NAME" are the columns for identification_ 
-  _"IS_SUCCESSFUL" variable is the way to confirm that the money was used in a right way._
-  _"APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION",_
-  _"STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT" were characteristics for this specific analysis._

## Data Preprocessing

![image](https://user-images.githubusercontent.com/82455263/134825154-68af98c9-deca-4643-8e12-b6631685eef9.png)

### What variable(s) are considered the target(s) for your model?
-  "IS_SUCCESSFUL" is the target.
### What variable(s) are considered to be the features for your model?
- All the bullets were considered to be the features for the model, however the most importants "IS_SUCCESSGUL" and " EIN " & " NAME"
### What variable(s) are neither targets nor features, and should be removed from the input data?
- The identification columns as " STATUS" , " SPECIAL_CONSIDERATIONS" were removed.

## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

- I select 2 layers 

![image](https://user-images.githubusercontent.com/82455263/134825558-3dc33432-4b14-4944-984a-d03a914d33b8.png)

### Were you able to achieve the target model performance?

![image](https://user-images.githubusercontent.com/82455263/134825574-3e024b33-c14a-481b-b539-087a7ba03e00.png)
![image](https://user-images.githubusercontent.com/82455263/134825900-7cf880b1-0484-4553-b521-743d7624d64b.png)
 
-  The performance for the first try it was excelent.

### What steps did you take to try and increase model performance?

![image](https://user-images.githubusercontent.com/82455263/134825609-155bacb9-40e5-456b-aab0-92a8a419f308.png)

-  I changed the Hiden layers values to try to test the best result for a Succesfull performance. 
 
![image](https://user-images.githubusercontent.com/82455263/134825727-98bcf367-684e-4200-bcfe-785a2b58d90c.png)

### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

- All the Atempts showed an accurace of more than 70%

##### - 1.-  Atempt 
![image](https://user-images.githubusercontent.com/82455263/134825831-616a2cfa-a887-479c-b3f0-99dbfc24e992.png)
##### - 2.-  Atempt
![image](https://user-images.githubusercontent.com/82455263/134825787-2083e6c3-b49f-4766-a34c-88fd26b01624.png)
##### - 3.-  Atempt
![image](https://user-images.githubusercontent.com/82455263/134825822-2c2b1176-e2b5-4e5a-b3c1-19dc8f5e5b94.png)



