# .github

Fichiers communs que GitHub applique aux dépôts de l'organisation
`ecotechceram` (Eco-Tech Ceram).

## Contenu

| Fichier | Rôle |
|---|---|
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Modèle de description d'une pull request |
| [`.github/ISSUE_TEMPLATE/01_bug_report.md`](.github/ISSUE_TEMPLATE/01_bug_report.md) | Signaler un dysfonctionnement |
| [`.github/ISSUE_TEMPLATE/02_feature_request.md`](.github/ISSUE_TEMPLATE/02_feature_request.md) | Proposer une évolution |
| [`SECURITY.md`](SECURITY.md) | Signaler une vulnérabilité |

## Comment GitHub les applique

GitHub utilise chacun de ces fichiers pour tout dépôt de l'organisation qui
n'a pas son propre fichier du même type, quelle que soit sa visibilité. Un
dépôt qui définit ses propres modèles ou sa configuration d'issue dans
`.github/ISSUE_TEMPLATE` n'hérite plus d'aucun modèle d'issue d'ici
([documentation GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)).

Un changement dans ce dépôt s'applique donc aussitôt à tous les dépôts qui en
héritent.

## Ce dépôt est public

Tout ce qui est écrit ici est visible de tous. Il ne contient que des modèles
et des politiques génériques : aucune information interne, aucun nom de
projet, aucune configuration, aucune donnée. Les règles de travail d'un projet
sont dans le dépôt de ce projet.

## Modifier ces fichiers

Toute modification passe par une pull request, validée par le responsable et
fusionnée par un commit de fusion. Personne ne pousse directement sur `main`.
