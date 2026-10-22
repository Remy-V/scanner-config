# Scanner Config Player

Page web qui fait défiler sur un téléphone les codes-barres de programmation des scanners, et fiches PDF équivalentes à imprimer.

| Configuration | Résultat attendu pour le code de test `TEST1400G` |
|---|---|
| **Preview V2** | `\|TEST1400G\|` (préfixe `\|` + suffixe `\|`) |
| **Preview V3** | `TEST1400G$\|` (suffixe `$\|`) |

Chaque configuration existe pour le **Sunmi Blink** et le **Honeywell Voyager 1400g**, en clavier **AZERTY** (France) ou **QWERTY** (US). Toutes commencent par un retour aux réglages d'usine.

## Site (`index.html`)

1. Ouvrir `index.html` sur le téléphone (ou via GitHub Pages).
2. Choisir le scanner, la configuration (Preview V2 / V3) et le clavier du poste.
3. Luminosité au maximum, puis **Démarrer**. Un bip par code.
4. Toucher une étape de la liste pour afficher son code seul.

Réglages par défaut : 0,5 s d'affichage par code, 0,5 s d'écran blanc entre deux codes.

## Fiches PDF (`pdf/`, à imprimer à 100 %)

AZERTY dans la colonne de gauche, QWERTY dans celle de droite : suivre une seule colonne, de haut en bas.

| Fichier | Scanner | Résultat |
|---|---|---|
| `Preview_V2_Sunmi_Blink.pdf` | Sunmi Blink | `\|TEST1400G\|` |
| `Preview_V3_Sunmi_Blink.pdf` | Sunmi Blink | `TEST1400G$\|` |
| `Preview_V2_Honeywell_Voyager_1400g.pdf` | Honeywell Voyager 1400g | `\|TEST1400G\|` |
| `Preview_V3_Honeywell_Voyager_1400g.pdf` | Honeywell Voyager 1400g | `TEST1400G$\|` |

Sunmi : le format de transmission est réglé avant le préfixe et les suffixes ; chaque caractère se saisit en 4 chiffres (`|` = 1124, `$` = 1036). Deux chiffres identiques à la suite : attendre 1 s entre les deux.
