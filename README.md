# oficina-git
learning more about github

comandos github

configurando a ssh key
colocando ssh-key
-> ssh-keygen

vendo a chave publica
-> cat ~/.ssh/id_rsa.pub

configurando o git para uso
-> git config --global user.name "guisantosalves"
-> git config --global user.email "workguisantos@gmail.com"

configurando um novo repositório
-> git init

-> git status

-> git add meu_arquivo.txt

-> git commit meuarquivo.txt -m "minha mensagem de commit"

-> git push -u origin main

-> git rm meu_arquivo.txt -> remove arquivo

-> git log

-> git pull -> baixa as alterações das coisas novas feitas

-> git restore --source < id do commit desejado para restaurar > .

-------- criando branch ---------

git branch -> visualizando branch

git switch -c 33-criando-uma-nova-funcao

------- observações -------
comandos linux:
mkdir -> cria diretório no linux
rm -rf -> excluir arquivo
cat -> lê um arquivo de texto no linux
nano -> executa e cria arquivos
mv [name] [newName] -> muda nome do arqui
