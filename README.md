Este projeto é uma Skill Alexa com integração com a Open AI e Model GPT
Este projeto é uma Skill Alexa que integra com a API da OpenAI para responder perguntas usando o modelo GPT. Desenvolvido por Madson Aguiar.

markdown
Copy code
## Configuração

1. Copie o arquivo `.env.example` na pasta lambda para `.env` e insira sua chave OpenAI:

```
OPENAI_API_KEY=SUA_CHAVE
```

## Detalhes do pacote

```json
{
  "name": "minha-openai",
  "version": "1.2.0",
  "description": "Este projeto é uma Skill Alexa com integração com a Open AI e Model GPT",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Madson Aguiar Rodrigues",
  "license": "Apache License",
  "dependencies": {
    "ask-sdk-core": "^2.7.0",
    "ask-sdk-model": "^1.19.0",
    "aws-sdk": "^2.326.0",
    "openai": "^3.1.0",
    "dotenv": "^10.0.0"
  }
}
```
