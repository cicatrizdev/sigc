# sigc
## LP3 - Sistema Interno de Gerenciamento de Chamados <br>


### Guia pra trabalhar nesse projeto:

* Clonando o repositório (com chave ssh cadastrada)

`git clone git@github.com:cicatrizwp/sigc.git`

* Clonando o repositório (sem chave ssh)

`git clone https://github.com/cicatrizwp/sigc.git`

* Ponto de partida para modificar o código

`git checkout master`

`git pull --all`

`git checkout -b <nome da nova branch>` (ex.: git checkout -b alteracao1)

`git push --set-upstream origin <nome da nova branch` (ex.: git push --set-upstream origin alteracao 1)

* Após fazer alterações, fazer o merge na master

`git add .`

`git commit -m “descricao das alteracoes”`

`git push`

`git checkout master`

`git pull --all`

`git merge <nome da branch> `
