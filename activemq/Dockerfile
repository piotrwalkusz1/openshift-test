FROM openjdk:8

RUN mkdir /home/activemq
RUN wget -O /home/activemq/activemq.tar.gz "http://www.apache.org/dyn/closer.cgi?filename=/activemq/5.15.6/apache-activemq-5.15.6-bin.tar.gz&action=download" 
RUN tar -zxf /home/activemq/activemq.tar.gz -C /home/activemq
RUN rm /home/activemq/activemq.tar.gz
RUN mv /home/activemq/apache-activemq-5.15.6 /home/activemq/apache-activemq

RUN chmod -R 777 /home/activemq/apache-activemq

CMD /home/activemq/apache-activemq/bin/activemq console
