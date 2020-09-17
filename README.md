In Big Data Analysis, we focus on how to implement and write code, not focus on building the infrastructure.

One way to build infrastructure quickly is with Docker. So we can easily setup Spark multi-node environment (Zookeper, Kafka, Spark-master, Spark-worker, and Jupyterlab) for algorithm implementation in processing datasets on docker, in seconds. : D

1. Download docker-ompose
$wget 

2. Run jupyterlab (open your browser visit url ip-public:8888)

3. Let's go to write code on Spark multi-node environment

Ref: 
1. https://towardsdatascience.com/apache-spark-cluster-on-docker-ft-a-juyterlab-interface-418383c95445 & https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker
2. https://towardsdatascience.com/diy-apache-spark-docker-bb4f11c10d24
3. https://github.com/amir-rahnama/pyspark-twitter-stream-mining
4. https://github.com/apssouza22/lambda-arch
5. https://github.com/kettlewell/pipeline
