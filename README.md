# Node e JWT
[![NPM](https://img.shields.io/badge/npm-6.14.6-green?style=for-the-badge)](https://www.npmjs.com/)
[![JWT](https://img.shields.io/badge/jwt-8.5.1-cyan?style=for-the-badge)](https://www.npmjs.com/package/jsonwebtoken)
[![Redis](https://img.shields.io/badge/redis-3.0.500-red?style=for-the-badge)](https://github.com/microsoftarchive/redis)
[![Nodemailer](https://img.shields.io/badge/nodemailer-6.4.8-green?style=for-the-badge)](https://nodemailer.com/about)
[![LPHolanda](https://img.shields.io/badge/dev-LPHolanda-blue?style=for-the-badge)](https://github.com/LPHolanda)


## Objetivo
> Projeto realizado para aprendizado e fixação de conhecimento de JWT com NodeJS.

## Conteúdo
- Hashing bcrypt para senhas.
- Autenticação local sem sessões.
- Utilizando o módulo crypto para gerar a chave de assinatura dos tokens.
- Utilizando variável de ambiente para guardar a chave de assinatura JWT.
- Tratamento de erros na autenticação.
- Tempo de expiração do token.
- Logout utilizando blacklist de tokens com o banco NoSQL Redis.
- Refresh Tokens.
- Verificação de token por email (email de produção e desenvolvimento).

## Execução
Primeiro, rode o seguinte comando dentro da pasta raiz para baixar todas as dependências listadas no arquivo package.json.
```bash
$  npm install
```  

Após a instalação das dependências, rode o seguinte comando para iniciar o servidor node.
```bash
$  npm start
```  

### Comandos
Comando usado para gerar uma chave de assinatura aleatória com npm.
```bash
$  node -e "console.log( require('crypto').randomBytes(256).toString('base64'))"
```  