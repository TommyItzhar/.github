docker run --name nginx2 --rm --network nginx-network -d nginx:alpine
docker run --name nginx1 --rm --network nginx-network -d nginx:alpine
