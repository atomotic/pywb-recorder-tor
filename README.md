# pywb-tor-docker

build:

    docker build -t pywb-tor .
    docker run -p 8080:8080 -v $(pwd)/anonymous-archive:/data/anonymous-archive pywb-tor

record:

http://localhost:8080/anonymous-archive/record/https://www.nytimes3xbfgragh.onion/