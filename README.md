# Neural_Network_Charity_Analysis
#### Overview:
The purpose of this challenge was to take data, test and train the data to produce an accuracy of 75 or above.

## Data Preprocessing:
*  What variable(s) are considered the target(s) for your model?
   
   #### Model variables:
    * Application Type
    * Affiliation
    * Classification
    * Use Case
    * Organization
    * Income Amount
    * Special Considerations
    
*  What variable(s) are considered to be the features for your model?
   
   #### Variable features included:
    * Application Type
    * Income Amount
    * Special Consideration
 
*  What variable(s) are neither targets nor features, and should be removed from the imput data?
   
   #### Columns removed:
    * Adult
    * EIN
    * Names

## Compiling, Training, and Evaluating the Model:

#### First Attempt: AlphabetSoupCharity
Used the initial coding
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    *  8 nodes for the first layer
    *  5 nodes for the 2nd layer
    *  100 Epochs
    
* Were you able to achieve the target model performance?
    *  No  Accuracy = .7245 Losses = .5551

#### What steps did you take to try and increase model performance?

#### Second Attempt: Optimize1
Duplicated from previous attempt code
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    *  Binning for ASK_AMT
    *  3 nodes for the first layer
    *  2 nodes for the 2nd layer
    *  25 Epochs
* Were you able to achieve the target model performance?
    *  No Accuracy = .7276 Losses = .5717
    
#### Third Attempt:  Optimize2  
Duplicated from previous attempt code
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    *  12 nodes for the first layer
    *  15 nodes for the 2nd layer
    *  75 Epochs
* Were you able to achieve the target model performance?
    * No Accuracy = .7289 Losses = .5511

#### Forth Attempt:  Optimize3  
Duplicated from previous attempt code
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    *  22 nodes for the first layer
    *  11 nodes for the 2nd layer
    *  40 Epochs
* Were you able to achieve the target model performance?
    * No Accuracy = .7263 Losses = .5527


#### Summary:

I was not able to achieve target of 75 or better.  I am not sure I complied the ASK_AMT correctly.  I did notice that depending on the hidden nodes I do not fully understand what I have completed.  I did enjoy the challenge.  I had some issues with the programs.  Had to pip install a few.  Had to update through Anaconda prompt.
Used Jupyter Lab.
