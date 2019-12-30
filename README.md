# Friend_recommendation_model
Given a directed social graph, have to predict missing links to recommend users (Link Prediction in graph)
 
 **@author : Akash Kumar<br/>
 https://www.linkedin.com/in/akash-kumar-9b87b5148/**

<br/>

<h2>Data Description</h2>

The code for the benchmarks may be downloaded from github. 

There are 5 files:
<br/>
**train.csv** contains the directed social graph, represented in a 2-column csv (source_node, destination_node)<br/>
**test.csv** contains a list of nodes to recommend other nodes to in a 1-column csv (source_node)<br/>
**bfs_benchmark.csv** contains a sample submission generated from bfs_benchmark.py<br/>
**top_k_benchmark.csv** contains a sample submission generated from top_k_benchmark.py<br/>
**random_benchmark.csv** contains a sample submission generated from random_benchmark.py<br/>

<br/>
Taken data from facebook's recruting challenge on kaggle data contains two columns source and destination eac edge in graph - Data columns (total 2 columns):<br/>

**source_node int64**<br/>
**destination_node int64**<br/><br/>
Type: DiGraph<br/>
**Number of nodes: 1862220**<br/>
**Number of edges: 9437519**<br/>
**Average in degree: 5.0679**<br/>
**Average out degree: 5.0679**<br/>
<br/>
Performance metric for supervised learning:<br/>
<ol><li>Both precision and recall is important so F1 score is good choice</li>
  <li>Confusion matrix</li></ol>
  
  
 Download the data from the link: **https://www.kaggle.com/c/FacebookRecruiting/data**<br/>
 Download the .pynb file and run it.
