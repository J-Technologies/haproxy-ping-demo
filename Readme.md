## Using HAProxy for loadbalancing 2 web servers in docker

This project contains 3 docker containers, two apache servers and one haproxy server which load balance between these two servers.
More information about this project can be found in this blog: http://www.vdzon.com/2015/03/31/using-haproxy-for-loadbalancing-2-web-servers-in-docker

To build and run all three containers, you can use the `run.sh` or `run.bat` command.
After the containers are started, the following addresses are available:

* http://[ip]:80     demo website
* http://[ip]:81     haproxy admin site
* http://[ip]:84     direct access to apache1
* http://[ip]:85     direct access to apache2
