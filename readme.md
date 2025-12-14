# API Calculadora Matemática

Este projeto consiste em uma API REST simples desenvolvida em Node.js com Express,
capaz de executar as quatro operações matemáticas básicas: soma, subtração,
multiplicação e divisão.

O projeto foi desenvolvido com fins acadêmicos, visando a prática de criação de
endpoints REST, uso do npm e versionamento com Git.

---

## Tecnologias Utilizadas

- Node.js
- Express.js
- JavaScript
- Git e GitHub

---

## Como Executar o Projeto

### Clonar o repositório
```bash
git clone https://github.com/seu-usuario/calculadora
````
Acessar a pasta do projeto
```bash
cd Calculadora
````
Instale as dependências
 ```bash
npm install
```` 
Executar a aplicação
 ```bash
npm start
````
O servidor sera iniciado 
``` bash
http://localhost:3000
````
## Como Utilizar a API
### Regras e Validações

Os parâmetros a e b devem ser números.

Divisão por zero não é permitida.

Em caso de erro, a API retorna o status HTTP 400.
``` bash
GET /math/soma?a=10&b=5
GET /math/subtracao?a=7&b=2
GET /math/multiplicacao?a=3&b=5
GET /math/divisao?a=15&b=3
````







