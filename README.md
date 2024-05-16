#Projeto Chat Bot com API Intermediária#
Este projeto consiste em um chatbot que utiliza uma API intermediária em Node.js para consumir a API de repositórios do GitHub, filtrando e retornando os 5 repositórios mais antigos em C#. O chatbot exibe esses dados em um carrossel.

Descrição das Pastas e Arquivos
api/src/controller/githubController.js: Contém a lógica de consumo da API do GitHub e o filtro para obter os 5 repositórios mais antigos em C#.
api/src/routes/githubRoutes.js: Define a rota que expõe os dados filtrados pela API intermediária.
api/src/index.js: Arquivo principal que inicializa o servidor Express.
Flow/chatbot.js: Arquivo onde o chatbot é salvo. Ele consome a API intermediária e exibe os dados em um carrossel.
