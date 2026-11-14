```
       ▄▄▀▀▄▄        ____       _                         _          _
    ▄▀▀  ▄▄  ▀▀▄    |  _ \ ___ | |_   _  __ _  ___  _ __ | |    __ _| |__
    █  ▄▀  ▀▄  █    | |_) / _ \| | | | |/ _` |/ _ \| '_ \| |   / _` | '_ \
    █  ▀▄  ▄▀  █    |  __/ (_) | | |_| | (_| | (_) | | | | |__| (_| | |_) |
    ▀▄▄  ▀▀  ▄▄▀    |_|   \___/|_|\__, |\__, |\___/|_| |_|_____\__,_|_.__/
       ▀▀▄▄▀▀                     |___/ |___/
                                   polygonlab.ai
```

# PolygonLab

PolygonLab est une société française de programmation informatique.
Elle conçoit, développe et exploite des logiciels et des services en ligne pour les entreprises.
Nous publions ici, sous licence libre, des bibliothèques et des outils écrits pour l'occasion :
utiles à d'autres développeurs, testés, documentés et maintenus.

## Ce que nous publions

- Des bibliothèques courtes, sans dépendance superflue, qui règlent un problème précis.
- Une documentation en français pour les outils propres à la France, en anglais pour les autres.
- Des versions numérotées, un journal des changements et une intégration continue sur chaque dépôt.

## Dépôts

| Dépôt | Rôle | Installation |
|---|---|---|
| [identifiants-entreprise-fr](https://github.com/polygonlab-ai/identifiants-entreprise-fr) | Validation des SIREN, SIRET, numéros de TVA intracommunautaire et codes APE, avec les nomenclatures NAF rév. 2 et NAF 2025 et la table de passage officielle (PHP) | `composer require polygonlab/identifiants-entreprise-fr` |
| [facture-electronique-fr-outils](https://github.com/polygonlab-ai/facture-electronique-fr-outils) | Lecture des factures électroniques CII, UBL et Factur-X et contrôle des mentions obligatoires françaises (PHP) | `composer require polygonlab/facture-electronique-fr-outils` |
| [mcp-php-kit](https://github.com/polygonlab-ai/mcp-php-kit) | Serveurs MCP (Model Context Protocol) en PHP, avec un Worker Cloudflare facultatif | `composer require polygonlab/mcp-php-kit` |
| [cloudflare-worker-securite](https://github.com/polygonlab-ai/cloudflare-worker-securite) | Worker Cloudflare qui pose les en-têtes de sécurité site par site, garde la CSP du site sur demande et affiche une page de maintenance (TypeScript) | Cloner, puis `npx wrangler deploy` |
| [velopack-canal-maj](https://github.com/polygonlab-ai/velopack-canal-maj) | Mise à jour automatique d'applications Windows .NET avec Velopack, depuis son propre serveur : application d'exemple, scripts de publication, configurations de serveur (C#) | Cloner, puis `build/pack.ps1` |
| [plateformes-agreees-fr](https://github.com/polygonlab-ai/plateformes-agreees-fr) | Liste officielle des plateformes agréées pour la facture électronique publiée par la DGFiP, en JSON et CSV, mise à jour automatiquement chaque jour (données ouvertes) | Télécharger `data/plateformes.json` ou `data/plateformes.csv` |

## Contribuer

Les tickets et les propositions sont lus avec attention. Le fonctionnement est décrit dans
[CONTRIBUTING.md](https://github.com/polygonlab-ai/.github/blob/main/CONTRIBUTING.md).
Une faille de sécurité se signale en privé : voir
[SECURITY.md](https://github.com/polygonlab-ai/.github/blob/main/SECURITY.md).

## Contact

- Site : [polygonlab.ai](https://polygonlab.ai)
- E-mail : contact@polygonlab.ai

PolygonLab, SASU au capital de 10 000 € — SIRET 108 196 957 00014 — RCS Avignon

## In English

PolygonLab is a French software company. We design, build and run software and online services
for businesses. This organization hosts open-source libraries and tools written for the purpose:
small, tested, documented and maintained. Issues are welcome; see CONTRIBUTING.md for how
contributions are handled and SECURITY.md to report a vulnerability privately.

---
— Conçu et développé par PolygonLab · polygonlab.ai · Licence MIT
