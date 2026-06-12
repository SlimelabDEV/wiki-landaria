---
title: 📈 Maisons & contrats
description: Comprendre les Maisons, les contrats, les participations et les dividendes.
sidebar_position: 1
---

# 📈 Maisons & contrats

Les **Maisons** représentent différents secteurs d'activité en rapport avec les métiers du serveur. Chaque Maison possède son propre budget, sa valeur de participation, ses dividendes et ses contrats.

En participant aux contrats, vous pouvez gagner des **participations**. Ces participations peuvent ensuite être conservées pour recevoir des dividendes réguliers, ou revendues directement contre de l'argent.

:::info
Les Maisons sont un système communautaire : plus les joueurs participent, plus les contrats avancent vite et plus l'économie des Maisons devient active.
:::

## 📖 Ouvrir le menu des Maisons

Pour ouvrir le menu principal des Maisons, utilisez :

```text
/maison
```

Depuis ce menu, vous pouvez consulter les Maisons disponibles, voir vos participations, suivre la valeur des parts, estimer vos dividendes et accéder au menu des contrats.

![Menu des Maisons](/img/maisons/maisons.png)

## 🏠 Les Maisons disponibles

Chaque Maison correspond à un type d'activité du serveur.

| Maison | Activité principale |
| --- | --- |
| **Mineur** | Ressources de minage et blocs de pierre |
| **Bûcheron** | Bois, bûches et tiges |
| **Chasseur** | Ressources de mobs et combat |
| **Fermier** | Cultures, agriculture et élevage |
| **Pêcheur** | Pêche et ressources aquatiques |
| **Armurier** | Équipements, armures et armes |
| **Enchanteur** | Ressources liées à l'enchantement |

:::tip
Vous pouvez participer à plusieurs Maisons. Vos participations sont séparées pour chaque Maison.
:::

## 🤝 Les contrats

Les contrats sont des objectifs communs lancés automatiquement tous les 1h30 par les Maisons.

Quand un contrat est actif, tous les joueurs peuvent contribuer au même objectif en déposant la ressource demandée. Chaque dépôt fait avancer la progression globale du contrat.

Pour ouvrir le menu de dépôt du contrat actif :

```text
/contrat
```

![Menu du contrat](/img/maisons/contrat.png)

Dans ce menu, déposez uniquement la ressource demandée. Les ressources invalides ne sont pas prises en compte.

:::info
Un contrat est un objectif commun : tous les joueurs du serveur peuvent contribuer ensemble pour le terminer.
:::

## 🎯 Participer à un contrat

Pour participer :

1. Ouvrez le menu avec `/contrat`.
2. Regardez la ressource demandée.
3. Déposez cette ressource dans le menu.
4. Votre contribution est ajoutée au contrat.
5. Si le contrat est terminé, un classement est affiché.

Plus vous contribuez, plus votre part dans les récompenses du contrat peut être importante.

## 🏆 Fin de contrat et classement

Quand un contrat est terminé, le serveur affiche un classement des participants.

Le classement indique :

- les joueurs qui ont participé ;
- la quantité de ressources déposées ;
- les participations gagnées ;
- la Maison concernée par le contrat.

![Classement de contrat](/img/maisons/classement.png)

:::tip
Après un contrat, vous pouvez garder vos participations pour recevoir des dividendes, ou les vendre pour gagner de l'argent directement.
:::

## 🕋 Les participations

Les participations représentent votre part dans une Maison.

Elles servent à deux choses :

- recevoir des dividendes réguliers ;
- être revendues contre de l'argent.

Chaque Maison possède sa propre valeur de participation. Par exemple, vos participations dans la Maison Mineur sont séparées de celles de la Maison Chasseur.

## 💰 Les dividendes

Si vous conservez vos participations, vous pouvez recevoir des dividendes.

Les dividendes dépendent du budget de la Maison et du nombre de participations en circulation. Plus une Maison possède un budget élevé, plus les dividendes peuvent être intéressants.

Dans le menu des Maisons, vous pouvez voir :

- le prix d'une participation ;
- le budget de la Maison ;
- les dividendes estimés par participation ;
- vos participations ;
- votre valeur de vente ;
- vos dividendes estimés.

![Informations d'une Maison](/img/maisons/maison.png)

## 💸 Vendre ses participations

Si vous préférez récupérer de l'argent directement, vous pouvez vendre vos participations.

Pour vendre une quantité précise :

```text
/maison sell <maison> <nombre>
```

Pour vendre toutes vos participations d'une Maison :

```text
/maison sell <maison> all
```

Exemple :

```text
/maison sell chasseur all
```

:::warning
Vendre vos participations vous donne de l'argent immédiatement, mais vous ne recevrez plus de dividendes sur les participations vendues.
:::

## 📋 Commandes utiles

| Commande | Utilité |
| --- | --- |
| `/maison` | Ouvre le menu principal des Maisons |
| `/contrat` | Ouvre le menu du contrat actif |
| `/maison list` | Affiche les Maisons et vos participations |
| `/maison house <maison>` | Affiche les informations d'une Maison |
| `/maison sell <maison> <nombre>` | Vend une quantité de participations |
| `/maison sell <maison> all` | Vend toutes vos participations d'une Maison |

## ✅ Bonnes pratiques

- Participez aux contrats des Maisons qui vous intéressent.
- Gardez vos participations si vous voulez recevoir des dividendes.
- Vendez vos participations si vous voulez de l'argent immédiatement.
- Regardez le budget et les dividendes avant de vendre.
- Utilisez `/contrat` régulièrement pour voir si un objectif commun est actif.
- Contribuez avec les autres joueurs pour terminer les contrats plus vite.

## 👷 Métiers personnels et Maisons (en développement)

![dev](https://i.ebayimg.com/images/g/nvQAAOSwmVZjD3HB/s-l1200.png)

Les **Maisons** et les **métiers personnels** sont actuellement deux systèmes distincts.

Les métiers personnels permettent de gagner de l'argent en réalisant différentes activités sur le serveur, tandis que les Maisons reposent sur les contrats, les participations et les dividendes.

Par exemple :

- vous pouvez exercer le métier de Mineur sans posséder de participations dans la Maison Mineur ;
- vous pouvez posséder des participations dans la Maison Pêcheur sans pratiquer la pêche ;
- les contrats sont ouverts à tous les joueurs, quel que soit leur métier favori.

Les Maisons représentent avant tout un système économique communautaire. Les métiers personnels restent quant à eux un moyen de générer des revenus grâce à vos activités.

:::info
Pour le moment, les Maisons et les métiers personnels sont indépendants l'un de l'autre. Participer à une Maison ne modifie pas les gains de votre métier, et exercer un métier ne vous accorde pas automatiquement de participations dans une Maison.
:::

