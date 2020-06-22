# S-graffito
## Streaming Graph Processing At Scale

S-graffito is a Streaming Graph Management System that addresses the processing of OLTP and OLAP queries on high streaming rate, very large graphs. These graphs are increasingly being deployed to capture relationships between entities (e.g., customers and catalog items in an online retail environment) both for transactional processing and for analytics (e.g., recommendation systems)

### Streaming Graph Querying

Existing work on streaming graph systems, by and large,focuses on either:
 1. maintenance of graph snapshots under a stream of updates for iterative graph analytic workloads, or
 2. specialized systems for persistent query workloads that are tailored for the task in hand
 
In a large number of applications, the unbounded nature of streaming graphs and the need for real-time answers on recent data make it impractical to employ snapshot-based techniques.
Specialized systems, on the other hand, provide satisfactory performance for the task in hand but they lack the flexibility to support a wide range of real-world scenarios.

The primary focus of this component is the efficient processing of persistent graph queries over large streaming graphs with very high edge arrival rates.
We investigate query execution techniques and robust system architectures for an efficient and scalable treaming Graph Management System (SGMS).
In particular, we tackle following problems for efficient persistent query evaluation over streaming graphs:

    1. Design and development of non-blocking algorithms for persistent evaluation of path navigation queries over streaming graphs.
    2. Query processing techniques for persistent graph queries with both structural and attribute-based predicates.
    3. Scale-out system architectures and distributed query evaluation techniques to scale to large streaming graphs arising in real-world applications.

### Streaming Graph Analytics

## Publications

SIGMOD'20: [Regular Path Query Evaluation on Streaming Graphs](https://arxiv.org/abs/2004.02012)

SIGMOD'19: [Experimental Analysis of Streaming Algorithms for Graph Partitining](https://dl.acm.org/authorize?N697045)


## People

[M. Tamer Özsu](https://cs.uwaterloo.ca/~tozsu/)

Aida Sheshbolouki (PhD Student)

[Anil Pacaci](https://cs.uwaterloo.ca/~apacaci/) (PhD Student)
