# NetStudio

Simulateur réseau **hors ligne** pour l'enseignement, dans l'esprit de Packet Tracer :
schéma logique et physique, configuration d'équipements, terminal en ligne de commande, paquets animés, exercices.
Pensé pour les étudiants **TSR (bac+2)** et **ASR (bac+3)**.

> Version **2.13** · Windows (version portable, aucune installation)
> Usage pédagogique — voir [LICENCE.md](LICENCE.md)

![Icône de NetStudio](icon.svg)

## Télécharger

Récupérez le fichier **`NetStudio 2.13.0.exe`** dans la section
**Releases** de ce dépôt (ou à l'emplacement indiqué par votre enseignant).

> Le nom exact du fichier suit la version : `NetStudio <version>.exe`.

## Démarrer

1. Placez le fichier `.exe` où vous voulez (Bureau, clé USB, dossier de cours).
2. Double-cliquez dessus : l'application démarre. **Rien n'est installé.**

### Avertissement Windows au premier lancement

L'application n'est pas signée numériquement. Windows peut afficher
*« Windows a protégé votre ordinateur »* :

1. cliquez sur **Informations complémentaires** ;
2. puis sur **Exécuter quand même**.

Sur un poste d'entreprise ou d'établissement, un antivirus ou une politique de
sécurité peut bloquer ce type de fichier : contactez alors votre
administrateur.

## Fonctionnalités

- **Schéma réseau** : routeurs, switchs, serveurs, postes et autres équipements, câblés à la souris ;
  notes et zones.
- **Vue logique et vue physique** : zones (salles), longueur des câbles avec alerte au-delà de la limite,
  baies et alimentation.
- **Configuration** : panneau graphique et **terminal en ligne de commande**.
- **Sécurité des ports** : port-security (adresses MAC autorisées, modes protect / restrict / shutdown, état err-disabled).
- **Paquets animés** : visualisation d'un ping saut après saut.
- **Supervision** et **Problèmes** : test de joignabilité et contrôle automatique des erreurs de configuration.
- **Exemples et exercices** : schémas corrigés ou à valider, avec missions et objectifs.
- **Fichier lié** : enregistrement dans un fichier précis (Ctrl+S), Enregistrer sous (Ctrl+Maj+S), Ouvrir (Ctrl+O).
- Annuler / rétablir, barre d'outils flottante, thèmes clair, sombre et contraste élevé, impression.

## Vos données

- L'application fonctionne **entièrement sur votre poste** : aucune donnée
  n'est envoyée sur Internet, aucun compte, aucun traceur.
- **Fichier lié** : `Fichier → Enregistrer` (Ctrl+S) écrit dans le fichier ouvert ;
  la première fois, ou avec `Enregistrer sous…` (Ctrl+Maj+S), une fenêtre vous demande où le placer.
  `Fichier → Ouvrir…` (Ctrl+O) rouvre un schéma.
- Le nom du fichier s'affiche dans l'en-tête, avec un point **orange** tant que des
  modifications ne sont pas enregistrées (vert quand tout est enregistré).
- À la fermeture, l'application propose d'enregistrer s'il reste des modifications.
- Au démarrage, le **dernier fichier** utilisé est rouvert.
- Option **Enregistrement automatique** (menu Fichier) : écrit dans le fichier après chaque modification.
- Si le fichier a été modifié ailleurs (autre fenêtre, synchronisation…), l'application vous
  le signale avant d'écraser.
- **Enregistrez régulièrement** vos schémas pour pouvoir les rouvrir sur un autre poste.

## Questions fréquentes

**L'application ne se lance pas.**
Vérifiez que Windows ne bloque pas le fichier : clic droit sur le `.exe` →
*Propriétés* → cochez **Débloquer** si la case est présente.

**Je change de poste, comment retrouver mes schémas ?**
Enregistrez-les en fichier (clé USB, OneDrive…) et rouvrez-les sur l'autre poste (`Fichier → Ouvrir…`, Ctrl+O).

**Puis-je en donner une copie à un camarade ?**
Non : la redistribution n'est pas autorisée sans accord de l'auteur. Indiquez
plutôt l'adresse de téléchargement. Voir [LICENCE.md](LICENCE.md).

## Licence

© 2026 Mickaël MURMANN. Tous droits réservés. Outil mis à disposition des
étudiants et enseignants du CESI pour un usage strictement pédagogique.
Détails dans [LICENCE.md](LICENCE.md).

L'application est fournie sans garantie : il s'agit d'un outil pédagogique qui simplifie
le comportement des équipements réels.

## Contact

Mickaël MURMANN — CESI
