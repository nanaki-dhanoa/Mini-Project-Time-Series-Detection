# Mini-Project-Time-Series-Detection
Submited by Nanaki Kaur Dhanoa (101903195)

For the prediction, I decided to go with only one model which generalizes over the different sections rather than creating a separate model for each section. I decided that because there was very little data associated with each section.

For the preprocessing I applied standardization over the dataset, and also removed a section for which no test row data was available.

For the model I decided to go with the Decision tree regression model, because for parameters 9-13 most of the data was integer type and also seemed to have a threshold type of structure (i.e. below a particular threshold the parameter values were completely zero). I felt that the decision tree would be able to capture this structure of the data much better. This approach gave a RMSE of 57.358.

I also tried using the Extra Trees regressor but it gave a much worse accuracy

