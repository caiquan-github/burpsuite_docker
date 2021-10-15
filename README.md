# burpsuite
burpsuite Batch deployment for docker

You can boot multiple Burp Suite in the Docker environment



Burp Suite 2020.11.3


docker run -di --name burp_gui -p 10030:8080 -e JAVA_OPTS='-Xmx2g ' -e DISPLAY=192.168.2.61:0.0  caiquan/burp_gui


