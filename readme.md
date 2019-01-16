1. sudo docker pull nginx

2. docker run --rm --name ngx-docker -v //*путь до папки*//app/nginx:/etc/nginx -v //*путь до папки*//app/html:/var/www/html -p 8000:80 -d nginx

3. Сайт доступен по адресу http://localhost:8000/