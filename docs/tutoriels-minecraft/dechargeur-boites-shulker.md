---
title: 📤 Déchargeur automatique de boîtes de Shulker Minecraft
description: "Videz automatiquement une boîte de Shulker Minecraft dans votre stockage puis récupérez la boîte vide avec un circuit contrôlé."
sidebar_position: 19
---

# 📤 Déchargeur automatique de boîtes de Shulker Minecraft

Un déchargeur de Shulker reçoit une boîte pleine, la place devant un distributeur et extrait son contenu avec des entonnoirs. Lorsque la boîte est vide, un piston la casse pour qu'elle puisse être réutilisée.

Le mécanisme doit distinguer le contenu extrait de la boîte vide. Il est particulièrement utile à l'entrée d'un entrepôt ou après un chantier transportant de grandes quantités de blocs.

## 🧰 Matériel nécessaire

- Un distributeur
- Un piston
- Des entonnoirs
- Des coffres pour entrée et sortie
- Un comparateur
- Des répéteurs et poudre de redstone
- Une collecte réservée aux boîtes vides

## 🛠️ Placer, vider puis récupérer la boîte

1. Orientez le distributeur vers l'emplacement de la boîte.
2. Reliez un coffre d'entrée contenant les boîtes pleines.
3. Placez un entonnoir sous la future boîte pour extraire son contenu.
4. Dirigez les objets vers un coffre tampon ou un trieur.
5. Utilisez un comparateur pour détecter quand la boîte ne contient plus rien.
6. Déclenchez alors le piston afin de casser la boîte.
7. Récupérez la boîte vide dans une ligne séparée avant de placer la suivante.

## ⚙️ Relier le déchargeur au stockage principal

La sortie peut alimenter un trieur automatique, mais son débit doit accepter celui de l'entonnoir. Ajoutez plusieurs coffres tampons pour éviter qu'une ressource pleine bloque toute la machine.

Conservez une commande manuelle permettant de suspendre le placement de nouvelles boîtes pendant la maintenance du stockage.

## ⚠️ Problèmes courants

### La boîte est cassée avant d'être vide

Le comparateur lit le mauvais bloc ou le délai est trop court. Vérifiez le signal avec une boîte contenant plusieurs piles différentes.

### Les boîtes vides partent dans le trieur

Séparez leur point de chute de la ligne d'objets et utilisez une collecte dédiée.

### Une nouvelle boîte ne peut pas être posée

L'ancienne n'a pas été récupérée ou un objet reste dans la cellule. Nettoyez la zone et ajustez le piston.

## ✅ À retenir

Le déchargeur doit attendre le dernier objet, récupérer la boîte vide séparément et protéger le stockage contre la saturation. Validez tout le cycle avec plusieurs contenus avant de l'automatiser.

Poursuivez avec [le chargeur de boîtes de Shulker](/docs/tutoriels-minecraft/chargeur-boites-shulker) et [le trieur automatique](/docs/tutoriels-minecraft/trieur-automatique-objets), ou revenez à la liste des [tutoriels Minecraft](/docs/tutoriels-minecraft).

## 🌍 Rejoindre Landaria

Vous cherchez un serveur Minecraft francophone pour mettre ce tutoriel en pratique ? Rejoignez **Landaria** et découvrez une économie entre joueurs, des métiers, des systèmes de progression, des quêtes, des donjons et de nombreux projets techniques.

**Adresse du serveur :** `go.landaria.fr`

Retrouvez les commandes et les systèmes propres au serveur dans le [wiki officiel de Landaria](/docs/bienvenue).
