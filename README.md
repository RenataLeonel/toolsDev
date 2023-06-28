![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>

<h1 align="center"> Tools for Dev - Linux/Ubuntu</h1>

<h5 align="center">Seu guia de instalação de ferramentas essências para dev!</h5>

<p align="center">
<img src="https://github.com/RenataLeonel/toolsDev/assets/62951843/dc15729b-2d69-43db-98fe-124090ee9e27"/>
</p>

# 🛠️  Tools do projeto

- `Git`: Sistema de controle de versão open source
- `SDKman`: Sistema de gestão de versões paralelas de vários Kits de Desenvolvimento de Software, incluindo o JAVA
- `Node`: Ambiente de execução do código JavaScript do lado servidor
 
## Installation

## ✔️ Git
<img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"/>

Abra o terminal e execute o comando a seguir para verificar se existe alguma versão já instalada
```bash
git --version
```
Se exibir alguma mensagem como demonstrado abaixo, já existe uma versão instalada.
```bash
Output
git version 2.25.1
```

Caso não tenha nenhuma versão instalada iremos prosseguir a instalação.

Utilizei o gerenciador de pacotes padrão APT do Ubuntu. Você pode atualiza-lo aexecutando o seguinte comando:
```bash
sudo apt update
```

No próximo passo, será realizado a instalação do git. Execute o comando a seguir para instalar a versão mais básica:
```bash
sudo apt install git
```
ou, o próximo comando que contém os subpacotes:
```bash
sudo apt-get install git-all
```

Verifique se a instalação foi concluída utilizando o comando `npm install`.

Com o git já instalado, seguimos para as configurações básicas.
Primeiro, configuramos o usuário:
```bash
git config --global user.name "Seu nome"
```
Em seguida, configuramos o e-mail. 

> **Warning**: É importante que seja o mesmo utilizado no github para evitar conflitos.
```bash
git config --global user.email seuemail@email.br
```

Para finalizar, conferimos a lista de configurações
```
git config --list
```
Instalação concluída com sucesso! 🏆 

## ✔️ SDKman

Em alguns sistemas o curl já vem instalado, caso o seu SO não tenha vamos instalar o curl utilizando o gerenciador de pacotes snap com o seguinte comando:
```
sudo snap install curl
```
Para verificar se o curl foi instalado execute:
```
dpkg -l | grep curl
```

Abra o terminal e execute o comando a seguir para iniciar a instalação do SDKman
```
curl -s "https://get.sdkman.io" | bash
```

Em seguida, digite e execute:
```
source "$HOME/.sdkman/bin/sdkman-init.sh"
```

Para verificar se a instalação foi concluída, consulte a versão utilizando o seguinte comando:
```
sdk version
```
Instalação concluída com sucesso! 🏆 

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>

Uma das facilidades do SDKman é gerenciar as versões do JAVA na sua máquina. Para visualizar as versões disponiveís do Java execute:
> Para sair da lista basta digitar a letra q 
```
sdk ls java
```

Para instalar o java basta executar o comando `sdk install java` com a versão escolhida, como no exemplo abaixo:
```
sdk install java 11.0.12-open
```

E, para selecionar a versão que deseja utilizar execute o seguinte comando
```
sdk use java 17.0.2-open
```

Caso queira desinstalar uma versão, execute o ccomando `sdk uninstall java` com a versão escolhida, como abaixo:
```
sdk uninstall java 11.0.12-open
```
Configuração JAVA concluída com sucesso! 🏆 

## ✔️ Node

Para intalar o node execute o script abaixo:
```
curl -fsSL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```
A númeração no script acima indica a versão, recomenda-se utilizar as versões LTS por serem mais estáveis.
E, para finalizarmos executamos o comando abaixo:
```
sudo apt-get install -y nodejs
```
O `-Y` serve para evitar a pergunta se quer ou não continuar que surge durante a instalação.
Para desistalar utilize:
```
sudo apt-get purge --auto-remove nodejs
```
Instalação concluída com sucesso! 🏆 





------------

Disponibilizado por Renata Leonel ✨
