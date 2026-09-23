# Ce qui change, version après version

Les nouveautés sont décrites du point de vue de ce qu'elles changent pour
vous. Les détails techniques restent dans le dépôt du code.

MusicOthèque se met à jour toute seule : elle vérifie au démarrage s'il
existe une version plus récente et propose de l'installer. Vous n'avez
rien à télécharger.

---

## 3.15 — Des menus rangés, des réglages qui vous suivent
*23 septembre 2026*

**Les menus sont réorganisés.** « Affichage » avait fini par tout
accueillir — quatre actions de podcasts, la récupération des métadonnées,
un réglage — pendant qu'« Édition » ne contenait qu'une seule ligne.
Chaque entrée est maintenant là où on la cherche :

- un menu **Bibliothèque** pour tout ce qui agit sur votre collection ;
- un menu **Podcasts** pour tout ce qui les concerne ;
- **Affichage** ne garde que ce qui touche à l'aspect ;
- les **Paramètres** passent dans **Édition** (Ctrl+,), à leur place.

**Les préférences sont enfin complètes**, en cinq onglets : Général,
Lecture, Bibliothèque, Podcasts et Transfert. Les réglages qui traînaient
en cases perdues dans les menus les ont rejointes.

**Vous pouvez emporter vos réglages.** Réinstaller Windows ou changer
d'ordinateur effaçait tout ce que vous aviez réglé : la langue, la sortie
audio, les colonnes choisies, leur ordre, leur largeur, le tri de chaque
vue, vos dossiers de musique. **Édition → Paramètres → Transfert**
enregistre tout cela dans un fichier, et sait le reposer ailleurs. Un
dossier de musique absent du nouvel ordinateur est écarté, et l'application
vous dit lequel.

**Compléter depuis MusicBrainz** (menu Bibliothèque) va chercher sur
internet ce qui manque encore : l'œuvre, le compositeur, le chef
d'orchestre, l'orchestre, le label, le numéro de catalogue et l'ISRC.

Un morceau n'est retenu que si sa **durée correspond à trois secondes
près**. Si deux enregistrements se valent, il est laissé de côté : mieux
vaut une case vide qu'une case fausse. Et rien de ce que vous avez n'est
jamais remplacé.

**Corrections**

- Les messages d'alerte affichés **avant** l'ouverture de la fenêtre
  principale étaient illisibles, texte clair sur fond clair.
- « Importer des fichiers » et « Statistiques » partageaient le raccourci
  Ctrl+I : Windows n'en déclenchait aucun. Les statistiques passent sur
  Ctrl+Maj+S.
- Le manuel restait figé pour qui l'avait déjà ouvert une fois : il se
  refait désormais à chaque nouvelle version.
- Cinq albums pouvaient pointer vers un artiste supprimé.

---

## 3.14 — Toutes les informations de vos morceaux
*22 et 23 septembre 2026*

> **3.14.5** — L'aide intégrée gagne deux chapitres : « Les colonnes du
> tableau » et « Les informations d'un morceau ». Le manuel se met à jour
> tout seul à chaque nouvelle version, alors qu'il restait figé pour qui
> l'avait déjà ouvert une fois.
>
> **3.14.2 à 3.14.4** — Corrections des blocages : l'application ne se fige
> plus pendant « Tout récupérer », « Retrouver les dates des épisodes » ni
> « Classer la bibliothèque ».

La grande affaire de cette version : MusicOthèque connaît désormais
**plus de cinquante informations** par morceau, au lieu d'une quinzaine.

**Ce qui arrive de neuf**

- L'**œuvre** et le **mouvement**, au sens où l'entend la musique
  classique : « Symphonie n° 9 », « II. Molto vivace », 2 sur 4.
- Le **chef d'orchestre**, l'**orchestre**, les **solistes**, le **chœur**.
- Le **label**, le **numéro de catalogue**, le **code-barres**, l'**ISRC**,
  le **sous-titre du CD**, le **copyright**.
- Les **clés de tri** d'iTunes — celles qui rangent « Antonín Dvořák » à la
  lettre D et non à la lettre A.
- Les **commentaires**, le **regroupement**, le **tempo**, les **paroles**,
  la **langue**, le **pays de parution**.

**Le numéro de piste affiche enfin son total** : « 1 sur 13 » au lieu de
« 1 ». La colonne s'appelle maintenant « N° piste » et non plus « # »,
qui ne disait rien à personne.

**Les colonnes se déplacent à la souris.** Attrapez un intitulé, glissez-le,
lâchez. Votre rangement est retenu d'une fois sur l'autre. Le choix des
colonnes et le rangement dans l'ordre de l'album, qui n'existaient qu'au
clic droit, sont maintenant dans le menu **Affichage**.

**Un seul geste pour tout récupérer** : **Affichage → Tout récupérer
(fichiers + iTunes)**. L'application relit vos fichiers, puis votre
bibliothèque iTunes. Les deux sources se complètent — les fichiers portent
le chef d'orchestre et le label, iTunes garde le compositeur que vous avez
saisi à la main. Rien n'est jamais effacé : seules les cases vides sont
remplies.

**La fenêtre de modification présente tous les champs**, et défile.

**Corrections importantes**

- Une relecture de la bibliothèque **n'efface plus rien**. Elle remplaçait
  auparavant le compositeur, le numéro de piste, le genre et l'année par ce
  que portait le fichier — même vide. Le titre, l'artiste et l'album
  pouvaient être remplacés par le nom du fichier et par « Unknown Artist ».
- L'application **ne se fige plus** pendant les travaux de fond. Un travail
  long gardait la bibliothèque verrouillée pendant la lecture des fichiers,
  et tout le reste attendait jusqu'à deux minutes.

---

## 3.13 — Démarrage, stabilité, lisibilité
*21–22 septembre 2026*

- **Le démarrage ne se fige plus** : 0,09 seconde au lieu de 2,4.
- L'**installateur efface proprement la version précédente**, et refuse de
  s'installer par-dessus une application ouverte.
- Le logiciel fermé **continuait de tourner** en arrière-plan : corrigé.
- **« Classer la bibliothèque »** tombait dès le premier morceau.
- Un **index de recherche abîmé** empêchait toute écriture dans la
  bibliothèque, sans rien dire.
- La **console noire qui clignotait** toutes les quatre secondes a disparu.
- Les **messages d'alerte sont lisibles** : ils s'affichaient en clair sur
  fond clair.
- Une action qui échoue **le dit**, au lieu de laisser une barre de
  progression figée.
- Le petit logo qui suivait la souris est **éteint par défaut**.

---

## 3.12 — Les podcasts, d'un seul coup
*21 septembre 2026*

- **Télécharger d'un coup** les épisodes manquants de toutes vos émissions.
- Les rapports d'incident indiquent sur quelle machine le problème a eu
  lieu.

---

## 3.10 et 3.11 — Les CD et les archives
*21 septembre 2026*

- Le **CD inséré s'affiche tout seul** et s'importe sans rien demander.
- La **gravure sur plusieurs disques** quand la sélection dépasse 79 minutes.
- Un **DVD n'est plus pris pour un album**.
- Les **nouveaux épisodes de podcast arrivent enfin tout seuls**.
- Les épisodes importés depuis des fichiers **retrouvent leur date**.
- Récupération des **anciens épisodes** d'une émission de Radio France.

---

## 3.8 et 3.9 — Graver, et un peu de fantaisie
*21 septembre 2026*

- **Gravure de CD audio** depuis une sélection ou une liste de lecture.
- Un instrument de l'orchestre suit le pointeur, et change chaque jour.
  (Éteint par défaut depuis la 3.13.)

---

## 3.7 — Quand quelque chose ne va pas
*20–21 septembre 2026*

- **Rapports d'incident** : en cas de plantage ou de blocage, l'application
  envoie seule ce qu'il faut pour comprendre.
- Le **tri des listes de lecture** cessait de mentir.
- Les **numéros de piste venus d'iTunes** étaient perdus à l'import, pour
  toute bibliothèque iTunes. Réparés, y compris les anciens.

---

## 3.6 — Une installation autonome
*20 septembre 2026*

- **Paquet Windows autonome** : plus besoin d'installer Python.
- **Mise à jour automatique** depuis l'application.
- **Aide à rubriques** (F1) et **manuel complet**.
- **Assistant de premier lancement** avec import iTunes complet.
- Enrichissement des **compositeurs** par MusicBrainz, et écriture dans les
  étiquettes des fichiers.
- Les **radios** réparées station par station, passerelle pour les flux BBC.

---

## 3.0 à 3.5 — Les fondations
*avril à septembre 2026*

- **Streaming multi-PC** et synchronisation avec un NAS.
- **Import de fichiers** par glisser-déposer.
- **Radios en direct** avec le titre du morceau diffusé.
- **Quiz musical**.
- **Visualiseur audio**.
- **Classification** des œuvres classiques : période, forme, catalogue,
  instruments, tonalité.
- **Harmonisation** des compositeurs, genres, artistes et albums.
- **Protection du seeding** : les fichiers en partage ne sont jamais
  déplacés ni modifiés.

---

## 2.0 — La première version complète
*12 mars 2026*

Podcasts, copie de CD, harmonisation des étiquettes, statistiques.
