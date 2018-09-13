# Analysis of the NYC cab data and model training

This exercise is structured in three different notebooks:
1. Data exploratory analysis and some insights: here the data for one month is loaded and cleaning processes are tested. Also some exploratory analysis is performed to see some basic insights from the data
2. Data preparation: here the whole data to be used during the model training is cleaned, some features are created, and some other data is used to enrich our samples, and then it is saved for the next phase
3. Models: training, results and discussions

To replicate the results, the original input data (taxi data for the months of March, June and November 2017, zones file) must be placed in the directory `inputdata`. Additionally within this directory a `shapes` directory must exist containing the files from the shapes provided by the NYC gov. Also it is expected to have an `outputdata` directory which will hold the processed data (around 7.5GB).

The `h2o` directory contains results from the training performed within H2O.
