# MapReduce-based-Mini-HIVE 

## Abstract
Mini-Hive is an SQL based engine which gives an SQL like interface to query data stored in various databases and file systems that integrate with Hadoop.
It uses the Map Reduce Programming model for the same. MapReduce is a framework using which we can write applications to process huge amounts of data, in parallel, on large clusters of commodity hardware in a reliable manner.

## Map-Reduce Programming Model
MapReduce is a processing technique and a program model for distributed computing based on java. The MapReduce algorithm contains two important tasks, namely Map and Reduce. Map takes a set of data and converts it into another set of data, where individual elements are broken down into tuples (key/value pairs). Secondly, reduce task, which takes the output from a map as an input and combines those data tuples into a smaller set of tuples. As the sequence of the name MapReduce implies, the reduce task is always performed after the map job.

## Algorithm and Design
Mini-Hive implements functionalities of SQL like SELECT and PROJECT queries along with the use of three aggregate functions - min, max, and count, using Map-Reduce to query data stored in databases integrated with Hadoop. 

LOAD query is used to load the database from the HDFS and also to store the schema in a file in the HDFS.

![MR Flow chart](https://github.com/sharanyavenkat25/MapReduce-based-Mini-HIVE/blob/master/sqlEngine/MapReduce_flowchart.jpg)

