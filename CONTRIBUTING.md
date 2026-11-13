# Contribuer aux dépôts de PolygonLab

Merci de l'intérêt que vous portez à nos dépôts. Ce guide s'applique à tous les dépôts publics
de l'organisation, sauf si un dépôt fournit le sien.

## Signaler une anomalie

Ouvrez un ticket avec le modèle « Anomalie » du dépôt concerné. Indiquez la version utilisée,
la version du langage, les étapes pour reproduire, le résultat attendu et le résultat obtenu.
Un exemple minimal qui reproduit le problème nous fait gagner beaucoup de temps.

Une faille de sécurité ne se signale **jamais** dans un ticket public : suivez
[SECURITY.md](SECURITY.md).

## Proposer une évolution

Ouvrez un ticket avec le modèle « Évolution ». Décrivez le besoin avant la solution : le cas
d'usage, ce qui manque aujourd'hui, et ce que vous proposez. Nous répondons dans le ticket.

## Les pull requests

Le code de nos dépôts est développé et testé dans notre environnement interne, puis publié
ici sous la forme d'une version. En conséquence :

1. Une pull request est **lue avec attention**, comme un ticket détaillé.
2. Si l'idée est retenue, **l'équipe la reprend** et l'intègre à une prochaine version.
3. La pull request **n'est pas fusionnée telle quelle** : elle est fermée avec un lien vers la
   version qui reprend l'idée.
4. Les contributeurs dont l'idée est reprise sont **remerciés dans le CHANGELOG.md** du dépôt.

En proposant une pull request, vous acceptez que son contenu soit repris sous la licence du
dépôt concerné.

## Règles de code

- Tests à jour pour tout changement de comportement.
- Pour PHP : `declare(strict_types=1);`, classes `final`, types déclarés partout, style
  PER Coding Style, analyse statique PHPStan au niveau maximal.
- Messages et documentation sans emoji, avec des exemples qui fonctionnent réellement.

## Code de conduite

La participation à nos dépôts est régie par notre [code de conduite](CODE_OF_CONDUCT.md).

## In English

Issues are welcome: please use the "Anomalie" (bug) or "Évolution" (feature request) forms.
Pull requests are read carefully; when the idea is accepted, our team reimplements it in a
future release and the pull request is closed with a link to that release, rather than merged
as is. Contributors are credited in the repository's CHANGELOG.md. Never report a security
issue in a public issue: see SECURITY.md.

---
— Conçu et développé par PolygonLab · polygonlab.ai · Licence MIT
