# Dockerized goread

Based on https://github.com/mjibson/goread

## Running

UI runs on port 8080

Admin console on port 8000

Inside the container config/data is stored at `/work/goread`. Bind mount where ever you want to store locally.

`docker run -d -p 8080:8080 -p 8000:8000 -v ~/.goread:/work/goread goread:latest`
