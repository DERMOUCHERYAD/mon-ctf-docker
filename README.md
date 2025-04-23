# Welcome CTF Docker

Ce dépôt ne contient qu'un fichier de configuration `docker-compose.yml`. L'image Docker est déjà publiée en ligne pour faciliter son utilisation.

## 🚀 Lancement de l'épreuve

1. **Téléchargez** le fichier `docker-compose.yml` :
   ```bash
   curl https://hackropole.fr/challenges/fcsc2024-misc-welcome-docker/docker-compose.public.yml -o docker-compose.yml
   ```

2. **Démarrez** le conteneur dans le même dossier :
   ```bash
   docker compose up
   ```

3. **Accédez** au service depuis un second terminal avec Netcat :
   ```bash
   nc localhost 4000
   ```

4. **Récupérez** le flag au format :
   ```text
   FCSC{...}
   ```

---

## 📄 Licence

Ce projet est distribué sous licence MIT.

