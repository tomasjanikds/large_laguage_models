# document-oriented-agent

## docker build

```
docker build --build-arg API_KEY=openai_api_key_value -t ghcr.io/tomasjanikds/document-oriented-agent .
```

## docker run

```
docker run --rm -it -e API_KEY=openai_api_key_value -p 1010:1010 ghcr.io/tomasjanikds/document-oriented-agent
curl --location 'http://0.0.0.0:1010/query/What%20is%20Falcon-40b%20and%20can%20I%20use%20it%20for%20commercial%20use'
```
