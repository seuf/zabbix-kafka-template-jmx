# Zabbix Kafka JMX Template

## Metrics

* jmx["kafka.server:type=ReplicaManager,name=UnderReplicatedPartitions",Value]
* jmx["kafka.server:type=BrokerTopicMetrics,name=BytesInPerSec",Count]
* jmx["kafka.server:type=BrokerTopicMetrics,name=BytesOutPerSec",Count]
* jmx["kafka.server:type=BrokerTopicMetrics,name=MessagesInPerSec",Count]

