---
sidebar_position: 4
---

# 💫 Guilde

**Une guilde** est une communauté regroupée autour d’une survie et régie par une organisation hiérarchique, tel qu'un chef, des officiers, les membres de guilde ainsi que les recrues.

---

## 🎨 Code couleurs et style

En ce qui concerne les couleurs, aucune restriction ne vous est imposée. Vous pouvez donc mettre plusieurs couleurs, comme bon vous semble.

:::tip Important
Toutefois, le code _Magic_ est **interdit**. Dans le cas où vous l'utiliseriez, il vous sera demandé de modifier votre préfixe de guilde.  
En cas de refus, une sanction et une suppression de la guilde peuvent être engendrées.
:::

---

## 🛠️ Créer une guilde

Il faut tout d'abord posséder le grade **Titan**, qui est le seul grade permettant les créations de guilde.

Utilisez la commande suivante pour créer une guilde :

```bash
/guilds create <nom>
```

Ensuite, pour valider ou annuler, faites :

```bash
/guilds confirm
```

ou

```bash
/guilds cancel
```

---

## ❓ Difficulté à créer votre guilde ?

:::info ℹ️
Si un message d'erreur s'affiche lorsque vous essayez de créer une guilde :
:::

- **Vérifiez que vous n'utilisez pas de caractères spéciaux** : Les caractères spéciaux ne sont pas acceptés et peuvent bloquer la création.
- **Vérifiez que le nom choisi n'est pas trop long** : Si c'est le cas, suivez ces étapes :

1. Créez votre guilde avec un nom plus court, par exemple :
   ```bash
   /g create Redstone
   ```
2. Validez avec :
   ```bash
   /g confirm
   ```
3. Modifiez le préfixe avec :
   ```bash
   /g prefix RedstoneTorchElec
   ```

---

## ❌ Supprimer une guilde

Pour supprimer votre guilde, utilisez cette commande :

```bash
/g delete
```

Confirmez ou annulez avec :

```bash
/g confirm
```

ou

```bash
/g cancel
```

---

## 🤝 Inviter quelqu'un dans une guilde

Pour inviter quelqu'un, utilisez la commande suivante :

```bash
/g invite <pseudo>
```

Le joueur invité doit accepter avec :

```bash
/g join <NomDeLaGuilde>
```

ou

```bash
/g accept <NomDeLaGuilde>
```

---

## ⚔️ Quels sont les avantages ?

:::tip 🏆
Créer une guilde vous permet de montrer votre coopération avec vos amis, de former un groupe de joueurs économiquement ou en combat.
:::

Vous pouvez également activer un chat privé entre les membres avec :

```bash
/g chat
```

Désactivez-le avec la même commande.

---

## 📈 Promouvoir et rétrograder

En tant que chef, vous pouvez gérer la hiérarchie de votre guilde.

**Rangs disponibles :**
- Chef 👑
- Officier 🛡️
- Membre 👥
- Recrue 🎓

Pour promouvoir un joueur, utilisez :

```bash
/g promote <pseudo>
```

Pour rétrograder un joueur, utilisez :

```bash
/g demote <pseudo>
```

Pour expulser un joueur, utilisez :

```bash
/g kick <pseudo>
```

---

## 🏠 Gérer le spawn de la guilde

Pour définir un home de guilde, placez-vous à l'endroit souhaité et utilisez :

```bash
/g sethome
```

Supprimez-le avec :

```bash
/g delhome
```

Téléportez-vous au home de guilde avec :

```bash
/g home
```

---

## 📋 Les informations de guilde

Utilisez la commande suivante pour afficher les infos de votre guilde :

```bash
/g info
```

Vous verrez :
- **Le lingot d'or 🪙** : indique la somme dans la banque.
- **Le casque en fer ⛑️** : affiche les membres et leurs connexions.
- **L'émeraude 💎** : montre le statut (public/privé).
- **Le lit 🛏️** : home de guilde.
- **Le coffre 🧰** : stockage commun.

---

## 🚀 Upgrade sa guilde

Vous pouvez augmenter le niveau de votre guilde pour plus d'avantages :

- **Augmentation du nombre de membres**.
- **Accès à plus de coffres de guilde**.

Pour upgrader, déposez la somme nécessaire avec :

```bash
/g bank deposit <somme>
```

Puis faites :

```bash
/g upgrade
/g confirm
```

### 📈 Passage au niveau 2
- Somme : 25.000 $
- 5 membres max.

### 📈 Passage au niveau 3
- Somme : 50.000 $
- 10 membres max.

### 📈 Passage au niveau 4
- Somme : 75.000 $
- 15 membres max.

### 📈 Passage au niveau 5
- Somme : 100.000 $
- 25 membres max.

---

## 🔧 Commandes

Voici quelques commandes pratiques :

- `/g bank balance` → Affiche l'argent de la guilde.
- `/g bank deposit <montant>` → Dépose de l'argent dans la banque.
- `/g bank withdraw <montant>` → Retire de l'argent.
- `/g vault` → Ouvre le coffre commun.
- `/g status` → Change le statut (public/privé).
- `/g list` → Liste des guildes.

:::tip
Toutes les commandes peuvent être abrégées avec `/g`.
:::
