# Social App for developers.

Un réseau social pour développeurs. Création de profil avec vos compétences, vos formations et vos expériences. Ajout de posts, de commentaires et de likes.

## Getting Started

Télécharger ou cloner le projet sur votre machine locale.

### Prerequisites

Il faut d'abord que vous ayez NodeJS installé sur votre machine, rendez-vous sur ce lien pour l'installer.

```
https://nodejs.org
```

### Installing

Télécharger le zip ou faites un git clone du projet sur votre machine.

Dans le projet, exécutez la commande suivante pour installer les packages.

```
npm install
```
Ensuite configurez un cluster et un user sur MongoDB. Dans production.json dans config et insérez votre le uri MangoDB.

```
{
  "mongoURI": "mongodb+srv://{votre user}:{password}@cluster0-iuuww.mongodb.net/test?retryWrites=true&w=majority",
}
```

Lancer le serveur Express et React simultanément.

```
npm run dev
```

## Built With

* [React](https://fr.reactjs.org/) - Framework Front-end.
* [Express](https://expressjs.com/fr/) - Framework Back-end.
* [MangoDB](https://www.mongodb.com/fr) - Base de données nosql.

## Authors

* **Donastien Karoumbata** - *Initial work* - [Donastien](https://github.com/donastien)





