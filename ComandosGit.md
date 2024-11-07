# Comandos de Git

- git status -->
- git add .
- git commit -m "Add index.html and Css"
- git push
- git pull
- git clone https://github.com/alce65/git.indra.course.git git.course
- code .

- git log --oneline
        4bbe7fc (HEAD -> main, origin/main) Add index.html and Css
        e1e30ec Colocacion correcta de Markdown
        dc6bd92 Update  commit
        27d5808 Initial commit
- git commit --amend --> deshace el ultimo commit y hace de nuevo el comit

- git checkout -b feature/contacts cambia de rama y si no exiite la crea

->git merge feature/contacts

- git restore --stage file
- git restore --> restaura el fichero
- git checkout file --> trae el fichero del repo
- git remote add origin https://github.com/OscarJavierDosSantos/git.sample.git

- git branch -d <nombre_de_rama> borra la rama local
- git branch --> Indica las ramas que tienes creadas 

        C:\Users\Mañanas\IFCD0210\git.sample>git branch
        feature/contacts
        * main

- git branch all
        C:\Users\Mañanas\IFCD0210\git.sample>git branch all

        C:\Users\Mañanas\IFCD0210\git.sample>git branch       
        all
        feature/contacts
        * main

- git branch -M main
- git push -u origin main

- git remote
- git remote -v
