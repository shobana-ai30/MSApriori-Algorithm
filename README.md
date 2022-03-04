# MSApriori-Algorithm

This project is an implementation of the MSApriori Algorithm, which is a modified version of the Apriori Algotithm and is used to mine frequent item sets with a given minimum item support value.
The dataset consists of two data files which are basically text files where each line is a transaction and each item is represented by an integer.
The next set of input files are the parameter files which contain the minimum item support or MIS values of all items in the data files.
The ouput is in the following format. 
(Length-1 <number of length 1 frequent itermsets>
<length-1 itemset 1>
<length-1 itemset 3>
…
)
(Length-2 <number of length 2 frequent itermsets>
<length-2 itemset 1>
<length-2 itemset 3>
…
)
…
For example:
(Length-1 3
(1)
(2)
(11)
)
(Length-2 2
(1 2)
(2 3)
)
