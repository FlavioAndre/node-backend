# Inicialziar projeto 
yarn init -y

# add express
yarn add express

# instalar o nodemon
yarn add nodemon -D

## coloar no package.json o script dev para rodar o sistema
"scripts": {
    "dev" : "nodemon src/index.js"
  },
### Rodar com yarn dev
yarn dev

# instalar banco mongodb
yarn add mongoose

# usar mongo cloud
## Criar usuario em Database Access
## No menu Network Access, clicar no botão '+ADD IP ADDRESS'
### liberar acesso para todos

'https://www.mongodb.com/cloud/atlas
mongodb+srv://admin:<password>@clusterteste-0vqw4.mongodb.net/test?retryWrites=true&w=majority'

# instalar o multer para receber dados de form multidata
yarn add multer

# instalar sharp para manipular images
yarn add sharp 

# instalar o cors
yarn add cors

# instalar o socket.io
yarn add socket.io