# Api de Clima e Tempo - Azure e Docker

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)


## Descrição

Este projeto implementa uma API de previsão do tempo utilizando .NET e Docker, com integração para execução em Azure Pipelines.

## Funcionalidades

- **GET /weatherforecast**: Retorna a lista de previsões do tempo.
- **GET /weatherforecast/{id}**: Retorna a previsão do tempo para um local específico com base no ID.
  
## Estrutura do Projeto

- **API/**: Contém a implementação da API.
- **Dockerfile**: Arquivo de configuração do Docker para construir a imagem da API.
- **appsettings.json**: Configurações para o ambiente de execução da API.
- **Docker-Compose.yml**: Configuração para rodar o contêiner Docker e facilitar a execução no ambiente local.

## Tecnologias Utilizadas

- **.NET**: Framework utilizado para implementar a API.
- **C#**: Linguagem principal do projeto.
- **Docker**: Utilizado para containerização da API.
- **Azure Pipelines**: Ferramenta de integração contínua para deploy da aplicação.
  
## Como Executar

### Pré-requisitos:

- [Docker](https://www.docker.com/get-started)
- [.NET SDK](https://dotnet.microsoft.com/download)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)
