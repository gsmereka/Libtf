# Libtf

### Português | [English](./README_en.md)

## Bliblioteca de funções em C.

Esta biblioteca foi desenvolvida em ambiente **Linux** e contém um conjunto de funções padrão em **C** que foram implementadas e testadas por mim. Além de aprender sobre o funcionamento dessas funções, o objetivo deste projeto foi criar uma biblioteca útil que possa ser utilizada e aprimorada em outros projetos, incluindo futuros projetos da **[42 SP](https://github.com/gsmereka/42_Projects)**.

## Como Utilizar a Libft em seu projeto ?

1. Verifique as [Dependencias](#dependencias).
1. Clone o Repósitorio.
	- ```git clone https://github.com/gsmereka/Libft.git```
1. Compile a biblioteca.
	- cd libft.
	- make.
1. Inclua o cabeçalho da libft no cabeçalho do seu projeto, exemplo:
	- ```#include libtf/header/libft.h```
1. Compile seu projeto incluindo o arquivo libft.a, exemplo:
	- ```gcc seu_projeto.c libft/libft.a``` 

## Dependencias

- ```sudo apt-get update```
- bibliotecas
	- ```sudo apt-get install libc6-dev```
- Makefile
	- ```sudo apt-get install make```
- gcc
	- ```sudo apt-get install build-essential```