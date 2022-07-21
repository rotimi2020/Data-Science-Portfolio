# Data-Science-Project

## Ionosphere-prediction
  1. Title: Johns Hopkins University Ionosphere database

2. Source Information:
   -- Donor: Vince Sigillito (vgs@aplcen.apl.jhu.edu)
   -- Date: 1989
   -- Source: Space Physics Group
              Applied Physics Laboratory
              Johns Hopkins University
              Johns Hopkins Road
              Laurel, MD 20723 

3. Past Usage:
   -- Sigillito, V. G., Wing, S. P., Hutton, L. V., \& Baker, K. B. (1989).
      Classification of radar returns from the ionosphere using neural 
      networks. Johns Hopkins APL Technical Digest, 10, 262-266.

      They investigated using backprop and the perceptron training algorithm
      on this database.  Using the first 200 instances for training, which
      were carefully split almost 50% positive and 50% negative, they found
      that a "linear" perceptron attained 90.7%, a "non-linear" perceptron
      attained 92%, and backprop an average of over 96% accuracy on the 
      remaining 150 test instances, consisting of 123 "good" and only 24 "bad"
      instances.  (There was a counting error or some mistake somewhere; there
      are a total of 351 rather than 350 instances in this domain.) Accuracy
      on "good" instances was much higher than for "bad" instances.  Backprop
      was tested with several different numbers of hidden units (in [0,15])
      and incremental results were also reported (corresponding to how well
      the different variants of backprop did after a periodic number of 
      epochs).

      David Aha (aha@ics.uci.edu) briefly investigated this database.
      He found that nearest neighbor attains an accuracy of 92.1%, that
      Ross Quinlan's C4 algorithm attains 94.0% (no windowing), and that
      IB3 (Aha \& Kibler, IJCAI-1989) attained 96.7% (parameter settings:
      70% and 80% for acceptance and dropping respectively).<br>
  [Download Dataset](https://github.com/rotimi2020/Ionosphere-prediction/blob/main/Ionosphere.csv)<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Ionosphere-prediction)
  
## Boston-Prediction
  Title: Boston Housing Data
Title: Boston Housing Data

Sources: (a) Origin: This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. (b) Creator: Harrison, D. and Rubinfeld, D.L. 'Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978. (c) Date: July 7, 1993

Download file : https://github.com/rotimi2020/Boston-Prediction/blob/main/Boston.csv

Relevant Information:

Concerns housing values in suburbs of Boston.

Number of Instances: 506

Number of Attributes: 13 continuous attributes (including "class" attribute "MEDV"), 1 binary-valued attribute.

Attribute Information:

CRIM: capita crime rate by town
ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: proportion of non-retail business acres per town
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX: nitric oxides concentration (parts per 10 million) [parts/10M]
RM: average number of rooms per dwelling
AGE: proportion of owner-occupied units built prior to 1940
DIS: weighted distances to five Boston employment centres
RAD: index of accessibility to radial highways
TAX: full-value property-tax rate per /10k]
PTRATIO: pupil-teacher ratio by town
B: The result of the equation B=1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT: % lower status of the population
MEDV: Median value of owner-occupied homes in ]
Missing Attribute Values: None.<br>

  [Download Dataset](https://github.com/rotimi2020/Boston-Prediction/blob/main/Boston.csv)<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Boston-Prediction)
 
## Advanced-Price<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Advanced-Price)
  
## Sonar-prediction<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Sonar-prediction)
