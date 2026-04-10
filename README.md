### Helm charts for Sentiment Analysis solution pattern


The `globex-mw/kafka-broker` subchart deploys **Strimzi Kafka in KRaft mode** with **one `KafkaNodePool`** (each replica is **broker + controller**), ephemeral storage, no ZooKeeper. Use **Strimzi 0.44+** (or AMQ Streams that supports `strimzi.io/kraft: enabled` and node pools). See [Strimzi KRaft examples](https://github.com/strimzi/strimzi-kafka-operator/blob/main/packaging/examples/kafka/kraft/kafka-ephemeral.yaml).
