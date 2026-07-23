# Full Cycle - Desafio Docker Go

Este projeto foi desenvolvido como solução para o desafio de Docker da Full Cycle.

## Objetivo

Criar uma aplicação em Go que imprima a mensagem:

```text
Full Cycle Rocks!!
```

A aplicação é empacotada em uma imagem Docker otimizada, utilizando **multi-stage build** e uma imagem final baseada em `scratch`, mantendo o tamanho final inferior a **2 MB**.

## Tecnologias

* Go
* Docker

## Estrutura do Projeto

```text
.
├── Dockerfile
├── go.mod
├── main.go
└── README.md
```

## Docker Hub

Imagem publicada em:

https://hub.docker.com/r/augustohermes/fullcycle-go

## Como executar

Baixe e execute a imagem:

```bash
docker run augustohermes/fullcycle-go
```

### Saída esperada

```text
Full Cycle Rocks!!
```

## Repositório

https://github.com/augustohermes/fullcycle-go
