# KGE-DEM

## Data Processing

GetRedun/

getallredun.py :  Geting the triples related to the nearduplicate relationship.

GetDCR.py :  Extracting triple of Cartesian product relation in data， Cartesian product relation is listed in references。

GetRedun.py : Obtaining all redundant triples and non-redundant triples in the training set and test set.

getredunR.py : The nearduplicate relationship is obtained according to the calculation method in this paper.

revert.py :  Obtaining the reverse relationship according to the calculation method in the paper.

Rule.py : The file is to determine a related redundant triplet for each non redundant triplet. Firstly, the corresponding test set sorting results are obtained by using the trans training code, and then a related redundant triple (the head entity or tail entity are the same) is found for each non redundant triple, and the sorting result of the redundant triple is better.

## Train Model

X_DEM.py :  You can use the corresponding code training model.

## Test Model

X_DEM.py :  It is worth noting that the model and test are carried out separately. During the test, the "data2" in the code should be changed to "train2id", which will affect the filter index.

GetResult : You can use this file to calculate the relevant indicators of non redundant test sets and redundant test sets.