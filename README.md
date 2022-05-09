# Python Flask App for Demo


#Python Flask默认启动端口为：5000
docker build -t flaskapp .
docker run -d -p 7373:5000 flaskapp
