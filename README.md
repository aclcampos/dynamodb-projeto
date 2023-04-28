
## Projeto utilizando o Amazon DynamoDB. 

### Serviços utilizados: 
##### * Amazon DynamoDB
#### * Amazon CLI para execução em linha de comando 

### Comandos para a exucução do projeto: 
#### * Criar uma tabela 
` aws dynamodb create-table  --table-name Music --attribute-definitions AttributeName=Artist,AttributeType=S AttributeName=SongTitle,AttributeType=S --key-schema AttributeName=Artist,KeyType=HASH AttributeName=SongTitle,KeyType=RANGE --provisioned-throughput ReadCapacityUnits=10,WriteCapacityUnits=5 `
