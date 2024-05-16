Projeto Chat Bot com API Intermediária
Este projeto consiste em um chatbot que utiliza uma API intermediária em Node.js para consumir a API de repositórios do GitHub, filtrando e retornando os 5 repositórios mais antigos em C#. O chatbot exibe esses dados em um carrossel.

Descrição das Pastas e Arquivos
api/src/controller/githubController.js: Contém a lógica de consumo da API do GitHub e o filtro para obter os 5 repositórios mais antigos em C#.
api/src/routes/githubRoutes.js: Define a rota que expõe os dados filtrados pela API intermediária.
api/src/index.js: Arquivo principal que inicializa o servidor Express.
Flow/chatbot.js: Arquivo onde o chatbot é salvo. Ele consome a API intermediária e exibe os dados em um carrossel.

Dependências
Para instalar as dependências necessárias, execute:

bash
npm install express axios
Configuração da API
Controller
O arquivo githubController.js contém a lógica de consumo da API do GitHub, filtrando os repositórios pela linguagem C# e ordenando-os por data de criação para obter os 5 repositórios mais antigos.

Rotas
O arquivo githubRoutes.js define a rota /repos/oldest que expõe os dados filtrados pela API intermediária.

Inicialização do Servidor
O arquivo index.js inicializa o servidor Express e configura a aplicação para usar as rotas definidas.

Implementação do Chatbot
O arquivo sa8.js, localizado na pasta Flow, contém a implementação do chatbot que consome a API intermediária e exibe os repositórios obtidos em um carrossel.
