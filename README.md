# Pour contribuer à MarbleBowl
 
La contribution au projet MarbleBowl se fait par **pull request** en suivant la philosophie du modèle de branche **GitFlow**.  

**Sommaire**

- [Pourquoi GitFlow](#pourquoi-gitflow)
- [Processus de collaboration](#processus-de-collaboration)
- [Soumettre une pull-request](#soumettre-une-pull-request)


### Pourquoi GitFlow

MarbleBowl est un **projet collaboratif open source**, le processus de développement se fait par **cycle d'itération**, chaque fonctionnalité doit donc être travaillée sur une **branche séparée** (en parallèle), dans le but de séparer le travail de chacun.

La possibilité de créer plusieurs branches rend le développement plus simple pour **collaborer avec plusieurs développeurs sur un projet commun**, en isolant le code en cours de développement de celui qui est terminé.  
Le code en cours de développement doit se trouver **sur une branche parralèle à la branche `develop`**

Une fois la branche poussée et validée par le gestionnaire du projet (via une `pull-request`), la fonctionnalité apparait sur la branche `develop`.

### Processus de collaboration

Pour collaborer au projet MarbleBowl, il est nécéssaire de faire des `pull-request`.   
Lorsque vous débuterez une nouvelle fonctionnalité, la branche branche en cours de développement devra se nommer tel que : `feature-nom-de-la-fonctionnalité`.

Par exemple : `feature-increment-counter`.

Il est préférable de faire des *commits atomiques* (petits commits contenant chacun un petit changement) pour faciliter le code review.

**Branche main**

La branche `main` est la **branche principale**, elle est gérée par le propriétaire du projet.   
À ce moment là, le code est stable, testé et validé; potentiellement éligible pour une **mise en production**.

**Branche develop**

La branche `develop` est la branche commune à tous les developpeurs, elle correspond à la prochaine version de l’application.  
Une fois que le développement d’une fonctionnalité (branche `feature`) est terminé, le code est fusionné sur cette branche.

**Branche feature-**

La branche `feature-` correspodond au code en cours de développement, elle implémente une nouvelle fonctionnalité à embarquer pour la prochaine version de l’application.

### Soumettre une pull-request

une fois que vous avez cloné le projet forké, il est necéssaire de créer une branche pour y soumettre la premère `pull-request` pour la nouvelle fonctionnalité :

1 : Créer une nouvelle branche à partir de `develop` :
`git checkout -b feature-new-branch`;

2 : Ajouter la feature à la **zone de staging** :
`git add <file>`;

3 : Commiter la fonctionnalité :
`git commit -m "commit message"`;

4 : Une fois que la nouvelle fonctionnalité a été poussée sur Git, se rendre sur *Github* et cliquer sur `compare & pull-request`,
puis, sur `Open a pull request`: laisser un commentaire détaillant tout les changements et les avancées de la nouvelle fonctionnalité.

La `pull-request` pourra être lue et commentée par les autres participant et pourra être validée par le propriétaire du projet pour être intégrer à la branche `develop`.# Pour contribuer à MarbleBowl
 
La contribution au projet MarbleBowl se fait par **pull request** en suivant la philosophie du modèle de branche **GitFlow**.  

**Sommaire**

- [Pourquoi GitFlow](#pourquoi-gitflow)
- [Processus de collaboration](#processus-de-collaboration)
- [Soumettre une pull-request](#soumettre-une-pull-request)


### Pourquoi GitFlow

MarbleBowl est un **projet collaboratif open source**, le processus de développement se fait par **cycle d'itération**, chaque fonctionnalité doit donc être travaillée sur une **branche séparée** (en parallèle), dans le but de séparer le travail de chacun.

La possibilité de créer plusieurs branches rend le développement plus simple pour **collaborer avec plusieurs développeurs sur un projet commun**, en isolant le code en cours de développement de celui qui est terminé.  
Le code en cours de développement doit se trouver **sur une branche parralèle à la branche `develop`**

Une fois la branche poussée et validée par le gestionnaire du projet (via une `pull-request`), la fonctionnalité apparait sur la branche `develop`.

### Processus de collaboration

Pour collaborer au projet MarbleBowl, il est nécéssaire de faire des `pull-request`.   
Lorsque vous débuterez une nouvelle fonctionnalité, la branche branche en cours de développement devra se nommer tel que : `feature-nom-de-la-fonctionnalité`.

Par exemple : `feature-increment-counter`.

Il est préférable de faire des *commits atomiques* (petits commits contenant chacun un petit changement) pour faciliter le code review.

**Branche main**

La branche `main` est la **branche principale**, elle est gérée par le propriétaire du projet.   
À ce moment là, le code est stable, testé et validé; potentiellement éligible pour une **mise en production**.

**Branche develop**

La branche `develop` est la branche commune à tous les developpeurs, elle correspond à la prochaine version de l’application.  
Une fois que le développement d’une fonctionnalité (branche `feature`) est terminé, le code est fusionné sur cette branche.

**Branche feature-**

La branche `feature-` correspodond au code en cours de développement, elle implémente une nouvelle fonctionnalité à embarquer pour la prochaine version de l’application.

### Soumettre une pull-request

une fois que vous avez cloné le projet forké, il est necéssaire de créer une branche pour y soumettre la premère `pull-request` pour la nouvelle fonctionnalité :

1 : Créer une nouvelle branche à partir de `develop` :
`git checkout -b feature-new-branch`;

2 : Ajouter la feature à la **zone de staging** :
`git add <file>`;

3 : Commiter la fonctionnalité :
`git commit -m "commit message"`;

4 : Une fois que la nouvelle fonctionnalité a été poussée sur Git, se rendre sur *Github* et cliquer sur `compare & pull-request`,
puis, sur `Open a pull request`: laisser un commentaire détaillant tout les changements et les avancées de la nouvelle fonctionnalité.

La `pull-request` pourra être lue et commentée par les autres participant et pourra être validée par le propriétaire du projet pour être intégrer à la branche `develop`.
