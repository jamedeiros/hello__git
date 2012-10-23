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
# Adicionando novos arquivos ou modificados: git add <arquivo>
# Para verificar o status: git status
# Para comitar as mudanças: git commit -m "MENSAGEM"

# Removendo arquivos: git rm <arquivo>

# Para listar as diferenças entre arquivos versionados: git diff
# Para listar as diferenças também pode ser utilizado: diff show
# Para listar o histórico do repositório: git log

Obs.:
   # Para realizar commits sem precisar adicionar pode-se utilizar: git commit -am

