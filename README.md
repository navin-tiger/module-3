# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

1) Linear regression
 
 2) Decision Tree
 
 3) Random Forest

## Steps performed
 1)  We prepare and clean the data. We check and impute for missing values.
 2)  Features are generated and the variables are checked for correlation.
 3)  Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 4)  All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To run the code
1) we have to create an environment from env.yml file which is attached in this repository.
2) First we have to download that file and save it in working directory.
3) "conda env create -f environment.yml" Type this command in the terminal.
4) Now we can see newly created environment by typing the command "conda env list".
5) Activate the environment -- "conda activate mle-dev"
6) Now execute the python script "python nonstandardcode.py".

## To execute the script
$
conda env create -f environment.yml"

$
conda activate mle-dev"

$
python nonstandardcode.py"


