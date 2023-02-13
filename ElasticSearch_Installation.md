### The Linux archive for Elasticsearch v8.6.1 can be downloaded and installed as follows:

```
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.6.1-linux-x86_64.tar.gz
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.6.1-linux-x86_64.tar.gz.sha512
shasum -a 512 -c elasticsearch-8.6.1-linux-x86_64.tar.gz.sha512 
tar -xzf elasticsearch-8.6.1-linux-x86_64.tar.gz
cd elasticsearch-8.6.1/
```

### Run Elastic Search

```
./bin/elasticsearch
```

### See the Current Entrollment token

```
./bin/elasticsearch-create-enrollment-token -s node
```

### Generate new token for Kibana entrollment

```
./bin/elasticsearch-create-enrollment-token -s kibana
```

### To make sure ElasticSearch is up and running

User name : elastic 
Password : <Get the value from terminal>
Url: https://localhost:9200


![Screenshot from 2023-02-13 11-38-43](https://user-images.githubusercontent.com/42825038/218383807-5da6cce5-97f8-43df-9cd2-d73683352336.png)
