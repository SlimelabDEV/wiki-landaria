---
title: 📈 Maisons & contrats
description: Comprendre les Maisons, les contrats, les participations, le budget et les dividendes.
sidebar_position: 1
---

# 📈 Maisons & contrats

Les **Maisons** sont un système économique communautaire. Chaque Maison représente une activité du serveur : minage, agriculture, pêche, chasse, bois, équipement ou enchantement.

En participant aux contrats, vous gagnez des **participations** dans une Maison. Ces participations peuvent ensuite être conservées pour toucher des **dividendes**, ou revendues contre de l'argent si la Maison possède assez de budget.

:::info
Les Maisons ne sont pas des métiers personnels. Tout le monde peut participer à un contrat, même sans exercer le métier correspondant.
:::

## 🧭 Résumé rapide

- Un seul contrat de Maison peut être actif à la fois.
- Un nouveau contrat apparaît régulièrement, environ toutes les **78 minutes** après le précédent.
- Un contrat dure au maximum **20 minutes**.
- Si le contrat est terminé, les participants gagnent des participations.
- Si le contrat expire avant d'être terminé, aucune participation n'est distribuée.
- Une Maison gagne du budget quand son contrat est terminé.
- Le budget sert ensuite à payer les dividendes et à racheter les participations vendues par les joueurs.

---

## 📖 Ouvrir le menu des Maisons

Pour ouvrir le menu principal :

```text
/maison
```

Depuis ce menu, vous pouvez consulter les Maisons, le prix d'une participation, la caisse de chaque Maison et vos participations.

![Menu des Maisons](/img/maisons/maisons.png)

Vous pouvez aussi utiliser :

```text
/maison list
/maison house <maison>
```

---

## 🏠 Les Maisons disponibles

Chaque Maison possède sa propre caisse, ses propres participations et ses propres contrats.

| Maison | Clé à utiliser | Ressources possibles |
| --- | --- | --- |
| **Maison des Mineurs** | `mineur` | Roche, pierre, granite, diorite, andésite, netherrack, pierre de l'End, pierre des abîmes, ardoise des abîmes, spéléothèmes, éclats d’améthyste, émeraudes, basalte... |
| **Maison des Fermiers** | `fermier` | Blé, carottes, pommes de terre, betteraves, bambou, cactus, cuir, blocs de mousse, planturnes, baies lumineuses, blocs/rayons de miel, roses de Wither, fleurs, pastèques, œufs. |
| **Maison des Pêcheurs** | `pecheur` | Morues, saumons, nénuphars, poches d'encre, ficelles, poissons tropicaux, morues cuites, saumons cuits... |
| **Maison des Bûcherons** | `bucheron` | Bûches de chêne, sapin, bouleau, acajou, acacia, mangrove, cerisier, feuilles, lianes, blocs de bambou... |
| **Maison des Chasseurs** | `chasseur` | Viandes crues, os, chair putréfiée, poudre à canon, bâtons de blaze, viandes cuites, plumes, peaux/pattes de lapin, éclats/cristaux de prismarine, flèches... |
| **Maison des Armuriers** | `armurier` | Épées, bottes, casques, plastrons et jambières en cuir, fer, or ou diamant |
| **Maison des Enchanteurs** | `enchanteur` | Cuir, papier, lapis-lazuli, poudre lumineuse, poudre de blaze, perles de l'Ender, livres et fioles d'expérience. |

:::tip
Vos participations sont séparées par Maison. Avoir des participations chez les Mineurs ne donne rien chez les Chasseurs, et inversement.
:::

---

## 🤝 Fonctionnement des contrats

Un contrat demande à tous les joueurs de livrer une ressource précise pour une Maison précise.

Exemple : la Maison des Mineurs peut demander de la roche, tandis que la Maison des Fermiers peut demander du blé ou des carottes.

Pour participer :

1. Attendez qu'un contrat soit actif.
2. Ouvrez le menu avec `/contrat`.
3. Regardez la ressource demandée.
4. Déposez uniquement cette ressource dans le menu.
5. Votre contribution est ajoutée au total du contrat.

![Menu du contrat](/img/maisons/contrat.png)

:::warning
Le menu accepte uniquement la ressource demandée par le contrat actif. Les autres objets ne comptent pas.
:::

Si vous déposez plus que ce qu'il reste à fournir, seul le nécessaire est accepté. Le surplus est rendu dans votre inventaire, ou tombe au sol si votre inventaire est plein.

---

## 🎯 Objectifs des contrats

L'objectif dépend de la Maison sélectionnée.

| Maison | Objectif possible |
| --- | --- |
| Mineurs | entre **50 000** et **100 000** ressources |
| Fermiers | entre **25 000** et **75 000** ressources |
| Pêcheurs | entre **1 000** et **5 000** ressources |
| Bûcherons | entre **25 000** et **75 000** ressources |
| Chasseurs | entre **25 000** et **75 000** ressources |
| Armuriers | entre **500** et **2 000** ressources |
| Enchanteurs | entre **25 000** et **75 000** ressources |

La ressource et l'objectif exact changent à chaque contrat.

---

## 🏆 Fin de contrat et classement

Quand l'objectif est atteint, le contrat se termine et un classement est affiché.

Le classement montre :

- les joueurs qui ont participé ;
- la quantité de ressources déposées ;
- les participations gagnées ;
- la Maison concernée ;
- la ressource demandée.

![Classement de contrat](/img/maisons/classement.png)

Les participations sont réparties selon la contribution de chacun. Plus vous avez contribué dans le contrat, plus votre part de la récompense est élevée.

---

## 🕋 Les participations

Les **participations** représentent vos parts dans une Maison.

Elles servent à deux choses :

- toucher des dividendes réguliers ;
- être vendues contre de l'argent.

Chaque Maison possède son propre prix de participation. Le prix commence bas, puis peut augmenter progressivement quand beaucoup de participations sont conservées par les joueurs.

:::tip
Un contrat distribue une récompense globale convertie en participations. Si le prix d'une participation est bas, le contrat distribue plus de participations. Si le prix est plus élevé, il en distribue moins.
:::

---

## 💰 Budget des Maisons

Chaque Maison possède une **caisse**, aussi appelée budget.

La caisse augmente quand un contrat de cette Maison est terminé. Un contrat terminé ajoute environ **11 000$** au budget de la Maison.

Cette caisse sert ensuite à deux choses :

- payer les dividendes aux joueurs qui gardent leurs participations ;
- racheter les participations quand un joueur utilise `/maison sell`.

:::warning
Si une Maison n'a plus assez de budget, elle ne peut pas tout payer. Les dividendes deviennent très faibles ou nuls, et la vente de participations peut être refusée si la caisse ne contient pas assez d'argent.
:::

---

## 💸 Les dividendes

Les dividendes sont versés environ toutes les **heures** aux joueurs qui possèdent encore des participations.

Le montant dépend de trois éléments :

- le budget actuel de la Maison ;
- le nombre total de participations conservées par les joueurs ;
- votre nombre de participations dans cette Maison.

En pratique, la Maison utilise une petite partie de sa caisse pour calculer le paiement par participation. Plus la Maison a de budget, plus le dividende par participation peut monter. Plus il y a de participations en circulation, plus ce montant est partagé entre les joueurs.

Exemple simplifié :

- une Maison possède **11 000$** de budget ;
- elle a **10 000** participations en circulation ;
- le dividende estimé est d'environ **0,011$ par participation** ;
- un joueur avec **500** participations reçoit environ **5,50$** lors du versement.

Après le paiement, l'argent versé est retiré de la caisse de la Maison.

![Informations d'une Maison](/img/maisons/maison.png)

---

## 💵 Vendre ses participations

Si vous préférez récupérer de l'argent immédiatement, vous pouvez vendre vos participations.

Vendre une quantité précise :

```text
/maison sell <maison> <nombre>
```

Vendre toutes vos participations d'une Maison :

```text
/maison sell <maison> all
```

Exemple :

```text
/maison sell chasseur all
```

Le montant reçu dépend du prix actuel de la participation dans cette Maison.

:::warning
La vente utilise la caisse de la Maison. Si la Maison n'a pas assez de budget pour racheter vos participations, la vente ne peut pas se faire pour ce montant.
:::

Vendre vos participations donne de l'argent tout de suite, mais vous ne toucherez plus de dividendes sur les participations vendues.

---

## 📋 Commandes utiles

| Commande | Utilité |
| --- | --- |
| `/maison` | Ouvre le menu principal des Maisons |
| `/contrat` | Ouvre le menu du contrat actif |
| `/maison list` | Affiche les Maisons, les prix, les budgets et vos participations |
| `/maison house <maison>` | Affiche les détails d'une Maison |
| `/maison sell <maison> <nombre>` | Vend une quantité de participations |
| `/maison sell <maison> all` | Vend toutes vos participations d'une Maison |

---

## ✅ Conseils

- Consultez régulièrement `/contrat` pour ne pas manquer un contrat actif.
- Gardez des participations si vous voulez recevoir des dividendes sur la durée.
- Vendez des participations si vous voulez récupérer de l'argent immédiatement.
- Regardez toujours la caisse d'une Maison avant de vendre beaucoup de participations.
- Les contrats terminés renforcent la caisse de la Maison, donc ils profitent aussi aux joueurs qui gardent leurs participations.
- Participer à plusieurs Maisons permet de diversifier vos sources de dividendes.

---

## 👷 Maisons et métiers personnels

Les Maisons et les métiers personnels sont deux systèmes séparés.

Vous pouvez très bien :

- miner sans posséder de participations chez les Mineurs ;
- posséder des participations chez les Pêcheurs sans pêcher ;
- participer à un contrat de Maison même si ce n'est pas votre activité principale.

Les métiers servent à gagner de l'argent avec vos activités personnelles. Les Maisons servent surtout aux contrats communautaires, aux participations, aux budgets et aux dividendes.
