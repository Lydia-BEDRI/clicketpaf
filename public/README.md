# ClicketPaf

**[ClicketPaf](https://www.clicketpaf.org/)** est une solution de livraison rapide et fiable pour vos repas, colis, courses et déménagements partout en France. Ce projet a été réalisé dans le cadre du module **[SEO](https://www.esgi.fr/actualites/21032023-en-quoi-consiste-le-metier-de-redacteur-web)** en 4ème année d’**[Ingénierie du Web](https://www.esgi.fr/programmes/ingenierie-web.html)** à l’**[ESGI](https://www.esgi.fr)**. L'objectif est de mettre en pratique les bonnes pratiques de référencement pour maximiser la visibilité du site sur les moteurs de recherche.  
**Mot-clé principal** : *clicketpaf*

* * *

## Table des matières

- [À propos du projet](# "#%C3%A0-propos-du-projet")
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Scripts](#scripts)
- [Structure du projet](#structure-du-projet)
- [Contribuer](#contribuer)
  
* * *

## À propos du projet

Le projet **ClicketPaf** vise à démontrer les meilleures pratiques de référencement (SEO) appliquées à un site vitrine. Ce site propose une solution complète de livraison adaptée à divers besoins tels que :

- Repas,
- Colis,
- Courses,
- Déménagements.

Grâce à des techniques SEO modernes et à l’utilisation des outils tels que **Tailwind CSS**, ce projet cherche à obtenir un classement optimal pour le mot-clé **clicketpaf**.

* * *

## Installation

### 1\. Clonez le dépôt

Pour commencer, récupérez le projet depuis GitHub :

```bash
git clone https://github.com/Lydia-BEDRI/clicketpaf.git
cd clicketpaf
```

### 2\. Installez les dépendances

Assurez-vous d'avoir **Node.js** et **npm** installés. Ensuite, exécutez la commande suivante pour installer les dépendances :

```bash
npm install
```

* * *

## Utilisation

### Démarrer en mode développement

Pour démarrer le projet en mode développement et surveiller les modifications en direct :

```bash
npm run watch
```

### Générer les fichiers pour la production

Pour générer les fichiers CSS optimisés pour la production :

```bash
npm run build
```

* * *

## Scripts

Voici les scripts disponibles dans le projet :

- **`npm run watch`** : Lance le projet en mode développement avec surveillance des fichiers.
- **`npm run build`** : Génère les fichiers CSS optimisés pour la production.

* * *

## Structure du projet

Voici la structure du projet pour une meilleure organisation :

```
clicketpaf/
├── public/
│   ├── index.html
│   ├── a-propos-clicketpaf.html
│   ├── services-livraison-clicketpaf.html
│   ├── contact-clicketpaf.html
│   ├── faq-clicketpaf.html
│   ├── politique-confidentialite-clicketpaf.html
│   ├── termes-conditions-clicketpaf.html
│   ├── robots.txt
│   ├── sitemap.xml
│   ├── assets/
│   │   ├── css/
│   │   │   ├── styles.css
│   │   │   ├── tailwind.min.css
│   │   └── images/
├── tailwind.config.js
├── package.json
├── package-lock.json
```

* * *

## Contribuer

Les contributions sont les bienvenues ! Suivez les étapes suivantes pour contribuer :

1.  **Forkez** le dépôt.
    
2.  Créez une branche pour votre fonctionnalité :
    
    ```bash
    git checkout -b feature/ma-fonctionnalité
    ```
    
3.  **Commitez** vos modifications :
    
    ```bash
    git commit -m 'Ajout de ma fonctionnalité'
    ```
    
4.  Poussez votre branche :
    
    ```bash
    git push origin feature/ma-fonctionnalité
    ```
    
5.  Ouvrez une **Pull Request**.