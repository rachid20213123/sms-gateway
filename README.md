# SMS Gateway Android App

Cette application Android agit comme une passerelle SMS, permettant d'envoyer et de recevoir des SMS via une interface utilisateur simple.

## Fonctionnalités

- Envoi de SMS via l'interface utilisateur
- Réception et stockage automatique des SMS entrants
- Historique des SMS envoyés et reçus
- Interface utilisateur Material Design
- Base de données locale pour le stockage des SMS

## Configuration requise

- Android Studio Arctic Fox ou plus récent
- SDK Android minimum : API 24 (Android 7.0)
- SDK Android cible : API 34 (Android 14)
- Gradle 8.0 ou plus récent

## Installation

1. Clonez ce dépôt
2. Ouvrez le projet dans Android Studio
3. Synchronisez le projet avec Gradle
4. Exécutez l'application sur un appareil Android ou un émulateur

## Permissions requises

L'application nécessite les permissions suivantes :
- `SEND_SMS` : Pour envoyer des SMS
- `RECEIVE_SMS` : Pour recevoir des SMS
- `READ_SMS` : Pour lire les SMS
- `INTERNET` : Pour la connectivité réseau

Ces permissions doivent être accordées manuellement dans les paramètres de l'application sur Android 6.0 et versions ultérieures.

## Utilisation

1. Lancez l'application
2. Entrez un numéro de téléphone
3. Entrez le message à envoyer
4. Appuyez sur "Envoyer SMS"
5. L'historique des SMS s'affiche automatiquement en dessous

## Architecture

- Kotlin comme langage principal
- Architecture MVVM
- Room pour la persistance des données
- Coroutines pour les opérations asynchrones
- Material Design pour l'interface utilisateur

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
