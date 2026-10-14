# MusicOthèque

**Un lecteur et une bibliothèque musicale pour Windows, Mac et Linux.**
Ce dépôt ne contient aucun code : il sert uniquement à distribuer
l'application.

➡️ **[Télécharger la dernière version](../../releases/latest)**
 · [Ce qui change d'une version à l'autre](CHANGELOG.md)
 · **[English](#english)**

---

## Installer

1. Ouvrez la page [Releases](../../releases/latest).
2. Téléchargez le fichier qui correspond à votre ordinateur :

   | Système | Fichier |
   |---|---|
   | **Windows** | `MusicOtheque-Setup-X.Y.Z.exe` |
   | **Mac Apple Silicon** (M1, M2…) | `MusicOtheque-X.Y.Z-macos-arm64.dmg` |
   | **Mac Intel** | `MusicOtheque-X.Y.Z-macos-x86_64.dmg` |
   | **Linux** | `MusicOtheque-X.Y.Z-linux-x86_64.tar.gz` (ou `-arm64`) |

3. **Windows** : lancez-le. **Mac** : ouvrez le `.dmg` et glissez
   l'application dans Applications ; la première fois, clic droit dessus →
   **Ouvrir**. **Linux** : décompressez l'archive et lancez `./installer.sh`.

Lien permanent vers le dernier installeur Windows :
<https://github.com/ARP273-ROSE/musicotheque-releases/releases/latest/download/MusicOtheque-Setup.exe>

L'installation se fait dans votre profil utilisateur : **aucun mot de passe
administrateur n'est demandé**, et rien n'est modifié ailleurs sur
l'ordinateur.

> **Windows affiche « Windows a protégé votre ordinateur » ?**
> C'est normal : l'installeur n'est pas signé électroniquement, et Windows
> se méfie par principe de tout programme qui ne l'est pas. Cliquez sur
> **Informations complémentaires**, puis sur **Exécuter quand même**.
> Cet avertissement n'apparaît **qu'une seule fois** : les mises à jour
> suivantes sont installées par l'application elle-même et ne le
> déclenchent pas.

## Au premier démarrage

MusicOthèque cherche toute seule votre bibliothèque iTunes et vous annonce
ce qu'elle contient. Un bouton suffit : **Tout importer**.

Elle reprend vos morceaux quel que soit leur format, vos listes de lecture
avec leur contenu, vos compteurs d'écoute, vos notes, et vos podcasts — y
compris les épisodes que vous n'aviez pas téléchargés.

Si vous n'avez jamais utilisé iTunes, désignez simplement le dossier où se
trouve votre musique.

> Si votre musique est sur un disque externe, **branchez-le avant** de
> lancer l'import, sinon les morceaux seront introuvables et vos listes de
> lecture arriveront vides.

## Mettre à jour

**Ne téléchargez rien.** MusicOthèque vérifie elle-même au démarrage s'il
existe une version plus récente, vous le dit, et l'installe si vous
acceptez.

Le fichier `musicotheque-app-X.Y.Z.zip` attaché à chaque version sert à
cette mise à jour automatique. Il ne s'installe pas à la main.

## Obtenir de l'aide

- Dans l'application : touche **F1**, ou menu **Aide**. Vingt-deux rubriques
  écrites pour quelqu'un qui n'a aucune notion d'informatique.
- Menu **Aide → Manuel (PDF)** : le même contenu, d'un seul tenant, avec des
  images de l'application, à imprimer si vous préférez le papier.

## Si quelque chose ne va pas

L'application signale elle-même les plantages et les blocages : vous n'avez
rien à décrire. Le menu **Aide → Signaler un problème** permet d'y ajouter
ce que vous étiez en train de faire, ce qui aide beaucoup.

## Ce qu'elle sait faire

**Votre bibliothèque** — plus de vingt formats audio, de MP3 à FLAC,
DSD, ALAC ou WavPack. Recherche instantanée sur le titre, l'artiste,
l'album, le compositeur. Navigation par artiste, album, genre, époque ou
liste de lecture.

**Vos informations** — plus de cinquante champs par morceau : l'œuvre, le
mouvement, le chef d'orchestre, l'orchestre, les solistes, le label, le
numéro de catalogue… Toutes affichables en colonnes, toutes modifiables,
et enregistrées dans les fichiers eux-mêmes pour vous suivre partout.

**Vos podcasts** — abonnement, téléchargement automatique des nouveaux
épisodes, récupération des archives.

**Les radios** — 82 stations en direct, avec le titre du morceau diffusé.

**Vos disques** (Windows) — copie d'un CD vers la bibliothèque, et gravure
d'un CD audio depuis une sélection. Sur Mac et Linux, ces fonctions sont
grisées : elles s'appuient sur des composants que seul Windows fournit.

**Le classique** — classement automatique par période, forme, catalogue,
instruments et tonalité ; harmonisation des noms de compositeurs.

---

## English

**A music player and library for Windows, Mac and Linux.** This repository
holds no code: it only distributes the application.

**Install** — open the [Releases](../../releases/latest) page and download
the file for your computer: `MusicOtheque-Setup-X.Y.Z.exe` (Windows),
`MusicOtheque-X.Y.Z-macos-arm64.dmg` (Apple Silicon Mac),
`MusicOtheque-X.Y.Z-macos-x86_64.dmg` (Intel Mac),
`MusicOtheque-X.Y.Z-linux-x86_64.tar.gz` or `-arm64` (Linux). No administrator
password is asked for. Windows may warn about an unsigned installer: **More
info → Run anyway** (once). On a Mac, the first time, right-click the app →
**Open**. On Linux, unpack and run `./installer.sh`.

**Update** — download nothing: MusicOthèque checks for a new version at
start-up and installs it when you agree. The `musicotheque-app-X.Y.Z.zip`
file is for that automatic update only.

**Help** — **F1** or the **Help** menu (22 topics), and **Help → Manual
(PDF)**. The interface is in English or French (chosen on first start,
changeable in the preferences). Problems are reported automatically if you
allowed it; **Help → Report a problem** lets you add what you were doing.

**Windows only** — burning audio CDs, the inserted audio CD, Apple Music for
Windows playlists. On Mac and Linux these entries are greyed out.

[What changes, version after version](CHANGELOG.en.md)

---

*Le code source est dans un dépôt privé. Ce dépôt-ci ne sert qu'aux
téléchargements.*
