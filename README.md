# KeyBridge — téléchargements Windows

Installateur personnel pour Windows 11 x64. Aucun prérequis .NET, Python ou WSL.
Exécutez l’installateur, fermez KeyBridge avant toute mise à jour/désinstallation.
Installation dans `%LOCALAPPDATA%\Programs\KeyBridge`, raccourci dans Démarrer,
raccourci Bureau facultatif. La désinstallation passe par Applications installées.

Ce programme d’installation n’est pas signé par un éditeur Windows : Windows peut
afficher un avertissement d’éditeur inconnu. Les publications comprennent un
manifeste RSA-PSS/SHA-256 signé, les sommes SHA-256 et les notes de version.

Réglages → Application permet une recherche manuelle ou la désactivation de la
recherche automatique au démarrage. GitHub reçoit les métadonnées réseau ordinaires,
jamais le texte saisi. Le téléchargement et l’installation nécessitent une action
explicite. Rien n’est installé à la fermeture ordinaire. Aucun service en arrière-plan.

La version indique la livraison logicielle et ne certifie aucune validation
matérielle. Usage uniquement sur des systèmes et périphériques autorisés.

## Télécharger

[Dernière version Windows](https://github.com/gorillaink/keybridge-releases/releases/latest). Téléchargez l’installateur `KeyBridge-<version>-win-x64-setup.exe`. Les fichiers de manifeste et signature sont utilisés par la mise à jour intégrée.

Le firmware Pico 2 est fourni séparément au format UF2. L’installateur Windows ne flashe jamais le Pico ; le mode Markdown de la version 0.2.1 demande le firmware 1.1.0. Le rendu Markdown dans OneNote reste en qualification.

Ce dépôt distribue les paquets et les notes de version ; le dépôt source reste privé.
