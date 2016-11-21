# Odeva
A simple project in ODEVA

 - On [GitHub](https://github.com/Elisyo/Odeva)

 - On [Travis](https://travis-ci.org/Elisyo/Odeva)

## Site of our teacher
https://github.com/seblucas/odeva/blob/master/odeva.md

# [Markdown docs](https://github.com/tchapi/markdown-cheatsheet) for this README

# How to use [Maven](https://maven.apache.org/guides/getting-started/)

# Some good examples of .yml for travis
 - https://github.com/seblucas/firebase-sensor/blob/master/.travis.yml
 - https://github.com/seblucas/cops/blob/master/.travis.yml

# Autres outils intégrés :
 - Selenium / Appium : Saucelabs, Browserstack, ...
 - Analyse statique de code : Codeclimate, Scrutinizer, ...
 - Couverture de code : Coveralls, ...
 
# Useful commands with Git
 - git rm --cached <fichier> [annule un add]
 - git checkout -f [annule toutes les modifications]
 - git reset --hard [supprime aussi les nouveaux fichiers non suivis]
 - git add -i / -p  [commit que d'une partie d'un fichier]
 - git diff --ignore-all-space [ne prend pas en compte l'indentation]
 - git commit --amen (--no-edit) [permet d'écraset le message de commit uniquement si aucun push n'a été fait]
 - git checkout -b new-feature [faites plusieurs modifications et plusieurs commits]
 - git commit -a -m "Début"
 - git commit -a -m "Modification du précédent"
 - git rebase -i master
 	- pick [conserver un commit]
 	- squash/fixup [fusionner 2 commits]
 	- edit [decouper un commit]
 	- reword [renommage de message]
 	- drop [suppression d'un commit]
 	- exec [execute une commande]
 