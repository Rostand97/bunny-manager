# BunnyManager 3.5

Application mobile de gestion cunicole professionnelle et amateur.

## Description

BunnyManager est une application mobile multiplateforme (iOS/Android) conçue pour la gestion complète d'une ferme cunicole. Elle permet de suivre l'ensemble des aspects de l'élevage : gestion des lapins, reproduction, ressources, santé et bien-être animal.

## Fonctionnalités principales

- Gestion individuelle des lapins (fiches détaillées, photos, historique médical)
- Suivi de la reproduction (couples, gestation, portées)
- Gestion des ressources (alimentation, eau, stocks)
- Suivi sanitaire et bien-être animal
- Tableaux de bord et rapports personnalisables
- Mode hors ligne avec synchronisation
- Interface intuitive et responsive

## Technologies utilisées

- Flutter (Framework multiplateforme)
- Firebase (Backend, authentification, stockage)
- SQLite (Base de données locale)
- Provider (Gestion d'état)
- GetIt (Injection de dépendances)

## Prérequis

- Flutter SDK (version 3.0.0 ou supérieure)
- Dart SDK (version 2.17.0 ou supérieure)
- Android Studio / Xcode pour le développement
- Un compte Firebase pour le backend

## Installation

1. Cloner le repository :
```bash
git clone https://github.com/Rostand97/bunny-manager.git
```

2. Installer les dépendances :
```bash
flutter pub get
```

3. Configurer Firebase :
- Créer un projet Firebase
- Télécharger et ajouter le fichier de configuration `google-services.json` (Android) et `GoogleService-Info.plist` (iOS)
- Activer l'authentification et le stockage dans la console Firebase

4. Lancer l'application :
```bash
flutter run
```

## Structure du projet

```
lib/
  ├── core/           # Configuration et utilitaires
  ├── data/           # Modèles de données et repositories
  ├── features/       # Fonctionnalités de l'application
  ├── services/       # Services (API, base de données)
  └── ui/             # Composants UI et écrans
```

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## Support

Pour toute question ou problème, veuillez :
- Consulter la documentation dans l'application
- Ouvrir une issue sur GitHub
- Contacter l'équipe de support à support@bunnymanager.com 
