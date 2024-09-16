Step 1:
  mkdir -p tmp/zookeeper/data
  mkdir -p tmp/zookeeper/log
  mkdir -p tmp/kafka1/data
  mkdir -p tmp/kafka2/data
  mkdir -p tmp/kafka3/data

Step 2:
  docker-compose up -d

Step 3:
  Run WikiMediaProducer -> Java file

Step 4:
  Run OpenSearchConsumer -> Java file
