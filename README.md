# MachineLearningSamples

This repo hosts variety of examples based on Apache Spark MLIB.

## Databricks Notebooks

### [Decision Tree](https://github.com/aosama/MachineLearningSamples/blob/master/databricks/DecisionTreeShapeExample.scala)

### [Census Income Decision Tree](https://github.com/aosama/MachineLearningSamples/blob/master/databricks/CensusIncomeDecisionTree.scala)

### [Census Income Random Decision Forest](https://github.com/aosama/MachineLearningSamples/blob/master/databricks/CensusIncomeDecisionTree.scala)

## Scala IDE Based Examples

### [Decision Tree](https://github.com/aosama/MachineLearningSamples/blob/master/src/main/scala/org/ibrahim/ezmachinelearning/DTShapeTypeExample.scala)
A vanilla decision tree example.

### [Decision Tree with Stratified Sampling](https://github.com/aosama/MachineLearningSamples/blob/master/src/main/scala/org/ibrahim/ezmachinelearning/DTShapeTypeStratifiedExamples.scala)
How to get a stratified sample so the test and train datasets are sampled accross possible values.

### [Decision Tree with Categorical Feature in the DataSet](https://github.com/aosama/MachineLearningSamples/blob/master/src/main/scala/org/ibrahim/ezmachinelearning/DTShapeTypeWithCategoricalFeaturesExample.scala)
How to index and encode categorical features.

### [Predicting Income Based on Census Data Using Decision Tree](https://github.com/aosama/MachineLearningSamples/blob/master/src/main/scala/org/ibrahim/ezmachinelearning/DTCensusIncomeExample.scala)
How to handle multiple categorical and continuous features on a real-life data set.
Uses the Census Income data set.

### [Predicting Income Based on Census Data Using Random Decision Forest](https://github.com/aosama/MachineLearningSamples/blob/master/src/main/scala/org/ibrahim/ezmachinelearning/RFCensusIncomeExample.scala)
How to handle multiple categorical and continuous features on a real-life data set.
Uses the Census Income data set.

## Data Sets References

#### [Census Income DataSet](http://archive.ics.uci.edu/ml/datasets/Census+Income)
First line from adult.test file removed for loading into Spark.

Census Income data set citation:
Dua, D. and Karra Taniskidou, E. (2017). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

#### [Default of Credit Card Clients DataSet](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
