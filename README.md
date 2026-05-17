# 🎰 Roulette Royale

Une simulation interactive et réaliste de roulette de casino européenne, développée entièrement en **HTML5**, **CSS3** (Flexbox) et **JavaScript** (Vanilla).

![Licence](https://img.shields.io/badge/Licence-MIT-green.svg)
![Technos](https://img.shields.io/badge/Tech-HTML5%20%2F%20CSS3%20%2F%20JS-orange.svg)
![Niveau](https://img.shields.io/badge/Projet-NSI%20Premi%C3%A8re-blue.svg)

---

## 📸 Aperçu de l'interface

L'application propose une interface immersive de table de jeu inspirée des vrais casinos :
* **À gauche :** Le cylindre de la roulette et son animation de bille fluide (ralentissement synchronisé de 3 secondes).
* **À droite :** Un tapis de mise vert complet et interactif, respectant l'organisation officielle d'une roulette européenne (3 colonnes de numéros de 1 à 36, le 0 vert, les douzaines et les chances simples).
* **En bas :** Le panneau de contrôle de la Banque Royale, le suivi des mises actives et la console de commentaires de la table.

---

## ✨ Fonctionnalités Majeures

* **Tapis de mise interactif :** Cliquez directement sur les cases pour placer vos jetons. Un effet de halo doré lumineux simule visuellement les jetons engagés.
* **Animation CSS/JS fluide :** La roulette et la bille tournent en sens inverse grâce à des transitions appliquées en JavaScript à l'aide de courbes de Bézier pour un effet de décélération réaliste.
* **Moteur de gain authentique :**
  * **Pari Plein (Numéro unique) :** Gain de $35 \times \text{mise}$ (ex: le `0` ou n'importe quel numéro).
  * **Douzaines (1ère, 2ème, 3ème) :** Gain de $2 \times \text{mise}$.
  * **Chances Simples (Rouge/Noir, Pair/Impair, Manque/Passe) :** Gain de $1 \times \text{mise}$.
* **Sécurité des règles de casino :** * Blocage des interactions et des clics sur le tapis pendant que la bille tourne (*"Rien ne va plus !"*).
  * Si le `0` sort, les chances simples et les douzaines sont automatiquement perdantes.
  * Vérification du solde de la banque avant validation de la mise.

---

## 🛠️ Technologies utilisées

* **HTML5** : Structure sémantique du plateau de jeu et de la grille numérique.
* **CSS3** : Design responsive avec Flexbox, variables CSS (`:root`), dégradés de couleurs (effet velours pour le tapis vert) et animations de rotation.
* **JavaScript (ES6)** : Logique algorithmique globale, gestion du tableau des mises, tirage pseudo-aléatoire et calculs des gains/pertes du joueur.

---

## 🚀 Installation et Lancement

Ce projet s'exécute entièrement côté client (dans le navigateur), il n'y a besoin d'aucun serveur ni d'aucune base de données !

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/rpmn0ise/roulette-royale.git](https://github.com/rpmn0ise/roulette-royale.git)
   ```
2. **Ouvrir le projet :**
   Double-cliquez simplement sur le fichier index.html pour le lancer dans votre navigateur préféré (Chrome, Firefox, Edge, Safari...).
