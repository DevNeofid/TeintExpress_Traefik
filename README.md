# infra-treafik

# Sur le VPS il faut créer les networks docker suivants :
- docker network create traefik-public
- docker network create teintexpress-backend

# Il faut aussi créer un fichier acme.json avec les droits suivants :
- touch acme.json
- chmod 600 acme.json

# command pour inspecter les networks :
- docker network inspect traefik-public
- docker network inspect teintexpress-backend