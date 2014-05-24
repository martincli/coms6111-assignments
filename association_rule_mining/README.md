COMS E6111 Advanced Database Systems<br/>
Project #3: Association Rule Mining

Assignment
----------
The purpose of this assignment was to implement the apriori algorithm on a real-world dataset and output association rules with sufficient support and confidence.

Running
-------
The program is written in Python version 2.7. To run:
>python main.py INTEGRATED-DATASET.csv \<MIN_SUPP\> \<MIN_CONF\>

MIN\_SUPP and MIN\_CONF should be numbers between 0 and 1.

Description
-----------
The included file 'INTEGRATED-DATASET.csv' is taken from NYC Open Data (https://data.cityofnewyork.us/Business/NYC-Jobs/kpav-sd4t). The program manipulates the data in a way that is specific to this dataset.

The output of a sample run (with 5% minimum support and 50% minimum confidence) is included in 'example_run.txt'.