Hadoop 2.x components:
Hadoop is an open source framework, that supports the processing off the large unstructured data
Sets in distributed computing environment. The main components of Hadoop are Hadoop distributed file system (HDFS), Yarn and MapReduce.
HDFS:
HDFS is the Hadoop file system and comprises of two major components: namespaces and blocks storage service. Operations on files such as creating and modifying files and directories and directories are managed by namespace service. The block storage service implements data node cluster management, block operations and replication.
Yarn:
The fundamental idea of YARN is to split up the functionalities of resource management and job scheduling/monitoring into separate daemons. The idea of YARN was to have have a global ResourceManager (RM) and per-application ApplicationMaster (AM). 
The ResourceManager and the NodeManager together build the data-computation framework. Ultimate authority that arbitrates resources is with the ResourceManager.
Benefits of YARN:
1.	Highly Scalability
2.	Highly Availability
3.	Supports Multiple Programming Models
4.	Supports Multi-Tenancy
5.	Supports Multiple Namespaces
6.	Improved Cluster Utilization
7.	Supports Horizontal Scalability
MapReduce:
Hadoop MapReduce is a software framework for writing applications which process vast amounts of data in-parallel on large cluster of commodity hardware in a reliable, fault-tolerant manner.
A MapReduce job usually splits the input data-set into independent chunks which are processed by the map tasks in a completely parallel manner. The framework sorts the outputs of the maps, which are then input to the reduce tasks. Typically both the input and the output of the job are stored in a file-system. The framework takes care of scheduling tasks, monitoring them and re-executes the failed tasks.
