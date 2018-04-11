# manifest-graylog

After the installation of your [manifest-server.jps](manifest-server.jps). You will need to configure an *input* to be able to receive syslog sent by the agent.



To create an input, go to your Graylog Server (http://@IPpublic:9000), then *Systems - Inputs*




> For example, select *Syslog TCP*, choose a title (ex : tcp syslog), the Bind Adress is the private IP of your Graylog Server (ex: 10.102.0.10), the port listen (ex: 2512).





If you want to collect the log of one of your environment, use the [manifest-agent.jps](manifest-agent.jps), then, specify the private IP of your Graylog Server (ex: 10.102.0.10) and the listenning port (ex: 2512)




Now, you will be able to see the information from your agent into Graylog Server.
