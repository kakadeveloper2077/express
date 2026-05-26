🚀 Meu Primeiro Servidor com Express.js

Este projeto é um exemplo simples utilizando o framework Express.js no ambiente Node.js.
O objetivo é estudar como criar um servidor básico e entender o funcionamento de rotas no backend. 💻

📚 Sobre o Express.js

O Express.js é um framework minimalista para Node.js que facilita a criação de servidores e APIs.

Com ele, é possível:

🌐 Criar rotas HTTP (GET, POST, PUT, DELETE)
⚡ Desenvolver APIs rapidamente
🛠️ Organizar aplicações backend
🔗 Trabalhar com middleware
📦 Integrar bancos de dados e outras bibliotecas
📄 Explicando o código
const express = require('express'); 

📌 Importa a biblioteca do Express.

const app = express();

📌 Cria uma instância da aplicação Express. <br><br>

const port = 8080;<br><br>

📌 Define a porta onde o servidor ficará escutando.<br><br>

app.get('/', (req, res) => {
  res.send('Hello from world.');
});<br><br>

📌 Cria uma rota GET para a página inicial (/).<br><br>

Quando alguém acessar:<br><br>

http://localhost:8080<br><br>

o servidor responderá com:<br><br>

Hello from world.
app.listen(port, () => {
  console.log(`Servidor iniciado | Porta de escuta [${8080}]`);
});<br><br>

📌 Inicia o servidor e mostra uma mensagem no terminal indicando que ele está funcionando.<br><br>

▶️ Como executar o projeto<br>
1️⃣ Instale as dependências<br>
npm install express<br>
2️⃣ Execute o arquivo<br>
node arquivo.js<br>
3️⃣ Abra no navegador<br>
http://localhost:8080<br>
🧠 O que estou aprendendo<br>
✅ Como criar servidores com Express<br>
✅ Como definir rotas<br>
✅ Como iniciar aplicações backend<br>
✅ Conceitos básicos de APIs REST<br>
📌 Tecnologias utilizadas<br>
🟢 JavaScript<br>
🟢 Node.js<br>
🟢 Express.js<br>
