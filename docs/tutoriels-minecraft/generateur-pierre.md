---
title: 🪨 Générateur de pierre automatique Minecraft
description: "Construisez un générateur de pierre Minecraft avec eau, lave et piston sans transformer accidentellement vos sources en obsidienne."
sidebar_position: 24
---

# 🪨 Générateur de pierre automatique Minecraft

Un générateur de pierre renouvelle un bloc solide à chaque contact contrôlé entre l'eau et la lave. Il fournit de la pierre pour la construction sans creuser une grande carrière.

La disposition des sources détermine si le résultat devient pierre, cobblestone ou obsidienne. Il faut donc tester une cellule protégée avant d'ajouter des pistons ou plusieurs points de génération.

## 🧰 Matériel nécessaire

- Un seau d’eau
- Un seau de lave
- Des blocs non inflammables
- Un piston
- Un observateur ou une horloge lente
- De la redstone
- Un bouton d’arrêt

## 🛠️ Créer une cellule de génération protégée

1. Construisez un bac en blocs non inflammables avec une sortie pour le bloc produit.
2. Placez la source d'eau dans un compartiment où elle ne peut pas atteindre directement la lave.
3. Ajoutez la source de lave dans le compartiment opposé.
4. Ouvrez un seul point de contact et observez le bloc généré.
5. Corrigez la hauteur ou le sens des flux si le résultat n'est pas de la pierre.
6. Placez un piston derrière la cellule pour pousser chaque nouveau bloc.
7. Reliez le piston à un observateur ou une horloge lente avec une commande d'arrêt.

## ⚙️ Pousser les blocs sans bloquer la machine

Les pistons ne déplacent qu'un nombre limité de blocs. Ajoutez une zone de récolte ou un mécanisme qui casse la rangée avant qu'elle atteigne cette limite.

Protégez les deux sources derrière des blocs fixes. La pioche du joueur ne doit jamais pouvoir viser la lave ou ouvrir un passage d'eau pendant la récolte.

## ⚠️ Problèmes courants

### Le générateur produit de la cobblestone

La lave et l'eau se rencontrent dans une configuration différente de celle prévue. Ajustez la hauteur et vérifiez quel flux atteint la cellule.

### La lave devient obsidienne

L'eau touche directement une source de lave. Fermez le mécanisme, remplacez la source et corrigez le point de contact.

### Le piston ne pousse plus

La rangée a atteint sa limite ou le signal arrive avant la formation du bloc. Videz la sortie et augmentez le délai.

## ✅ À retenir

Un générateur de pierre fiable protège ses sources, crée le bloc dans une seule cellule et pousse à un rythme raisonnable. Validez le matériau obtenu avant toute duplication du module.

Poursuivez avec [le générateur de basalte](/docs/tutoriels-minecraft/generateur-basalte) et [le guide de l'observateur](/docs/tutoriels-minecraft/guide-observateur-redstone), ou revenez à la liste des [tutoriels Minecraft](/docs/tutoriels-minecraft).

## 🌍 Rejoindre Landaria

Vous cherchez un serveur Minecraft francophone pour mettre ce tutoriel en pratique ? Rejoignez **Landaria** et découvrez une économie entre joueurs, des métiers, des systèmes de progression, des quêtes, des donjons et de nombreux projets techniques.

**Adresse du serveur :** `go.landaria.fr`

Retrouvez les commandes et les systèmes propres au serveur dans le [wiki officiel de Landaria](/docs/bienvenue).
