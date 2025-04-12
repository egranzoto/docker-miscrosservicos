# Estrutura de Microsserviços com Docker

## Descrição do Desafio

A tecnologia de **Containers** está transformando a maneira como as operações de TI são realizadas. Ela abstrai ambientes de desenvolvimento e otimiza o consumo de recursos, permitindo maior flexibilidade e escalabilidade.

Neste projeto, você irá implementar uma estrutura de **Microsserviços** utilizando o **Docker**, seguindo as melhores práticas do mercado internacional. O objetivo é **ganhar independência entre as aplicações e a infraestrutura**, aproveitando os benefícios dos containers.

Este conteúdo oferece um caminho para você se aprofundar em **Docker**, **Microsserviços** e como integrar essas tecnologias com infraestrutura como a **AWS**.

## Pré-requisitos

Antes de começar, é importante que você tenha os seguintes conhecimentos e ferramentas:

- **Conhecimentos básicos de Linux**
- **Conhecimentos básicos de Docker**
- **Conhecimentos básicos de AWS**

Além disso, você precisará de algumas ferramentas instaladas em sua máquina para poder seguir com a implementação:

1. **Docker**: Para criar, gerenciar e orquestrar containers.
2. **AWS CLI**: Para interagir com os serviços da Amazon Web Services.
3. **Uma conta na AWS**: Para provisionar e gerenciar a infraestrutura na nuvem.

## Objetivos

- Criar uma **estrutura de microsserviços** utilizando containers Docker.
- Aprender as **melhores práticas** para criar e gerenciar microsserviços.
- Integrar a solução com a **infraestrutura de nuvem** (AWS) para provisionamento e escalabilidade.

## Arquitetura do Projeto

Este projeto é baseado na arquitetura de **Microsserviços**, onde:

- Cada serviço é **containerizado** para garantir a independência entre as aplicações.
- A comunicação entre os microsserviços pode ser feita através de **APIs REST** ou **mensageria** (RabbitMQ, Kafka, etc.), dependendo da sua escolha.
- A infraestrutura será provisionada utilizando a **AWS**, garantindo escalabilidade e alta disponibilidade.

## Tecnologias Utilizadas

- **Docker**: Para a criação e gerenciamento de containers.
- **AWS**: Para provisionamento da infraestrutura na nuvem (EC2, VPC, S3, etc.).
- **Microsserviços**: Arquitetura de serviços independentes e escaláveis.
- **Docker Compose**: Para orquestrar múltiplos containers e facilitar o gerenciamento da aplicação.
- **API REST**: Comunicação entre os microsserviços.
