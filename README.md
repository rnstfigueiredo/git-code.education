# git-code.education

    Curso Git/GitHub - code.education

#### Criar chave publica privada SSH
* ssh-keygen -t rsa -C "Rnst Figueiredo - leoni@SeuDominio.eti.br"

##### Criando o Ambiente
        mkdir git-code.education
        cd git-code.education/
        git init
        git status

##### Criando Arquivo .md
        echo "# git-code.education" >> README.md

##### Adicionando Arquivo
        git status
        git add README.md

##### Commit local
        $ git commit -m "Meu primeiro Commit"
        [master (root-commit) cb3b06f] Meu primeiro Commit
         1 file changed, 15 insertions(+)
         create mode 100644 README.md

##### Adicionando Repositorio Virtual-Remoto
    git remote add origin https://github.com/rnstfigueiredo/git-code.education.git
    git push -u origin master
