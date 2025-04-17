cd Documents
mkdir eval
cd eval
git remote add origin https://github.com/Spectra-afk/eval.git
git init
cd ..
git clone https://github.com/Enblightened/controle.git
git remote add origin https://github.com/Enblightened/controle.git
cd controle
git config user.name "Spectra-afk"
git config user.email "hugodimithr@gmail.com"
git checkout -b hugo
cd Documents
cd controle
git push -u origin master
mkdir hugo 
git checkout -b hugo
git add hugo
git commit -m "mon dossier"
git commit -m "hugo"
git push -u origin hugo
cd Documents
cd controle
cd hugo
nano index.html
mkdir images
cd Documents
cd controle
git checkout hugo
git push -u origin hugo
git checkout hugo
git add hugo
git commit -m "page d'acceuil"
git push -u origin hugo
git pull origin contact
git config pull.rebase false
git pull origin contact
git config pull.rebase true
git pull origin contact
git branch -a
git pull origin contact
git status
git pull origin contact
git rebase --skip
git rebase --abort
git pull origin contact
