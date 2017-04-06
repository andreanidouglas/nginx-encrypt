# nginx-encrypt
Docker container for a nginx webserver expecting Letsencrypt files

# run it...

1. Generate SSL dhparam.pem

`openssl dhparam -out sslcerts/dhparam.pem 2048`

2. Build the docker container
`docker build . -t andreani/nginx-encrypt`

3. Run it with docker-compose
`docker-compose up -d`
