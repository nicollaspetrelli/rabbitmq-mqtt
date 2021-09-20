### Rodar o build com a tag
docker build --no-cache -t rmq-mqtt ./env/rabbit

### Rodar o docker compose
docker-compose up -d

### Verificar se o plugin foi instalado
### > Dentro do container do rabbit
rabbitmq-plugins list

## Packages
go get github.com/eclipse/paho.mqtt.golang