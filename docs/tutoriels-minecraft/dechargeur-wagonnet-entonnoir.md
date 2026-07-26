---
title: 🚋 Déchargeur automatique de wagonnet à entonnoir Minecraft
description: "Arrêtez un wagonnet à entonnoir Minecraft, videz son contenu dans un coffre puis relancez-le automatiquement sur les rails."
sidebar_position: 15
---

# 🚋 Déchargeur automatique de wagonnet à entonnoir Minecraft

Un déchargeur automatique reçoit un wagonnet à entonnoir, le maintient au-dessus d'un entonnoir puis le relance quand il est vide. Il relie facilement une mine, une ferme mobile ou une collecte sous grande surface au stockage principal.

Le circuit utilise un comparateur pour lire le wagonnet et un rail propulseur dont l'état change selon la présence d'objets. Il doit être testé avec des charges partielles et complètes.

## 🧰 Matériel nécessaire

- Un wagonnet à entonnoir
- Des rails et un rail propulseur
- Un entonnoir
- Un coffre ou tonneau
- Un comparateur
- Une torche de redstone
- De la poudre et un répéteur facultatif

## 🛠️ Construire la station de déchargement

1. Placez le coffre de sortie et reliez un entonnoir sur le dessus.
2. Posez un rail au-dessus de l'entonnoir pour accueillir le wagonnet.
3. Installez un rail propulseur à la sortie de la station.
4. Ajoutez un bloc d'arrêt afin que le wagonnet reste immobile pendant le transfert.
5. Placez le comparateur afin qu'il lise l'entonnoir de déchargement.
6. Reliez ce signal à une torche qui coupe le rail propulseur tant que l'entonnoir transfère des objets.
7. Testez la station avec une pile, puis avec un wagonnet presque plein.

## ⚙️ Relancer le wagonnet au bon moment

Le rail de sortie doit recevoir l'impulsion seulement lorsque le wagonnet est vide. Un répéteur peut stabiliser le signal si le départ se produit trop tôt.

Inclinez la voie d'arrivée ou ajoutez un rail propulseur avant la station pour garantir que le wagonnet atteint toujours le point d'arrêt.

## ⚠️ Problèmes courants

### Le wagonnet repart avec des objets

Le comparateur lit le mauvais conteneur ou le rail reste alimenté. Revérifiez le sens du circuit et allongez le délai.

### Le wagonnet ne repart jamais

Vérifiez que le coffre de sortie n'est pas plein et que le rail propulseur reçoit un signal lorsque la station devient vide.

### Le wagonnet rebondit avant l'entonnoir

Réduisez sa vitesse d'arrivée, déplacez le bloc d'arrêt et testez le sens de la pente.

## ✅ À retenir

Un bon déchargeur immobilise le wagonnet jusqu'au dernier objet, puis le relance avec un rail propulseur. Testez plusieurs niveaux de remplissage et prévoyez un coffre de sortie assez grand.

Poursuivez avec [la collecte par wagonnet à entonnoir](/docs/tutoriels-minecraft/collecte-wagonnet-entonnoir) et [la super fonderie](/docs/tutoriels-minecraft/super-fonderie-minecraft), ou revenez à la liste des [tutoriels Minecraft](/docs/tutoriels-minecraft).

## 🌍 Rejoindre Landaria

Vous cherchez un serveur Minecraft francophone pour mettre ce tutoriel en pratique ? Rejoignez **Landaria** et découvrez une économie entre joueurs, des métiers, des systèmes de progression, des quêtes, des donjons et de nombreux projets techniques.

**Adresse du serveur :** `go.landaria.fr`

Retrouvez les commandes et les systèmes propres au serveur dans le [wiki officiel de Landaria](/docs/bienvenue).
