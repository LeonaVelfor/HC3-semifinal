# Loja da Maria

Projeto construído em VTEX.IO e AWS para a semifinal do Hiring Coders #3. O desafio proposto era criar um front-end funcional, responsivo e com boa UI, de um E-commerce que estivesse com o processo de compras funcional e que possuisse uma API, hospedada em AWS, que armazenasse transformava as compras faturadas em pontos a serem exibidos no front para o usuário.

## 🚀 Começando


### 📋 Recomendações


``` 
1. Fazer login na workspace Control <https://controll.myvtex.com/admin> para a correta visualização das categorias de produtos.

2. Utilizar o Insomnia ou o Postman para validação das API's.
```

## 📦 Desenvolvimento

### Frontend

* Notion: [Acesse Aqui](https://nonstop-iguanadon-22e.notion.site/Ideias-para-o-Front-End-54ec6c6bc8e44462835b2df6817df0f0)
* Benchmark: [Frontend](https://nonstop-iguanadon-22e.notion.site/Benchmark-Front-0d343129b7bb4d1d97a099e4fe0636bb)
* Benchmark [Sistema de Pontos](https://nonstop-iguanadon-22e.notion.site/Benchmark-Sistemas-de-Pontos-d5f68f137b764b71b75bbaa0292c33ad)
* Figma: [Acesse Aqui](https://www.figma.com/file/6aahFva4lbFnXsdmOMlzQE/Projeto-hiring-coders)

### Backend

* Notion: [Acesse Aqui](https://nonstop-iguanadon-22e.notion.site/Ideias-para-Back-End-e69803bf11484699976015dd7d7591aa)


## APIs

* 1
GET: https://gs9vut5z2m.execute-api.sa-east-1.amazonaws.com/points // lista todos os usuarios cadastrados

* 2
POST: https://gs9vut5z2m.execute-api.sa-east-1.amazonaws.com/points // salva os dados {userID, points}

* 3
GET: https://gs9vut5z2m.execute-api.sa-east-1.amazonaws.com/points/:{id} // busca um cliente pelo ID

```
"userID": "string",
"points": "number"
```

## 🛠️ Construído com

* [VTEXIO](https://developers.vtex.com/vtex-developer-docs/docs/welcome) - O framework web usado
* [AWS](https://aws.amazon.com/) - Para construção do Backend


## ✒️ Autores

* **Cristiane Santos** - *Frontend e Documentação* - [Cristiane](https://www.linkedin.com/in/cristianedsc/)
* **Flávio Viana** - *Prototipação e Frontend* - [Flávio](https://www.linkedin.com/in/fl%C3%A1vioviana113/)
* **Leona Vieira Evangelista** - *Frontend e Documentação* - [Leona](https://www.linkedin.com/in/leona-evangelista/)
* **Rodolfo da Silva** - *Backend* - [Rodolfo](https://www.linkedin.com/in/rodolfo-silva-14573b117/)
* **Victor Hugo Fonseca** - *Frontend* - [Victor](https://www.linkedin.com/in/victorhugommf/)
* **Walter Souza** - *Prototipação e Backend* - [Walter](https://www.linkedin.com/in/waltersasouza/)


## Preview
* [prev1](https://ibb.co/9VZxn6B)
* [prev2](https://ibb.co/TmgGttD)




