# ollama-docker


Example docker compose for ollama. This setup will provide:

- ollama
- ollama-webui
- litellm (openai compatible api)
- redis (caching)

## Usage

Start the services 

`docker compose up -d`

Download a model (can also be done also from webui)

```sh
make ollama/bash
# enter docker image

# See avail models at https://ollama.ai/library
ollama pull "model-name"

```


## Web UI

To use the webui go to http://localhost:3002/

**Note**: create a new user and login to proceed to the chat ui
