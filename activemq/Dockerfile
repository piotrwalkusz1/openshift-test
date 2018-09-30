FROM openjdk:8

ADD resources/apache-activemq-5.15.6-bin.tar.gz /home/activemq/
RUN mv /home/activemq/apache-activemq-5.15.6 /home/activemq/apache-activemq

CMD /home/activemq/apache-activemq/bin/activemq console
