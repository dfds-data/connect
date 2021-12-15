FROM confluentinc/cp-kafka-connect-base:7.0.1
USER root
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.2.6
USER appuser
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-s3:10.0.3
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-common:0.1.0.54
