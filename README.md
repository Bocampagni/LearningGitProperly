# GIT

* `git init` -> inicia a linha do tempo
* `git add` -> Adiciona o arquivo para ser commitado
* `git commit` -> Cria um ponto na linha do tempo
* `git commit -am` -> Atualiza o commit, sem gerar outro hash.
* `git log` -> Mostra os pontos na história do projeto
* `git status` -> estado do desenvolvimento
* `git show` -> Mostra os acontecimentos de um dado ponto na história (último ponto do log)


## git branch ->
    É uma ramificação que podemos fazer a partir da linha principal de desenvolvimento.
    É como uma dimensão paralela que podemos usar para fazer alterações em nosso desenvolvimento sem precisar muda-lo de fato.
    A master é nossa linha principal, todas as branchs serão ramificações dela. 




* `git branch` -d -> deleta a branch especificada
* `git branch name` -> cria uma branch chamada name.
* `git branch` null -> lista todas as branchs

* `git checkout` -> similar ao cd do windows. Muda da master para a branch.
* `git checkout -b name` -> Cria uma branch chamada name e muda pra lá.
* `git merge` -> vai unir as branchs




# GITHUB

* `git remote` -v -> olha os repositórios remotos.
* `git push` -u origin master -> É necessário criar a branch master quando vamos fazer o `git push` pela primeira vez.
* `git push` -> vai empurrar o repositório local para o da nuvem.
* `git clone` -> Clona um projeto.
* `git pull`-> Atualiza o repositório local em relação ao repositório da nuvem.

# Recuperando um arquivo em um dado ponto passado:

* `git checkout ` + hash do commit + nome do arquivo -> Irá te retornar o arquivo já pronto para o commit.

# Recuperando um arquivo deletado:

    Caso você tenha deletado o arquivo, ao invés de ir na lixeira, você pode recuperar pelo git: 
* `git checkout -- ` + nome do arquivo.