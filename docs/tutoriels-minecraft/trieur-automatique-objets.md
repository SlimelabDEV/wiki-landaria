---
title: 🧮 Trieur automatique d’objets Minecraft
description: "Construisez un trieur automatique Minecraft avec entonnoirs, comparateurs et filtres stables pour ranger les objets empilables."
sidebar_position: 10
---

# 🧮 Trieur automatique d’objets Minecraft

Un trieur automatique dirige chaque objet empilable vers le coffre correspondant. Il devient utile lorsqu'une ferme produit plusieurs ressources ou lorsque le stockage principal reçoit trop d'objets pour être rangé à la main.

Le filtre classique utilise un entonnoir verrouillé par redstone. Lorsqu'un objet correspondant arrive, le signal augmente juste assez pour déverrouiller le transfert sans vider les objets de réglage.

## 🧰 Matériel nécessaire

- Des coffres ou tonneaux
- Plusieurs entonnoirs
- Des comparateurs
- Des répéteurs
- De la poudre de redstone
- Des torches de redstone
- Des objets de filtre renommés et non utilisés ailleurs

## 🛠️ Construire un module de filtre

1. Placez le coffre de destination et reliez un entonnoir à son arrière.
2. Posez au-dessus un entonnoir de filtre orienté latéralement, pas vers le coffre.
3. Installez un comparateur qui lit le contenu de cet entonnoir.
4. Construisez le circuit avec poudre, répéteur et torche pour verrouiller l'entonnoir inférieur.
5. Placez l'objet à trier dans le premier emplacement du filtre.
6. Remplissez les autres emplacements avec des objets renommés servant uniquement de cales.
7. Envoyez une petite série d'objets dans la ligne supérieure et vérifiez qu'aucun filtre voisin ne se vide.

## ⚙️ Étendre le tri sans casser les filtres

Copiez un module validé en conservant exactement l'orientation des entonnoirs et composants. Une rotation involontaire suffit à envoyer tous les objets dans le mauvais coffre.

Prévoyez un coffre de débordement à la fin de la ligne. Les objets non filtrés, non empilables ou arrivant dans une colonne pleine doivent conserver une destination accessible.

## ⚠️ Problèmes courants

### Tous les objets passent dans le dernier coffre

Le filtre n'est pas correctement configuré ou l'entonnoir supérieur pointe vers le bas. Revérifiez les orientations et le niveau de signal.

### Un filtre se vide dans le voisin

Les objets de cale ne sont pas uniques ou le signal devient trop puissant. Utilisez des objets renommés et respectez la quantité du modèle testé.

### Les objets non empilables bloquent la ligne

Séparez-les avant le trieur ou laissez-les partir vers le coffre de débordement.

## ✅ À retenir

Un trieur fiable commence par un seul module testé avec plusieurs piles. Utilisez des objets de cale uniques, ajoutez un débordement et ne dupliquez le circuit qu'après avoir validé les signaux.

Poursuivez avec [le stockage en silos](/docs/tutoriels-minecraft/stockage-silos) et [le guide du comparateur](/docs/tutoriels-minecraft/guide-comparateur-redstone), ou revenez à la liste des [tutoriels Minecraft](/docs/tutoriels-minecraft).

## 🌍 Rejoindre Landaria

Vous cherchez un serveur Minecraft francophone pour mettre ce tutoriel en pratique ? Rejoignez **Landaria** et découvrez une économie entre joueurs, des métiers, des systèmes de progression, des quêtes, des donjons et de nombreux projets techniques.

**Adresse du serveur :** `go.landaria.fr`

Retrouvez les commandes et les systèmes propres au serveur dans le [wiki officiel de Landaria](/docs/bienvenue).
