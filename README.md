# document-oriented-agent

## docker build

```
docker build --build-arg API_KEY=openai_api_key_value -t ghcr.io/tomasjanikds/document-oriented-agent .
```

## docker run

```
docker run --rm -it -e API_KEY=openai_api_key_value -p 1010:1010 ghcr.io/tomasjanikds/document-oriented-agent
```
