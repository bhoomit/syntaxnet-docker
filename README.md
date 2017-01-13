# syntaxnet-docker

Copied from https://github.com/johndpope/DockerParseyAPI

To build new image:

docker build --no-cache=true -t syntaxnet .
docker push bhoomit/syntaxnet-docker

Run:

docker run -d -p 9000:9000 -i bhoomit/syntaxnet-docker
