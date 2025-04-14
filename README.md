# SECURITY UNIVERSITY

## Description
Ce projet est une application de gestion universitaire sécurisée, conçue pour faciliter l'administration et la gestion des données académiques tout en maintenant des standards élevés de sécurité.

## Fonctionnalités
- Gestion des étudiants
- Gestion des cours et des programmes
- Système de notation
- Gestion des emplois du temps
- Sécurité renforcée des données
- Interface responsive pour mobile

## Technologies Utilisées
- PHP
- MySQL
- HTML/CSS
- JavaScript
- Git pour le contrôle de version

## Installation
1. Clonez le dépôt :
```bash
git clone https://github.com/reiiny-ahmad/SECURITY_UNIVERSITY.git
```

2. Configurez votre environnement :
- Copiez `config.inc.sample.php` vers `config.inc.php`
- Modifiez les paramètres de configuration selon votre environnement

3. Installez les dépendances :
```bash
composer install
npm install
```

## Démarrage et Accès
1. Démarrez votre serveur web (Apache/Nginx)

2. Démarrez MySQL :
```bash
sudo service mysql start  # Pour Linux
# ou lancez MySQL depuis XAMPP/WAMP pour Windows
```

3. Importez la base de données :
- Créez une nouvelle base de données
- Importez le fichier SQL fourni dans le dossier `database`

4. Accédez à l'application :
- Ouvrez votre navigateur
- Accédez à : `http://localhost/SECURITY_UNIVERSITY`
- Connectez-vous avec les identifiants par défaut :
  * Utilisateur : admin
  * Mot de passe : admin123
  * **Important** : Changez le mot de passe après la première connexion !

5. En cas de problème :
- Vérifiez que tous les services (Apache/Nginx, MySQL) sont en cours d'exécution
- Vérifiez les logs dans le dossier `logs`
- Assurez-vous que les permissions des fichiers sont correctes

## Configuration Requise
- PHP 7.4 ou supérieur
- MySQL 5.7 ou supérieur
- Serveur Web (Apache/Nginx)

## Sécurité
Ce projet met l'accent sur la sécurité avec :
- Authentification sécurisée
- Chiffrement des données sensibles
- Protection contre les injections SQL
- Gestion des sessions sécurisée

## Contribution
Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## Licence
Ce projet est sous licence MIT.

## Contact
Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue sur GitHub.
