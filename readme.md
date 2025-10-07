# Apache Kafka Demo
## Setting Up Server
Follow these commands(terminal, path-go to kafka):
- For creation of Cluster ID(UUID)
<pre>.\bin\windows\kafka-storage.bat random-uuid</pre>
- For formatted Storage
<pre>.\bin\windows\kafka-storage.bat format -t <uuid which is generated> -c <location of broker.properties in config folder> </pre>
- For Server Start
<pre>.\bin\windows\kafka-server-start.bat <location of broker.properties></pre>
