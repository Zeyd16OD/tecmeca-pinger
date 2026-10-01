# tecmeca-pinger

Declencheur **24/7 gratuit** du bot de surveillance de stock Tecmeca, heberge
sur Vercel : <https://tecmeca-stock-bot.vercel.app>.

- Workflow **Ping bot stock Tecmeca** : appelle `/api/check` ~**toutes les 2 min**.
- Depot **public** => minutes GitHub Actions **illimitees et gratuites**.
- Le jeton est stocke dans le **secret** `CHECK_TOKEN` (jamais dans le code).
- Workflow **Keepalive** : empeche la desactivation apres 60 jours d'inactivite.

Ce depot ne contient **aucun code du bot** : uniquement le declencheur.