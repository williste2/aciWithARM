npm install
docker build -t techieslounge/node-web-app:0.1 .
docker images
docker run -p 3000:8080 -d techieslounge/node-web-app:0.1
