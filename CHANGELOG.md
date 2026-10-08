# Ce qui change, version après version

Les nouveautés sont décrites du point de vue de ce qu'elles changent pour
vous. Les détails techniques restent dans le dépôt du code.

MusicOthèque se met à jour toute seule : elle vérifie au démarrage s'il
existe une version plus récente et propose de l'installer. Vous n'avez
rien à télécharger.

---

## 3.21.0 — Ordre des listes de lecture
*8 octobre 2026*

- Quand vous triez par une colonne, une flèche apparaît à côté de son nom :
  ▲ dans un sens, ▼ dans l'autre. Chaque clic inverse le sens.
- Les listes de lecture ont une colonne **N° liste** : la place de chaque
  morceau dans la liste.
- Vous pouvez changer l'ordre d'une liste : faites glisser un morceau plus
  haut ou plus bas, ou clic droit → **Déplacer dans la liste**.
- Menu **Bibliothèque → Remettre l'ordre d'Apple Music dans les listes…** :
  vos listes reprennent l'ordre qu'elles avaient dans Apple Music.

---

## 3.20.3 — Reprise automatique sans droits d'administrateur
*8 octobre 2026*

La reprise de l'envoi après un redémarrage ne demande plus de droits
d'administrateur.

---

## 3.20.2 — Partage de musique vers Kevin : reprise automatique
*8 octobre 2026*

L'envoi de morceaux vers le serveur de Kevin reprend tout seul après un
redémarrage de l'ordinateur.

---

## 3.20.1 — Partage de musique vers Kevin (suite)
*8 octobre 2026*

Amélioration de l'outil d'envoi de morceaux vers le serveur de Kevin.

---

## 3.20.0 — Préparation d'un partage de musique vers Kevin
*8 octobre 2026*

Ajout d'un outil d'envoi de morceaux vers le serveur de Kevin, utilisé
avec son aide. Rien ne change dans l'utilisation habituelle du logiciel.

---

## 3.19.2 — Apple Music retrouvé partout
*8 octobre 2026*

- Si votre dossier Musique a été déplacé sur un autre disque, MusicOthèque
  y trouve maintenant la bibliothèque d'Apple Music.
- Deux listes d'Apple Music identiques ne sont plus ajoutées toutes les
  deux.

---

## 3.19.1 — Pas de listes en double
*8 octobre 2026*

En récupérant vos listes d'Apple Music, MusicOthèque repère maintenant celles
que vous avez déjà sous un autre nom (mêmes morceaux) : elles sont signalées
et ne sont pas cochées, pour ne pas les ajouter deux fois.

---

## 3.19.0 — Vos listes d'Apple Music
*8 octobre 2026*

Si vous avez remplacé iTunes par Apple Music, vos nouvelles listes de
lecture n'arrivaient plus dans MusicOthèque : Apple Music pour Windows ne
sait pas les exporter. MusicOthèque va maintenant les chercher lui-même :
menu **Bibliothèque → Récupérer les listes d'Apple Music…**. Il vous montre
celles qui vous manquent ; vous cochez, il les ajoute. Rien n'est modifié
dans Apple Music, et vous pouvez recommencer quand vous voulez.

---

## 3.18.5 — Plus de bibliothèque vide par erreur
*7 octobre 2026*

- Si MusicOthèque s'ouvre sur une bibliothèque vide alors que votre
  bibliothèque habituelle se trouve ailleurs, il vous le dit et vous propose
  de l'ouvrir.
- Le logiciel ne modifie plus vos raccourcis du Bureau.
- La détection du lecteur de CD ne produit plus d'erreur en arrière-plan.

---

## 3.18.4 — L'écoute des morceaux de Kevin ne s'interrompt plus
*3 octobre 2026*

L'écoute d'un morceau de Kevin pouvait s'interrompre au bout de deux
minutes environ. Désormais le morceau arrive en une ou deux secondes, puis
se joue d'un bout à l'autre sans dépendre de la connexion internet. Rien
n'est enregistré sur votre disque.

---

## 3.18.3 — Une fin de quiz propre
*29 septembre 2026*

Quand le quiz se termine, le morceau en cours va jusqu'au bout, puis la
musique s'arrête : les morceaux du quiz ne s'enchaînent plus au hasard.
Votre liste d'avant le quiz revient, dans son ordre habituel. Et le quiz se
termine tout seul à la fin de son dernier morceau.

---

## 3.18.2 — Le quiz part vraiment au milieu
*29 septembre 2026*

Dans le quiz, la case « Commencer en plein milieu des pistes » ne marchait
que pour le premier morceau : les suivants repartaient du début. Désormais
chaque morceau commence quelque part entre le quart et les trois quarts, et
on n'entend jamais son début.

---

## 3.18.1 — L'écoute des morceaux de Kevin démarre
*29 septembre 2026*

Les morceaux de Kevin ne se lançaient pas : le lecteur passait de l'un à
l'autre sans rien jouer. Corrigé : ils s'écoutent désormais normalement, et
l'avance rapide fonctionne.

---

## 3.18.0 — La musique de Kevin, directement dans vos listes
*29 septembre 2026*

- **Quand vous cherchez un morceau**, la liste montre d'abord les vôtres,
  puis ceux de Kevin que vous n'avez pas encore : ceux-là sont en
  *italique bleu*, avec un petit nuage ☁ devant le titre. En bas à droite,
  le compte distingue « sur mon PC » et « chez Kevin ».
- **Dans « Toutes les pistes »**, une case *☁ Afficher les morceaux de
  Kevin* ajoute toute sa musique à la suite de la vôtre. Décochez-la pour
  revenir à vos seuls morceaux ; le choix est retenu.
- **Double-cliquez** sur un morceau de Kevin pour l'écouter, sans rien
  copier. **Clic droit** pour l'ajouter à votre bibliothèque ou à une
  liste de lecture.
- Pendant l'écoute d'un morceau de Kevin, l'étiquette *☁ CHEZ KEVIN*
  s'affiche près du lecteur.

---

## 3.17.2 — Plus fluide pendant les téléchargements
*29 septembre 2026*

- **Le logiciel ne se fige plus** à la fin d'un téléchargement depuis la
  bibliothèque partagée, ni quand vous cliquez sur « Arrêter » : l'arrêt est
  immédiat.
- Vous pouvez **fermer la fenêtre de la bibliothèque partagée** pendant un
  téléchargement : il continue, et son avancement s'affiche en bas de la
  fenêtre principale.
- Trier, filtrer ou tout sélectionner parmi des dizaines de milliers de
  morceaux reste instantané, même pendant un téléchargement.
- Après un ajout, la liste ne saute plus : votre sélection et votre position
  restent en place.
- La connexion ne bloque plus la fenêtre si le serveur tarde à répondre.

---

## 3.17.1 — Une taille plus lisible
*29 septembre 2026*

La taille d'un téléchargement depuis la bibliothèque partagée s'affiche
désormais **en un seul chiffre, le total**, dans l'unité qui convient :
*850 Ko*, *21,0 Mo*, *3,27 Go*…

---

## 3.17.0 — La taille avant de télécharger
*29 septembre 2026*

**Vous savez ce que vous allez télécharger.** Avant chaque ajout depuis la
bibliothèque partagée, MusicOthèque annonce la taille du téléchargement.
Vous confirmez ou vous annulez. La barre de progression suit ensuite ce qui
a été reçu.

**La bibliothèque partagée se tient à jour toute seule** : au démarrage,
puis toutes les deux heures. Quand des morceaux y sont ajoutés, un message
l'annonce en bas de la fenêtre.

**Quand le serveur se repose** (par forte chaleur, ses disques dorment), un
bandeau orange le signale : la recherche marche toujours, ce qui est déjà
sur votre ordinateur se joue normalement, et l'écoute en ligne comme les
téléchargements reprennent tout seuls à la fin de la canicule.

---

## 3.16.0 — La bibliothèque partagée
*29 septembre 2026*

**Vous pouvez parcourir et écouter la bibliothèque d'un proche**, qui se
trouve sur son serveur : menu **Bibliothèque → Bibliothèque partagée…**,
puis l'identifiant et le mot de passe qu'il vous a donnés. Une fois
connecté, elle apparaît dans la colonne de gauche.

- **Écouter** (double-clic) : le morceau est lu en ligne, **rien n'est
  copié** sur votre ordinateur.
- **Ajouter à ma bibliothèque** : le morceau est copié sur votre disque,
  rangé par artiste et par album, et apparaît chez vous comme les autres.
- **Ajouter à une liste de lecture** : pareil, et il entre dans la liste
  choisie (ou une nouvelle). Vous pouvez aussi **recopier une de ses
  listes entière**, sous le même nom.
- **Copier dans un dossier** : sur le Bureau par exemple, sans l'ajouter
  à la bibliothèque.

Chaque morceau indique **✔ Sur mon PC** ou **☁ Sur le NAS**. Ce que vous
avez déjà n'est jamais téléchargé une deuxième fois. La recherche est
immédiate, même hors connexion ; et quand vous cherchez dans votre propre
bibliothèque, un bouton bleu vous dit combien de morceaux correspondent
aussi dans la bibliothèque partagée.

Le mot de passe n'est pas enregistré : l'ordinateur garde une clé
chiffrée, valable tant que vous vous en servez au moins une fois par mois.

---

## 3.15.2 — Retirer un morceau
*27 septembre 2026*

**Vous pouvez retirer un morceau**, de deux façons qui ne font pas la
même chose :

- **d'une liste de lecture** : clic droit → « Retirer de la playlist ».
  Le morceau quitte cette liste, mais reste dans votre bibliothèque et
  dans vos autres listes ;
- **de la bibliothèque** : clic droit → « Retirer de la bibliothèque… ».
  Le morceau disparaît partout, de la bibliothèque comme de toutes vos
  listes. MusicOthèque vous demande confirmation avant.

**La touche Suppr marche aussi** : dans une liste de lecture, elle retire
de la liste ; ailleurs, de la bibliothèque (après confirmation).

Pour en retirer plusieurs d'un coup : sélectionnez-les avec **Ctrl + clic**.

**Votre fichier n'est jamais effacé du disque.** Et un morceau retiré ne
revient pas tout seul lors d'une nouvelle lecture de vos dossiers ou
d'iTunes. Si vous changez d'avis : Fichier → Importer des fichiers, et
désignez-le.

## 3.15.1 — Chaque morceau n'apparaît plus qu'une fois
*27 septembre 2026*

**Des morceaux apparaissaient en double.** Après « Tout récupérer »,
certains albums montraient chaque piste deux fois : une ligne « 1 », une
ligne « 1 sur 4 ». Ce n'étaient pas deux fichiers, mais le même, compté
deux fois : une fois en lisant vos dossiers, une fois en lisant iTunes.
Il suffisait qu'un nom de dossier diffère d'une majuscule entre les deux.

**C'est réparé tout seul.** Une minute environ après le premier
démarrage de cette version, MusicOthèque fait une sauvegarde, puis réunit
chaque paire en un seul morceau. Celui qui reste garde **tout ce que les
deux savaient** : le nombre de pistes, le compositeur, vos écoutes, vos
notes. Vos listes de lecture le retrouvent. **Aucun fichier n'est touché**,
seulement la liste de la bibliothèque. Un message en bas de la fenêtre
vous dit combien de doublons ont été retirés.

**Pour écouter une œuvre dans l'ordre** (un opéra, une symphonie) :
cliquez sur le titre de la colonne **Album**, ou Affichage → Ranger dans
l'ordre de l'album (Ctrl+Alt+A). Pour tous les disques d'un artiste dans l'ordre
où ils sont sortis : cliquez sur la colonne **Artiste**.

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
