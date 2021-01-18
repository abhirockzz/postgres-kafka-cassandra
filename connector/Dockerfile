#FROM debezium/connect-base:1.2
FROM debezium/connect:1.3
WORKDIR $KAFKA_HOME/connect
RUN curl -L -O https://downloads.datastax.com/kafka/kafka-connect-cassandra-sink.tar.gz
RUN tar zxf kafka-connect-cassandra-sink.tar.gz
RUN rm kafka-connect-cassandra-sink.tar.gz

#optoonally, you can download the connnector locally
#COPY kafka-connect-cassandra-sink-1.4.0.tar.gz .
#RUN tar zxf kafka-connect-cassandra-sink-1.4.0.tar.gz
#RUN rm kafka-connect-cassandra-sink-1.4.0.tar.gz