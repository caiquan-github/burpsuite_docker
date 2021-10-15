# burpsuite Batch deployment for docker

You can boot multiple Burp Suite in the Docker environment

Burp Suite 2020.11.3

Burp Suite config addres is :
   
   /usr/local/docker/burp/space/files/default.json


# GUI

Prepare an x11 server <DISPLAY> in x11 ip adders

docker run -di --name burp-gui -e JAVA_OPTS='-Xmx2g ' -e DISPLAY=127.0.0.1:0.0  caiquan/burp-gui

# NO GUI

Suitable for batch deployment on the server, saving the resources of GUI
  
docker run -di --name burp-nogui -e JAVA_OPTS='-Xmx2g '  caiquan/burp-nogui
  


