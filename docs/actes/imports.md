---
title: Ajouter Actes et Annexes
description: Comment utiliser de l'application métier Pristy Publication des Actes Administratifs
---

<!--
  Copyright 2022 - Jeci SARL - https://jeci.fr

  Permission is granted to copy, distribute and/or modify this document
  under the terms of the GNU Free Documentation License, Version 1.3
  or any later version published by the Free Software Foundation;
  with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
  A copy of the license is included in the section entitled "GNU
  Free Documentation License".

  You should have received a copy of the GNU Free Documentation License
  along with this program.  If not, see http://www.gnu.org/licenses/.
-->

# Page de séance : Ajouter et modifier Actes et Annexes

!!! info inline end "Pré-requis"
      Pour ajouter une séance il faut avoir créé un [espace de type Actes](../bien-debuter/#creer-un-espace-actes), si vous ne savez pas comment faire rendez-vous sur la page [Bien débuter](bien-debuter/#creer-un-espace-actes).

## Créer une séance

Pour créer une séance, cliquer sur l'espace Actes Administratifs (label rose "Actes") :

-   Cliquer sur le bouton vert "Créer une nouvelle séance"
-   Choisir la date où la séance a eu lieu
-   Écrire une description si nécessaire (elle s'affichera sous la date de la séance)
-   Cliquer sur "Valider"

!!! note "Classement"
      Peu importe l'ordre dans lequel vous créez les séances, après rafraîchissement de la page, les séances sont toujours affichées de la plus récente à la plus ancienne.

??? example "En vidéo : Créer une séance"

      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/gVMcNs4ZQ3K9Za564VRNdA/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Creer-une-seance-->
      <figcaption>Créer une séance</figcaption>
      </figure>

!!! warning "Impossible de modifier la date d'une séance"
      Pour éviter les erreurs, nous avons décidé qu'il est impossible de changer la date d'une séance. Aussi, si vous vous trompez, il faudra supprimer la séance et la recréer à la bonne date.

!!! info "Évolution à venir"
      Au 22 juillet, il est impossible dans cette interface de modifier la description d'une séance ou même de la supprimer. Cela sera possible au mois de septembre (au plus tard).

## Contenu de la page d'une séance :

Deux zones de contenus sont présentes dans les pages de séances.

La première zone affiche les actes, la seconde permet d'importer du contenu.

Une fois des actes ajoutés, chaque séance affiche un tableau qui regroupe de gauche à droite :

| Les vignettes | Le nom du document | La nature (type) de fichier avec l'affichage de son code | La taille du fichier | Sa date de Publication | Les boutons d'action |
| :--- | :--- | :---- | :--- | :--- | :--- |
| Première page du document | [Tri](../recherche/#tri) possible de A à Z et de Z à A) | DE (Délibération), AR (Actes réglementaires), [AI (Actes individuels)](../utilisation/#actes-individuels), CC (Contrats conventions et avenants), BF (Documents budgétaires et financiers), AU (Autres) | [Tri](../recherche/#tri) possible du plus petit au plus grand (et inversement) | [Tri](../recherche/#tri) possible du plus ancien au plus récent (et inversement) | En gris "[télécharger](#telecharger-un-acte)", en vert "[modifier](#modifier-un-acte)", en rouge "[supprimer](#supprimer-un-acte)" |

En haut à droite du tableau se trouve un barre de [filtre](../recherche/#Filtre), elle permet de chercher les termes des noms des documents.  

## Importer Actes et Annexes

### Ajouter des Actes

Pour ajouter des actes, cliquer sur la séance à propos.

Vous avez sous le bloc intitulé "Actes de la Séance du [date de la séance]" un bloc pour ajouter du contenu :

-   Cliquer sur sélectionner des fichiers
-   OU Glisser-Déposer vos fichiers dans la boite de dépôt
-   Choisir la nature des documents :
    -   "Délibération" (DE)
    -   "Actes réglementaires" (AR)
    -   ["Actes individuels" (AI)](../utilisation/#actes-individuels)
    -   "Contrats conventions et avenants" (CC)
    -   "Documents budgétaires et financiers" (BF)
    -   "Autres" (AU)
-   Vérifier vos fichiers (ils sont publiés à l'envoi)
    -   Vous pouvez cliquer sur la croix pour supprimer un fichier sélectionné par erreur.
-   Quand vous êtes sûr de votre contenu, cliquer sur "Envoyer"

??? example "En vidéo : Ajouter des délibérations "

      <figure> <video width="100%" controls>
        <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/0tPdyvs7TE6qB4LYKAM0Uw/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Ajouts-deliberations-->
      <figcaption>Ajouter des délibérations</figcaption>
      </figure>

!!! tip "Type d'acte"
      Vous pouvez aussi importer du contenu sans choisir de type.
      Pour gagner du temps, nous vous recommandons de {==typer à l'import==}. Cependant, si vous le souhaitez ou si vous faites une erreur, vous pouvez le faire dans un second temps voir "[modifier l'acte](#modifier-un-acte)".

### Ajouter des annexes

Pour chaque acte importé, vous pouvez accoler une ou plusieurs annexe(s) :

-   Cliquer sur l'icône "Modifier", un pop-up s'ouvre
-   Ajouter un ou plusieurs annexe(s) dans la box d'import
-   Cliquer sur "Envoyer"

Vos annexes sont ajoutées, si vous cliquez dessus, il s'ouvre à la suite de l'acte annexé. Ainsi, chaque document est contextualisé.

??? example "En vidéo : Ajouter une annexe"

      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/AHymSFVJQEWADZ6-G2H6FQ/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Ajouter-une-annexe-->
      <figcaption>Ajouter une annexe à une délibération</figcaption>
      </figure>

!!! missing "Supprimer une annexe"
      Pour supprimer une annexe, cliquer sur la croix à côté de son nom. ^^Attention^^ le document ne perdra pas uniquement son lien il sera également supprimé de la plateforme.

## Modification après l'import

### Modifier un acte

Vous pouvez également modifier l'acte :

-   Cliquer sur l'icône "Modifier", un pop-up s'ouvre, vous pouvez :
    + Ajouter ou modifier un titre
    + Modifier le nom du fichier ; ^^attention^^, pensez à conserver l'extension (.pdf)
    + Ajouter une description
    + Changer la nature d'un acte
    + Ajouter le code acte
    + Ajouter ou supprimer une annexe (voir "[Ajouter des annexes](#ajouter-des-annexes)")

??? example "En vidéo : Modifier un acte"
    <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/DLVIFOEWSjq18l5KvTKHxw/content?attachment=false" type="video/webm">
    Votre navigateur ne supporte pas le tag vidéo.
    </video>
    <!--Modifier-un-acte-->

    <figcaption>Modifier un acte : ajouter un titre, une description, changer le type, ajouter un code acte</figcaption>
    </figure>

### Supprimer un acte

Pour supprimer un acte, cliquer sur le logo "poubelle" rouge.

Il est aujourd'hui impossible de supprimer plusieurs actes en même temps.

??? example "En vidéo : Supprimer un acte"

      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/5basva-eQUG7h-ekz3EN9A/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Supprimer-un-acte-->
      <figcaption>Supprimer un acte</figcaption>
      </figure>

### Télécharger un acte

Pour télécharger un acte, cliquez sur le logo "télécharger" en gris à la droite de son nom.
S'il contient une annexe, il nous est alors proposé de télécharger l'acte et/ou ses annexes.

En mode "[consultation](#consulter-un-acte)" cliquez sur le logo "télécharger" jaune à droite de la zone de zoom.

??? example "En vidéo : Télécharger les actes"
      <figure> <video width="100%" controls>
        <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/pyEKI9x7RjGWlnEtAVMkuw/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Télécharger-contenu-->

      <figcaption>Télécharger les actes administratifs et leurs annexes</figcaption>
      </figure>

### Consulter un acte

Pour consulter un acte, cliquez sur le nom de fichier.
S'ouvre alors une fenêtre de visualisation, qui peut être ajustée avec les boutons de zooms "+" et "-". Si l'acte contient des annexes, ils s'afficheront sous ce dernier.

On peut aussi avoir sur la page d'une séance des aperçus du document en cliquant sur sa vignette, s'affichera alors la première page du document.

??? example "En vidéo : Consulter un acte"

      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/4cBrmKgGQWC0qsMDcYj4vg/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Consulter-->
      <figcaption>Consulter un acte : et fonction de (dé)zoom.</figcaption>
      </figure>

---

!!! summary inline "En lien avec cette page :"

    - [Bien débuter : accès et création](../bien-debuter/)
    - [Page de publication / publicité](../publication/)
    - [Recherche, tri et filtre](../recherche/)
