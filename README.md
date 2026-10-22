# DIRM Méditerranée

Application Symfony pour les demandes administratives de la Direction interrégionale de la mer Méditerranée : mobilité des agents, accès aux outils métier, déclarations de mise en chantier.

## Stack

- PHP, Symfony, Twig
- MySQL, MongoDB
- Docker

## Démarrage

```bash
cp .env.example .env
docker compose up --build
```

`APP_SECRET`, la base et le mailer se configurent dans `.env`, en local. Ne jamais y mettre un mot de passe de messagerie réelle dans le dépôt.
