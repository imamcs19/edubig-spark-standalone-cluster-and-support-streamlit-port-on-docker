In Big Data Analysis, we focus on how to implement and write code, not focus on building the infrastructure. One way to build infrastructure quickly is with Docker. So we can easily setup Spark multi-node environment (Zookeper, Kafka, Spark-master, Spark-worker, and Jupyterlab) for implementation of algorithm to processing datasets on docker, in seconds. : D

1. Download docker-compose
( $ wget https://raw.githubusercontent.com/imamcs19/edubig-spark-standalone-cluster-and-support-streamlit-port-on-docker/master/docker-compose.yml )

2. Install docker-compose

<ul>
<li>$ sudo apt-get remove docker-compose</li>
<li>$ sudo curl -L "https://github.com/docker/compose/releases/download/1.26.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose</li>
<li>$ sudo chmod +x /usr/local/bin/docker-compose</li>
<li>$ sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose</li>
</ul>

3. docker-compose up

4. Run jupyterlab (open your browser visit url ip-public:8888). 

5. Let's go to write code on Spark multi-node environment & support to create web App using streamlit

Ref: 
1. https://towardsdatascience.com/apache-spark-cluster-on-docker-ft-a-juyterlab-interface-418383c95445 & https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker
2. https://towardsdatascience.com/diy-apache-spark-docker-bb4f11c10d24
3. https://github.com/amir-rahnama/pyspark-twitter-stream-mining
4. https://github.com/apssouza22/lambda-arch
5. https://github.com/kettlewell/pipeline
