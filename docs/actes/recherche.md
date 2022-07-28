---
title: Recherche sur les Actes
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

# Recherche, Filtre et Tri

Pour les utilisateurs connectés, une page de recherche dédiée aux actes administratifs existe :

dans le menu cliquer sur " :octicons-search-16: Tous les actes "

 Les mêmes champs de recherche, tri et filtre sont disponibles sur la page de [publication](../publication/).

## Tri


`Tri` : Classe des données dans un ordre croissant ou décroissant.

Sur la liste des fichiers, en cliquant sur l'entête, on active les tris.

=== "En cliquant ^^une^^ fois sur :"
      - "Nom" on classe les documents par ordre alphabétique chiffre puis "a" à "z".
      - "Séance" on classe les documents par date de séance : du plus vieux au plus récent.
      - "Publié le" on classe par date de publication les actes : du plus vieux au plus récent.
      - "Type" on classe les documents par ordre alphabétique de "a" à "z".
      - "Nature" on classe les documents par ordre alphabétique de "a" à "z".
      - "Taille" on classe la taille du document en KB : du moins volumineux au plus volumineux.
=== "En cliquant ^^deux^^ fois sur :"
      - "Nom" on classe les document par ordre alphabétique inversé de "z" à "a" puis les chiffres.
      - "Séance" on classe les documents par date de séance : du plus récent au plus vieux.
      - "Publié le" on classe par date la publication des actes : du plus récent au plus vieux.
      - "Type" on classe les documents par ordre alphabétique inversé de "z" à "a".
      - "Nature" on classe les documents par ordre alphabétique inversé de "z" à "a".
      - "Taille" on classe la taille du document en KB : du plus volumineux au moins volumineux.


{++Les tris ne sont pas cumulables.++}

## Filtre

`Filtre` : Un filtre examine les données et n'extrait que les informations correspondant à la requête.

Il s'applique ici sur le nom du fichier (ID) et sur le type,  {++les deux filtres sont cumulables, les filtres sont cumulables avec le tri++}.

### Nom de fichiers (ID)

Sur le nom de fichier, vous pouvez trier en tapant n'importe quelle lettre, mot ou phrase dans la barre de filtre.

La casse de phrase n'est pas prise en compte, un seul terme peut-être filtré.

### Type

On peut sélectionner le type de document que l'on veut afficher :

- Cliquer sur la case "Tous"
- Sélectionner le type à afficher

## Recherche

`Recherche` : Permet de trouver un terme présent dans le titre, corps, nom du document, etc.

Dans la barre intitulée "recherche" taper le mot rechercher.

La casse de phrase n'est pas prise en compte, un seul terme peut être recherché (ou une suite de terme présente dans un document).

{++La recherche est cumulable avec les filtres et le tri.++}

??? example "En vidéo : Recherches et Filtres"
      <figure> <video width="100%" controls>
      <source src="https://jeci.pristy.net/alfresco/api/-default-/public/alfresco/versions/1/shared-links/UwnY19ZuTg2Aah1g6uEfgg/content?attachment=false" type="video/webm">
      Votre navigateur ne supporte pas le tag vidéo.
      </video>
      <!--Recherches-et-filtres-->
      <figcaption>Recherches et Filtres</figcaption>
      </figure>

---
!!! summary inline "En lien avec cette page :"

    - [Page de publication / publicité](../publication/)
    - [Importer et modifier des actes](../imports/)
