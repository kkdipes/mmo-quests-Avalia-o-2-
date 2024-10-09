# Projeto: Missões de MMORPG

## Descrição

Este projeto é um web service desenvolvido para gerenciar missões em um jogo MMORPG. Ele permite a consulta de missões disponíveis e a obtenção de dicas sobre elas. O serviço processa requisições HTTP no formato JSON e integra dados externos para fornecer informações sobre as missões.


## Funcionalidades

- Consulta de todas as missões disponíveis (GET /quests)
- Recebe o nome de uma missão e retorna dicas (POST /quests/hints)
- Rota de informações sobre o projeto e o desenvolvedor (GET /quests/sobre)

## Utilizados

- **Java 11**
- **Spring Boot**
- **Docker**
- **Maven** (para build e gerenciamento de dependências)
