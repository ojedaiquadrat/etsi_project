* Zookeper: /bin/zookeeper-server-start.sh ./config/zookeeper.properties
* kafka-server: ./bin/kafka-server-start.sh ./config/server.properties
* consumer for the Topic:
./bin/kafka-console-consumer.sh --bootstrap-server 192.168.100.5:9092 --topic 1_sensors_dataset --from-beginning
