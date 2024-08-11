# BIG DATA ANALYTICS USING PYSPARK AND SPARKSQL

## Task 1

Index a set of documents and build a function to search through these documents using the index.

## Task 2
Read the data (all the files in the ‘data’ directory) using the function textFile. Take only the “text” part of each article and count the frequency of all the words (convert the text into lowercase). Remove (Filter) any word whose frequency is less than 10.

Report the following:

a. Total size of the output data (after the filtering).                    

b. Frequency of the following words – congress, London, Washington, football.                 

c. The word with maximum frequency for each month (hint: to read only a month’s articles you can use ‘’. E.g. for February ‘2012-02’ represents all files starting with 2012-02,i.e. files belonging to Feb).           

d. The list of words appeared on ‘2012-09-01’ but not on ‘2012-08-01’.            

e. Frequency of the word ‘monsoon’ for all months.


## Task 3

build a model to predict taxi fare from trip distance and a model to predict taxi fare from trip distance and trip duration in minutes.

a. What is the fare of a 20-mile-long trip using M1.                                

b. What is the fare of a 14-mile trip that took 75 minutes using M2                   

c. Which fare is higher 10 mile trip taking 40 min or 13 mile trip taking 25 min?               

d. compute the average tip amount               

e. During which hour the city experiences the most number of trips? E.g. 10 am-11 am or 4 pm-5 pm               

f. Divide the data into 10 parts: 10%, 20%, …, 100%           

g. Plot the time taken by each method.             

## Task 4 
a directed graph with 25 nodes (node 1 to node 25) Read and store the data as an adjacency list.

a. Find all self-loops (i.e. edge between a node onto itself)

b. Node with the largest out-degree

c .Node with the larges in-degree

d. Find the distribution of vertices in-degrees

e. Find a path between node 1 to node 9 

## Task 5

The following file contains information about permits issued to export wildlife items/products. wildlife_trade.csv Use SparkSQL and other Spark utilities to answer the following question

a. what is the most frequent Class of animal traded

b. List all the items (Term) traded that are associated with Mammals

c. List all CITES Appendix II species

d .What is the most common animal (Taxon) traded in 2017?

e. List all the Classes of animals where the following items are traded

i) teeth

ii) live

ii) carvings
