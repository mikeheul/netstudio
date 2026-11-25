# Historique des versions

Les versions les plus récentes sont en haut.

## 2.12

- **Fichier lié** : enregistrement dans un fichier précis au lieu de télécharger un nouveau JSON à chaque sauvegarde.
  - *Enregistrer* (Ctrl+S), *Enregistrer sous* (Ctrl+Maj+S), *Ouvrir* (Ctrl+O), utilisables même depuis le terminal.
  - Pastille d'état du fichier dans l'en-tête (point orange : modifications non enregistrées) et nom du fichier dans la barre de titre.
  - Sauvegarde automatique optionnelle, détection d'un conflit si le fichier a été modifié ailleurs,
    reprise du dernier fichier au démarrage.
  - À la fermeture, proposition d'enregistrer s'il reste des modifications ; avertissement avant de remplacer un schéma non enregistré.
  - Repli sur le téléchargement classique quand l'API de fichiers n'est pas disponible.

## 2.11.2

- Première version distribuée en application Windows portable (Electron), avec icône.
- Nouvelle barre de navigation sobre : fond bleu nuit, boutons arrondis, logo en dégradé.
- Barre de navigation corrigée entre 1440 et 1660 px de large : les libellés passent en
  icônes plus tôt, le bouton « Enregistrer » n'est plus coupé.
- Vue physique en thème sombre : fond, pastilles de longueur de câble et échelle adaptés.

## 2.10 et antérieures

*Historique à compléter.*
