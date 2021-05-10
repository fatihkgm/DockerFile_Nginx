# DockerFile_Nginx
Ubuntu as base image and deploy the  website in the docker container

Using ubuntu as base image and deploy the below website in the docker container.Build the image using  below web server

Web Server: Nginx

https://onepagelove.com/download/slick/



🔴Commands for Dockerfile

 ✔️ docker build -t nginx-webappdemo .
 ✔️ docker run -itd -p 80:80 nginx-namehere
 ✔️ check the web browser

<img width="1435" alt="Screen Shot 2021-05-09 at 10 18 10 PM" src="https://user-images.githubusercontent.com/63836841/117599162-48e0fa80-b117-11eb-9b79-08a155334e71.png">


For Apache  Change dockerfile as   

ENV APACHE_RUN_DIR /var/www/html  
ENV APACHE_RUN_USER www-data  
ENV APACHE_RUN_GROUP www-data  
ENV APACHE_LOG_DIR /var/log/apache2  

make the set up docker installation properly 
