Iniciar docker:
docker-compose up -d

Entrar no container:
docker-compose exec goapp bash

go run cmd/consumer/main.go

Para baixar as dependências
go mod tidy

Instalar o openCV para Linux

Para gerar um único binário
Vá para o /go/app/cmd/consumer
GOOS=linux go build -o consumer
Aí você cria o binário
