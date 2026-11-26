# Historique des versions

Les versions les plus récentes sont en haut.

## 2.13

- **Port-security** (commutateurs) : `switchport port-security`, `maximum`, `violation protect|restrict|shutdown`,
  `mac-address`, `mac-address sticky`, `clear port-security`.
  - Un appareil non autorisé est bloqué selon le mode choisi ; en mode `shutdown`, le port passe en **err-disabled**
    (affiché en rouge sur le schéma) et se réactive par `shutdown` puis `no shutdown`.
  - Commandes d'affichage : `show port-security`, `show port-security interface`, `show port-security address`,
    `show interfaces status err-disabled`.
- **Commandes inconnues refusées** : une faute de frappe (ex. `spanning-tree poert`) donne maintenant l'erreur
  `% Invalid input detected`. Les options acceptées mais non simulées (portfast, bpduguard, speed, duplex, storm-control…)
  s'affichent dans la configuration et indiquent discrètement qu'elles n'ont pas d'effet dans la simulation.
- **Messages système** : `shutdown` / `no shutdown` affichent les messages IOS (`%LINK-5-CHANGED`, `%LINEPROTO-5-UPDOWN`),
  y compris côté voisin ; nouvelle commande `show logging`.
- **Configuration en texte** : le bouton *Appliquer* applique aussi les suppressions (une exclusion DHCP retirée ne revient plus).
- **Services** : les sections ouvertes ou fermées d'un serveur restent telles quelles après une modification.
- **SSH** disponible sur les postes Windows.
- **Noms des ports et adresses** toujours affichés au premier plan, lisibles au-dessus des câbles et des noms d'équipements.
- **Préférences** (Paramètres) : animation des paquets après une commande de terminal (désactivée par défaut),
  invite de commandes placée à la suite du texte.

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
