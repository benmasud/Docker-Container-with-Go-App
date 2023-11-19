# Docker-Container-with-Go-App
simple go api with docker
![image](https://github.com/benmasud/Docker-Container-with-Go-App/assets/69720999/1f5c79b5-4095-4065-b07d-db1c8eb6f6e3)

## How to start 
clone the repo and run it using this command 

### Build it first 
```
docker build . -t go-containerized-api:latest   
```
### Then run it
```
docker run -e PORT=9000 -p 9000:9000 go-containerized-api:latest
```
You can select port likewise or can use the default port 8080
