# Api pour l'école

### `npm i`

1. Installer les paquets

### Lancer le projet

2. Lancer le serveur:

```bash
npm run start
```

| Type | URL  | Paramètres  |
| ------- | --- | --- |
| Tout les services | /api/v1/resources/services/all | aucun |
| Service selon id | /api/v1/resources/service/id/:id | id(type=nombre) |
| Services selon localisation | /api/v1/resources/service/localisation/:localisation | localisation(type=number) |
| Scrap services | /api/v1/resources/service/export | aucun |

