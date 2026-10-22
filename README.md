# Scanner Config Player

Page web qui fait défiler sur un téléphone les codes-barres de programmation des scanners :

- **Sunmi Blink** : Preview V2 (`|TEST1400G|`) et Preview V3 (`TEST1400G$|`)
- **Honeywell Voyager 1400g** : Preview V2 (`|TEST1400G|`) et Preview V3 (`TEST1400G$|`)

Chaque configuration existe en clavier AZERTY (France) et QWERTY (US).

## Utilisation

1. Ouvrir `index.html` sur le téléphone (ou via GitHub Pages).
2. Choisir le scanner, la configuration et le clavier du poste.
3. Luminosité au maximum, puis **Démarrer**. Un bip par code.
4. Toucher une étape de la liste pour afficher son code seul.

Fichier unique, sans dépendance (seule la police IBM Plex est chargée depuis Google Fonts).

## Fiches PDF (à imprimer à 100 %)

| Fichier | Scanner | Résultat |
|---|---|---|
| `pdf/Preview_V2_Sunmi_Blink.pdf` | Sunmi Blink | `\|TEST1400G\|` |
| `pdf/Preview_V3_Sunmi_Blink.pdf` | Sunmi Blink | `TEST1400G$\|` |
| `pdf/Honeywell_Voyager1400g_prefixe_suffixe_pipe.pdf` | Voyager 1400g | `\|TEST1400G\|` |
| `pdf/Honeywell_Voyager1400g_suffixe_dollar_pipe.pdf` | Voyager 1400g | `TEST1400$\|` |
