# saucedemo-bootcampcypress
Projeto de automação em cypress da página saucedemo

<p align="center">Esse projeto tem por objetivo realizar a automação de 3 cenários de testes  página saucedemo</p>

### 🌱 Cénarios de Teste

- [x] Efetuar login com cada um dos tipos de usuário disponíveis
- [x] Efetuar login com standard_user e mudar a forma de ordenação dos produtos; realizar também a compra de um produto qualquer e validar
- [x] Adicionar 3 itens a sacola e verificar a soma do valor total

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- Cypress
- Javascript


### 🤝 Para executar o projeto:

    Para executar os testes em sua máquina, você pode baixar esse projeto usando o Github e seguir os passos abaixo:<br>

    Instalar as dependências configuradas do package.json, usando o comando: yarn install
    Executar uma spec específica no modo headless com o comando: 
    Executar testes no modo interface do cypress com o comando: yarn cypress open

### 🤝 Para executar testes com Allure:
    Apagar os testes que já foram executados com o comando: 
        yarn run allure:clear   
    Executar teste por linha de comando gerando allure results
        yarn cypress run --env allure=true
    Depois de gerar allure results, apresentar o servidor de testes
        yarn allure serve
