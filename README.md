# API Node.js com TypeScript e HTTP Module - DIO

Este repositório contém um projeto desenvolvido utilizando Node.js com TypeScript, utilizando o módulo nativo `http` para criar uma API simples. O projeto faz parte de um curso da Digital Innovation One (DIO).

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Módulo HTTP nativo do Node.js

## Como Executar o Projeto

### Requisitos

Antes de iniciar, certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) 

### Instalação

1. Clone o repositório:

   ```sh
   git clone https://github.com/LucasDamasioDias/API-NodeJS-Com-Typescript-e-HTTP-Module-DIO.git
   ```

2. Acesse a pasta do projeto:

   ```sh
   cd API-NodeJS-Com-Typescript-e-HTTP-Module-DIO
   ```

3. Instale as dependências:

   ```sh
   npm install
 

### Execução

Para iniciar o servidor, utilize o seguinte comando:

```sh
npm run start:dev

```

O servidor será iniciado e poderá ser acessado em `http://localhost:3333`.


## Endpoints da API

A API possui os seguintes endpoints:

- `GET /users` - Retorna a lista de usuários
- `POST /users` - Cria um novo usuário
- `GET /users/:id` - Retorna um usuário específico
- `PUT /users/:id` - Atualiza os dados de um usuário
- `DELETE /users/:id` - Remove um usuário

## Contribuição

Se deseja contribuir com melhorias no projeto:

1. Fork o repositório.
2. Crie uma branch (`git checkout -b minha-feature`).
3. Commit suas alterações (`git commit -m 'Adicionando uma nova feature'`).
4. Faça push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.

