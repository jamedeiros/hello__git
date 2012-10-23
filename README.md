Treinamento Git - 0.1
=====================
José Augusto de Medeiros <jamedeiros@gmail.com>

Tutorial desenvolvido durante o treinamento e pode ser seguido por novos seguidores.

Configurando usuário e email:
----------------------------
git config --global user.name "NOME"
git config --global user.email "EMAIL"

Configurando extenções que devem ser ignoradas durante o commit
1 - Criar um arquivo chamado .gitignore
2 - Colocar as extensões a serem ignoradas, exemplo: *.pyc


Comandos:
---------
# Como clonar um repositório: git clone https://github.com/jamedeiros/hello__git.git
# Adicionando novos arquivos ou modificados: *git add <arquivo>*
# Para verificar o status: *git status*
# Para comitar as mudanças: *git commit -m "MENSAGEM"*

# Removendo arquivos: *git rm <arquivo>*

# Para listar as diferenças entre arquivos versionados: *git diff*
# Para listar as diferenças também pode ser utilizado: *git show*
# Para listar o histórico do repositório: *git log*
# Para realizar diff entre branchs: *git diff <BRANCH> <BRANCH>*

# Para mostrar modificações em um arquivo - com a pessoa que modificou: *git blame <arquivo>*

# Para reverter um arquivo: *git checkout <arquivo>*

* Trabalhando com branch
# Para listar os branchs: *git branch*
# Para criar um novo branch: *git branch <nome>*

* Para realizar o merge: *git merge <branch> <branch>*

* Trabalhando com TAG
# Listar as tags: *git tag*
# Criar uma nova tag: *git tag -af <nome|versão>*
# Acessando uma tag: *git checkout <tag>


Obs.:
   1. Para realizar commits sem precisar adicionar pode-se utilizar: *git commit -am*
   2. Quando acessamos uma TAG, os arquivos não podem ser modificados, ou seja, a TAG é uma fotografia do repositório.


