# Pristy User Documentation

## Démarrage

```
mkdocs serve
```
Accès à la documentation sur http://127.0.0.1:8000/

ou

```
mkdocs serve --dirtyreload
```
Pour un build plus rapide, mais avec risque de liens non fonctionnels.

### Sur Docker

```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```
Accès via : http://localhost:8000/

## navigation

Dans mkdocs.yml sous la section nav.
https://www.mkdocs.org/user-guide/writing-your-docs/#configure-pages-and-navigation


# Mise à jour de contenu :
Penser à mettre à jour le menu dans
'''~/mkdocs.yalm/#nav'''
Et à mettre à jout le plan du site
'''~/docs/plan-du-site/'''

#Notes

- le logo soit être placé dans le dossier 'assets' qui doit être dans le dossier 'docs'
- le favicon doit se trouvé dans le dossier 'images' du dossier 'assets'
