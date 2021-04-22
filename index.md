---
layout: default
title: Accueil
nav_order: 1
description: "Likapi - Documentation officielle."
permalink: /
---

# Trouvez, la meilleure API avec Likapi
{: .fs-9 }

Concevez et personnalisez rapidement des sites mobiles réactifs avec Likapi, la librairie d'API's open source, gratuite la plus adaptée au monde, comprenant des liens d'appels données et des exemples de codes.
{: .fs-6 .fw-300 }

[Commencer maintenant]({{ '/docs/getting-started' | relative_url }}){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Voir sur GitHub](https://github.com/likapi/docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Installation du logiciel

### Versions

Vous pouvez retrouver les versions officielles du logiciel sur ce dépôt [tracker](https://github.com/likapi/tracker/releases).

### Linux

```bash
$ wget https://github.com/likapi/tracker/releases/download/v1.0-beta-linux/v1.0-beta-likapi.deb

$ sudo dpkg -i [nomdupacket].deb

$ likapi
```

### Windows

Pas encore disponible...

### Mac Os

Pas encore disponible...

## Exécution en interface graphique

### Linux

```bash
$ likapi-gui
```

## Désinstallation du logiciel

### Linux

```bash
$ sudo apt-get remove likapi
```

---

## À propos du projet

Likapi à été codé et crée  &copy;2020-{{ "now" | date: "%Y" }} par [Keany Vy KHUN](https://www.instagram.com/thisiskeanyvy/).

### Licence

Likapi est distribué avec [licence MIT](https://github.com/likapi/docs/blob/main/LICENSE).

### Contributeurs

Lorsque vous contribuez à ce référentiel, veuillez d'abord discuter du changement que vous souhaitez apporter via un problème,
email, ou toute autre méthode avec les propriétaires de ce référentiel avant d'apporter une modification. En savoir plus sur comment devenir contributeur sur [notre dépôt GitHub](https://github.com/likapi/docs#contributing).

#### Merci aux contributeurs de Likapi !

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code de conduite

Likapi s'engage à favoriser une communauté accueillante.

[Consultez notre code de conduite](https://www.contributor-covenant.org/) sur notre dépôt GitHub.
