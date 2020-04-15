<!-- # bootcamp-gostack-desafios -->
![](./images/header.png)

<h3 align="center">  Desafio 2 - Conceitos NodeJs </h3>

### Sobre o desafio

Neste desafio foi proposto que fosse feito um crud de repositorios do Github.

### As rotas

![](./images/rotas.PNG)

Um crud para quem não sabe é feito dos seguintes metodos:

- Create
- Update
- Read (list)
- Delete

- Rota para Listar  dd
    url : /repositories, 

- Rota para criar
    url : /repositories
    <br>parametros : title, url, techs 

- Rota para alterar
    url : /repositories/:id,
    <br>parametros :  título, url, techs, id do repositorio que vem no header da requisição

- Rota para deletar
    url : /repositories/:id,
    <br>parametros : id do repositorio que vem no header da requisição 

- Rota para incrementar likes
    url : /repositories/:id/likes,
    <br>parametros : id do repositorio que vem no header da requisição 

---

> Conceitos do foguete. 
