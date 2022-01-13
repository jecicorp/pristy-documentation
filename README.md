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
