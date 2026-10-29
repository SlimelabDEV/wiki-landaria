---
description: "Découvrez les guildes de Landaria : créer sa guilde, inviter des membres, gérer les rôles, la banque, le coffre, les alliances et débloquer les 7 paliers."
sidebar_position: 4
---

# 💫 Les guildes

![Guildes](/img/guilde/guildes-banniere.svg)

Une **guilde** réunit plusieurs joueurs autour d'un même projet : construire, farmer, combattre ou faire du commerce ensemble. Elle possède sa propre **banque**, un **coffre partagé**, un **home** et peut **s'allier** avec d'autres guildes. Plus elle grandit, plus elle débloque de places et d'avantages !

---

## 📜 Le menu de guilde

Utilisez **`/guild`** (ou **`/g`**) pour ouvrir le menu de votre guilde. Survolez l'étoile en haut pour retrouver l'essentiel : préfixe, chef, palier, banque, membres et alliances.

![Menu de guilde](/img/guilde/guildes-menu.png)

En bas du menu, vous avez accès à :

- 📦 **Coffre de guilde** : les objets rangés en commun.
- 👥 **Membres** : la liste des membres, leurs rôles et leurs contributions.
- 💰 **Banque de guilde** : l'historique des dépôts, retraits et gains.
- 🪧 **Classement des guildes** : les meilleures guildes du serveur.
- 📖 **Journal de guilde** : les actions importantes et les changements récents.
- ⚙️ **Options de guilde** : préfixe, nom, statut, emblème, home et taxe Jobs.

---

## 🛠️ Créer une guilde

Fonder une guilde coûte **1 000 000 $**. Utilisez la commande :

```text
/guild create <nom> [préfixe]
```

Confirmez ensuite avec **`/guild confirm`** dans les 30 secondes, ou annulez avec **`/guild cancel`**.

| | Règles |
| --- | --- |
| 🏷️ **Nom** | Lettres et chiffres uniquement, sans couleur, **16 caractères** maximum. |
| 🎨 **Préfixe** | Lettres, chiffres et codes couleur `&`, **12 caractères** maximum (les codes couleur ne comptent pas). |

:::tip 💡
Si vous ne précisez pas de préfixe, le nom de la guilde est utilisé. Pour un nom de plus de 12 caractères, indiquez un préfixe plus court.
:::

:::warning ⚠️
Le code couleur *Magic* (texte qui change en permanence) est **interdit** dans les préfixes. En cas d'utilisation, le staff vous demandera de le modifier ; un refus peut entraîner une sanction et la suppression de la guilde.
:::

Vous ne pouvez faire partie que d'**une seule guilde** à la fois.

---

## 🤝 Inviter et rejoindre

- ✉️ **Inviter un joueur** : `/guild invite <joueur>`, ou le bouton **Inviter un joueur** dans le menu Membres. Le joueur doit être connecté.
- ✅ **Accepter une invitation** : `/guild accept <guilde>`.
- ❌ **Refuser une invitation** : `/guild decline <guilde>`.
- 🔓 **Guilde publique** : n'importe qui peut la rejoindre avec `/guild accept <guilde>`, sans invitation. Une guilde privée n'accepte que les joueurs invités.
- 🚪 **Quitter sa guilde** : `/guild leave`, puis `/guild confirm`.

![Invitation et chats de guilde](/img/guilde/guildes-chat.png)

:::info
Le chef ne peut pas quitter sa guilde : il doit d'abord **céder la direction** à un membre avec `/guild transfer <joueur>`, ou dissoudre la guilde.
:::

---

## 👑 Les rôles

Chaque membre a un rôle qui définit ce qu'il peut faire :

| Rôle | Ce qu'il peut faire |
| --- | --- |
| 👑 **Chef** | Tout : renommer la guilde, changer le préfixe et l'emblème, gérer le statut, la taxe Jobs et les paliers, céder la direction ou dissoudre la guilde. |
| ⚔️ **Officier** | Inviter, expulser, promouvoir et rétrograder, gérer le home et les alliances, déposer et retirer de l'argent, ouvrir le coffre. |
| 🛡️ **Vétéran** | Inviter des joueurs, déposer de l'argent, ouvrir le coffre, parler dans le chat d'alliance. |
| 🙂 **Membre** | Déposer de l'argent, parler dans le chat d'alliance. |
| 🌱 **Recrue** | Déposer de l'argent. |
| 🔍 **À l'essai** | Participer au chat de guilde. |

Tous les membres ont accès au **chat de guilde** et au **home**.

Pour changer le rôle d'un membre, ouvrez le menu **Membres**, cliquez sur son nom puis choisissez son nouveau rôle. Vous pouvez aussi utiliser `/guild promote <joueur>`, `/guild demote <joueur>` ou `/guild boot <joueur>` pour l'expulser.

---

## 🚀 Les paliers

Votre guilde commence au **palier 1** et peut monter jusqu'au **palier 7**. Chaque palier augmente le nombre de membres, d'alliances et de pages de coffre.

| Palier | Prix | Membres | Alliances | Pages de coffre | Taxe Jobs max |
| --- | --- | --- | --- | --- | --- |
| 🟫 **1** | Palier de départ | 3 | 1 | 2 | 1 % |
| ⬜ **2** | 500 000 $ | 5 | 2 | 3 | 2 % |
| 🟨 **3** | 750 000 $ | 10 | 3 | 4 | 3 % |
| 💎 **4** | 1 000 000 $ | 15 | 4 | 5 | 4 % |
| ⬛ **5** | 1 250 000 $ | 25 | 5 | 6 | 5 % |
| ✨ **6** | 1 500 000 $ | 35 | 6 | 7 | 6 % |
| 🥚 **7** | 1 750 000 $ | 40 | 7 | 8 | 7 % |

Le prix est payé avec la **banque de la guilde**. Seul le chef peut débloquer un palier : cliquez sur le prochain palier dans le menu, ou utilisez `/guild upgrade`.

![Paliers de guilde](/img/guilde/guildes-paliers.png)

Dans le menu, la ligne sous les paliers indique leur état : 🟩 **débloqué**, 🟨 **prochain palier**, 🟥 **verrouillé**.

---

## 💰 La banque de guilde

La banque permet de mettre de l'argent en commun pour faire grandir la guilde.

- 💵 **Déposer** : `/guild bank deposit <montant>` (tous les rôles sauf *À l'essai*).
- 💸 **Retirer** : `/guild bank withdraw <montant>` (chef et officiers).
- 📊 **Consulter le solde** : `/guild bank balance`.

Le menu **Banque** affiche l'historique des opérations et un bilan des entrées et sorties sur la journée, les 7 derniers jours et les 30 derniers jours.

### Taxe Jobs

Le chef peut fixer une **taxe sur les gains de métier** de ses membres, depuis le menu **Options**. Ce pourcentage est prélevé automatiquement sur leurs salaires de [métier](/docs/gameplay/jobs) et versé directement à la banque de la guilde. Son maximum dépend du palier (de 1 % à 7 %).

Le menu **Membres** indique ce que chaque membre a rapporté aujourd'hui, sur 7 jours et sur 30 jours.

---

## 📦 Le coffre de guilde

Le coffre permet de ranger des objets en commun. Ouvrez-le avec **`/guild vault`** ou depuis le menu. Chaque page contient 45 emplacements, et votre palier détermine le nombre de pages disponibles (de 2 à 8).

![Coffre de guilde](/img/guilde/guildes-coffre.png)

Le coffre est accessible au **chef**, aux **officiers** et aux **vétérans**. Le même coffre est disponible partout sur le serveur.

---

## 🏠 Le home de guilde

- 📍 **Placer le home** : `/guild sethome` à l'endroit voulu (chef et officiers).
- 🏠 **S'y téléporter** : `/guild home` (tous les membres).
- 🗑️ **Le supprimer** : `/guild delhome`.

Certains mondes ne peuvent pas accueillir de home de guilde : si un message vous l'indique, placez-le ailleurs.

---

## ⚔️ Alliances et chats

Les alliances permettent de rapprocher plusieurs guildes. Le nombre d'alliances possibles dépend de votre palier.

- 🤝 **Proposer une alliance** : `/guild ally add <guilde>`.
- ✅ **Accepter** ou ❌ **refuser** : `/guild ally accept <guilde>` ou `/guild ally decline <guilde>`.
- 💔 **Rompre une alliance** : `/guild ally remove <guilde>`.
- 📋 **Voir vos alliés** : `/guild ally list`.

Les alliances sont gérées par le chef et les officiers.

Deux chats privés sont disponibles :

- 💬 **Chat de guilde** : `/guild gc <message>`, ou `/guild gc` seul pour y basculer.
- 🛡️ **Chat d'alliance** : `/guild ac <message>`, ou `/guild ac` seul pour y basculer.

Dans le chat, écrivez **`#guild`** pour afficher le nom de votre guilde, ou **`#gbank`** pour montrer le solde de sa banque.

---

## 🏆 Classement et options

Utilisez **`/guild list`** pour ouvrir le **classement des guildes**, triées selon leur **score**. Le score est attribué par l'équipe du serveur. `/guild info <guilde>` affiche la fiche publique de n'importe quelle guilde.

Depuis le menu **Options**, le chef peut aussi :

- 🎨 changer le **préfixe** ou le **nom** de la guilde ;
- 🔒 rendre la guilde **publique** ou **privée** (`/guild status`) ;
- 🖼️ choisir l'**emblème** affiché dans le classement : prenez un objet avec votre curseur et déposez-le sur l'emblème (l'objet n'est pas consommé).

---

## ❌ Dissoudre une guilde

Le chef peut dissoudre sa guilde avec `/guild delete`, puis `/guild confirm`.

:::danger Attention
Le **coffre doit être vide** avant de dissoudre la guilde. L'argent restant dans la banque est **reversé au chef**, et toutes les alliances prennent fin.
:::

---

## ⌨️ Récapitulatif des commandes

| Commande | Action |
| --- | --- |
| `/guild` | Ouvrir le menu de votre guilde |
| `/guild help` | Afficher l'aide |
| `/guild create <nom> [préfixe]` | Fonder une guilde |
| `/guild confirm` / `/guild cancel` | Confirmer ou annuler l'action en attente |
| `/guild invite <joueur>` / `/guild uninvite <joueur>` | Inviter un joueur ou retirer l'invitation |
| `/guild accept <guilde>` / `/guild decline <guilde>` | Accepter ou refuser une invitation |
| `/guild leave` | Quitter votre guilde |
| `/guild promote <joueur>` / `/guild demote <joueur>` | Changer le rôle d'un membre |
| `/guild boot <joueur>` | Expulser un membre |
| `/guild transfer <joueur>` | Céder la direction |
| `/guild rename <nom>` / `/guild prefix <préfixe>` | Renommer la guilde ou changer son préfixe |
| `/guild status` | Rendre la guilde publique ou privée |
| `/guild upgrade` | Débloquer le palier suivant |
| `/guild bank <balance\|deposit\|withdraw> [montant]` | Gérer la banque |
| `/guild vault [page]` | Ouvrir le coffre |
| `/guild sethome` / `/guild home` / `/guild delhome` | Gérer le home |
| `/guild ally <add\|accept\|decline\|remove\|list> [guilde]` | Gérer les alliances |
| `/guild gc [message]` / `/guild ac [message]` | Chat de guilde ou d'alliance |
| `/guild list` / `/guild info <guilde>` | Classement et fiche d'une guilde |
| `/guild delete` | Dissoudre la guilde |

:::tip 💡
Toutes ces commandes fonctionnent aussi avec le raccourci **`/g`**, par exemple `/g home`.
:::
