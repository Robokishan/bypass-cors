# Bypass-cors-nginx

only for development purpose only 

This Bypass-cors-nginx-docker repo. it is reverse proxy for any frontend so that cors for backend can be bypassed


`docker build -t reverse-proxy . ; docker run --rm -it -p 8082:8082 --name nginx reverse-proxy`

use http://localhost:8082/server_name/{whatever the api is}
