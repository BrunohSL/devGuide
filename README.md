# Dev Guide
#### Instruções de intalação e configuração de projetos
____
## Indice
  * **1 - GitHub**
  * **2 - PHP + Composer**
  * **3 - Laravel**
  * **4 - NodeJs e ReactJs**
  * **5 - Yarn**
____

## 1 - GitHub

* **sudo apt-get update**
* **sudo apt-get install git**
____

## 2 - PHP + Composer
  
  * Instalar o PHP e alguma bibliotecas para o composer
    * **sudo apt-get update**
    * **sudo apt install php7.2**
    * **sudo apt-get install php7.1-xml**
    * **sudo apt-get install php-mbstring**
    
  * Instalar o Composer
    * **sudo apt install composer**
_____

## 3 - Laravel
  ### Após instalar o PHP e o composer seguir os passos abaixo
  
  * 1 - Vá até a pasta onde ficará o projeto e rode o comando abaixo alterando o **nome_do_projeto**
    * **composer create-project --prefer-dist laravel/laravel nome_do_projeto "5.5.*"**

  * 2 - Acessar pasta do projeto e instalar as dependencias do composer
    * **cd nome_do_projeto**
    * **composer install**

  * 3 - Acessar a url abaixo para ver a tela inicial padrão do Laravel
    * **localhost:8080/**
____
  
## 4 - NodeJs e ReactJs

  * **sudo apt-get update**
  * **sudo apt-get install nodejs**
  * **sudo apt-get install npm**
    * **nodejs -v** (Deve exibir a versão do node que está instalada)
    * **npm -v** (Deve exibir a versão do npm que está instalada)
  * **sudo apt-get install -y build-essential**
  * **sudo npm install -g create-react-app**
____
## 5 - Yarn

 * **curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -**
 * **echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list**
 * **sudo apt update**
 * **sudo apt install yarn**
