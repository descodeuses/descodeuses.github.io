# descodeuses.github.io

Site web de l'association DesCodeuses

[descodeuses.github.io](https://descodeuses.github.io)

## Développement

Nous utilisons [Jekyll](https://jekyllrb.com/) pour construire ce site, déployé sur [github pages](https://pages.github.com/).

Pour modifier des éléments de ce site, nous pouvons
- le faire directement sur github
- cloner le projet pour le faie localement

En local, [installer jekyll](https://jekyllrb.com/docs/installation/) (nécessite l'installation de Ruby, RubyGems et un outil de compilation).

Puis installer les Gem (librairies) nécessaire pour Jekyll avec la commande (depuis le répertoire du projet):

```bash
bundle install
```

Ensutie, nous pouvons 

### Construire le site avec la commande

```bash
bundle exec jekyll build
```

Le site est généré dans le répertoire `_site` que l'on peut servir en démarrant un serveur web dedans (ou en déplacement le contenu du répertoire).

### Servir le site


```bash
bundle exec jekyll serve
```

Jekyll surveille alors le répertoire des sources et reconstruit le site dès qu'une modification est enregistrée. Il démarre aussi un serveur web qui permet de visualiser le résultat sur l'adresse [localhost:4000](http://localhost:4000) par défaut.
