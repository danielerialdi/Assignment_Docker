# docker-course-2
Simple application for Course Assignment


Comandi per utilizzare l'immagine docker creata con il workflow:

- Creare un token (password temporanea): https://github.com/settings/tokens/new?scopes=write:packages
- `docker login ghcr.io -u <nome_utente_github>`
    - la password è il token creato al punto 1
- Prendere il tag dal log della creazione dell'immagine che si vuole lanciare
- Comando per eseguire la pull di un'immagine:
```
docker pull ghcr.io/danielerialdi/assignment_docker/ssgs:781188c052fba05f558369fbf78c136067976d04
```

