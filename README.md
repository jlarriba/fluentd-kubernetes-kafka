# fluentd-kubernetes-kafka
Extracts Kubernetes logs and send them to Kafka

Accepts two environment variables:

KAFKA_BROKERS: A comma-separated list of <host:port> for each Kafka broker
KAFKA_TOPIC: The topic on which the logs will be published
