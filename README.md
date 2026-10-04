# Puits 3D

Prototype de Tetris 3D pédagogique pour entraîner la vision dans l'espace.

Ouvrir `index.html` dans un navigateur (PC ou mobile). Three.js est chargé depuis un CDN.

## Règles du prototype
- Puits de 5×5 (4, 7 ou 9 au choix), 12 étages. Un étage plein disparaît.
- Les 8 tétracubes : 5 plats (I, O, T, L, S) et 3 spatiaux (Coin, Vis gauche, Vis droite).

## Commandes (PC)
| Touche | Action |
|---|---|
| ← ↑ → ↓ | déplacer, toujours par rapport à la caméra (↑ éloigne la pièce) |
| J / L | pivoter à plat ↺ ↻ |
| I / K | basculer vers l'avant / l'arrière |
| U / O | rouler à gauche / à droite |
| Espace | lâcher · ⇧↓ descendre d'un cran |
| ⇧← / ⇧→ | tourner la caméra de 90° · T vue de dessus |
| PgUp / PgDn | mode coupe (masque les étages du haut) |
| G X F H N M | aides : fantôme, rayons X, faisceau, trous, flèches, carte |

Sur mobile : le pavé tactile en bas à gauche déplace la pièce, glisser ailleurs sur l'écran tourne la caméra (pincer pour zoomer), boutons pour les rotations.
