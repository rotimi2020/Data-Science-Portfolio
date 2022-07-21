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
  [Dataset](https://github.com/rotimi2020/Boston-Prediction/blob/main/Boston.csv)<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Boston-Prediction)
 
## Advanced-Price<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Advanced-Price)
  
## Sonar-prediction<br>
  [Jupyter Notebook](https://github.com/rotimi2020/Sonar-prediction)
