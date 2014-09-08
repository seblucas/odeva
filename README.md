# Quoi ?

Cours en français pour les Master e-Services de l'université de Lille 1

# Comment générer la page web

Installer [mdpress](https://github.com/egonSchiele/mdpress)

```bash
rm -Rf odeva
rm -Rf odeva-classic
cp odeva.md odeva-classic.md
mdpress -s impress -i images odeva.md
mdpress -i images odeva-classic.md
cp odeva-style.css odeva/css/style.css
```

# Sources

 * [Wikipedia](http://fr.wikipedia.org/wiki/Wikip%C3%A9dia:Accueil_principal)
 * [A Visual Guide to Version Control](http://betterexplained.com/articles/a-visual-guide-to-version-control/)

# Licence

[CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)