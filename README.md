# zonatech
Transportes e Servicos

Transporte de Carga e Serviços

PASSOS A EXECUTAR PARA INSTALAÇÃO DO AMBIENTE Foram usadas duas tecnologias CORDOVA E FRAMEWORK7

---------------- CONFIGURAÇÃO DO AMBIENTE CORDOVA -------------------

Instalar Node.Js e npm
Atraves do CMD execute os comandos a seguir
npm install -g cordova
cordova create nomeapp com.example.nomeApp NomeApp
Entrar na pasta do App: cd nomeapp
cordova platform add android
cordova platform add browser
cordova build android
-------------------- Instalacao do Tamplate Framework7 ---------------

npm install -g framework7-cli
npm install -g framework7-cli --unsafe-perm=true --allow-root
framework7 create --ui --port 8080 (Criação da aplicação especificando o porto a sua escolha)
Aceder o browser e escolher a opcão simple web app
Executar os comando no console mostrados no browser para buscar bibliotecas de desenvolvimento e produção
