# TodoApp

## Instructions
Veillez à bien importer les **node modules** si besoin.

## Migration pour la base de données
Exécutez les commandes suivantes pour générer et appliquer les migrations :

#Style
Style fait avec bootstrap et Twig.

```bash
php bin/console make:migration
php bin/console doctrine:migrations:migrate
```

| Méthode       | URL                                      | Description                 |
|--------------|-----------------------------------------|-----------------------------|
| **GET**      | `http://127.0.0.1:8000/task`           | Récupérer toutes les tâches |
| **GET**      | `http://127.0.0.1:8000/task/{id}`      | Récupérer une tâche par ID  |
| **POST**     | `http://127.0.0.1:8000/task/new`       | Créer une nouvelle tâche    |
| **UPDATE** | `http://127.0.0.1:8000/task/{id}/edit` | Mettre à jour une tâche     |
| **DELETE**   | `http://127.0.0.1:8000/task/{id}`           | Supprimer une tâche        |




