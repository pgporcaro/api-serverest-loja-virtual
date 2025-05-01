
📜 Descrição Este projeto consiste em uma coleção de testes de API desenvolvidos utilizando o Postman. O objetivo é fornecer um ambiente prático e eficiente para testar as funcionalidades da API. 🔍

Este repositório contém:

Uma coleção de testes Postman (API-serveRest.postman_collection.json) Um ambiente Postman configurado (API-serveRest.postman_environment) Workflow de CI/CD para execução automática dos testes (.github/workflows/main.yml) O objetivo é facilitar a validação das APIs do projeto, tanto manualmente pelo Postman quanto de forma automatizada via linha de comando (Newman) e CI/CD.

⚙️ Especificações API alvo: Os testes são realizados na API da aplicação ServeRest. Ferramenta utilizada: O Postman é utilizado para a execução dos testes. Linguagem de teste: Os testes são escritos em JavaScript, utilizando a sintaxe do Postman. Integração contínua (CI/CD): Os testes são executados em um pipeline de CI/CD utilizando GitHub Actions.

🔧 Pré-requisitos Antes de executar os testes, certifique-se de que você tem os seguintes requisitos instalados:

Carteiro: Para executar uma coleção de testes. 🖥️ Git: Para clonar este repositório. 💻

📝 Como Executar os Testes Clone o repositório abaixo para o seu ambiente local:

https://github.com/pgporcaro/api-serverest-loja-virtual.git

Abra o Carteiro.

Importe uma coleção de testes:

Clique no botão "Importar" no canto superior esquerdo do Postman. Selecione o arquivo API-serveRest.postman_collection.json na pasta do repositório clonado. Importe as variáveis ​​de ambiente Clique no botão "Importar" novamente. Selecione o arquivo API-serveRest.postman_environment na pasta do repositório clonado. Selecione a variável de ambiente importada na barra lateral do Postman. Execute uma coleção de testes: Selecione a coleção "api-serverest-loja-virtual" e depois no botão "Run" no canto superior direito da tela. Na nova aba chamada "Runner", clique em "Run api-serverest-loja-virtual no botão inferior do lado direito da tela" e aguarde a execução dos testes. Será aberta uma nova aba chamada "api-serverest-loja-virtual- Run results", nela visualize os resultados dos testes.

🔄 Integração Contínua (CI/CD) O projeto possui um fluxo de trabalho configurado em .github/workflows/main.yml. A cada solicitação push ou pull, os testes são executados automaticamente via GitHub Actions. O status da execução pode ser acompanhado na aba Actions do repositório no GitHub.

📁 Estrutura do Projeto api-serverest-loja-virtual-postman/ ├── .github/workflows/main.yml # Workflow de CI/CD ├── README.md # Documentação do projeto ├── API-serveRest.postman_collection.json # Coleção de testes Postman ├── API-serveRest.postman_environment # Ambiente Postman

🤝 Contribuição Sinta-se à vontade para abrir issue ou pull requests com sugestões, melhorias ou correções. Mantenha a padronização dos arquivos e atualize o README se necessário.
