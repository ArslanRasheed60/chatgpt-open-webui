# Take no Prisoners

> docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always opengui

> docker run -d --network="host" -v ollama-webui:/app/backend/data -e OLLAMA_BASE_URL=http://localhost:11434 --name ollama-webui --restart always opengui

## deploying of models

> ollama run llama2
>
> ollama serve
>
> ollama list
