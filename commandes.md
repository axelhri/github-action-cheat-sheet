# Commandes diverses

## Types de déclencheurs d'événements

### Push

- **Syntaxe**: `on: push`
- **Description**: Ce déclencheur active un workflow chaque fois qu'un commit est poussé vers le dépôt. Il peut être configuré pour réagir à des poussées sur des branches ou des tags spécifiques.

### Pull Request

- **Syntaxe**: `on: pull_request`
- **Description**: Active un workflow lorsqu'une action est effectuée sur une Pull Request, comme sa création, sa mise à jour, ou sa fermeture. Ce déclencheur est utile pour automatiser des tests ou des vérifications de code avant la fusion d'une Pull Request.

### Schedule

- **Syntaxe**: `on: schedule`
- **Description**: Permet de planifier l'exécution d'un workflow à des moments précis, en utilisant la syntaxe cron. Ce déclencheur est idéal pour des tâches récurrentes, comme des mises à jour quotidiennes ou des vérifications régulières de l'état du dépôt.

### Workflow Dispatch

- **Syntaxe**: `on: workflow_dispatch`
- **Description**: Ce déclencheur permet de lancer manuellement un workflow depuis GitHub, offrant une flexibilité pour exécuter des workflows selon les besoins, sans attendre un événement automatique.

### Autres Événements

- **Syntaxe**: `on: <event_name>`
- **Description**: GitHub Actions supporte une variété d'autres événements, tels que `issues`, `release`, et `fork`. Chaque type d'événement permet de déclencher des workflows pour des cas d'usage spécifiques, renforçant l'intégration et l'automatisation dans l'écosystème GitHub.
