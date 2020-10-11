As nowadays there is a need for running organization from different geographical locations the need
for distributed database system also rapidly increases day by day. The two main things that the
distributed query processing depends for better performance and efficiency are fragmentation method
and allocation method. The fragmentation solution is basically used for analyzing query patterns.
This methods are not applicable during initial designing of databases ,we can make use of this
method only to the existing distributed databases. The semantics or relationship of the fragmented
data is not considered in most of the existing methods. While fragmenting if data relationship is
considered we can have much better and time effective fragments that can be easily retrieved.
Clustering technique can used to obtain the related data from datasets. In this project clustering
method for fragmentation is used. When we use clustered fragments instead of normal fragments ,we
get a minimum query retrieval time.


Horizontal Fragmentation Based on Data Semantics

Step1 : Run kproto.py to make clusters 

Step 2: Find  The similarity between clusters Run similarity.py

Step 3: Run the Fragment.py for simple Fragmentation

Step4 : Run cluster_fragment.py for cluster based Fragmenttaion 

Step 4: Run query.py for calculating Execution time of simple fragmentaion

Step 5: Run clusterquery.py for calculating Execution time of clustered fragmentaion


