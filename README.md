# Kibana 3 docker image

Kibana 3.1.3

## Usage

- `docker build -t kibana .`
- `docker run kibana -p8000:80 -e ES_HOST=es.example.com`

## Exposed ports

- 80

## Env

- ES_HOST (defaults to browser hostname)
- ES_PORT (defaults to 9200)
- ES_SCHEME (http or https, defaults to http)
