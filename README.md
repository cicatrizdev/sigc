# sigc
## LP3 - Sistema Interno de Gerenciamento de Chamados <br>

### Instruções:
* Clone o projeto; <br>
* Exporte no Netbeans; <br>
* Rode o projeto para as dependências serem baixadas automaticamente; 

### Guia pra trabalhar nesse projeto:

* Clonando o repositório (com chave ssh cadastrada)

`git clone git@github.com:cicatrizwp/sigc.git` <br>
`cd sigc`

* Clonando o repositório (sem chave ssh)

`git clone https://github.com/cicatrizwp/sigc.git` <br>
`cd sigc`

* Ponto de partida para modificar o código

`git checkout master` <br>
`git pull --all` <br>
`git checkout -b <nome da nova branch>` (ex.: git checkout -b alteracao1) <br>
`git push --set-upstream origin <nome da nova branch>` (ex.: git push --set-upstream origin alteracao 1)

* Após fazer alterações, fazer o merge na master

`git add .` <br>
`git commit -m “descricao das alteracoes”` <br>
`git push` <br>
`git checkout master` <br>
`git pull --all` <br>
`git merge <nome da branch>` <br>
