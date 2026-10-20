# Hitome TV — Téléchargements

Lecteur multimédia pour l'API Xtream : séries, films, favoris et « Reprendre » synchronisés
entre la TV, le téléphone et le PC avec un seul compte.

> **Hitome TV ne fournit aucun contenu** : ni chaînes, ni films, ni séries,
> ni playlists. C'est uniquement un lecteur : chaque utilisateur y saisit les
> identifiants de son propre abonnement, auprès du fournisseur de son choix,
> et reste responsable de la légalité de ce qu'il regarde.

➡️ **[Télécharger la dernière version](https://github.com/YokaiProd/hitome-releases/releases)**

Chaque version est publiée dans l'onglet **Releases**, avec les fichiers à
télécharger en bas de la page (rubrique « Assets »). Versions bêta (nouveautés à tester,
possibles bugs) : **[YokaiProd/hitome-releases-beta](https://github.com/YokaiProd/hitome-releases-beta/releases)**.

## Quel fichier choisir ?

### Android TV / Google TV (`Hitome-TV-…`)

| Fichier | Appareils |
|---|---|
| `…-universal.apk` | **En cas de doute** (à partir de la version 1.1) : s'installe sur toutes les TV et choisit seul la bonne version |
| `…-armeabi-v7a.apk` | Plus léger. Chromecast avec Google TV, Mi Box, la plupart des téléviseurs et box TV (système 32 bits) |
| `…-arm64-v8a.apk` | Plus léger. Nvidia Shield, TV et box récentes à système 64 bits (refusé avec « Application non installée » sur un système 32 bits) |

Installation : activer « Sources inconnues » pour l'appli qui ouvre le
fichier (par ex. *Downloader* ou un gestionnaire de fichiers), puis ouvrir
l'APK.

### Android téléphone / tablette (`Hitome-Mobile-…`)

| Fichier | Appareils |
|---|---|
| `…-arm64-v8a.apk` | **Presque tous les téléphones et tablettes** (Android 8 ou plus récent) |
| `…-armeabi-v7a.apk` | Seulement les appareils anciens en 32 bits, si l'autre ne s'installe pas |

Installation : ouvrir l'APK téléchargé et autoriser l'installation depuis
le navigateur ou le gestionnaire de fichiers quand Android le demande.

### Windows (`Hitome-Windows-…`)

Bientôt disponible.

---

Ce dépôt ne contient que les fichiers d'installation ; le code source est privé.
