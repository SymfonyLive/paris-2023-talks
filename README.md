# [Symfony Live - Paris 2023](https://live.symfony.com/2023-paris/) talks

- All talks are in **french**.
- You can send feedback and love to speakers on their twitter account
- See [all tweets](https://twitter.com/search?q=(%23symfonylive%20OR%20%23symfony_live)%20until%3A2023-03-25%20since%3A2023-03-23%20-%23LuckyWebby&src=typed_query&f=top) during the event

## Keynote

[Slides](https://speakerdeck.com/fabpot/s)  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)  
![mastodon](icon/mastodon.png) [@fabpot@mastodon.social](https://mastodon.social/@fabpot)

---

## Réinventer le composant Console de Symfony

<dl>
  <dt>Description</dt>
  <dd>Console est le composant Symfony le plus utilisé. Des outils critiques comme Composer jusqu'aux autres frameworks PHP populaires, en passant par nos applications finales, il est omniprésent.

L'inconvénient de cela est que changer quoi que ce soit n'est pas une mince affaire. Même le plus petit bug fix est susceptible de casser des milliers d'usages. Néanmoins, le composant s'améliore constamment grâce aux innombrables contributions qu'il reçoit depuis son introduction en 2010, tout en conservant sa rétrocompatibilité.

Mais nous pensons qu'il est temps de faire peau neuve, notamment pour ouvrir le composant à davantage de possibilités et le débarrasser de certains problèmes de design. C'est pourquoi nous, quelques contributeurs clés dont Théo Fidry, Kevin Bond et moi-même, avons travaillé intensivement à le revisiter. C'est ce ce que je vais vous présenter dans ce talk.

Préparez-vous à redécouvrir la Console !</dd>
</dl>

[Slides](https://speakerdeck.com/chalasr/reinvent-symfony-console)  
~~Video~~

By [Robin Chalas](https://connect.symfony.com/profile/chalas_r)  
![github](icon/github.png) [@chalasr](https://github.com/chalasr)  
![twitter](icon/twitter.png) [@chalas_r](https://twitter.com/chalas_r)  
![mastodon](icon/mastodon.png) [@chalasr@phpc.social](https://phpc.social/@chalasr)

---

## Bienvenue dans le monde merveilleux des systèmes distribués !

<dl>
  <dt>Description</dt>
  <dd>Pour la plupart d’entre nous, installer une application PHP + MySQL sur une seule machine n’est plus qu’un souvenir d’un lointain passé — ou une légende racontée au café. Désormais, nous développons des plateformes composées de dizaines de services, que nous assemblons à travers « le réseau ». Nous concevons, déployons et essayons de maintenir des systèmes distribués.

Mais qu’est-ce qu’un système distribué ? Quelles contraintes subit-il ? Et surtout, quels dangers devons-nous anticiper quand nous architecturons des applications distribuées que nous souhaitons efficientes, performantes et résilientes ?

Transactions à travers plusieurs serveurs, stockage et cache, microservices et communication asynchrone : autant de préoccupations qui deviennent notre quotidien et que nous découvrirons ensemble ! Nous plongerons aussi dans des scénarios de pannes classiques et décrirons des architectures et solutions pour nous en protéger.
Bienvenue dans le monde merveilleux des systèmes distribués !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Pascal Martin](https://connect.symfony.com/profile/pmartin)  
![github](icon/github.png) [@pmartin](https://github.com/pmartin)  
![twitter](icon/twitter.png) [@pascal_martin](https://twitter.com/pascal_martin)  
![mastodon](icon/mastodon.png) [@pascal_martin@mastodon.social](https://mastodon.social/@pascal_martin)

---

## Il était une fois le composant Workflow

<dl>
  <dt>Description</dt>
  <dd>La conférence présentera l'utilisation du composant Workflow de Symfony sur un projet au sein de Sézane, en se basant sur des exemples concrets pour expliquer comment le composant a été mis en place et utilisé en premier lieu en mode "workflow", puis comment l'implémentation a été entièrement revue pour passer en mode "state machine" plus adapté. Le talk détaillera les étapes de la mise en place, les interrogations rencontrées, les possibilités offertes par le composant, et les ajustements effectués pour arriver à une implémentation efficace.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Florence Cauchy](https://connect.symfony.com/profile/fcauchy)  

---

## Jongler en asynchrone avec Symfony HttpClient

<dl>
  <dt>Description</dt>
  <dd>Si faire des requêtes HTTP est une pratique bien ancrée, la gestion de leurs réponses le semble un peu moins. Les blocages qu'elles peuvent engendrer peuvent très vite devenir un goulot d’étranglement dans les performances d’une application.

Je vous propose de voir comment, grâce à un outil un peu méconnu qui se présente sous forme d’un trait du composant Symfony HttpClient, nous avons pu gagner de la largesse dans la manipulation des réponses de nos requêtes tout en préservant au maximum la notion d’asynchronicité.

Nous allons voir ensemble les contextes d’application auxquels l’AsyncDecoratorTrait serait destiné et quels en seraient ses avantages tout comme ses limites. Mais également de voir en quoi il se distingue de la décoration qu’on pourrait faire au niveau de la requête ou de la réponse reçue.

Alors prêt ? Traçons!</dd>
</dl>

[Slides](https://speakerdeck.com/alli83/jongler-en-asynchrone-avec-symfony-httpclient)  
~~Video~~  

By [Allison Guilhem](https://connect.symfony.com/profile/a_guilhem)  
![github](icon/github.png) [@alli83](https://github.com/alli83)  
![twitter](icon/twitter.png) [@Alli_g83](https://twitter.com/Alli_g83)

---

## SQLite en production ? Et si vous réévaluiez vos options ?

<dl>
  <dt>Description</dt>
  <dd>Si vous utilisez fréquemment des SGBD tels que MySQL, PostgreSQL ou MongoDB pour stocker des informations, vous savez probablement qu'utiliser ces SGBD peut causer des soucis lorsque vous devez effectuer une mise à l'échelle ou réduire le temps de réponse de l'application. Il existe une solution open-source appelée SQLite qui est entièrement serverless, tourne en production dans des sous-marins et sur vos téléphones, et ne requiert ni Docker ni exécutable. SQLite a été conçu pour résoudre des problèmes spécifiques, mais peut également aider à résoudre des problèmes de coûts, de mise à l'échelle, de gestion de localisation, etc. Dans ce talk, nous discuterons des avantages de l'utilisation de SQLite dans nos applications pour réduire le temps de réponse, l'utilisation de ressources et améliorer l'expérience utilisateur.</dd>
</dl>

[Slides](https://speakerdeck.com/guikingone/sqlite-en-production-et-si-vous-reevaluiez-vos-options)  
~~Video~~

By [Guillaume Loulier](https://connect.symfony.com/profile/guikingone)  
![github](icon/github.png) [@Guikingone](https://github.com/Guikingone)  
![twitter](icon/twitter.png) [@Guikingone](https://twitter.com/Guikingone)

---

## Symfony et Hotwire : faire un front interactif sans trop d'efforts

<dl>
  <dt>Description</dt>
  <dd>En décembre 2020, 37 Signals a publié la première version officielle de la suite Hotwire. En combinant la bibliothèque historique Turbolinks avec leur micro-framework Stimulus js, il en ressort un combo puissant pour faire des applications complexes tout en codant une application Rails fullstack. L'équipe Symfony n'a pas tardé à porter le projet sur son écosystème, et les résultats sont étonnants !

Chez Windoo, nous utilisons le composant symfony/ux-turbo depuis début 2021 pour remplacer progressivement notre code hérité de React. Nous avons beaucoup appris sur la façon de l'utiliser, les bonnes pratiques à suivre, les erreurs à éviter et les cas d'utilisation délicats à résoudre.

Formulaires, messagerie, modales, asynchrones... Je vous montrerai des applications très concrètes de cette bibliothèque dans vos projets !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Florent Destremau](https://connect.symfony.com/profile/florentdestremau)  
![github](icon/github.png) [@florentdestremau](https://github.com/florentdestremau)  
![twitter](icon/twitter.png) [@FloDestremau](https://twitter.com/FloDestremau)

---

## Du social à la tech - plaidoyer en faveur des profils atypiques

<dl>
  <dt>Description</dt>
  <dd>En m'appuyant sur mon parcours de trois ans de reconversion et sur des exemples concrets, je vais petit à petit dérouler un plaidoyer pour l'inclusion de profils atypiques dans la tech. Durant cette conférence je donnerai un contexte à la question du manque de diversité dans les équipes tech, j'apporterai des pistes d'améliorations mais surtout j'expliquerai pourquoi cette diversité est vitale à notre industrie.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Magali Milbergue](https://connect.symfony.com/profile/magali_milbergue)  
![github](icon/github.png) [@TheDaisyMoon](https://github.com/TheDaisyMoon)  
![twitter](icon/twitter.png) [@MagaliMilbergue](https://twitter.com/MagaliMilbergue)  
![mastodon](icon/mastodon.png) [@daisymoon@hachyderm.io](https://hachyderm.io/@daisymoon)

---

## Les génériques (en PHP)

<dl>
  <dt>Description</dt>
  <dd>Les génériques sont un concept des langages de programmation. En bref, ils permettent d'écrire du code typé mais sans être spécifiquement lié à un type particulier. Beaucoup de langages supportent déjà les génériques plus ou moins nativement : Java, C#, Go, Rust Typescript... Ce n'est pas le cas de PHP, mais grâce à sa communauté et son ecosystème, il est tout de même possible de les utiliser. Je vous propose de voir comment et dans quel but, en s'appuyant sur l'exemple de composants Symfony.</dd>
</dl>

[Slides](https://slides.com/kpn13/les-generiques-en-php)  
~~Video~~  
[Examples](https://github.com/kpn13/generics-php)

By [Karim Pinchon](https://connect.symfony.com/profile/kpinchon)  
![github](icon/github.png) [@kpn13](https://github.com/kpn13)  
![twitter](icon/twitter.png) [@kpn13](https://twitter.com/kpn13)  
![mastodon](icon/mastodon.png) [@kpn13@phpc.social](https://phpc.social/@kpn13)

---

## Concevoir son API pour le futur

<dl>
  <dt>Description</dt>
  <dd>Concevoir une API est complexe, la preuve en est la quantité de technologies inventées pour tenter de le simplifier et l'uniformiser : REST, GraphQL, HAL, JSON-LD, Hydra...

Concevoir une API pour le futur, c'est s'assurer de sa stabilité sur le long-terme : stabilité des formats en entrée/sortie, gestion du versionning et des deprecations, inclusion des sous-ressources, communication des changements aux consomateurs...

Discutons ensemble de ces challenges et de comment les adresser dans le cadre d'une API Symfony.</dd>
</dl>

[Slides](https://speakerdeck.com/tgalopin/concevoir-son-api-pour-le-futur)  
~~Video~~  
[Package](https://github.com/selency/openapi)

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)  
![mastodon](icon/mastodon.png) [@tgalopin@phpc.social](https://phpc.social/@tgalopin)

---

## Symfony UX sans NPM ni WebPack ! #UseThePlatform

<dl>
  <dt>Description</dt>
  <dd>Node, Yarn, NPM, pnpm, Babel, SWC, Webpack, TurboPack, Rollup, Parcel... Ces outils sont-ils vraiment nécessaires pour créer un site web beau et interactif à l'aide de JavaScript ?

L'initiative Symfony UX a grandement simplifié la façon de construire la partie "front" des projets Symfony en revenant aux sources : HTML généré côté serveur (adieu JSX, notre bon vieux Twig est de retour), et JavaScript minimaliste grâce à Hotwire. Cependant, pour utiliser Symfony UX, vous devez toujours installer, configurer et maintenir une suite d'outils JS complète... et complexe. Et ce n'est pas une partie de plaisir.

Mais est-ce encore vraiment nécessaire ? Les navigateurs ont récemment gagné des fonctionnalités permettant de se passer de la plupart d'entre elles. Voyons comment se débarrasser de cette complexité en utilisant la plateforme web !</dd>
</dl>

~~Slides~~  
~~Video~~  
[Symfony's Pull Request](https://github.com/symfony/symfony/pull/48371)

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)  
![mastodon](icon/mastodon.png) [@dunglas@mastodon.social](https://mastodon.social/@dunglas)

---

## Les tests dans une application Symfony

<dl>
  <dt>Description</dt>
  <dd>Écrire des tests pour son projet est une assurance pour l'efficacité de développement et pour la chaîne de livraison du logiciel. Dans Symfony, on utilise PHPUnit pour cela, et on dispose de facilités pour écrire des tests fonctionnels.

En mettant en pratique la documentation, on se retrouve confronté à des questions comme : comment avoir une suite de tests maintenable ? dois-je faire des tests unitaires ou fonctionnels ? comment gérer les dépendances aux services tiers dans les tests ? comment je teste l'envoi de mails ? comment je dois organiser mes données de tests ?

Cette conférence est le résumé de plus de 10 ans de pratique de tests automatisés avec Symfony.</dd>
</dl>

[Slides](https://speakerdeck.com/alexandresalome/les-tests-dans-une-application-symfony)  
~~Video~~

By [Alexandre Salomé](https://connect.symfony.com/profile/alexandresalome)  
![github](icon/github.png) [@alexandresalome](https://github.com/alexandresalome)  
![twitter](icon/twitter.png) [@alexandresalome](https://twitter.com/alexandresalome)

---

## Se préparer à la certification Symfony - et au-delà

<dl>
  <dt>Description</dt>
  <dd>Lorsque j'ai envisagé pour la première fois la certification Symfony, je ne savais pas du tout par où commencer. Après avoir paniqué devant l'ampleur de la tâche, j'ai réalisé que j'avais juste besoin d'une bonne feuille de route pour commencer !

Nous allons parler méthodologie, outils, calendrier, ressources. Pas de recettes magiques, seulement des trucs et astuces qui m'ont aidée à trouver le chemin vers l'examen final. Et puis j'expliquerai comment tout cela peut s'appliquer à *tout* besoin d'auto-formation.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Camille Jouan](https://connect.symfony.com/profile/ca-jou)  
![github](icon/github.png) [@Ca-Jou](https://github.com/Ca-Jou)  
![twitter](icon/twitter.png) [@camillepauron](https://twitter.com/camillepauron)

---

## Retour sur 12 mois d'innovations

<dl>
  <dt>Description</dt>
  <dd>Il s'est passé beaucoup de choses depuis un an ! 52 billets de blog pour vous tenir au courant de toutes les nouveautés, un tas de "pull requests", deux nouvelle versions, des fonctionnalités en pagaille... Eh bien, je suis sûr que vous avez raté quelque chose. Revenons ensemble sur ce qui s'est passé ces 12 derniers mois dans l'écosystème Symfony.</dd>
</dl>

[Slides](https://speakerdeck.com/nicolasgrekas/whats-new-in-early-2023)  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)  
![mastodon](icon/mastodon.png) [@nicolasgrekas@phpc.social](https://phpc.social/@nicolasgrekas)
