# 🎭 Time's Up!

Un jeu de mime et de devinettes jouable directement dans le navigateur, sans installation ni connexion requise. Il suffit d'ouvrir le fichier `timesup.html`.

---

## 🚀 Lancer le jeu

1. Clone ou télécharge ce dépôt
2. Ouvre `timesup.html` dans n'importe quel navigateur moderne
3. C'est parti !

> Le jeu fonctionne entièrement en local, sans serveur ni dépendance externe (hormis la police Google Fonts).

---

## 🎯 But du jeu

Faire deviner le maximum de mots à son équipe avant la fin du temps imparti. Chaque mot vaut un certain nombre de points selon sa difficulté. Le joueur avec le plus de points à la fin de la partie l'emporte.

---

## 👥 Joueurs

- De **2 à 10 joueurs**
- Chaque joueur choisit un nom à l'écran d'inscription
- Un avatar et une couleur lui sont attribués automatiquement
- Les joueurs jouent chacun leur tour, à tour de rôle

---

## 🃏 Déroulement d'un tour

1. L'écran affiche à qui c'est le tour — les autres joueurs ne regardent pas
2. Le joueur actif appuie sur **🎲 Révéler le mot** pour découvrir le mot à faire deviner
3. Le **timer de 60 secondes** démarre automatiquement dès la révélation
4. Le joueur fait deviner le mot à son équipe en mimant, décrivant ou chantant — **sans prononcer le mot ni ses dérivés**
5. Si le mot est trouvé → **✓ Trouvé !** (les points sont comptabilisés)
6. Si le mot est trop difficile → **✗ Passer** (dans la limite des passes autorisées)
7. Quand le timer atteint zéro, l'animation **TIME'S UP !** s'affiche et le tour se termine

---

## ⭐ Système de points

Les mots sont classés par difficulté, chaque niveau rapporte plus de points :

| Difficulté | Étoiles | Points |
|---|---|---|
| Facile | ★☆☆ | 1 pt |
| Moyen | ★★☆ | 2 pts |
| Difficile | ★★★ | 3 pts |

---

## ⚙️ Options configurables

Avant de lancer la partie, tu peux régler :

- **Durée du tour** : 30, 60, 90 ou 120 secondes
- **Nombre de passes** : 0, 3, 5 ou illimité
- **Catégories actives** : sélectionne uniquement les thèmes souhaités

---

## 📚 Catégories disponibles (1 000+ mots)

| Catégorie | Exemples |
|---|---|
| 🐾 Animaux | Lion, Axolotl, Flamant rose… |
| 👔 Métiers | Pompier, Luthier, Trapéziste… |
| 📦 Objets | Aspirateur, Tire-bouchon, Sablier… |
| 🍕 Nourriture | Raclette, Bouillabaisse, Mochi… |
| ⚽ Sports | Curling, Biathlon, Escrime… |
| 🎬 Films | Titanic, Parasite, Pulp Fiction… |
| 🗺️ Lieux | Machu Picchu, Fjords, Las Vegas… |
| 🌟 Célébrités | Mozart, Picasso, Usain Bolt… |
| 🏃 Actions | Jongler, Ronfler, Faire le poirier… |
| 🌿 Nature | Aurore boréale, Geyser, Typhon… |
| 🎵 Musique | Saxophone, Flamenco, Fugue… |
| 🚗 Transport | Montgolfière, Hovercraft, Gondole… |
| 😅 Émotions | Nostalgie, Euphorie, Mélancolie… |
| 🧚 Contes | Minotaure, Phénix, Hansel et Gretel… |
| 🔬 Science | Trou noir, Blockchain, Nanotechnologie… |
| 👗 Mode | Kimono, Smoking, Chapeau de cowboy… |
| 🏠 Maison | Jacuzzi, Pergola, Coffre-fort… |
| 🎮 Jeux | Rubik's Cube, Escape room, Babyfoot… |
| 🏛️ Histoire | Gladiateur, Samouraï, Catapulte… |
| 😂 Situations | Glisser sur une peau de banane, Rater son réveil… |
| 💭 Abstrait | Démocratie, Entropie, Paradoxe… |

---

## 🚫 Règles à respecter

- ❌ Interdiction de dire le mot ou ses dérivés
- ❌ Interdiction d'épeler le mot
- ✅ On peut mimer, chanter, décrire avec d'autres mots, faire des bruits…

---

## 🏆 Fin de partie

La partie se termine quand les joueurs décident d'arrêter (bouton **🏁 Fin de partie**). Un écran final affiche :
- Le **podium** des 3 meilleurs joueurs
- Le **classement complet** avec les points et le nombre de mots trouvés par chacun
- Une pluie de **confettis** pour fêter le gagnant 🎊

---

## 🛠️ Stack technique

- HTML / CSS / JavaScript vanilla — aucune dépendance, aucun framework
- Fonctionne hors ligne (sauf pour la police Boogaloo chargée via Google Fonts)
- Compatible GitHub Pages : il suffit d'activer Pages sur ce dépôt

---

*Bon jeu ! 🎭*
