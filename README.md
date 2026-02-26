# FWX Tag-Address Mapper

Script R pour parser les fichiers FWX de WinCC flexible et établir la correspondance entre les tags (VAR) et les adresses DATALINK.

## 📋 À propos

Ce script est basé sur un travail original trouvé sur GitHub, amélioré avec :
- Correction des erreurs de parsing
- Distinction Siemens/Omron
- Gestion des variables internes
- Export Excel structuré

## 🚀 Utilisation

1. Installer R et les packages : `install.packages(c("bitops", "openxlsx"))`
2. Modifier le chemin du fichier FWX dans le script
3. Exécuter le script
4. Récupérer le fichier Excel généré dans le dossier `SPOT`

## 📦 Fichiers

- `fwx_parser.R` : script principal
- `types.csv.example` : exemple de fichier de types

## 📄 Licence

MIT

## 👤 Auteur

[Abdelaziz Bensalem] - [[votre LinkedIn](https://www.linkedin.com/in/abdelaziz-bensalem-28481a23/)]
