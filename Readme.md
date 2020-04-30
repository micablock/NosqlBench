Frequently Used Code : 

drop table baselines2.keyvalue;

desc baselines2.keyvalue;

select * from baselines2.keyvalue;

truncate table baselines2.keyvalue;


Talking points : 

Part 1:

What is nosqlbench ? 
origins ? 
  - data generation capability came from ' Virtual Data Set' and core runtime and scripting harness was from 'EngineBlock'
who maintains it ? 
  - March 2020 we open sourced it for the community and other users so they can experience this new way of testing.
documentation location 
  - nosqlbench.io

Intro to how we will be doing the virtul workshop ? 

Note:  Flow available in the document we would be using. 

Level by Level : 
Level 1 - Basics of NoSqlbench

Cycle :
Cycle determines which statement is selected for execution and also the synthetic payload attached to it.

Activty : 
Set of statements in some sequence and ratio, activities run over the number of cycle. 

so lets so suppose you say : 

run = 10 Cycles 
Activity : 
   S1 - Do A 
   S2 - Do B
   ratio of 4:6 

then during the entire cycle - > A occurs 4 times and B occurs 6 times !! 
   
Driver : 

Scenario : 

Scenario Script : 

Workload Managed via YAMLS !! 
So, how do we define all you specific workloads into a YAML file !! 

Experimentation Friendly - > so one workload statment can be interpreted by different drivers example cql driver statments in stdout driver !

ok so lets start with writing a basic yaml test and then lets test it !! 

Level 1 Code : 

Ask them to try : 

Then Level 2 : Coding how it will work with CQL 

- create schema - keyspace and table 
- insert data 

How that works  .. explain binding functions 

then Level 3 : 
different phases - main phase 

probably end here !! 


