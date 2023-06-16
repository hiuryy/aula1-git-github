# aula1-git-github
repositório com fins acadêmicos/ git e github

-para criar pasta:

mdkir nome da pasta

-para acessar pasta

CD nome-da-pasta

-para sair de uma pasta:

CD ..

-para iniciar repo: 

git init


Listar arquivos e pastar:

LS


-Criar arquvivo dentro da pasta:

echo "# nome-da-pasta" >> arquivo.extensão

-para adicionar conteúdo(arquivos)

git add nome-do-arquivo-pasta

-para adicionar todos os arquivos/pastas:

git add . git add

-para desfazer um add especificio 

git reset nome-do-arquivo

para desfazer um add geral:
 git reset

-Criar arquivo mais facil
touch teste.extensão

-Adicionar Commit

git commit -m "adicionamos pasta aula e arquivo README"
 
- para abrir o vs code
Code . 

-No vs code para fazer mudanças dentro do git bash sem dar commit(lembrar de deixar no auto save)

git status

-Retornar  ao ultimo commit, mantendo as alterações feitas nos arquivos 
git reset --soft HEAD~1

Voltar para o ultimo commit salvo

git reset --hard HEAD~1


-para adicionar o link do git e sair de master para main

 git remote add origin link

