#Github

#Curso de git e github:

O curso foi levado no site https://www.udemy.com/ com link https://www.udemy.com/git-e-github-para-iniciantes ...

#Setup inicial:

git config --global [user.name, user.email] "informações"
git config --list

#Comandos básicos:

git init
git status
git log [--graph, --decorate]
git add [., nome do arquivo]
git commit [-a(adiciona tudo), -m(mensagem),]
git diff [--name-only]
git reset [--soft, --mixed, --hard]

#Para criar e pegar chave SSH:

ssh-keygen -t rsa -b 4096 -C "andre.cfs@fisica.ufrn.br"

cd ~/.ssh/
[cat, more] id_rsa.pub

#Configurando repositório remoto:

git remote add origin git@github.com:andrcfs/git.git
git remote [-v]
git push [-u] origin master

-Clonando:

git clone [endereço ssh] [nova pasta]

#Criando e usando um branch:

git checkout [-b(cria)] [nome do branch]
git branch [-D(deleta)]

