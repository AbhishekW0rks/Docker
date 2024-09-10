Build the Docker image: docker build -t nginx-simple-web .
Run the container: docker run -d -p 8080:80 nginx-simple-web