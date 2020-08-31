# docker-react

__for development mode:__

`docker-compose up -d`

in case you already have an image:

docker-compose up --build

`http://localhost:3000`

__for production mode:__

`docker build -t dockerreact .`

`docker run -p 8080:80 dockerreact`

`http://localhost:8080`
