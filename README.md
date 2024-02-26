# docker-apache-webserver
My own Webserver deployed via a Apache docker image 

1. $ docker build -t apache-docker-example .
2. After this check to see running images by using docker images
3. $ docker run -d --rm --name httpd-docker-01 -p 80:80 apache-docker-example
4. Once you complete docker run, go to brower and type localhost:80
5. You should see the website you deployed, my website is Karl Valcourt
