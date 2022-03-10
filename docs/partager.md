---
title: Partager
description:
---

# Partager
Les fonctions de partage peuvent paraître complexes de prime abord : pas de panique, après avoir lu cette section tout sera, normalement, plus clair.

D'abord, il faut distinguer le partage en interne et le partage en externe.

### En externe

Il suffit d'utiliser au choix la fonction [Obtenir le lien](../bandeau-actions/#obtenir-le-lien) ou la fonction [Envoyer par mail](../bandeau-actions/#envoyer-un-mail) cela générera un lien consultable par toute personne à qui vous le partager.
Cela ne fonctionne que pour des documents et ne permet que de la lecture seul (pas de modification).

### En interne

C'est-à-dire aux personnes ayant un compte sur Pristy.

Pour accéder à la fonction il faut :

- Sélectionner l'espace de travail, le dossier ou le document
- Cliquer sur les 3 points pour accéder à "Plus d'action"
- Cliquer sur "Partager" sur le menu déroulant

Vous pouvez aussi faire un clic droit sur l'espace de travail, le dossier ou le document puis cliquer sur "Partage".

Une fenêtre s'ouvre :

- Saisir le mail de la personne avec qui l'on veut partager le contenu
- Cliquer sur son nom
- Cliquer sur ajouter
- Dans la section du dessous choisir le [rôle](#role) à attribuer.




#### À savoir avant de partager

On peut partager tout ce qui se trouve dans son compte : les espaces de travail, les dossiers, les documents (quel que soit leurs formats).

Pour partager il faut avoir le [rôle](#role) de gestionnaire ou de collaborateur sur l'espace de travail, le dossier, le document que l'on souhaite partager. Cela veut dire qu'un lecteur peut seulement consulter un contenu.

Le partage des espaces de travail et des dossiers est automatiquement hérité à son contenu, c'est-à-dire que si un espace de travail est partagé à un utilisateur tout le contenu de l'espace sera accessible à l'utilisateur, en suivant les mêmes autorisations. Il en va de même pour un dossier. Cet héritage peut être contrôlé voir [Héritage de rôle](#heritage-de-role).

## Rôle
Il existe 3 rôles : Gestionnaire, Collaborateur/Éditeur et Lecteur – chacun de ses rôle s'attribue au moment du partage. Les rôles définissent les autorisations de l'utilisateur à consulter, modifier ou déplacer un dossier ou un document.


**Un gestionnaire** à tous les pouvoirs sur son contenu, il peut le créer, le modifier, le déplacer, le partager et l'organiser ou le réorganiser à sa guise.

Le créateur d'un espace, d'un document ou d'un fichier en est automatiquement gestionnaire. S'il s'agit d'une espace ou d'un document, il est également gestionnaire de tout le contenu ajouté (sauf si le comportement a été modifié manuellement dans l'[Héritage de rôle](#heritage-de-role)).

**Un collaborateur / éditeur** peut tout consulter et créer du contenu, mais ne peut pas supprimer ou changer l'emplacement du contenu qu'il n'a pas créée. Il peut consulter les partages attribués et changer les siens pour des droits plus restrictifs.
Par extension au paragraphe précédent, le collaborateur d'un espace de travail qui a créée un dossier est donc gestionnaire de ce dossier et profite des droits de gestionnaire sur ce dossier.

**Un lecteur** peut uniquement consulter le contenu. Il ne peut pas partager, mais peut toujours le télécharger. Il peut générer un lien qu'il peut partager.

### Héritage de rôle



### Action limitée par le rôle attribué à l'espace de travail.
#### Gestionnaire – actions
- Espace de travail
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Partager](../partager/)
    - [**Quitter l'espace de travail**](../creation-import/#quitter-un-espace-de-travail/)
    - [Supprimer](../bandeau-actions/#supprimer)
    - [Favori](../bandeau-actions/#favori)
- Dossier :
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Partager](../partager/)
    - [Télécharger](../bandeau-actions/#telecharger)
    - [**Modifier**](../bandeau-actions/#modifier-du-contenu)
    - [Favori](../bandeau-actions/#favori)
    - [Déplacer](../bandeau-actions/#deplacer-du-contenu)
    - [Copier](../bandeau-actions/#copier)
    - [Supprimer](../bandeau-actions/#supprimer)
- Fichier :
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Partager](../partager/)
    - [**Obtenir un lien**](../bandeau-actions/#obtenir-le-lien)
    - [Télécharger](../bandeau-actions/#telecharger)
    - [**Envoyer un mail**](../bandeau-actions/#envoyer-un-mail)
    - [**Afficher**](../bandeau-actions/#afficher)
    - [**Modifier avec Collabora Online**](../bandeau-actions/#modifier-avec-Collabora-Online) (uniquement pour les formats modifiables)
    - [Éditer hors-ligne](../bandeau-actions/#editer-hors-ligne)
    - [**Importer une nouvelle version**](../bandeau-actions/#gestion-de-version)
    - [Favori](../bandeau-actions/#favori)
    - [Déplacer](../bandeau-actions/#deplacer-du-contenu)
    - [Copier](../bandeau-actions/#copier)
    - [Supprimer](../bandeau-actions/#supprimer)
    - [**Gérer les versions**](../bandeau-actions/#gestion-de-version)

IMAGE :
Clic_droit_Dossier_Gestionnaire
Clic_droit_Fichier_modifiable_Gestionnaire
Clic_droit_Fichier_non_modifiable_Gestionnaire

#### Collaborateur - actions
- Espace de travail
    - [**Quitter l'espace de travail**](../creation-import/#quitter-un-espace-de-travail/)
    - [Supprimer](../bandeau-actions/#supprimer)
    - [Favori](../bandeau-actions/#favori)
- Dossier (non crée par l'utilisateur):
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Partager](../partager/)
    - [Télécharger](../bandeau-actions/#telecharger)
    - [**Modifier**](../bandeau-actions/#modifier-du-contenu)
    - [Favori](../bandeau-actions/#favori)
    - [Copier](../bandeau-actions/#copier)
- Fichier (non crée par l'utilisateur) :
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Partager](../partager/)
    - [**Obtenir un lien**](../bandeau-actions/#obtenir-le-lien)
    - [Télécharger](../bandeau-actions/#telecharger)
    - [**Envoyer un mail**](../bandeau-actions/#envoyer-un-mail)
    - [**Afficher**](../bandeau-actions/#afficher)
    - [**Modifier avec Collabora Online**](../bandeau-actions/#modifier-avec-Collabora-Online) (uniquement pour les formats modifiables)
    - [**Importer une nouvelle version**](../bandeau-actions/#gestion-de-version)  
    - [Favori](../bandeau-actions/#favori)
    - [Copier](../bandeau-actions/#copier)
    - [**Gérer les versions**](../bandeau-actions/#gestion-de-version) (suppression impossible)

IMAGE :
Clic_droit_Dossier_Collaborateur :a:
Clic_droit_Fichier_modifiable_Collaborateur :a:
Clic_droit_Fichier_non_modifiable_Collaborateur :a:

#### Lecteur - actions
- Espace de travail
    - [**Quitter l'espace de travail**](../creation-import/#quitter-un-espace-de-travail/)
    - [Supprimer](../bandeau-actions/#supprimer)
    - [Favori](../bandeau-actions/#favori)
- Dossier (non crée par l'utilisateur):
    - [Informations (détails)](../bandeau-actions/#volet-de-detail)
    - [Télécharger](../bandeau-actions/#telecharger)
    - [Favori](../bandeau-actions/#favori)
    - [Copier](../bandeau-actions/#copier)
- Fichier (non crée par l'utilisateur) :
- [Informations (détails)](../bandeau-actions/#volet-de-detail)
- [**Obtenir un lien**](../bandeau-actions/#obtenir-le-lien)
- [Télécharger](../bandeau-actions/#telecharger)
- [**Envoyer un mail**](../bandeau-actions/#envoyer-un-mail)
- [**Afficher**](../bandeau-actions/#afficher)
- [Favori](../bandeau-actions/#favori)
- [Copier](../bandeau-actions/#copier)
- [**Gérer les versions**](../bandeau-actions/#gestion-de-version)(seul la fonction de téléchargement est disponible)

IMAGE :
Clic_droit_Dossier_Lecteur :a:
Clic_droit_Fichier_modifiable_Lecteur :a:
Clic_droit_Fichier_non_modifiable_Lecteur :a:

### Exemples d'utilisation :


Au sein d'un espace de travail, les accès peuvent être  augmentés.
Par exemple :

- Un espace de travail n'est partagé avec personne.
- On peut partager un dossier ou un fichier qui le contient.
- Il sera accessible via l'url partagé avec lui ou en cherchant le nom de ce dossier ou fichier.
- S'il s'agit d'un dossier, tout son contenu aura les mêmes droits que ce dossier.
- Nous aurons accès au contenu de l'espace de travail si ce dernier et public. Pour y avoir accès depuis ces espaces de travail, il faudra en demander l'accès.
- Conseil : mettez le contenu de ce dossier qui vous intéressé en favoris !

Ou

Dans une entreprise composée de 4 employés, 2 cadres et 2 non cadres. 2 employés cadres : Marie Doe et Kate Tie et 2 employés non cadre : John Foster et Lucie Lix

- Le gérant a partagé un espace de travail avec tous les employés en lecture seul. L'espace "Ressource Humaines"
- Dans cet espace se trouve un dossier d'informations pour les salariés "Informations générales", et un dossier par employé.
- Il a retiré les droits hérités des employés sur leurs dossiers personnels. Et ajouté les droits d'éditeur à chaque dossier, employé par employé. (Dans ces dossiers on retrouve le contrat de travail de l'employé, ses bulletins de salaires, l'employé peut lui ajouter les documents comme les justificatifs de frais, rapport de mission, suivi journalier, etc.)
- Sur le dossier "Informations générales" il n'a rien changé, mais ces derniers contiennent des informations sur les mutuelles. Il a donc retiré les droits hérités des employés sur les dossiers mutuelles et ajoutées aux cadres le partage en lecture seul du dossier "Mutuelle Cadre", il a fait de même pour les non-cadre et le dossier "Mutuelle non-cadre". Pour autant le dossier sur la médecine du travail et toutes informations futurs pourront être ajoutés dans ce dossier pour tous les employés.
- L'entreprise débute, mais après quelque temps, le gérant embauche un salarié en charge des ressources humaines, il lui partage donc ce dossier et créer le dossier du nouveau salarié. Puis lui confère aussi les droits d'accès de tous les dossiers des employés pour qu'il puisse reprendre le suivi. Le nouveau responsable RH a alors tout l'historique d'information et le gérant peut toujours suivre le dossier si besoin.
- L'entreprise grandie encore et une dizaine d'employés s'ajoute alors le gérant demande à son administrateur de créer un groupe "cadre" et un groupe "non cadre" pour simplifier le partage des dossiers respectant cette thématique.



## Visibilité de l'espace de travail
La visibilité d'un espace influe sur sa capacité à sortir dans les résultats de recherches.

L'espace **public** non partagé et son contenu est recherchable par tous les utilisateurs. N'importe quels utilisateurs peut intégrer l'espace de travail.
Si du contenu de l'espace vous est partagé, la recherche vous indique son emplacement.

VIDEO
IMAGE

L'espace **modéré** non partagé est recherchable par tous les utilisateurs. N'importe quels utilisateurs peut demander au(x) gestionnaire(s) à intégrer l'espace de travail (depuis l'application).
Si du contenu de l'espace vous est partagé, la recherche ne vous indique pas son emplacement.

VIDEO
IMAGE

L'espace **privé** non partagé n'est pas recherchable. Aucun utilisateur ne peut demander au(x) gestionnaire(s) à intégrer l'espace de travail (depuis l'application) ou connaître l'existence du dossier.
Si du contenu de l'espace vous est partagé, la recherche ne vous indique pas son emplacement.

VIDEO
IMAGE

## Groupe
