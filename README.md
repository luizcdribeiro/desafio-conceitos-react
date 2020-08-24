# desafio-nodejs

<img src="https://reactjs.org/logo-og.png" title="ReactJS" alt="ReactJS" width="100" align="center">


# Desafio: Conceitos do ReactJS

> Começando no Bootcamp do excelente Gostack 11 disponibilizado pela Instituição de Ensino Rocketseat

- O objetivo do desafio era  criar uma aplicação para treinar o que aprendemos até agora no ReactJS, podendo adicionar ou remover os repositorios criados!
- Para isso criamos duas funções que adicionariam o repositorio através do setRepositories e uma que deletaria o repositorio pelo id


## Exemplo de uma das funções que aprendemos e praticamos

```javascript
// code away!

async function handleAddRepository() {
    const response = await api.post('repositories', {
      title: "Desafio Javascript", 
      url: "https://github.com/luizcdribeiro/desafio-nodejs", 
      techs: ["Node.js", "Express", "Javascript", "React"], 
    })
    setRepositories([...repositories, response.data])
  }
```

---

## Instalação

- Possua o Node mais atual é o ideal para o servidor funcionar de forma eficaz

### Clone

- Clone esse repositório na sua maquina utilizando `https://github.com/luizcdribeiro/desafio-conceitos-react`

### Configuração

> Verifique se possui o `yarn` e o `node` instalados e atualizados na sua máquina

```shell
$ yarn -v
$ node -v
```

> Execute o comando abaixo e inicie o node para a aplicação iniciar

```shell
$ yarn
$ yarn start //inicia a aplicação
```
> Execute o comando abaixo para realizar os testes da aplicação

```shell
$ yarn test
```

## Contato

<a href="https://twitter.com/luizjuniordant1">
  <img align="left" alt="Ajay's Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.linkedin.com/in/luiz-carlos-dantas-ribeiro-junior-7422b9124/">
  <img align="left" alt="Ajay's Linkdein" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://github.com/luizcdribeiro">
  <img align="left" alt="Ajay's Github" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
</a>
