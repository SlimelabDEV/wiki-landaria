---
description: "Découvrez l'hôtel des ventes de Landaria pour acheter, mettre en vente, rechercher et récupérer des objets entre joueurs."
sidebar_position: 9
---

# 🏡 Hôtel des ventes

**L'hôtel des ventes** permet à tous les joueurs de vendre et d'acheter des items.

Chaque joueur peut vendre ses items dans l'hôtel des ventes au prix qu'il le souhaite. À l'inverse, il peut également acheter les items mis en vente par d'autres joueurs au prix choisi par ceux-ci.

L'hôtel des ventes n'est donc pas une vente aux enchères, mais bien un système de vente à part entière à distinguer des coffres de vente.

### Exemple 📝 :

Je décide de mettre ma pioche extra 6 en vente lundi à 13h30. Si personne ne l'achète, l'annonce expire jeudi à 13h30 et la pioche rejoint **Items expirés**. J'ai alors **6 jours supplémentaires** pour la récupérer dans ce menu avant sa suppression.

---

## 🔍 Principe

Si vous voulez vendre vos items dans l'hôtel des ventes, il vous faudra d'abord observer les prix pratiqués par les autres joueurs. 🪙 Si vous vendez vos items trop chers, vous ne trouverez probablement pas d'acheteurs. Mais si vous vendez vos items à prix réduit, ils seront sûrement vendus, mais vous ne profiterez pas pleinement de leur valeur.

📈 Observez régulièrement l'hôtel des ventes ainsi que les objets qui y sont vendus pour vous faire une idée précise de la valeur de vos items.

🕒 Tout item mis en vente reste disponible pendant **72 heures (3 jours)**. S'il n'a pas trouvé preneur, il est déplacé dans **Items expirés**, où vous devez le récupérer manuellement.

---

## 🛍️ Acheter dans l'hôtel des ventes

Utilisez la commande **/ah** ou **/hdv** pour accéder au menu de l'hôtel des ventes.

Pour **acheter un item**, passez la souris dessus pour vérifier le vendeur, le prix et le temps restant. Cliquez ensuite sur l'objet et validez avec **Acheter** dans le menu de confirmation. Un message apparaît dans le chat en jeu 💬 :

![Exemple de message après un achat](/img/hdv/hdv2.png)

L'objet est remis directement dans votre inventaire si vous avez assez de place. Sinon, retrouvez-le dans **Items achetés** et récupérez-le dans les **6 jours suivant l'achat**.

🛠️ Les boutons de la dernière ligne du menu vous permettent de naviguer :

* 🗃️ Le coffre **Items en vente** affiche vos annonces actives.
* 📦 Le coffre de l'End **Items achetés** affiche les achats à récupérer.
* 🪣 Le seau de lave **Items expirés** affiche les objets invendus ou retirés à récupérer.
* 🔄 Les flèches permettent de changer de page.
* 📕 Le livre **Informations & Tri** permet de trier par prix ou par date, dans les deux sens.
* 📝 Le livre et plume **Historique** affiche vos achats et vos ventes.
* 💚 L'émeraude **Catégories** permet de filtrer les objets (blocs, outils, spawners, etc.).

Un **clic droit sur une shulker** dans le catalogue permet de consulter son contenu avant l'achat.

### 🔎 Rechercher un objet ou un vendeur

Utilisez **/ah search &lt;recherche&gt;** pour chercher du texte dans le nom, la description, le type d'objet ou le pseudo du vendeur. La recherche ignore les majuscules.

Par exemple, **/ah search épée rare** recherche cette expression et **/ah search Pseudo** permet de retrouver les annonces d'un vendeur. Vous pouvez ensuite changer le tri ou la catégorie. Faites **/ah** pour revenir au catalogue complet.

---

## 💸 Vendre dans l'hôtel des ventes

Tenez l'item à vendre dans votre **main principale** 🖐️, puis utilisez **/ah sell &lt;prix&gt; [quantité]**. La quantité est facultative : sans elle, tout le stack tenu en main est mis en vente. Si vous précisez une quantité, elle doit être comprise entre 1 et le nombre d'objets dans ce stack.

Le prix indiqué correspond au **lot entier**. Par exemple, **/ah sell 1k 16** met en vente 16 objets du stack tenu en main pour **1 000 $ au total**.

Le prix total doit être un nombre entier compris entre **1 $ et 50 000 000 $**. Les suffixes **k**, **m** et **b** sont acceptés (millier, million, milliard), dans cette limite. Patientez **5 secondes** entre deux mises en vente.

![Exemple de message après une mise en vente](/img/hdv/hdv4.png)

Pour retrouver vos annonces, faites **/ah** et ouvrez le coffre **Items en vente**. Cliquez sur un objet pour le retirer. Vous pouvez aussi cliquer sur votre propre annonce dans le catalogue, puis confirmer avec **Retirer**.

Dans **Items en vente**, **Items achetés** et **Items expirés**, l'entonnoir **Tout retirer** permet de récupérer les objets de la liste. Prévoyez assez de place dans votre inventaire.

---

## 📌 À savoir

- 🕒 Les objets restent **3 jours en vente**, puis **6 jours supplémentaires dans Items expirés** s'ils sont invendus, soit **9 jours au total** avant suppression. Les objets retirés de la vente qui n'ont pas pu être remis dans votre inventaire sont également à récupérer dans **Items expirés** sous **6 jours**.
- 📦 Les achats qui n'ont pas pu être remis directement restent dans **Items achetés** pendant **6 jours après l'achat**. Au-delà, les objets non récupérés sont supprimés.
- 💰 Il n'y a pas de taxe sur les ventes ou les achats.
- 🎖️ Le nombre d'annonces simultanées dépend de votre grade.
- 🔔 Vos objets peuvent être achetés même lorsque vous êtes déconnecté. Le vendeur reçoit l'argent **immédiatement, même hors ligne**.
- 🪙 **/ah claim** permet de récupérer d'éventuels crédits de vente en attente. Leur récupération est aussi automatique à la connexion.
- 📜 **/ah history** ouvre l'historique de vos achats et de vos ventes. Vous pouvez filtrer les transactions et les trier par date ou par prix.

---

## 📜 Commandes

Les arguments entre crochets sont facultatifs.

* **/ah** ou **/hdv** – Ouvrir l'hôtel des ventes.
* **/ah sell &lt;prix&gt; [quantité]** – Mettre en vente tout ou partie du stack tenu en main, au prix total indiqué.
* **/ah search &lt;recherche&gt;** – Rechercher un objet ou les annonces d'un vendeur.
* **/ah history [page]** ou **/ah historique [page]** – Consulter vos achats et vos ventes.
* **/ah claim** – Récupérer l'argent des ventes en attente.
* **/ah page &lt;page&gt;** ou **/ah p &lt;page&gt;** – Ouvrir une page du catalogue.

---

:::important
⚠️ Des règles encadrent les ventes et interdisent les arnaques. Pour éviter tout abus et sanction, veuillez consulter le [règlement](/docs/Information/rules).
:::
