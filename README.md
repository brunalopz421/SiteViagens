# SiteViagens

## Comandos Git:

### git init - _Para iniciar o git no seu projeto_

### git add - _Para incluir as alterações de um ou vários arquivos em nosso próximo commit._

**Para adicionar um único arquivo:**

```
  git add nome-do-arquivo
```

**Para adicionar todos arquivos do projeto:**

```
  git add .
```

### git commit - _Para salvar as alterações feitas antes pelo git add, com a opção de uma breve descrição_

```
  git commit -m "mensagem do commit"
```

### git branch - _(Necessário configurar apenas no começo do projeto, ou quando está trabalhando com mais de uma pessoa no projeto) Podemos usar o comando git branch para criar, listar e excluir as branches._

**Como criar uma branch:**

```
  git branch nome-da-branch
```

**Enviar da sua branch para o repositório remoto, você precisa usar o comando a seguir:**

```
  git push -u local-remoto nome-da-branch
```

**Visualizar branches:**

```
  git branch ou git branch --list
```

**Excluir branches:**

```
  git branch -d nome-da-branch
```

### git push - _É responsável por enviar suas alterações ao servidor remoto, git push faz o upload dos seus commits no repositório remoto._

```
  git push repositório-remoto nome-da-branch
```
