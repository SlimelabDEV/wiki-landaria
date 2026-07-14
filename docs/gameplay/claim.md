---
title: 🛡️ Guide des claims
description: Apprendre à créer, gérer et protéger son claim sur le serveur.
sidebar_position: 6
---

# 🛡️ Les claims

Les claims permettent de protéger vos constructions et de gérer qui peut entrer, construire, interagir ou participer à votre territoire.

Un claim protège une zone précise du monde. Vous pouvez ensuite y ajouter des membres, régler des options, afficher ses limites, définir un point de téléportation, personnaliser son icône ou bloquer certains joueurs.

:::info
Certains mondes peuvent être bloqués pour la création de claims, comme le spawn ou les zones PvP.
:::

## 🔎 Avant de créer un claim

Avant de vous installer, vérifiez les claims proches avec :

```text
/claim near
```

Cette commande affiche les régions autour de vous, leur centre et leur propriétaire. Elle aide à éviter de construire trop près d'un autre joueur.

:::warning
Respectez les claims autour de vous. Si vous voulez vous installer près d'un autre joueur, demandez-lui son accord avant de construire.
:::

## ⚡ Créer un claim rapidement

Placez-vous au centre de la zone que vous voulez protéger, puis utilisez :

```text
/claim
```

Si vous n'êtes dans aucun claim, le menu de création s'ouvre. Choisissez ensuite une taille.

![Menu de création de claim](/img/claim/claim.png)

Les tailles disponibles dans le menu sont :

| Taille | Prix |
| --- | ---: |
| 10x10 | 5$ |
| 50x50 | 25$ |
| 100x100 | 500$ |
| 200x200 | 2000$ |

Les claims sont payants et ne sont pas remboursés en cas de suppression.

## 🎯 Créer un claim avec précision

Pour choisir vous-même les coins de votre région, utilisez un bâton.

![Sélection au bâton](/img/claim/claim2.png)

Avec le bâton en main :

1. Faites clic gauche sur un coin de la zone.
2. Faites clic droit sur le coin opposé.
3. Ajustez la sélection si besoin.
4. Validez avec :

```text
/claim create
```

Des particules peuvent apparaître pour montrer les limites de la sélection.

![Délimitation d'un claim](/img/claim/claim3.png)
![Exemple de claim](/img/claim/claim4.png)

:::tip
Avec le bâton, le prix est calculé selon la taille de la zone. La taille maximale est de 400x400.
:::

## 🧭 Ouvrir le menu de gestion

Placez-vous dans un claim que vous pouvez gérer, puis utilisez :

```text
/claim
```

Si vous avez accès à plusieurs claims superposés à cet endroit, le plugin vous proposera de choisir lequel gérer.

Le menu de gestion donne accès aux options principales :

- **Informations** : voir le monde, le centre, la taille, les chefs, admins et membres.
- **Message de bienvenue** : afficher un message quand un joueur entre dans le claim.
- **Renommer le claim** : changer le nom affiché.
- **Afficher la bordure** : voir les limites avec des particules.
- **Point de téléportation** : enregistrer votre position comme point d'arrivée.
- **Vos régions** : voir la liste de vos claims et modifier leur icône.
- **Créer une autre région** : ajouter une région secondaire.
- **Membres** : gérer les joueurs autorisés.
- **Permissions des rôles** : choisir ce que les admins, membres et visiteurs peuvent faire.
- **Flags** : activer ou désactiver des protections.
- **Bannissements** : bloquer des joueurs dans le claim.
- **Priorité** : choisir quel claim passe en premier lorsque plusieurs claims se superposent.
- **Supprimer le claim** : retirer la protection, sans supprimer les constructions.

## 📜 Voir ses claims

Pour afficher vos claims :

```text
/claim list
```

Vous pouvez aussi ouvrir cette liste depuis le menu de gestion avec **Vos régions**.

Depuis cette liste, le chef du claim peut personnaliser l'icône affichée pour un claim. L'item utilisé sert seulement d'icône et n'est pas consommé.

## 📊 Voir ses limites

Pour afficher vos limites de claims et de blocs :

```text
/claim limit
```

La commande indique le monde actuel, le nombre de claims possédés, la surface utilisée, votre limite de blocs et ce qu'il vous reste.

## 👥 Inviter et gérer des joueurs

Dans le menu **Membres**, vous pouvez gérer les joueurs qui ont accès à votre claim.

Les rôles principaux sont :

- **Chef** : propriétaire principal du claim, avec toutes les permissions.
- **Admin** : joueur de confiance qui peut aider à gérer le claim selon les permissions données.
- **Membre** : joueur autorisé à participer au claim selon les permissions données.
- **Visiteur** : joueur sans rôle particulier.

:::tip
Donnez le rôle admin uniquement aux joueurs en qui vous avez vraiment confiance.
:::

## 🔐 Gérer les permissions des rôles

Le menu **Permissions des rôles** permet de choisir ce que chaque rôle peut faire.

Par exemple, vous pouvez autoriser ou non :

- gérer les admins ;
- gérer les membres ;
- gérer les flags ;
- gérer les bannissements ;
- modifier le message de bienvenue ;
- changer la priorité ;
- définir le point de téléportation ;
- renommer le claim ;
- supprimer le claim ;
- transférer le claim ;
- afficher la bordure.

Les chefs gardent toutes les permissions.

## 🚩 Régler les flags

Les flags sont les options de protection du claim. Ouvrez le menu **Flags** depuis le menu du claim, puis cliquez sur une option pour la modifier.

Ils permettent notamment de contrôler :

- l'entrée et la sortie du claim ;
- le fly ;
- les potions et certains effets ;
- les portes, trappes, portillons, boutons, leviers et plaques de pression ;
- les coffres, shulker boxes, tonneaux, fours et autres interactions ;
- les tables de craft, enclumes, tables d'enchantement et coffres de l'End ;
- le feu, l'eau, la lave, la gravité et certaines transformations de blocs ;
- les cultures ;
- les blocs que les visiteurs peuvent casser ou poser ;
- les commandes bloquées ;
- l'apparition des animaux ;
- l'apparition des monstres ;
- les animaux que les visiteurs peuvent blesser ou tuer.

## 🐾 Animaux et monstres

Les menus **Gestion des animaux** et **Gestion des monstres** permettent de choisir précisément quelles créatures peuvent apparaître dans votre claim.

Vous pouvez :

- tout activer ;
- tout désactiver ;
- activer ou désactiver une créature précise ;
- changer de page si la liste est longue.

:::danger
Les spawns des monstres et animaux suivent le comportement du serveur par défaut tant que vous ne les modifiez pas. Si vous changez la liste, vérifiez bien les créatures activées pour éviter les mauvaises surprises.
:::

## ⛔ Bannir un joueur du claim

Dans le menu **Bannissements**, vous pouvez ajouter un joueur à la liste des bannis.

Un joueur banni ne peut plus entrer dans le claim. S'il est déjà dedans au moment du ban, il est renvoyé hors de la zone.

Pour retirer un ban, retournez dans le même menu et cliquez sur le joueur banni.

## 🌀 Définir le point de téléportation

Placez-vous à l'endroit voulu dans le claim, puis ouvrez :

```text
/claim
```

Cliquez sur **Définir le point de téléportation**.

Les joueurs autorisés peuvent ensuite utiliser :

```text
/claim tp <claim> [monde]
```

:::tip
Si plusieurs claims portent le même nom, indiquez aussi le monde avec `/claim tp <claim> <monde>`.
:::

## 💬 Chat de claim

Pour parler uniquement aux membres présents du claim :

```text
/claim chat <message>
```

Exemple :

```text
/claim chat Quelqu'un peut venir m'aider ?
```

## 🔔 Notifications et bossbar

Vous pouvez activer ou désactiver certaines informations liées aux claims :

```text
/claim notify
```

Cette commande active ou désactive les notifications d'entrée/sortie et les messages de bienvenue.

```text
/claim bossbar
```

Cette commande active ou désactive la bossbar permanente du claim.

## 🤝 Claims où vous êtes membre

Pour voir les claims dans lesquels vous êtes membre ou admin :

```text
/claim trusted
```

Depuis ce menu, vous pouvez retrouver les claims partagés avec vous et quitter un claim si vous ne voulez plus en faire partie.

## 🔁 Transférer un claim

Pour proposer le transfert d'un claim à un autre joueur :

```text
/claim transfert <joueur> [claim] [monde]
```

Le joueur doit accepter la demande pour devenir propriétaire.

:::warning
Un transfert change le propriétaire du claim. Vérifiez bien le pseudo avant de confirmer.
:::

## 🧨 Supprimer un claim

Vous pouvez supprimer un claim depuis le menu de gestion.

Supprimer un claim retire seulement la protection. Les blocs et constructions restent en place.

:::danger
Il est interdit de faire un claim sur le toit du Nether dans le but de s'y téléporter ou d'y construire. Des sanctions peuvent être appliquées en cas de non-respect des règles.
:::

## ⌨️ Commandes utiles

| Commande | Utilité |
| --- | --- |
| `/claim` | Ouvre le menu principal |
| `/claim create` | Crée un claim avec la sélection au bâton |
| `/claim list` | Affiche vos claims et permet de modifier leur icône |
| `/claim trusted` | Affiche les claims où vous êtes membre ou admin |
| `/claim near` | Affiche les claims proches |
| `/claim info` | Affiche les informations du claim actuel |
| `/claim limit` | Affiche vos limites de claims et de blocs |
| `/claim tp <claim> [monde]` | Vous téléporte vers un de vos claims |
| `/claim chat <message>` | Envoie un message aux membres du claim |
| `/claim notify` | Active ou désactive les notifications de claim |
| `/claim bossbar` | Active ou désactive la bossbar du claim |
| `/claim flag` | Ouvre le menu des flags |
| `/claim member` | Ouvre le menu des membres |
| `/claim ban` | Ouvre le menu des bannissements |
| `/claim border` | Affiche la bordure du claim |
| `/claim transfert <joueur> [claim] [monde]` | Propose de transférer un claim |

## ✅ Bonnes pratiques

- Créez votre claim avant de construire une base importante.
- Regardez les claims proches avant de vous installer.
- Vérifiez la bordure pour éviter de laisser des coffres hors protection.
- Ajoutez seulement des joueurs de confiance.
- Utilisez les permissions des rôles pour limiter ce que les membres peuvent modifier.
- Définissez un point de téléportation dans un endroit sûr.
- Gardez une distance correcte avec les claims voisins.
