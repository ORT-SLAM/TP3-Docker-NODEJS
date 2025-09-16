# TP Docker NODEJS

1. Construire son app puis la démarrer :

```bash
docker build -t my-node-app .
```

```bash
docker run -p 3000:3000 my-node-app
```

1. Ou bien en utilisant docker compose

```bash
docker-compose up -d
```

Ouvrez un navigateur web et allez à http://localhost:3000. Vous devriez voir le message "Hello World!" affiché.
