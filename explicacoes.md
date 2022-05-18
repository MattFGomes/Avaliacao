git init - inicializa o repositorio
git remote add origin "link do repositório" - conecta nosso repositorio local ao rep do github
git add arquivo.extencao adiciona o arquivo a staging area
git add . adiciona todas as alterações de docs em staggind area
git commit -m "mensagem" - comita a acao de add e manda uma mensagem
git checkout -b "nome" - cria uma nova branch e ja entra nela com checkout
git checkout main/nomeDaBranch - sai para a branch main/branch de nome dado
git push origin nomeDaBranch - empurra as mudancas para a branch marcada
    precisa estar dentro da propria branch
git merge nomeBranch - a partir da branch main, se puxa o merge com a branch alterada
git push origin main - empurra tudo, inclusive o que ta merge pra main do github