# Everything to know about Apache Hadoop

[ <br />
&nbsp;@ Open-source <br />
&nbsp;@ Data processing framework <br />
&nbsp;@ HDFS <br />
&nbsp;@ MapReduce <br />
&nbsp;@ Master/Slave architecture <br />
]

#### Quick Intro to Hadoop :
[ <br />
&nbsp;@ An open-source data processing framework <br />
&nbsp;@ written in Java <br />
&nbsp;@ is used to develop data processing applications which are executed in a distributed computing environment <br />
&nbsp;@ allows us to store and process big data in a distributed environment across clusters of cheap and widely available commodity computers using simple programming models <br />
&nbsp;@ data processing model is based on ‘Data Locality’ concept wherein computational logic is sent to cluster nodes(server) containing data <br />
&nbsp;@ such computational logic sent to cluster nodes is nothing but a compiled version of a program written in a high level language such as Java which processes data stored in HDFS <br />
&nbsp;@ designed to scale up from single servers to thousands of machines, each offering local computation and storage <br />
&nbsp;@ runs applications using the MapReduce algorithm, where the data is processed in parallel on different CPU nodes <br />
&nbsp;@  <br />
]

#### Big Data:
[ <br />
&nbsp;@ is also a data but huge in size <br />
&nbsp;@ refers to a term to describe collection of data that is huge in size and yet growing exponentially with time <br />
&nbsp;@ such a data that is so large and complex that none of the traditional data management tools are able to store it or process it efficiently <br />
&nbsp;@ could be found in three forms, such as **Structured**(employee table in a database), **Unstructured**(google search result) and **Semi-structured**(personal data stored in a XML file)<br />
&nbsp;@ **Volume**, **Variety**, **Velocity**, **Variability** are the characteristics of Big data <br />
for more click [here](https://www.guru99.com/what-is-big-data.html) [read] or [here](https://www.tutorialspoint.com/hadoop/hadoop_big_data_overview.htm) [read] <br />
]

#### Big Data challenges:
[ <br />
* Capturing data
* Curation
* Storage
* Searching
* Sharing
* Transfer
* Analysis
* Presentation
]

#### Hadoop Architecture:
[ <br />
&nbsp;@ Hadoop Common <br />
&nbsp;@ Hadoop YARN <br />
&nbsp;@ HDFS <br />
&nbsp;@ MapReduce <br />
]

#### MapReduce:
[ <br />
&nbsp;\> a computational model and software framework for writing applications which run on Hadoop <br />
&nbsp;\> divides the task into small parts and assigns those parts to many computers connected over the network, and collects the results to the final result dataset <br />
&nbsp;\>  <br />
]

#### HDFS:
[ <br />
&nbsp;\> takes care of storage part of Hadoop applications <br />
&nbsp;\> creates multiple replicas of data blocks and distributes them on compute nodes in cluster <br />
&nbsp;\> MapReduce applications consume data from HDFS <br />
]

#### References:
\> [https://www.tutorialspoint.com/hadoop/index.htm](https://www.tutorialspoint.com/hadoop/index.htm ) <br />
\> [https://www.guru99.com/bigdata-tutorials.html](https://www.guru99.com/bigdata-tutorials.html) <br />

### License

[MIT licensed](./LICENSE)
