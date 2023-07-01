Olá, esse projeto ensina você a usar o git

/* criando um repositório no git bash */

init git                        //cria o repositório local
git add <file>                  //adiciona <file> ao estage  
git commit -m "<description>"   //comita todas modificações  
git branch -M main              //renomeia a branch principal  

git remote add origin https://github.com/davi-kauan/projetogit.git    //linkando o repositorio local e remoto no github

git push -u origin main    //primeiro push no projeto

/* outros comandos */

git status              //verifica se há mudanças e commits a serem feitos  
git add .               //adiciona ao estage todos os arquivos do diretório    
git push                //push que não seja o primeiro  
git checkout <file>     //remove as mudanças em <file>  
git branch              //lista todas branch  
git checkout <branch>   //muda para branch <branch>  
git pull                //recebe as atualizações do repositorio remoto  
git fetch               //recebe branches remotos que não estão mapeados  
git merge <branch>      //recebe de as atualizações <branch> na branch atual  
