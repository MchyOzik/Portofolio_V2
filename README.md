cd /docker/web1
git clone https://github.com/MchyOzik/Portofolio_V2

Dockerfile
Search httpd
FROM httpd:2.4
COPY ./public{direktori}/ /usr/local/apache2/htdocs/

docker image ls
$ docker build -t web1{docker} .
$ docker run -d -p 8080:80 web1

docker container ls

