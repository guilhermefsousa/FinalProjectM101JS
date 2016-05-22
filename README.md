1 - Baixe o aplicativo MongoMart.
2 - Instale as depend�ncias, entre no diret�rio e rodar o comando: npm install 
3 - Certifique-se de que voc� tem uma vers�o mongod executando 3.2.x do MongoDB.
4 - Importar a cole��o "item":  mongoimport -d mongomart -c item data/items.json
5 - Importar a cole��o "carrinho": mongoimport -d mongomart -c cart data/cart.json
6 - Execute o aplicativo com o comando "node mongomart" no diret�rio.