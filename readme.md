# Apache Kafka Demo
## Setting Up Server
Follow these commands(terminal, path-go to kafka):
<pre>.\bin\windows\kafka-storage.bat random-uuid</pre>
.\bin\windows\kafka-storage.bat format -t <uuid which is generated> -c <location of broker.properties in config folder> 
.\bin\windows\kafka-server-start.bat <location of broker.properties>
