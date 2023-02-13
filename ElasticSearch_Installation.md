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



