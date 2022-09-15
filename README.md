<center> <h1>💻 Boas Praticas do dia-a-dia de um Dev 💻</h1> </center>

## Descrição

<p>Neste readme deixarei alguns exemplos de comandos que usamos em nossos dias a dias como desenvolvedores. </p>

--------------------
## Tabela de conteúdos
<!--ts-->
   * [Como criar uma branch](#como-criar-uma-branch)
   * [Como mudar a branch](#como-mudar-a-branch)
   * [Como atualizar uma branch](#como-atualizar-uma-branch)
   * [Como commitar uma branch](#como-commitar-uma-branch)
   * [Como fazer um push](#como-fazer-um-push)
   * [Autor](#Autor)

<!--te-->
--------------------
## Como criar uma branch
<p> Os repositórios no GitHub funcionam como uma árvore. Quando criamos um repositório, ele automaticamente é iniciado com a branch master, que é equivalente ao tronco da sua árvore, ou seja, é a parte principal do seu projeto. As próximas branches são secundárias e, portanto, ramos da branch master. 
Em aplicações desenvolvidas por mais de uma pessoa, é uma boa prática que além da master, cada desenvolvedor crie e desenvolva seu código em sua própria branch, que pode ter qualquer nome.
 
  
Como criar uma branch:
Abra seu terminal certifique-se que esta na branch master/main digite o seguinte comando:</p>

```bash
# PARA VERIFICAR A BRANCH:
$ git checkout main 

# PARA GERAR UMA NOVA BRANCH:
$ git checkout -b nome-da-branch

```

<h3>Exemplo em imagens📌</h3>

<img src="scr\open-terminal.jpeg" width="900px;" alt=""/>
<img src="scr\create-branch.jpeg" width="900px;" alt=""/>
<img src="scr\create-branch-1.jpeg" width="900px;" alt=""/>


--------------------
## Como mudar a branch

<p>Para mudar de branch é muito simples, execute este comando no terminal:</p>

```bash
# PARA TROCAR A BRANCH:
$ git checkout nome-da-branch

```
<h3>Exemplo em imagens📌</h3>

<img src="scr\checkout.jpeg" width="900px;" alt=""/>
<img src="scr\checkout1.jpeg" width="900px;" alt=""/>

--------------------
## Como atualizar uma branch

<p> Primeiramente para saber se sua branch esta atualizada ou nao sempre devemos dar um git pull antes de começarmos o projeto mas oque é um git pull?
O comando git pull é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em Git. </p>

```bash
# COMO FAZER UM GIT PULL:
$ git pull origin main

# A MAIN É REFERENTE A BRANCH QUE VOCE GOSTARIA DE PUXAR 
# NO CASO ESTOU PUXANDO DA BRANCH MAIN

```
<h3>Exemplo em imagens📌</h3>
<img src="scr\Screenshot_6.png" width="900px;" alt=""/>
<img src="scr\Screenshot_7.png" width="900px;" alt=""/>


--------------------
## Como commitar uma branch

<p> Oque sao commits, criados com o comando git commit para capturar o estado de um projeto naquele momento.</p>

```bash
# COMO FAZER UM COMMIT:
# PRIMEIRO DEVEMOS ADICIONAR AS NOSSAS ALTERAÇOES.

$ git add .

# COM ESTE COMANDO ESTAREMOS ADICIONANDO TODAS AS ALTEREÇOES FEITAS.
# DEPOIS DEVEMOS COMMITAR COM O SEGUINTE COMANDO

$ git commit -m "Breve explicaçao da alteração

# PARA CONFIRMAR SE TODAS AS ALTERAÇOES FORAM FEITAS DE UM GIT STATUS

$ git status

```

<h3>Exemplo em imagens📌</h3>
<img src="scr\Screenshot_8.png" width="900px;" alt=""/>
<img src="scr\Screenshot_9.png" width="900px;" alt=""/>
<img src="scr\Screenshot_10.png" width="900px;" alt=""/>


--------------------
## Como fazer um push 

<p>Apos commitarmos devemos subir o nosso projeto para o github ou onde esta armazenado ou seu projeto, para isso devemos fazer um push seguindo estes comandos</p>

```bash
# PARA FAZER UM PUSH:
$ git push origin nome-da-branch

```
<h3>Exemplo em imagens📌</h3>

<img src="scr\Screenshot_11.png" width="900px;" alt=""/>
<img src="scr\Screenshot_12.png" width="900px;" alt=""/>

--------------------

## Autor


 <img style="border-radius: 50%;" src="scr/FotoPerfil.jpeg" width="100px;" alt=""/>
  <br />
 <sub><b>Matheus Torsoni</b></sub></a>

Feito por Matheus Torsoni👋🏽 Entre em contato!

[![Twitter Badge](https://img.shields.io/badge/-@tcmatheus-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/tcmatheus_)](https://twitter.com/tcmatheus_) [![Linkedin Badge](https://img.shields.io/badge/-Matheus-Torsoni?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/matheus-torsoni-b33957156/)](https://www.linkedin.com/in/matheus-torsoni-b33957156/) 
[![Outlook Badge](https://img.shields.io/badge/matheus_tcampos@hotmail.com-c14438?style=flat-square&logo=outlook&logoColor=white&link=mailto:matheus_tcampos@hotmail.com)](matheus_tcampos@hotmail.com)
