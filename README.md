`hugolidaires`
=============

Un modèle de site internet pour les sections de l'[Union syndicale Solidaires](https://solidaires.org/) (basé sur [Hugo](https://gohugo.io/))

Le résultat est visible à l'adresse: [`https://hugolidaires.frama.io/site-template/`](https://hugolidaires.frama.io/site-template/) ✨

Une version dérivé pour les sections [Solidaires Informatique](https://solidairesinformatique.org/) est disponible dans la branche [`sol_info`](https://framagit.org/hugolidaires/site-template/-/tree/sodl_info)

Si besoin d'une version pour une nouvelle branche Solidaires, vous pouvez lui créer une branche dédiée et le préciser ici.


Pourquoi ❔
----------

Ce modèle permet de démarrer un site internet [facilement hébergeable/maintenable et léger](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9rateur_de_site_statique) avec une mise en page [aux couleurs Solidaires](https://solidaires.org/sinformer-et-agir/brochures/brochures-et-argumentaires-interpro/) et sa [magnifique typographie](https://ancien.solidaires.org/Police-de-caracteres-logo-Solidaires).

Par ce que les luttes syndicales sont notre raison d'être, maintenir un site internet doit nous prendre le mois de temps possible : fédérer le travail autour de celui-ci est précieux.


Installation ⚙️
---------------

Pour installer ce modèle dans un environnement Linux, suivez ces étapes. Hugo s'[installe aussi avec d'autres OS](https://gohugo.io/installation/), mais ça ne sera pas abordé ici :

1. Installer [`hugo`](https://gohugo.io/installation/linux/) et [`git`](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git)
1. Récupérer les sources du modèle dans un répertoire de travail :
    - `git clone https://framagit.org/hugolidaires/site-template.git`
1. Installer le thème [`beautifulhugo`](https://github.com/halogenica/beautifulhugo) :
    - `git submodule init && git submodule update`
1. Faire tourner 🚀
    - `hugo server -D`

Voilà il y a maintenant un message qui vous indique l'adresse a utiliser dans un navigateur web pour visualiser votre nouveau _solisite_ ✨


Du contenu 📝
-------------

Vous pouvez passer ensuite à la personnalisation du contenu existant et créer le votre.

* Le contenu à personnaliser
    1. [`README.md`](https://framagit.org/hugolidaires/site-template/-/tree/stable/README.md)
    1. [`content/pages`](https://framagit.org/hugolidaires/site-template/-/tree/stable/content/pages)
    1. Et il restera à supprimer la publication en exemple: [`content/posts`](https://framagit.org/hugolidaires/site-template/-/tree/stable/content/posts)
* [Créer du contenu](https://gohugo.io/getting-started/quick-start/#add-content)
    1. générer le fichier vide: `hugo new posts/premiere-publication.md`
    1. ajouter du contenu: `${EDITOR} posts/premiere-publication.md`

Félicitation, votre site est prêt a être disponible publiquement 🎉


Et ensuite 🤔
-------------

Malheureusement pour le reste, il vous faudra faire appel à des compétences qui ne sont pas explicables ici… La force du collectif fait qu'il y aura probablement ce qu'il faut parmi vos camarades.

* hébergement publique
* gestion d'un nom de domaine
* partager vos contributions dans ce modèle
* modifications visuelles
* …


Remerciement 🤝
---------------

Ce projet est avant tout une _conversion en modèle_ et une documentation du travail réalisé par la section syndicale d'entreprise _[Solidaires OCTO](https://solidaires-octo.com/)_, qu'iels en soient _Solidairement remerciés_ !
