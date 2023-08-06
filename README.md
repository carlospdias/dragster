o
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é


## Stack utilizada

Adicione etiquetas de algum lugar, como: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Dependências Externas
 - App1
 - App2

## Infraestrutura Corporativa
Estão aqui todos os ambientes que precisam estar disponíveis para aplicação

|Ambiente| Servidor app   | Tipo       | Instalação |Link final                           |IC
|:-------| :----------    | :--------- |:-----------|:---------------------------------- |:--------|
|Desenvolvimento| app.jus.br/junc| JBoss      | Ansible    |**Obrigatório**. A chave da sua API |link pa ic|
|Homologação| app.jus.br/junc| JBoss      | Ansible    |**Obrigatório**. A chave da sua API |link pa ic|
|Produção| app.jus.br/junc| JBoss      | Ansible    |**Obrigatório**. A chave da sua API |link pa ic|


## Repositórios

 - [Eclipse](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Jboss eap 7.4](https://github.com/matiassingers/awesome-readme)
 - [Driver Jdbc Oracle ](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Documentação

[Documentação](https://link-da-documentação)


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`API_KEY`

`ANOTHER_API_KEY`


## Rodando localmente

Clone o projeto

```bash
  git clone https://link-para-o-projeto
```

Entre no diretório do projeto

```bash
  cd my-project
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run start
```


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Instalação

Instale my-project com npm

```bash
  npm install my-project
  cd my-project
```
    
## Rodando os testes

Para rodar os testes, rode o seguinte comando

```bash
  npm run test
```


## Deploy

Para fazer o deploy desse projeto rode

```bash
  npm run deploy
```


## Monitoramento

```http
  GET ${CONTEXT_APP}/sre/health
  GET ${CONTEXT_APP}/sre/version
  GET ${CONTEXT_APP}/sre/contruction
```
