---
layout: default
title: Partage de fichiers
parent: Education
nav_order: 1
---

# Partage de fichiers
{: .no_toc }

Avec notre équipe, nous avons développé un outil, nommé EduShare. Cet outil, vous permet de partager, vos fichiers gratuitement sans passer par un serveur.
{: .fs-6 .fw-300 }

---

## Fonctionnement du logiciel

### Concept

Le logiciel EduShare, développé principalement en Python et Shell, utilise des tunnels Ngrok pour ouvrir les ports de votre machine, sans passer par la configuration du pare-feu de votre routeur. Ce principe est appellé reverse tunneling. Un lien HTTP(S) Ngrok pointe alors vers votre localhost avec le port ouvert.

À partir de cette étape, n'importe quelle personne avec une connexion internet et disposant du lien de partage peut accéder à vos fichiers partagés.

Le concept principal du logiciel EduShare, est de décentraliser le partage de fichiers pour éviter la surcharge du serveur. Une attaque par déni de service (DDOS), ne peut donc pas être effectuée sur le service de partage de fichiers car quand vous partagez des fichiers via notre outil, vous devenez le serveur.

C'est donc un partage de client à client. Vous pouvez, effectuer un partage de fichiers à plusieurs clients en simultané.

### Protocoles utilisés

Les protocoles, utilisés par EduShare, sont principalement le HTTP(S) donc du web sécurisé par TLS(SSL), qui est une couche de sockets sécurisés.

Les échanges, sont donc chiffrés, par le protocole TLS(SSL) qui lui garanti l'intégrité et la confidentialité des données.

### Modification du code source

Nous avons, mis le code source du logiciel EduShare en ligne sur un dépôt Github. Vous pouvez y contribuer en suivant [les indications de contribution](https://github.com/likapi/edushare#contribution).

Vous êtes, de mêmes autorisés en tant qu'étudiant à récupérer, modifier et adapter le code source pour vos besoins. Cela peut vous permettre d'apprendre à réutiliser du code pour vos propres applications dans le futur.

---

## Installation du logiciel

### Versions

Vous pouvez retrouver les versions officielles du logiciel sur ce dépôt [EduShare](https://github.com/likapi/edushare/releases).

### Linux

```bash
$ wget https://github.com/likapi/edushare/releases/download/v1.0-beta-linux/v1.0-beta-linux-edushare.deb

$ sudo dpkg -i v1.0-beta-linux-edushare.deb

$ sudo edushare
```

### Windows

Pas encore disponible...

### Mac Os

Pas encore disponible...

## Exécution en interface graphique

### Linux

```bash
$ sudo edushare-gui
```

## Désinstallation du logiciel

### Linux

```bash
$ sudo apt-get remove edushare
```