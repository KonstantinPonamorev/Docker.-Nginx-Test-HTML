docker build -t nginx-new-html ./Dockerfile

docker run --name new-html-nginx-server -d -p 80:80 nginx-new-html