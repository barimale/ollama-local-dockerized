# ollama-local-dockerized
```
docker run -d --gpus=all -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama:latest
```
Download and run for NVIDIA Quadro T1000:
```
docker exec -it ollama ollama pull qwen2.5-coder:1.5B
docker exec -it ollama ollama run qwen2.5-coder:1.5B
```