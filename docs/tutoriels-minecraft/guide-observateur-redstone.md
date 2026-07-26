---
title: 👁️ Utiliser un observateur redstone Minecraft
description: "Comprenez l’observateur Minecraft, son sens de pose et son impulsion pour détecter cultures, blocs et changements dans vos machines."
sidebar_position: 32
---

# 👁️ Utiliser un observateur redstone Minecraft

L'observateur détecte une mise à jour du bloc placé devant son visage et produit une courte impulsion par le point rouge situé à l'arrière. Il est très utilisé dans les fermes à canne à sucre, bambou, citrouilles et dans les générateurs à pistons.

Son orientation est la première source d'erreur. Le visage regarde le bloc surveillé, tandis que le point rouge doit faire face au circuit ou au piston.

## 🧰 Matériel nécessaire

- Des observateurs
- Une lampe de redstone
- De la poudre de redstone
- Un piston
- Des blocs de test
- Une culture ou un mécanisme à surveiller
- Un levier d’arrêt pour la machine finale

## 🛠️ Tester le sens de détection

1. Placez une lampe à l'emplacement où vous voulez recevoir l'impulsion.
2. Posez l'observateur avec son point rouge tourné vers la lampe.
3. Modifiez le bloc situé devant le visage de l'observateur.
4. Vérifiez que la lampe s'allume brièvement.
5. Ajoutez un piston à la sortie pour observer la durée réelle de l'impulsion.
6. Déplacez le bloc surveillé jusqu'à détecter uniquement le changement utile.
7. Ajoutez une commande d'arrêt avant de relier plusieurs observateurs.

## ⚙️ Éviter les boucles de mises à jour

Un piston déclenché peut modifier le bloc observé et provoquer une seconde impulsion. Séparez le capteur du mouvement ou ajoutez un délai lorsque ce double signal n'est pas souhaité.

N'alignez pas de nombreux observateurs face à face sans raison. Les mises à jour rapides peuvent créer une horloge bruyante et inutile.

## ⚠️ Problèmes courants

### Aucun signal ne sort

L'observateur regarde probablement dans le mauvais sens. Le point rouge est la sortie, pas la zone de détection.

### Le piston s'active deux fois

Le mouvement du piston crée une nouvelle mise à jour observée. Décalez le capteur ou filtrez les impulsions.

### La machine reste active en permanence

Une boucle de blocs se met à jour mutuellement. Coupez l'alimentation, isolez chaque observer et reconnectez-les un par un.

## ✅ À retenir

L'observateur possède un visage de détection et un point rouge de sortie. Testez cette orientation avec une lampe, puis surveillez les doubles impulsions avant de l'intégrer à une ferme.

Poursuivez avec [le générateur de pierre](/docs/tutoriels-minecraft/generateur-pierre) et [l'horloge redstone](/docs/tutoriels-minecraft/horloge-redstone-minecraft), ou revenez à la liste des [tutoriels Minecraft](/docs/tutoriels-minecraft).

## 🌍 Rejoindre Landaria

Vous cherchez un serveur Minecraft francophone pour mettre ce tutoriel en pratique ? Rejoignez **Landaria** et découvrez une économie entre joueurs, des métiers, des systèmes de progression, des quêtes, des donjons et de nombreux projets techniques.

**Adresse du serveur :** `go.landaria.fr`

Retrouvez les commandes et les systèmes propres au serveur dans le [wiki officiel de Landaria](/docs/bienvenue).
