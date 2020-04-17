# docker-tutorial

try at [Play with docker](https://labs.play-with-docker.com/)

# Remove If running container
`docker rm -f myapp`

# Build Image
`docker build -t myapp .`

# Run the App (Container  myapp-v2) (Image name mypp)
`docker run -itd -p 5000:80 --name myapp-v2 myapp`

# See the response
`curl localhost:5000`
