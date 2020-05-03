# docker-react

for development mode:

`docker-compose up -d`

`http://localhost:3000`

for production mode:
`docker build .`

(take the CONTAINER_ID from above line) and 

`docker run -p 8080:80 CONTAINER_ID`

`http://localhost:8080`
