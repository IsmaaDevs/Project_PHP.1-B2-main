# 📚 Isma's-Anime

**Isma's-Anime** est une application web qui permet aux utilisateurs de lire des scans de manga stockés dans une base de données PostgreSQL.

## Fonctionnalités

- **Inscription et Connexion** : Les utilisateurs peuvent s'inscrire et se connecter pour accéder aux scans de manga.
- **Lecture de Scans** : Les utilisateurs peuvent lire les scans de manga disponibles.
- **Gestion des Scans** : Les administrateurs peuvent ajouter, modifier et supprimer des scans de manga.

## Installation

1. **Cloner le Dépôt** :

   ```bash
   git clone <url-du-dépôt>
   cd manga-scan-reader
   ```

2. **Installer les Dépendances** :

   ```bash
   composer install
   ```

3. **Démarrer le Serveur** :

   Utilisez un serveur web local (comme Apache) pour servir l'application. Assurez-vous que le répertoire racine pointe vers le dossier du projet.

## Utilisation

### Inscription et Connexion

1. Accédez à la page d'inscription pour créer un compte.
2. Utilisez les informations de connexion pour vous connecter et accéder aux fonctionnalités de l'application.

### Lecture de Scans

- Naviguez vers la section des scans pour voir la liste des mangas disponibles.
- Cliquez sur un manga pour lire les scans disponibles.

### Gestion des Scans

- Connectez-vous en tant qu'administrateur pour accéder aux fonctionnalités de gestion des scans.
- Ajoutez, modifiez ou supprimez des scans de manga via l'interface d'administration.

## Structure du Projet

```plaintext
ismas-anime/
│
├── src/
│   ├── home/
│   │   ├── handler.php
│   │   ├── model.php
│   │   └── view.php
│   ├── login/
│   │   ├── handler.php
│   │   ├── model.php
│   │   └── view.php
│   ├── register/
│   │   ├── handler.php
│   │   ├── model.php
│   │   └── view.php
│   ├── scans/
│   │   ├── handler.php
│   │   ├── model.php
│   │   ├── view.php
│   │   ├── config.php
│   │   └── main.php
│
├── .gitignore
├── composer.json
├── composer.lock
└── README.md
```

## Technologies Utilisées

- **PHP** : Langage de programmation utilisé pour développer l'application.
- **PostgreSQL** : Base de données utilisée pour stocker les scans de manga.
- **Composer** : Gestionnaire de dépendances pour PHP.

---

Voilà **Isma's-Anime** ! Si vous avez des questions ou des suggestions, n'hésitez pas à les partager. 📚✨
