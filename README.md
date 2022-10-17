# AI-Summit-2022

The AI Summit London

Hackathon

Problem 1: Using the data, compute what fraction of total EU GHG emissions are attributable to agriculture as a whole.

Approach: Using Pandas and countrygroups library on given "Agriculture Dataset_text.csv" , all data corresponding to EU countries is filtered out, emissions are summed and compared with the rest of world emissions.

Problem 2: Using the data, compute the fraction of total EU GHG emissions attributable to each agricultural product.

Approach: Using the cleansed data above, all data corresponding to each category of agriculture is summed column-wise. A plot is created for visual presentation.

Problem 3: Design an ideal diet that meets the nutrition requirements while minimising environmental cost.

Approach:
•	Algorithm: Linear Programming
•	Why: We chose this linear approach for multiple reasons. Few reasons being less amount of data available, a lot of time needed for data cleaning, time constraint overall and back propagation using gradient descent on cost function seems to be the best way to minimise cost (emissions) and maximise value (nutrition).
We have basically created two matrix one which represents all the food items with nutritional values and second with all the nutrient contents 
The dot product then needs to be compared with the cost function and the resulting cost function will be the maximum nutrient and minimum emission
