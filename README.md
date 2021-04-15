# Refs
# https://docs.docker.com/engine/examples/dotnetcore/
# Run
docker build -t aspnetcoreapp .
docker run -d -p 8080:80 --name myapp aspnetcoreapp
# Test
Using Postman, try hitting localhost:8080 after running the container.
GET `http://localhost:8080/api/ping`

