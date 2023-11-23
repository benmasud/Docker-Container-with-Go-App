# Docker-Container-with-Go-App
![image](https://github.com/benmasud/Docker-Container-with-Go-App/assets/69720999/e7e30c51-6664-47f5-913b-c6391386a764)

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
