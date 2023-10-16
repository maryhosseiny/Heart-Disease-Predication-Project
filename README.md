# Heart-Disease-Predication

## Introduction
Heart failure is a common form of cardiovascular heart disease that can lead to numerous complications, often fatal. The ability to predict, with reasonable accuracy, whether a patient is experiencing an undiagnosed heart disease is an extremely volatile procedure in modern healthcare. The objective of this project is to use a classification model and predict whether or not an individual currently has heart disease based on various health and physical attributes.

**Question:** Will an individual have a heart disease based on age, number of coloured vessels, and old peak values?

Age, Colored Vessels and Old Peak values were chosen as predictors because they generated the highest accuracy. As a result, they are used to find the K values for this classification model. The method for finding these predictors is later explained in Methods & Results: Data Analysis Section.

The dataset used in this project is a combination of four publicly available heart disease datasets on archive.ics.uci.edu; namely, Processed Cleveland Data, Processed VA Data, Processed Switzerland Data, and Processed Hungary Data. The datasets were combined in R to generate a larger, cross-continent data frame which includes a total of 920 observations with 15 attribute columns. It describes and utilizes 14 common biological characteristics to predict the probability of existing heart disease in patients.
