- Baixe o aplicativo MongoMart.
- Instale as dependencias, entre no diretorio e rodar o comando: npm install 
- Certifique-se de que voce tem uma versao mongod executando 3.2.x do MongoDB.
- Importar a colecao "item":  mongoimport -d mongomart -c item data/items.json
- Importar a colecao "carrinho": mongoimport -d mongomart -c cart data/cart.json
- Execute o aplicativo com o comando "node mongomart" no diretorio.

