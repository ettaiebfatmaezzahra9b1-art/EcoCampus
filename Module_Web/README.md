# EcoCampus - Module Web (phase 3)

Fichiers : `index.html`, `style.css`, `script.js`, `data.json` (genere par le module C), `data.js` (copie de data.json
pour l'ouverture sans serveur), `vendor/chart.umd.js` (Chart.js).

## Lancer
Ouvrir le dossier dans VS Code puis **Go Live** (extension Live Server). La page lit `data.json` toute seule et se
met a jour toutes les 10 s quand le module C regenere le fichier. Sans serveur (double-clic), la page affiche `data.js`.

## Remarques
- Les icones (Bootstrap Icons) et les polices (Google Fonts) viennent d'Internet.
- Ajouter ou supprimer une mesure sur la page est garde dans le navigateur. Pour l'envoyer au module C :
  page Ajouter > Exporter CSV (format measures_in.csv), ou Profil > Telecharger data.json.
