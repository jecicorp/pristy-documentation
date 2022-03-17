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


---

# Pour garder une cohérence voici une parti des shortcodes employés régulièrement

ATTENTION : La mise en page n'est pas rendue dans le READ ME.

## Visuels

### Boutons d'actions

[Essayer Pristy](https://pristy.fr/demo){ .md-button }

### Vidéos

??? example "En vidéo : "
      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/ID/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Nom_du_fichier-->
      <figcaption></figcaption>
      </figure>

??? example "À VENIR > En vidéo : "
    Contenu à venir
  <!---   
      <figure> <video width="100%" controls>
        <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/ID/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <figcaption></figcaption>
      </figure>
-->

### Images :

<figure markdown>![sens](https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/ID/content?attachment=false){width=80%}
<!--Nom_du_fichier-->
<figcaption>Légende</figcaption>
</figure>

## Box informatives (admonitions)

### Liens vers articles connexes

***Voir aussi : [Supprimer](../bandeau-actions/#Supprimer)***

### Box inline (dans le texte)
[Infos complémentaires](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#inline-blocks)

#### Box accessibilité / rôle

!!! check inline end "Accessible avec le rôle"
        - [x] Gestionnaire
        - [ ] Collaborateur / Éditeur
        - [ ] Lecteur

#### Box options

!!! check inline end "Option"
        - [ ] Incluse dans le pack de base
        - [x] À souscrire

#### Liens de bas de page
---
!!! summary inline "En lien avec cette page :"

    - [Fonctionnalité : ajout de Favori](../bandeau-actions/#favori)
    - [Espace de travail : création, gestion](../creation-import/#espace-de-travail)
    - [Obtenir le lien](../bandeau-actions/#obtenir-le-lien)
    - [Supprimer](../bandeau-actions/#Supprimer)

!!! info inline end "Pour aller plus loin :"

    - [Gérer son contenu](../creation-import/creation-import)
    - [Partager](../creation-import/partager/)
    - [Rechercher](../creation-import/rechercher/)


---
[Autres favicon et couleur dispo](https://squidfunk.github.io/mkdocs-material/reference/admonitions/?h=tip#supported-types)


## Autres mise en page disponibles
### Tableau basic

| Method      | Description                          |
| :---------- | :----------------------------------- |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |


### Tableau à onglets

=== "Tableau à onglets"
    Contenu onglet 1

=== "Onglets 2"

      Contenu onglet 2

=== "Onglets 3"

      Contenu onglet 3

=== "Onglets 4"

      Contenu onglet 4
