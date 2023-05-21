Olá, esse projeto ensina você a usar o git

/* criando um repositório no git bash */

init git                        //cria o repositório
git add <file>                  //adiciona <file> ao estage
git commit -m "<description>"   //comita todas modificações
git branch -M main              //renomeia a branch principal

git remote add origin https://github.com/davi-kauan/projetogit.git          //salvando o projeto no github

git push -u origin main         //primeiro push no projeto

/* outros comandos */

git status
git add .                       //adiciona ao estage todos os arquivos do diretório
git push                        //push que não seja o primeiro