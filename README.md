# Apriori-Algorithm
Serial implementation of Apriori Algorithm
(Implementation has features that require c++11 or its successor versions)

Agruments : "min. support count" "min. confidence" "dataset"
Dataset : Space seperated items with '-1' as a delimiter for each transaction.

Sample dataset - "small_set.in"

Sample Usage commands:
$ g++ Serial_Apriori.cpp
$ ./a.out 2 70 small_set.in 
