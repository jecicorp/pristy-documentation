# Partager
Les fonctions de partage peuvent parraître complexes de prime abord : pas de panique, après avoir lu cette section tout sera, normalement,plus clair.

D'abord, il faut distinguer le partage en interne et le partage en externe.

### En externe

Il suffit d'utiliser au choix la fonction [Obtenir le lien](#Obtenir-le-lien) ou la fonction [Envoyer par mail](#Envoyer-un-mail) cela générera un lien consultable par toute personne à qui vous le partager.
Cela ne fonctionne que pour des documents et ne permet que de la lecture seul (pas de modification).

### En interne

C'est à dire au personne ayant un compte sur Pristy.

Pour accéder à la fonction il faut :
- Sélectionner l'espace de travail, le dossier ou le document
- Cliquer sur les 3 points pour accéder à "Plus d'action"
- Cliquer sur "Partager" sur le menu déroulant

Vous pouvez aussi faire un clic droit sur l'espace de travail, le dossier ou le document puis cliquer sur "Partage".

Une fenètre s'ouvre :
- Saisir le mail de la personne avec qui on veut partager le contenu
- Cliquer sur son nom
- Cliquer sur ajouter
- Dans la section du dessous choisir le [rôle](#Rôle) à attribuer.




#### À savoir avant de partager

On peut partager tout ce qui se trouve dans son compte : les espaces de travail, les dossiers, les documents (quelque soit leurs formats).

Pour partager il faut avoir le [rôle](#Rôle) de gestionnaire ou de collaborateur sur l'espaces de travail, le dossier, le document que l'on souhaite partager. Cela veut dire qu'un lecteur peut seulement consulter un contenu.

Le partage des espaces de travail et des dossiers est automatiquement hérité à son contenu, c'est à dire que si un espace de travail est partagé à un utilisateur tout le contenu de l'espace sera accessible à l'utilisateur, en suivant les mêmes autorisations. Il en va de même pour un dossier. Cet héritage peut être controlé voir [Héritage de rôle](#Héritage-de-rôle).

## Rôle
Il existe 3 rôles : Gestionnaire, Collaborateur/Éditeur et Lecteur - chacun de ses rôle s'attribue au moment du partage. Les rôles définissent les autorisations de l'utilisateur à consulter, modifier ou déplacer un dossier ou un document.


**Un gestionnaire** à tous les pouvoirs sur son contenu, il peut le créer, le modifier, le déplacer, le partager et l'organiser ou le réorganiser à sa guise.

Le créateur d'un espace, d'un document ou d'un fichier en est automatiquement gestionnaire. S'il s'agit d'une espace ou d'un document il est également gestionnaire de tous le contenu ajouté (sauf si le comportement à été modifié manuellement dans l'[Héritage de rôle](#Héritage-de-rôle)).

**Un collaborateur / éditeur** peux tout consulter et créer du contenu mais ne peux pas supprimer ou changer l'emplacement du contenu qu'il n'a pas créer. Il peut consulter les partages attribués et changer les siens pour des droits plus restrictifs.
Par extension au paragraphe précédent, le collaborateur d'un espace de travail qui a créer un dossier est donc gestionnaire de ce dossier et profite des droits de gestionnaire sur ce dossier.

**Un lecteur** peux uniquement consulter le contenu. Il ne peut pas partager mais peux toujours le téléchargé. Il peut généré un lien qu'il peut partager.

### Héritage de rôle



### Action limité par le rôle attribué à l'espace de travail.
#### Gestionnaire - actions
- Espace de travail
    - [Informations (détails)](#Volet-de-détail)
    - [Partager](#5-Partager)
    - [**Quitter l'espace de travail**](#Quitter-un-espace-de-travail)
    - [Supprimer](#Supprimer-un-espace-de-travail)
    - [Favori](#Favori0)
- Dossier :
    - [Informations (détails)](#Volet-de-détail)
    - [Partager](#5-Partager)
    - [Télécharger](#Télécharger)
    - [**Modifier**](#Modifier-du-contenu)
    - [Favori](#Favori0)
    - [Déplacer](#Déplacer-du-contenu)
    - [Copier](#Copier)
    - [Supprimer](#Supprimer)
- Fichier :
    - [Informations (détails)](#Volet-de-détail)
    - [Partager](#5-Partager)
    - [**Obtenir un lien**](#Obtenir-le-lien)
    - [Télécharger](#Télecharger)
    - [**Envoyer un mail**](#Envoyer-un-mail)
    - [**Afficher**](#Afficher)
    - [**Modifier avec Collabora Online**](#Modifier-avec-Collabora-Online) (uniquement pour les formats modifiables)
    - Editer hors-ligne
    - [**Importer une nouvelle version**](#Gestion-de-version)
    - [Favori](#Favori0)
    - [Déplacer](#Déplacer-du-contenu)
    - [Copier](#Copier)
    - [Supprimer](#Supprimer)
    - [**Gérer les versions**](#Gestion-de-version)

IMAGE :
Clic_droit_Dossier_Gestionnaire
Clic_droit_Fichier_modifiable_Gestionnaire
Clic_droit_Fichier_non_modifiable_Gestionnaire

#### Collaborateur - actions
- Espace de travail
    - [**Quitter l'espace de travail**](#Quitter-un-espace-de-travail)
    - [Supprimer](#Supprimer-un-espace-de-travail)
    - [Favori](#Favori0)
- Dossier (non crée par l'utilisateur):
    - [Informations (détails)](#Volet-de-détail)
    - [Partager](#5-Partager)
    - [Télécharger](#Télecharger)
    - [**Modifier**](#Modifier-du-contenu)
    - [Favori](#Favori0)
    - [Copier](#Copier)
- Fichier (non crée par l'utilisateur) :
    - [Informations (détails)](#Volet-de-détail)
    - [Partager](#5-Partager)
    - [**Obtenir un lien**](#Obtenir-le-lien)
    - [Télécharger](#Télecharger)
    - [**Envoyer un mail**](#Envoyer-un-mail)
    - [**Afficher**](#Afficher)
    - [**Modifier avec Collabora Online**](#Modifier-avec-Collabora-Online) (uniquement pour les formats modifiables)
    - Editer hors-ligne
    - [**Importer une nouvelle version**](#Gestion-de-version)
    - [Favori](#Favori0)
    - [Copier](#Copier)
    - [**Gérer les versions**](#Gestion-de-version) (suppression impossible)

IMAGE :
Clic_droit_Dossier_Collaborateur :a:
Clic_droit_Fichier_modifiable_Collaborateur :a:
Clic_droit_Fichier_non_modifiable_Collaborateur :a:

#### Lecteur - actions
- Espace de travail
    - [**Quitter l'espace de travail**](#Quitter-un-espace-de-travail)
    - [Supprimer](#Supprimer-un-espace-de-travail)
    - [Favori](#Favori0)
- Dossier (non crée par l'utilisateur):
    - [Informations (détails)](#Volet-de-détail)
    - [Télécharger](#Télecharger)
    - [Favori](#Favori0)
    - [Copier](#Copier)
- Fichier (non crée par l'utilisateur) :
    - [Informations (détails)](#Volet-de-détail)
    - [**Obtenir un lien**](#Obtenir-le-lien)
    - [Télécharger](#Télecharger)
    - [**Envoyer un mail**](#Envoyer-un-mail)
    - [**Afficher**](#Afficher)
    - [Favori](#Favori0)
    - [Copier](#Copier)
    - [**Gérer les versions**](#Gestion-de-version) (seul la fonction de téléchargement est dispo)

IMAGE :
Clic_droit_Dossier_Lecteur :a:
Clic_droit_Fichier_modifiable_Lecteur :a:
Clic_droit_Fichier_non_modifiable_Lecteur :a:

### Exemples d'utilisation :


Au sein d'un espace de travail, les accès peuvent être  augmentés.
Par exemple :

- Un espace de travail n'est partagé avec personne.
- On peut partager un dossier ou un fichier qui le contient.
- Il sera accessible via l'url partagé avec lui ou en cherchant le nom de se dossier ou fichier.
- S'il s'agit d'un dossier Tous son contenu aura les mêmes droits que ce dossier.
- Nous aurons accès au contenu de l'espace de travail si ce dernier et public. Pour y avoir accès depuis ces espaces de travail, il faudra en demander l'accès.
- Conseil : mettez le contenu de ce dossier qui vous interresse en favoris !

Ou

Dans une entreprise composé de 4 employés, 2 cadres et 2 non cadres. 2 employés cadres : Marie Doe et Kate Tie et 2 employés non cadre : John Foster et Lucie Lix

- Le gérant a partagé un espace de travail avec tous les employés en lecture seul. L'espace "Ressources Humaines"
- Dans cet espace se trouve un dossier d'informations pour les salariés "Informations générales", et un dossier par employé.
- Il a retiré les droits hérités des employés sur leurs dossiers personnels. Et ajouté les droits d'éditeur à chaque dossier, employé par employé. (Dans ces dossiers on retrouve le contrat de travail de l'employé, ses bulletins de salaires, l'employé peut lui ajouter les documents comme les justificatifs de frais, rapport de mission, suivi journalier, etc.)
- Sur le dossier "Informations générales" il n'a rien changé, mais ces derniers contiennent des informations sur les mutuelles. Il a donc retiré les droits hérités des employés sur les dossiers mutuelles et ajouté aux cadres le partage en lecture seul du dossier "Mutuelle Cadre", il a fait de même pour les non cadre et le dossier "Mutuelle non cadre". Pour autant le dossier sur la médecine du travail et toute informations futurs pourront être ajouté dans ce dossier pour tous les employés.
- L'entreprise débute, mais après quelques temps, le gérant embauche un salarié en charge des ressources humaines, il lui partage donc ce dossier et créer le dossier du nouveau salarié. Puis lui confère aussi les droits d'accès de tous les dossiers des employés pour qu'il puisse reprendre le suivi. Le nouveau responsable RH a alors tous l'historique d'information et le gérant peux toujours suivre le dossier si besoin.
- L'entreprise grandis encore et une dizaine d'employé s'ajoute alors le gérant demande à son administrateur de créer un groupe "cadre" et un groupe "non cadre" pour simplifier le partage des dossiers respectant cette thématique.



## Visibilité de l'espace de travail
La visibilité d'un espace influe sur sa capacité à sortir dans les résultats de recherches.

L'espace **public** non partagé et son contenu sont recherchables par tous les utilisateurs. N'importe quels utilisateurs peut intégrer l'espace de travail.
Si du contenu de l'espace vous est partagé, la recherche vous indique sont emplacement.

VIDEO
IMAGE

L'espace **modéré** non partagé est recherchable par tous les utilisateurs. N'importe quels utilisateurs peut demander au(x) gestionnaire(s) à intégrer l'espace de travail (depuis l'application).
Si du contenu de l'espace vous est partagé, la recherche ne vous indique pas son emplacement.

VIDEO
IMAGE

L'espace **privé** non partagé n'est pas recherchable. Aucun utilisateurs ne peut demander au(x) gestionnaire(s) à intégrer l'espace de travail (depuis l'application) ou donnaitre l'existence du dossier.
Si du contenu de l'espace vous est partagé, la recherche ne vous indique pas son emplacement.

VIDEO
IMAGE

## Groupe
