# simple-text-app
Simple text app containing frontend and backend, where you can store your magic text up to 200 chars to data storage.

## Start application
1. Go to simple-text-crud-backend, start docker-compose.yaml with either production or development environment.
- Run with default environment:
  `$docker-compose -f docker-compose.yaml --env-file .config/.env up`
- Run with production environment:
  `$docker-compose -f docker-compose.yaml --env-file .config/.env.prod up`
- Run with development environment:
  `$docker-compose -f docker-compose.yaml --env-file .config/.env.dev up`
2. Go to simple-text-crud-ui, start ui using npm.
  - Start npm:
    `$npm start`
  - Go to any browser and write ui url:
    `$http://localhost:3000`






Enjoy app :).
