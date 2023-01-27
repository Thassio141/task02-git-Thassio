# task02-git-Thassio   

## Neste README será abordado oque aprendi com as aulas de git!

## Releembrei coisas iniciais do git como:

Criação de um novo projeto com o git:
```shell
$ git init 
```

Adcionar os arquivos na área de preparação:
```shell
$ git add .
```

Fazer um commit: 
```shell
$ git commit -m "oque foi feito"
```

Saber como está a situação da área de preparação:
```shell
$ git status
```

Criação do repositorio remoto:
```shell
$ git remote add escolher-nome url-do-repositorio
```

Usar o push para mandar o commit junto com novas alterações para o github:
```shell
$ git push
```

E o clonar o repositorio no github:
```shell
$ git clone url
```

## Aprendi boas praticas para nomeclatura de categoria de branch:

**docs:** apenas mudanças de documentação;<br>

**feat:** uma nova funcionalidade;<br>

**fix:** a correção de um bug;<br>

**perf:** mudança de código focada em melhorar performance;<br>

**refactor:** mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;<br>

**style:** mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);<br>

**test:** adicionar ou corrigir testes.<br>

# Aprendi novas funções como: 

## Git checkout -b
É utilizado para criar uma nova branch.

```shell
$ git checkout -b nome-da-branch
```

E tambem usado para mudar de branch

```shell
$ git checkout nome-da-branch
```

## Git rebase
É utilizado para alterar um ou vários commit e também é possível unificar diversos commits em um único commit.


![image](https://user-images.githubusercontent.com/73563601/214727711-8afba25a-a1be-43f9-a2d4-262353cbfa00.png)
## Sintaxe
```shell
$ git rebase (nome-da-branch)
```
## Aplicação
```shell
$ git rebase main
```

# Git cherry-pick
Permite ao usuário selecionar commits específicos para trazer ao branch desejado.


![image](https://user-images.githubusercontent.com/73563601/214729395-fe12193e-3559-4763-a188-31ab681d0d1b.png)
## Sintaxe
```shell
$ git cherry-pick (nome-da-branch)
```
## Aplicação
```shell
$ git cherry-pick master
```

# Git revert
É usado para desfazer alterações ao histórico de commits do repositório.


![image](https://user-images.githubusercontent.com/73563601/214730557-d6989c6c-3333-467c-9b6b-406e9a5a97ce.png)

## Sintaxe
```shell
$ git revert 
```
## Aplicação 
```shell
$ git revert HEAD~3
```

# Git squash
A combinação por squash permite que você combine vários commits no histórico do seu branch em um único commit.


![image](https://user-images.githubusercontent.com/73563601/214730843-62a9bab0-ee16-4187-bf30-83bbf2ef2f78.png)

## Sintaxe
```shell
$ git rebase 
```
## Aplicação 
```shell
$ git revert HEAD
```



Falta falar sobre :

git fetch
git status
git checkout
git branch
A importancia do gitignore
git pull
git stash & git stash list
git reset

A importancia do Pull Request e do Merge

### Git Flow

→ **O Git Flow padrão genérico trabalha com duas branches principais, a Develop e a Main, que duram para sempre; e três branches de suporte, Feature, Release e Hotfix, que são temporários e duram até realizar o merge com as branches principais.**