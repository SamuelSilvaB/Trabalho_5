<h1 align="center">Trabalho 5</h1><br>

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

<h1 align="center">Problema</h1>

<h3>Implementar uma função que cria uma estrutura para o heap. Além de funções para adicionar e remover números inteiros na heap respeitando as regras da estrutura.</h3><br>

### :warning: Para rodar a aplicação é nescessario ter o `gcc` e o `git` instalado na sua máquina, caso já tenha avance para: 

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

<h1 align="center">instalando o Gcc </h1>

No terminal digite o seguinte comando:

```
sudo apt update 

sudo apt install build-essential
```

<h1 align="center">instalando o Git </h1>

No terminal digite o seguinte comando:

```
sudo apt-get update sudo apt-get install git
```
<h1 align="center">
Como rodar a aplicação :arrow_forward:
</h1>

Clone o projeto no terminal:
```
git clone https://github.com/SamuelSilvaB/Trabalho_5.git
```
Logo após clonar o projeto, entre na pasta clonada com o seguinte comando no terminal:
```
cd Trabalho_5
```
Em seguida, obtenha as bibliotecas com o seguinte comando:
```
gcc -c trabalho_5.c
```
## Compilação

Cole o comando no terminal para gera um arquivo execultável:

```
gcc ./trabalho_5.o ./main.c -o main
```

## Execução
Cole um dos seguintes comandos para rodar o projeto:

Linux:
```
./main
```
Windows:
```
./main.exe
```

Após isso, o programa irá printar os elementos que foram adicionados e organizados na heap. Em seguida, o programa irá remover os elementos e printar os removidos, e por último, o programa será encerrado.
