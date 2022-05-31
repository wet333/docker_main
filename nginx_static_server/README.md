# to build the image

docker build -t nginx:template_v1 .

# to run the image

docker run -it -p LOCALPORT:80 nginx:template_v1

# to start the server

service nginx start