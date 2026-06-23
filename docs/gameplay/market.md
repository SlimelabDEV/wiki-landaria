---
title: 🛒 Markets
description: Créer un market, vendre, acheter et utiliser le menu market.
sidebar_position: 10
---

# 🛒 Markets

Les **markets** sont des boutiques physiques créées sur des **coffres** ou des **tonneaux**.

> Les markets sont aussi souvent appelés **shops** par les joueurs. Sur cette page, les deux mots désignent le même système.

Les items restent dans le coffre du joueur. Le menu `/market` sert à trouver les offres, comparer les prix, filtrer les ventes ou les achats et se rendre aux coffres, mais la transaction utilise toujours le stock réel du market.

---

## 🚀 Ouvrir le menu market

```text
/market
```

Alias possibles :

```text
/shop
/slimeshop
```

Depuis ce menu, vous pouvez chercher un item, filtrer les offres, trier par prix ou stock, consulter vos markets et ouvrir votre historique.

---

## 🔍 Rechercher une offre

```text
/market search <item/pseudo>
```

Exemples :

```text
/market search diamant
/market search Steve
```

La recherche peut servir à trouver un item précis ou les markets d'un joueur.

---

## 🧰 Créer un market

Pour créer un market :

1. Placez un coffre ou un tonneau.
2. Mettez l'item concerné dans votre main.
3. Regardez le coffre ou le tonneau.
4. Lancez une commande de création.

Le prix indiqué est le **prix à l'unité**.

### Market de vente

Un market de vente permet aux joueurs de vous acheter des items.

```text
/market create sell <prix>
```

Exemple :

```text
/market create sell 500
```

Si vous tenez un diamant en main, le market vendra des diamants à 500$ l'unité.

Pour que les joueurs puissent acheter, le coffre doit contenir du stock.

### Market d'achat

Un market d'achat permet aux joueurs de vous vendre des items.

```text
/market create buy <prix>
```

Exemple :

```text
/market create buy 250
```

Si vous tenez du fer en main, le market achètera le fer des joueurs à 250$ l'unité.

Pour que les joueurs puissent vendre, votre solde doit permettre de payer les achats et le coffre doit avoir assez de place.

---

## ➕ Ajouter une offre

Un même coffre market peut contenir plusieurs offres.

```text
/market add <sell|buy> <prix>
```

Exemple :

```text
/market add sell 1000
```

Un coffre market peut contenir jusqu'à **4 offres**. Vous ne pouvez pas ajouter deux fois exactement la même offre avec le même item et le même type.

---

## ⚙️ Gérer son market

Cliquez sur votre coffre market pour ouvrir son menu de gestion.

Depuis ce menu, vous pouvez :

- voir les offres du market ;
- modifier ou retirer des offres ;
- gérer les membres ;
- consulter les informations utiles du coffre.

Pour ouvrir le coffre normalement, accroupissez-vous puis cliquez sur le coffre.

---

## 👥 Membres du market

Vous pouvez ajouter des membres à un market.

Un membre peut aider à gérer le stock du coffre. Selon le réglage choisi, il peut aussi recevoir une part des revenus générés par le market.

Exemple :

- un membre à 20% reçoit 20% des revenus concernés ;
- le propriétaire reçoit le reste ;
- le total des parts des membres ne peut pas dépasser 100%.

Gardez uniquement des joueurs de confiance dans vos markets.

---

## 💰 Acheter ou vendre dans un market

Quand vous cliquez sur une offre :

- une offre de **vente** vous permet d'acheter les items du coffre ;
- une offre d'**achat** vous permet de vendre vos items au coffre.

La transaction peut être refusée si :

- le coffre n'a plus assez de stock ;
- le coffre n'a plus assez de place ;
- votre inventaire est plein ;
- vous n'avez pas assez d'argent ;
- le propriétaire du market n'a pas assez d'argent pour une offre d'achat ;
- le market est déjà utilisé ;
- le stock ou votre inventaire a changé pendant la transaction.

Si une transaction échoue, vérifiez le stock, votre inventaire, votre solde et l'espace disponible dans le coffre.

---

## 📋 Voir ses markets

```text
/market list
```

Cette commande affiche vos markets actifs et permet de retrouver leur position.

Vous pouvez aussi utiliser le bouton **Mes markets** depuis le menu market.

---

## 🧾 Historique

```text
/market history
```

L'historique permet de retrouver vos transactions récentes : achats, ventes, quantités, prix et joueurs concernés.

---

## 📍 Se rendre à un market

Depuis le menu market ou la liste de vos markets, vous pouvez retrouver la position d'un coffre market.

Selon les options disponibles sur le serveur, le menu peut proposer une localisation ou une téléportation vers le market.

---

## 🗑️ Supprimer un market

```text
/market remove
```

Vous devez regarder le coffre market à supprimer.

Supprimer un market retire ses offres du menu market, mais ne vide pas automatiquement le coffre.

---

## ⚠️ Restrictions utiles

- Les markets peuvent être créés uniquement dans les mondes autorisés.
- Les coffres et tonneaux classiques sont prévus pour les markets.
- Certains coffres spéciaux peuvent être bloqués.
- Vous devez regarder le coffre à courte distance pour créer, ajouter ou supprimer une offre.
- Un market sans stock ne peut pas vendre.
- Un market d'achat ne peut pas payer si le propriétaire n'a plus assez d'argent.

---

## 📌 Commandes utiles

| Commande | Utilité |
| --- | --- |
| `/market` | Ouvre le menu market |
| `/market help` | Affiche l'aide |
| `/market create sell <prix>` | Crée un market de vente |
| `/market create buy <prix>` | Crée un market d'achat |
| `/market add sell <prix>` | Ajoute une offre de vente |
| `/market add buy <prix>` | Ajoute une offre d'achat |
| `/market remove` | Supprime le market regardé |
| `/market list` | Affiche vos markets |
| `/market search <item/pseudo>` | Recherche une offre ou un joueur |
| `/market history` | Affiche votre historique |

---

## ✅ Conseils

- Mettez toujours du stock dans vos markets de vente.
- Gardez de la place dans vos markets d'achat.
- Vérifiez votre solde si vous achetez des items aux joueurs.
- Comparez les prix avant d'acheter ou de vendre.
- Retirez les offres inutiles pour garder un market lisible.
