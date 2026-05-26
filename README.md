🚀 Meu Primeiro Servidor com Express.js<br><br>

Este projeto é um exemplo simples utilizando o framework Express.js no ambiente Node.js.<br>
O objetivo é estudar como criar um servidor básico e entender o funcionamento de rotas no backend. 💻<br>

📚 Sobre o Express.js<br><br>

O Express.js é um framework minimalista para Node.js que facilita a criação de servidores e APIs.<br><br>

Com ele, é possível:<br><br>

🌐 Criar rotas HTTP (GET, POST, PUT, DELETE)<br>
⚡ Desenvolver APIs rapidamente<br>
🛠️ Organizar aplicações backend<br>
🔗 Trabalhar com middleware<br>
📦 Integrar bancos de dados e outras bibliotecas<br>
📄 Explicando o código<br>
const express = require('express'); <br><br>

📌 Importa a biblioteca do Express.<br><br>

const app = express();<br>

📌 Cria uma instância da aplicação Express. <br><br>

const port = 8080;<br>

📌 Define a porta onde o servidor ficará escutando.<br><br>

app.get('/', (req, res) => {<br>
  res.send('Hello from world.');<br>
});<br><br>

📌 Cria uma rota GET para a página inicial (/).<br><br>

Quando alguém acessar:<br>

http://localhost:8080<br><br>

o servidor responderá com:<br><br>

Hello from world.<br>
app.listen(port, () => {<br>
  console.log(`Servidor iniciado | Porta de escuta [${8080}]`);<br>
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
