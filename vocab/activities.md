# Vocabulary: Activity Types

---

- [Learning Activity](#learning)
- [Structural Activity](#structural)
- [Competency](#competencies)
- [Statement Category](#categories)


<a name="learning"></a>
## Learning Activity


### assignment

**IRI:** `http://vocab.xapi.fr/activities/assignment`

Activité de type "devoir" ou "travail personnel". L'apprenant doit suivre les instructions du formateur afin de réaliser un travail, puis le remettre au formateur qui pourra éventuellement l'évaluer. Il peut s'agir d'un travail individuel ou collectif. Ce type d'activité se distingue de l'activité `http://vocab.xapi.fr/activities/workshop` dans le sens où il s'agit d'un travail en relative autonomie, sans présence et animation permanente d'un formateur.


### chat-room

**IRI:** `http://vocab.xapi.fr/activities/chat-room`

Activité dans laquelle prennent place des discussions textuelles en temps réel. Plusieurs sessions ou canaux de discussion peuvent prendre place au sein d'une salle de chat. Chaque discussion, prise indépendamment, utilise le type `http://id.tincanapi.com/activitytype/chat-channel`.


### collaborative-content

**IRI:** `http://vocab.xapi.fr/activities/collaborative-content`

Activité consistant à éditer un contenu de manière collaborative. Le Wiki est un exemple de contenu collaboratif.


### external-activity

**IRI:** `http://vocab.xapi.fr/activities/external-activity`

Activité externe à une plateforme, dont le type ne peut être défini plus précisément. L'accès à l'activité depuis la plateforme peut se faire par un lien ou une intégration LTI par exemple.


### face-to-face

**IRI:** `http://vocab.xapi.fr/activities/face-to-face`

Séance présentiel.


### flight

**IRI:** `http://vocab.xapi.fr/activities/flight`

Séance de vol.


### forum

**IRI:** `http://vocab.xapi.fr/activities/forum`

Activité de type "forum de discussion", c'est à dire un espace dans lequel prennent place une ou plusieurs discussions textuelles et asynchrones. Chaque fil de discussion, pris indépendamment, utilise le type `http://id.tincanapi.com/activitytype/discussion`.


### level-report

**IRI:** `http://vocab.xapi.fr/activities/level-report`

Activité de type "bilan d'étape", c'est à dire une évaluation permettant de vérifier le niveau de l'apprenant à une étape clé de son parcours.


### live-session

**IRI:** `http://vocab.xapi.fr/activities/live-session`

Activité synchrone, pouvant se dérouler en présentiel ou à distance. Ce type d'activité est utilisé à défaut d'un type plus précis.


### poll

**IRI:** `http://vocab.xapi.fr/activities/poll`

Activité de type "vote", constituée le plus souvent d'une seule question ou d'un nombre très limité de questions, utilisé principalement à des fins d'animation de la formation. Cette activité se distingue de l'activité `http://vocab.xapi.fr/activities/survey` par son coté bref et informel.


### quiz

**IRI:** `http://vocab.xapi.fr/activities/quiz`

Questionnaire électronique, constitué d'une série de questions dont la nature peut varier (QCM, association, texte à trou, etc.), donnant généralement lieu à une notation. Les quiz peuvent avoir une visée formative ou sommative. 

### resources

**IRI:** `http://vocab.xapi.fr/activities/resources`

Ensemble de ressources à consulter, quelle que soit la nature de ces ressources (fichiers, liens, vidéos, etc.).


### skills-test

**IRI:** `http://vocab.xapi.fr/activities/skills-test`

Activité de type "évaluation de capacités", c'est à dire une évaluation permettant de vérifier la capacité de l'apprenant à mettre en oeuvre ses connaissances dans un contexte pratique.


### survey

**IRI:** `http://vocab.xapi.fr/activities/survey`

Activité de type "sondage" ou "enquête", qui vise par une série de questions a évaluer des attentes ou collecter des avis. Cette activité se distingue de l'activité `http://vocab.xapi.fr/activities/poll` par une approche plus formelle et systématique.

### web-content

**IRI:** `http://vocab.xapi.fr/activities/web-content`

Contenu constitué d'un ensemble structuré de pages HTML. On ne distingue pas ici la manière dont sont produits et déployés les contenus. Il peut s'agir de packages standardisés (SCORM, IMS CC, CMI5), non standardisés (ZIP + HTML) ou de contenus directement développés au sein de la plateforme.


### web-link

**IRI:** `http://vocab.xapi.fr/activities/web-link`

Lien vers une ressource Web, c'est à dire une page, un site ou un fichier disponible sur le Web. Cela exclut les liens internes à une plateforme, utilisés à des fins de simple navigation.


### web-page

**IRI:** `http://vocab.xapi.fr/activities/web-page`

Contenu constitué d'une seule page HTML. Les contenus plus structurés, composés de plusieurs pages, adoptent pour leur part le type `http://vocab.xapi.fr/activities/web-content`.


### workshop

**IRI:** `http://vocab.xapi.fr/activities/workshop`

Activité de type "atelier", c'est à dire un travail collaboratif autour d'un sujet soumis par le formateur. Cette activité donne généralement lieu à une production collective pouvant être évaluée ou non. Ce type d'activité se distingue de l'activité `http://vocab.xapi.fr/activities/workshop` dans le sens où la présence du formateur en tant qu'animateur joue un rôle primordial.



<a name="structural"></a>
## Structural Activity


### course

**IRI:** `http://vocab.xapi.fr/activities/course`

Ensemble d'activités organisées de manière structurée, visant à réponse à un objectif pédagogique clairement défini. Un cours peut être composé d'activités de diverses natures : contenu, activités sociales, séances présentiels, etc.


### registration

**IRI:** `http://vocab.xapi.fr/activities/registration`

Activité correspondant à une "session de formation", c'est à dire à la mise en oeuvre d'une formation pour un groupe d'apprenants inscrits. Cela fournit une alternative claire à la propriété `context.registration` dont l'usage est plus vague.


### system

**IRI:** `http://vocab.xapi.fr/activities/system`

Système informatique quelconque, permettant aux utilisateurs d'accéder à des activités. Il peut s'agir d'un LMS, d'une plateforme de MOOC, d'un blog, d'une application, etc. 


### training-program

**IRI:** `http://vocab.xapi.fr/activities/training-program`

Programme de formation permettant de traiter un objectif pédagogique très large (ex. master). Un programme est généralement étalé dans le temps et décomposé en périodes (phases) et/ou matières (modules).


### training-phase

**IRI:** `http://vocab.xapi.fr/activities/training-phase`

Période de formation s'inscrivant généralement dans un programme plus large (ex. 1er semestre d'un master). Une phase est généralement étalée dans le temps et peut être décomposée en matières (modules) et/ou activités pédagogiques.


### training-module

**IRI:** `http://vocab.xapi.fr/activities/training-module`

Partie d'un programme de formation focalisant sur une matière précise ou un objectif pédagogique précis. Un module est généralement composé d'activités pédagogiques.




<a name="competencies"></a>
## Competency

### competency-domain

**IRI:** `http://vocab.xapi.fr/activities/competency-domain`

Domaine de compétences, c'est à dire un ensemble de compétences clairement identifiées. 


<a name="categories"></a>
## Statement Category


### granularity-level

**IRI:** `http://vocab.xapi.fr/activities/granularity-level`

Les activités de type "granularity-level" sont utilisées pour marquer les Statements en fonction du niveau de granularité dans lequel se situe l'action. Ce marquage peut être utile pour filtrer les Statements en ne focalisant que sur un certain niveau de détail. Ce type d'activité est inséré dans la propriété `context.contextActivities.category`.


