# Neural_Network_Charity_Analysis
Deep learning analysis

## Overview of the analysis:

We tried to analize data for doantions to figure out how to eliminate those that will not become successful. We used Neural Networks to create mode for our analysis

## Results: 

Data Preprocessing:
- We eliminated Name as well as EIN which we did not think will impact the resulst (in additional tests Status was also eliminated)
- The key variables was success or lack of success
- We needed to remove any variables that did not have direct impact on results. We had to reclassify any classification variable to provide numerical variables to evaluate in the model
- All the data had to be standardized

Training and Optimizatoin:
- Initial model included 2 layers, and 110 neurons total with RELU activation function - resulted in sub 75% accuracy 
- We tried to remove additional variables such as status to see if results will improve - no improvement
- We tried to increase the neurons in the model - again no improvement 
- We tried to test the model with Sigmoid and Tenth function - again this did not yield an improvement in performance


## Summary: 

Overall the model could only explain between 72-74% of the outcomes. Perhaps for classification - we could improve the performance by changing from neutal network to simpler Random Forest classification. 