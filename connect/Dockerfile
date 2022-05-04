FROM confluentinc/cp-kafka-connect-base:7.0.1
USER root
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.4.1
USER appuser
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-s3:10.0.7
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-common:0.1.0.54
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-azure-blob-storage:1.6.9