# README

short demo transferring data from ConfluentCloud to Azure Event Hub with MirrorMaker2


### start the connect stack

set enva
```bash
export CC=<prefix>.germanywestcentral.azure.confluent.cloud:9092

export SCHEMA_REGISTRY_URL="https://<prefix>.eu-central-1.aws.confluent.cloud"

export SASL_JAAS_CONFIG='org.apache.kafka.common.security.plain.PlainLoginModule required username="API-KEY" password="API-KEY-SECRET";'

export SCHEMA_REGISTRY_BASIC_AUTH_USER_INFO=SR-API-KEY:SR-API-SECRET

start the  stack
```bash
docker-compose up -d
```
