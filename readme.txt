Ovo je test repo!

Inicijalizacija Git repositorija lokalno

```bash
# Inicijaliziraj Git u folderu
git init

# Dodaj sve fajlove u staging
git add .

# Napravi prvi commit
git commit -m "Initial commit"
```

Kreiranje Github repositorija na GitHubu pritiskom na "+"

```bash
# Dodaj remote origin (zamijeni sa svojom GitHub URL adresom)
git remote add origin https://github.com/tvoje-korisnicko-ime/ime-repoa.git

# Preimenuj branch u main (ako je potrebno)
git branch -M main

# Push-aj kod na GitHub
git push -u origin main
```