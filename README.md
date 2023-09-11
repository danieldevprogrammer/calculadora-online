# Calculadora Online
Uma calculadora on-line criada para cumprir com a tarefa da criação detalhada de um README de um projeto para o desafio do módulo 02 do curso de **Desenvolvedor de Software Backend** da Cubos Academy, foi uma API simples mas que serviu para testar e práticar os conhecimentos aprendidos no decorrer das aulas.

Nesta API criamos um servidor com 4 rotas GET para executar as 4 operações básicas da matemática (somar, subtrair, multiplicar, dividir).

## Pré-requisitos

![Node.js](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000.svg?style=for-the-badge&logo=Express&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF.svg?style=for-the-badge&logo=Insomnia&logoColor=white)

## Como instalar a API
Para instalar e executar o código da calculadora on-line, siga o passo a passo a seguir:

1. Clone este repositório:

```
git clone git@github.com:danieldevprogrammer/calculadora-online.git
```

2. Acesse o repositório:

```
cd calculadora-online
```

3. Instale as dependências:

```
npm install
```

---

## Funções da API

- Somar;
- Subtrair;
- Multiplicar;
- Dividir;

---

## Endpoints para utilização da API
Os números atribuidos aos parametros num1 e num2 nas rotas a seguir, são apenas sugestões é possivel usar qualquer número que desejar.

GET - Somar
```
"http://localhost:3000/somar?num1=10&num2=5"
```
GET - Subtrair
```
"http://localhost:3000/subtrair?num1=10&num2=5"
```
GET - Multiplicar
```
"http://localhost:3000/multiplicar?num1=10&num2=5"
```
GET - Dividir
```
"http://localhost:3000/dividir?num1=10&num2=5"
```
---

## Utilização dos Endpoints da API
A seguir temos a exemplicação da utilização de cada endpoints para acessar as funções da calculadora usando o isomnia.

![Insomnia - Utilização de endpoints](https://github.com/danieldevprogrammer/calculadora-online/blob/main/src/images/calculadora-online.gif?raw=true)