# Kubernetes e hpa

## URL da imagem publicada no docker hub
<a href="https://hub.docker.com/r/osniantonio/go-hpa" target="_blank">https://hub.docker.com/r/osniantonio/go-hpa</a>

## Comando usado para criar a imagem
docker build -t osniantonio/go-hpa .

## Comando para baixar a imagem
docker pull osniantonio/go-hpa

## Comando para executar
docker run -d -p 8000:8000 osniantonio/go-hpa