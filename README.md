# elk-docker-apache-log

this docker image is a customization of [elk-docker] with a specific pipeline for  apache logs management  from  Filebeat, and perform [geoip analysis][elk-geoip].

```
docker pull iostream82/elk-docker-apache-log
docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk  iostream82/elk-docker-apache-log

```
for further details please refer to [elk-docker].

[RS]: <https://github.com/kiritbasu/Fake-Apache-Log-Generator>
[elk-docker]: <https://elk-docker.readthedocs.io/>
[elk-geoip]:<https://www.elastic.co/blog/geoip-in-the-elastic-stack>
