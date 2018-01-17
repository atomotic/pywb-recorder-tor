# pywb-recorder-tor

build:

    docker build -t pywb-recorder-tor .
    docker run -p 8080:8080 -v $(pwd)/anonymous-archive:/data/anonymous-archive pywb-recorder-tor

record:

http://localhost:8080/anonymous-archive/record/https://www.nytimes3xbfgragh.onion/
