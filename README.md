# amou 💗

Un jeu simple pour se détendre : touche les cœurs avant qu'ils s'envolent, puis bats le boss.

**Jouer en ligne : https://univetx.github.io/amou/**

## Règlement

### Les cœurs (30 secondes)

| Cœur | Effet |
|------|-------|
| ❤️ rouge | +1 point |
| 💙 💚 💛 💜 🧡 | +½ point |
| 🖤 noir | −1 point (le score ne descend pas sous 0) |

- 3 cœurs de même couleur touchés à la suite : **+2 secondes**.
- Le jeu monte en crescendo : les cœurs apparaissent et montent de plus en plus vite pendant environ 45 secondes.

### Le boss 👹

Quand le temps est écoulé, le boss arrive.

- Il saute d'un angle de l'écran à l'autre, deux fois plus vite que les cœurs.
- Il ne s'arrête pas et ne part pas avant d'être battu.
- Il n'y a pas de limite de temps : **20 touches** suffisent pour le vaincre.

### Les niveaux

Après le boss, le niveau suivant s'ouvre.

- Bonus de vitesse = score ÷ durée totale de la partie (cœurs + boss), limité entre **0,3 et 1**.
- Le bonus s'ajoute à la vitesse à chaque niveau (niveau 2 : ×1,3 à ×2).
- La vitesse s'applique aux cœurs et au boss.
- Le score repart à zéro à chaque niveau. Le meilleur score est gardé sur l'appareil.

## Technologies

- HTML, CSS, JavaScript
- [Bootstrap 5.3](https://getbootstrap.com/), chargé par CDN
- Police Baloo 2 (Google Fonts)
- Aucune installation, aucun serveur : un seul fichier `index.html`

## Mettre en ligne avec GitHub Pages

1. Dépose `index.html` à la racine du dépôt (le dépôt doit être public).
2. Va dans **Settings** → **Pages**.
3. **Source** : *Deploy from a branch*, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après 1 à 2 minutes, le jeu est en ligne sur `https://univetx.github.io/amou/`.

## Structure

```
amou/
├── index.html
└── README.md
```
