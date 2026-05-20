---
title: 🛡️ Guide des claims
description: Apprendre a creer, gerer et proteger son claim sur le serveur.
sidebar_position: 6
---

# 🛡️ Les claims

Les claims permettent de proteger vos constructions et de gerer qui peut entrer, construire, interagir ou participer a votre territoire.

Un claim protege une zone precise du monde. Vous pouvez ensuite y ajouter des membres, regler des options, afficher ses limites, definir un point de teleportation ou bloquer certains joueurs.

:::info
Certains mondes peuvent etre bloques pour la creation de claims, comme le spawn ou les zones PvP.
:::

## 🔎 Avant de creer un claim

Avant de vous installer, verifiez les claims proches avec :

```text
/claim near
```

Cette commande affiche les regions autour de vous, leur centre et leur proprietaire. Elle aide a eviter de construire trop pres d'un autre joueur.

:::warning
Respectez les claims autour de vous. Si vous voulez vous installer pres d'un autre joueur, demandez-lui son accord avant de construire.
:::

## ⚡ Creer un claim rapidement

Placez-vous au centre de la zone que vous voulez proteger, puis utilisez :

```text
/claim
```

Si vous n'etes dans aucun claim, le menu de creation s'ouvre. Choisissez ensuite une taille.

![Menu de creation de claim](/img/claim/claim.png)

Les tailles disponibles dans le menu sont :

| Taille | Prix |
| --- | ---: |
| 10x10 | 5$ |
| 50x50 | 25$ |
| 100x100 | 500$ |
| 200x200 | 2000$ |

Les claims sont payants et ne sont pas rembourses en cas de suppression.

## 🎯 Creer un claim avec precision

Pour choisir vous-meme les coins de votre region, utilisez un baton.

![Selection au baton](/img/claim/claim2.png)

Avec le baton en main :

1. Faites clic gauche sur un coin de la zone.
2. Faites clic droit sur le coin oppose.
3. Ajustez la selection si besoin.
4. Validez avec :

```text
/claim create
```

Des particules peuvent apparaitre pour montrer les limites de la selection.

![Delimitation d'un claim](/img/claim/claim3.png)
![Exemple de claim](/img/claim/claim4.png)

:::tip
Avec le baton, le prix est calcule selon la taille de la zone. La taille maximale est de 400x400.
:::

## 🧭 Ouvrir le menu de gestion

Placez-vous dans un claim que vous pouvez gerer, puis utilisez :

```text
/claim
```

Si vous avez acces a plusieurs claims superposes a cet endroit, le plugin vous proposera de choisir lequel gerer.

Le menu de gestion donne acces aux options principales :

- **Informations** : voir le monde, le centre, la taille, les chefs, admins et membres.
- **Message de bienvenue** : afficher un message quand un joueur entre dans le claim.
- **Renommer le claim** : changer le nom affiche.
- **Afficher la bordure** : voir les limites avec des particules.
- **Point de teleportation** : enregistrer votre position comme point d'arrivee.
- **Vos regions** : voir la liste de vos claims.
- **Creer une autre region** : ajouter une region secondaire.
- **Membres** : gerer les joueurs autorises.
- **Permissions des roles** : choisir ce que les admins, membres et visiteurs peuvent faire.
- **Flags** : activer ou desactiver des protections.
- **Bannissements** : bloquer des joueurs dans le claim.
- **Supprimer le claim** : retirer la protection, sans supprimer les constructions.

## 📜 Voir ses claims

Pour afficher vos claims :

```text
/claim list
```

Vous pouvez aussi ouvrir cette liste depuis le menu de gestion avec **Vos regions**.

## 👥 Inviter et gerer des joueurs

Dans le menu **Membres**, vous pouvez gerer les joueurs qui ont acces a votre claim.

Les roles principaux sont :

- **Chef** : proprietaire principal du claim, avec toutes les permissions.
- **Admin** : joueur de confiance qui peut aider a gerer le claim selon les permissions donnees.
- **Membre** : joueur autorise a participer au claim selon les permissions donnees.
- **Visiteur** : joueur sans role particulier.

:::tip
Donnez le role admin uniquement aux joueurs en qui vous avez vraiment confiance.
:::

## 🔐 Gerer les permissions des roles

Le menu **Permissions des roles** permet de choisir ce que chaque role peut faire.

Par exemple, vous pouvez autoriser ou non :

- gerer les membres ;
- gerer les flags ;
- gerer les bannissements ;
- modifier le message de bienvenue ;
- changer la priorite ;
- definir le point de teleportation ;
- renommer ou supprimer le claim ;
- afficher la bordure.

Les chefs gardent toutes les permissions.

## 🚩 Regler les flags

Les flags sont les options de protection du claim. Ouvrez le menu **Flags** depuis le menu du claim, puis cliquez sur une option pour la modifier.

Ils permettent notamment de controler :

- l'entree et la sortie du claim ;
- le vol ;
- les effets ;
- les homes et teleportations ;
- les portes, trappes, portillons, boutons, leviers et plaques de pression ;
- les coffres et autres interactions ;
- les spawners ;
- le feu, l'eau, la lave, la gravite et certaines transformations de blocs ;
- les cultures ;
- les blocs que les visiteurs peuvent casser ou poser ;
- les commandes bloquees ;
- le chat de claim ;
- l'apparition des animaux ;
- l'apparition des monstres.

## 🐾 Animaux et monstres

Les menus **Gestion des animaux** et **Gestion des monstres** permettent de choisir precisement quelles creatures peuvent apparaitre dans votre claim.

Vous pouvez :

- tout activer ;
- tout desactiver ;
- activer ou desactiver une creature precise ;
- changer de page si la liste est longue.

:::danger
Les spawns des monstres et animaux suivent le comportement du serveur par defaut tant que vous ne les modifiez pas. Si vous changez la liste, verifiez bien les creatures activees pour eviter les mauvaises surprises.
:::

## ⛔ Bannir un joueur du claim

Dans le menu **Bannissements**, vous pouvez ajouter un joueur a la liste des bannis.

Un joueur banni ne peut plus entrer dans le claim. S'il est deja dedans au moment du ban, il est renvoye hors de la zone.

Pour retirer un ban, retournez dans le meme menu et cliquez sur le joueur banni.

## 🌀 Definir le point de teleportation

Placez-vous a l'endroit voulu dans le claim, puis ouvrez :

```text
/claim
```

Cliquez sur **Definir le point de teleportation**.

Les joueurs autorises utiliseront ensuite ce point pour arriver dans le claim.

## 💬 Chat de claim

Pour parler uniquement aux membres presents du claim :

```text
/claim chat <message>
```

Exemple :

```text
/claim chat Quelqu'un peut venir m'aider ?
```

## 🤝 Claims ou vous etes membre

Pour voir les claims dans lesquels vous etes membre ou admin :

```text
/claim trusted
```

Depuis ce menu, vous pouvez retrouver les claims partages avec vous et quitter un claim si vous ne voulez plus en faire partie.

## 🔁 Transferer un claim

Pour proposer le transfert d'un claim a un autre joueur :

```text
/claim transfert <joueur>
```

Le joueur doit accepter la demande pour devenir proprietaire.

:::warning
Un transfert change le proprietaire du claim. Verifiez bien le pseudo avant de confirmer.
:::

## 🧨 Supprimer un claim

Vous pouvez supprimer un claim depuis le menu de gestion.

Supprimer un claim retire seulement la protection. Les blocs et constructions restent en place.

:::danger
Il est interdit de faire un claim sur le toit du Nether dans le but de s'y teleporter ou d'y construire. Des sanctions peuvent etre appliquees en cas de non-respect des regles.
:::

## ⌨️ Commandes utiles

| Commande | Utilite |
| --- | --- |
| `/claim` | Ouvre le menu principal |
| `/claim create` | Cree un claim avec la selection au baton |
| `/claim list` | Affiche vos claims |
| `/claim trusted` | Affiche les claims ou vous etes membre ou admin |
| `/claim near` | Affiche les claims proches |
| `/claim info` | Affiche les informations du claim actuel |
| `/claim chat <message>` | Envoie un message aux membres du claim |
| `/claim transfert <joueur>` | Propose de transferer un claim |

## ✅ Bonnes pratiques

- Creez votre claim avant de construire une base importante.
- Regardez les claims proches avant de vous installer.
- Verifiez la bordure pour eviter de laisser des coffres hors protection.
- Ajoutez seulement des joueurs de confiance.
- Utilisez les permissions des roles pour limiter ce que les membres peuvent modifier.
- Definissez un point de teleportation dans un endroit sur.
- Gardez une distance correcte avec les claims voisins.
