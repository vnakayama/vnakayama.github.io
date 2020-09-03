---
layout: post
title:  "Instalação do CircuitMaker 2000 com Wine em sitemas Unix"
date:   2020-07-28 16:55:45 -0300
categories: jekyll update
---

## Download
Faça o download do arquivo zip [aqui][download].
## macOS (Catalina não suportado)
### Instalação
Abra o aplicativo Terminal. Caso você não saiba onde achá-lo, utilize a lupa na barra superior da tela para procurar. Copie e cole o código abaixo, e aperte **Return**.
```
cd ~/Downloads/CircuitMaker\ 2000/
sh circuitmaker2000_macOS.sh
```
Siga os passos do instalador, selecionando a versão **Standard** e as outras opções padrão. A chave de ativação é:
```
5axx-wcdj-qyba-c92n
```
A instalação completa pode demorar vários minutos, então não estranhe a demora.
### Rodando pela linha de comando
Sempre que desejar rodar o simulador, é necessário rodar o atalho pelo terminal:
```
circuitmaker
```
Caso não queira abrir o simulador pela linha de comando todas as vezes, siga o passo a passo abaixo para criar um aplicativo executável.
### Criando o executável (Em construção)
Baixe o WineBottler [aqui][winebottler].
* O WineBottler não funcionou na minha máquina, assim que voltar concluo o tutorial.
## Linux (Em construção)

[download]: https://drive.google.com/file/d/1gIWiCRRrABUL2n3EeoBzjJDkgWVioMGZ/view?usp=sharing
[winebottler]: https://winebottler.kronenberg.org/
