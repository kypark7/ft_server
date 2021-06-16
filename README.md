# ft_server
This project is intended to introduce you to the basics of system and network administration. It will allow you to install a complete web server, using a deployment technology named Docker.

## How to 
이미지 생성
<pre>
<code>
docker build . -t ft_server
</code>
</pre>

도커 파일 실행
<pre>
<code>
docker run -it -p80:80 -p443:443 ft_server
</code>
</pre>
### Mandatory 

- [x] You must set up a web server with Nginx, in only one docker container. The
container OS must be debian buster.
- [x] Your web server must be able to run several services at the same time. The services
will be a WordPress website, phpMyAdmin and MySQL. You will need to make
sure your SQL database works with the WordPress and phpMyAdmin.
- [x] Your server should be able to use the SSL protocol.
- [x] You will have to make sure that, depending on the url, your server redirects to the
correct website.
- [x] You will also need to make sure your server is running with an autoindex that must
be able to be disabled.
