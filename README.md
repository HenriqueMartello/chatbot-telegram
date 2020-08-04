#### Criando o bot
	- Se inscreva no Telegram (Você pode usar o cliente web, desktop ou mobile)
	- Abra o aplicativo ou acesse o website
	- Pesquise por @BotFather e inicie a conversa
	- Envie o comando /newbot e execute as instruções
	- Armazene o token enviado pelo @BotFather
### 1) Bibliotecas utilizadas no projeto
- [https://www.npmjs.com/package/youtube-node](https://www.npmjs.com/package/youtube-node) (Buscas no Youtube)
- [https://www.npmjs.com/package/dialogflow](https://www.npmjs.com/package/dialogflow) (Comunicação com o Dialogflow)
- [https://www.npmjs.com/package/node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api) (Comunicação com o Telegram)

### 2) Dialogflow
- [https://dialogflow.com/](https://dialogflow.com/)

### 3) Gerar credenciais
- [https://console.developers.google.com/start/api?id=youtube](https://console.developers.google.com/start/api?id=youtube) (Youtube)
- [https://console.cloud.google.com/iam-admin/serviceaccounts](https://console.cloud.google.com/iam-admin/serviceaccounts) (Dialogflow) Lembrar de ir na conta de serviço criada pelo Dialogflow e gerar seu arquivo json com as credenciais

### 4) Rodar o projeto
- Efetuar o clone do repositório em uma pasta do sistema operacional
- Executar o comando `npm install` dentro da pasta raiz do projeto para baixar as dependências
- Substituir os arquivos de credenciais do agent e do youtube
- Executar o comando `npm start` dentro da pasta raiz do projeto para executar o código

### Para mais informações do Projeto Original: 
- https://github.com/carlosvictor/dio-live-coding-chatbot