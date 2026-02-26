# Git
Um projeto de estudos para o treino do uso da ferramenta git por meio da CLI.

## Codigos

### $ git init

iniciar um repositorio

### $ git clone <url>

clonar um repositorio ja existente

### $ git add “arquivo”

adiciona arquivos ao seu repositorio 

### $ git commit “arquivo”

leva o arquivo adicionado para a comissão desses arquivos (Prepara eles)

### $ git push

entrega tudo que estava em “commit” para o github

### $ git status

checa em qual situação o git está naquele momento, branch, e se tem algo a comitar ou ser adicionado

### $ git branch

“Caminho” que o seu git está seguindo para fazer as adições, posso ter varias branchs e ficar alternando entre elas para fazer uma estrutura do meu codigo e locais de trabalho para depois adicionar novas coisas no nosso programa

### $ git checkout

checa em qual branch eu estou trabalhando

### $ git log

acessa todos os commits feitos “historico”

### $ git commit —amend

pega a sua ultima alteração e conserta uma alteração, usado para pequenas coisas “Remenda o ultimo commit” (pede um $ git pull, para entregar mesmo assim use $ git push —force-with-lease)

### $ git pull

checa se tudo está dentro da mesma “linha do tempo”, ramificação… 

---

## Conceitos

### main

“linha do tempo sagrada”

### .gitignore

Arquvio de identificação de projeto especifico para ignorar o envio pelo git para a pagina do projeto no github

### .env

local no projeto para se guardar dados sensíveis e não desejados para o github (chave de api, cadastro de banco de dados…)

“DATABASE_PASSWORD=senha”

“${DATABASE_PASSWORD}”

### Branch

linhas do tempo para adição 

git push deve ser especificado para qual branch que eu quero enviar com **$ git push origin “branch”**

“estou trabalhando no funcionamento de uma função do meu programa na branch ‘main’, mas surgiu uma issue urgente, crio uma nova branch para trabalhar na issue especifica e depois adicioná-la”

### Pull Requests

Solicitação de mesclagem (merge) para a main, sendo possível uma revisão antes do merge (Trabalho em conjunto)
