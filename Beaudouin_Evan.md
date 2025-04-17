Commandes effectuer sur le terminal

```bash
cd Documents
mkdir controle
cd controle
git init
ls -a
git clone https://github.com/Emblightened/controle
git config user.name "EvanBeaudouin"
git config user.email "evanbeaudouin92@gmail.com"
git branch evan
git checkout evan
nano destination.html
git add destination.html
git commit -m "version 1 destination"
git push -u origin evan
git add destination.html
git commit -m "version 2 destination"
git push -u origin evan
git checkout -b contact
git pull origin James
git checkout main
mkdir css
mkdir pages
git checkout contact
git add contacts.html
git commit -m "version contact evan"
git push -u origin contact
git checkout -b index
git pull origin hugo
git checkout -b newdestination
git pull origin James
git checkout -b css
git checkout main
git merge index
git checkout css
git pull origin htmlfinal
git add css
git commit -m "css version 1"
git push -u origin css
git checkout -b historiquecommande
git add Beaudouin_Evan.md
git commit -m "envoie du fichier md"
git push -u origin historiquecommande
```
