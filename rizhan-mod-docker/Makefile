help:
	@cat Makefile

DOCKER_FILE=Dockerfile
SRC?="${HOME}/keras-workspace"

build:
	docker build -t t20.local:5000/rizhan/swift-notebook:latest -f $(DOCKER_FILE) .

