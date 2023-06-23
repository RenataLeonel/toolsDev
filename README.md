![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>

<h1 align="center"> Tools for Dev</h1>

<h5 align="center">Seu guia de instalação de ferramentas essências para dev!</h5>

<p align="center">
<img src="https://github.com/RenataLeonel/toolsDev/assets/62951843/dc15729b-2d69-43db-98fe-124090ee9e27"/>
</p>

# 🛠️  Tools do projeto

- `Git`: Sistema de controle de versão open source
- `SDKman`: Sistema de gestão de versões paralelas de vários Kits de Desenvolvimento de Software, incluindo o JAVA


## Installation

## ✔️ Instalando o git 
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

## ✔️ Instalando o SDKman 

------------

Disponibilizado por Renata Leonel.
