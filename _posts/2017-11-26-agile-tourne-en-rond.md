---
title: Pourquoi l'agile tourne en rond ?
description: >
  Travailler par itération ne vous garantit pas de faire les choses les plus
  utiles, c'est pour cela qu'il vous faut aussi veiller à protéger l'attention
  de vos équipes pendant la phase exploratoire.
image: /assets/img/2017/11/circles.png
source:
  author: Ryan Singer
  title: Running in Circles
  url: https://m.signalvnoise.com/running-in-circles-aae73d79ce19
---

[Basecamp](https://basecamp.com/about), anciennement 37 signals, est la société
éditrice du logiciel de gestion de projet bien connu du même nom. Elle est
également connue pour avoir initié le développment du framework [Ruby on
Rails](http://rubyonrails.org/), ainsi que pour la publication de livres majeurs
comme [Getting Real](https://basecamp.com/books/getting-real),
[Rework](https://basecamp.com/books/rework) et
[Remote](https://basecamp.com/books/remote).
Basecamp est un PME américaine qui connait un fort succès, elle est reconnue
pour son management sain et pragmatique. La direction privilégie une croissance
lente mais soutenue et qui favorise l'équilibre et le bien-être de ses salariés.
[Ryan Singer](https://twitter.com/rjs), en charge de la stratégie produit,
partage au travers de cet article ce qui pourrait simplement passer pour du bon
sens aux yeux de certains, mais qui est malheureusement encore bien trop souvent
oublié par les équipes et la direction qui sous-estiment toujours la difficulté
de concevoir un logiciel utile et performant.
La confrontation au plus tôt avec le réel, la priorisation, la confiance, la
préservation de l'attention, autant de choses essentielles ici appliquées à la
lettre alors que ces aspects sont encore bien trop souvent négligés dans les
projets numériques.
{: .lead }

## Pourquoi l'agile ne marche pas et ce que nous faisons différemment

{% cloudinary /assets/img/2017/11/circles.png %}

Au départ, l'agile était [un ensemble de
valeurs](http://agilemanifesto.org/iso/fr/manifesto.html). Mais ces valeurs sont
subtiles et abstraites. Et lorsque l'agile s'est répandu, ce ne sont pas les
valeurs qui se sont propagées mais le travail en cycles. Les cycles c'est simple
à expliquer et facile à copier.

Dans notre industrie, les gens pensent donc qu'ils ont arrêté de faire du cycle
en V et qu'ils sont passés à l'agile. La vérité, c'est qu'ils sont simplement
passés à du cycle en V à haute-fréquence.

L'agile est devenu synonyme de rapidité. Tout le monde veut toujours plus,
toujours plus vite. Et une des choses que les équipes ne font jamais assez vite,
c'est livrer. Les cycles sont donc devenus des *sprints* et la *vélocité* est
devenue la métrique de référence.

Mais ce n'est pas la vitesse le vrai problème. Et les cycles à eux-seuls ne vous
aideront pas à livrer. Le vrai problème, c'est de ne pas faire ce qu'il faudrait
faire, de suivre des spécifications à la lettre et de se laisser distraire.

Déclarer qu'il y a une vraie *Méthode Agile™* quelque part dans le passé ou le
futur n'est pas non plus d'une grande aide. Quand vos équipes bataillent pour
livrer, vous avez besoin d'étapes concrètes que vous pouvez appliquer dès à
présent, pas de viser un idéal.

Les cycles c'est chouette. [Nous travaillons par
itérations](https://m.signalvnoise.com/how-we-set-up-our-work-cbce3d3d9cae) chez
Basecamp. Mais en plus des cycles, vous avez besoin de trois autres pratiques
pour pouvoir livrer à temps et en bonne santé.

### Une allocation de ressources réfléchie

Les concepteurs et les développeurs n'avanceront pas dans leurs tâches si leur
attention est constamment requise par d'autres personnes. Peu importe que le
support ait trouvé une anomalie ou que le commercial ait besoin d'une nouvelle
fonctionnalité. Allouer des ressources signifie **dédier** des ressources. Les
personnes responsables de l'attribution du temps et de l'argent pour développer
une fonctionnalité doivent également protéger l'équipe afin qu'elle puisse faire ce
qui lui est demandé. L'équipe fait *une* chose et *une seule* pendant le cycle.

Chez Basecamp, nous démarrons chaque cycle de travail avec une équipe de trois
personnes : un designer et deux développeurs. Ils n'ont rien d'autre à faire que
ce projet.

Aussi, si vous sentez que vous devez corriger les anomalies dès qu'elles se
produisent, alors dédiez des ressources à cela. Si une tension existe entre le
service des ventes et le produit, faites un choix pour ce cycle-là. Si vous
n'avez pas assez d'effectifs, alternez les cycles entre chaque service.

Notez que seul le management peut être garant de l'attention. Dire à l'équipe de
rester concentrée ne fonctionne que si la direction les aide dans cette tâche.

### Des exigences modifiables

Lorsqu'une équipe travaille d'après des spécifications précises, le travail par
itération ne sert à rien, le but du travail incrémental étant de pouvoir changer
de direction en cours de route. Or, définir le projet à l’avance et dans les
moindres détails oblige l’équipe à fonctionner en cycle en V. En se devant de
respecter ces spécifications à la lettre, les équipes n’ont ainsi aucune marge
de manœuvre lorsque quelque chose s’avère plus difficile ou moins important que
prévu, ou encore lorsque la réalité contredit le plan établi.

Chez Basecamp, nous démarrons chaque projet avec un concept de base. Nous
étudions bien notre stratégie en amont de manière à nous assurer qu'**une des
versions** de notre idée est réalisable dans le temps alloué. Nous savons bien
que le concept ne sera pas forcément livré à 100%. Tout ne pourra pas être
fait, mais les choses importantes le seront. Si nous ne sommes pas sûrs, nous
mettrons autre chose dans le cycle afin de pouvoir revenir ultérieurement sur
une fonctionnalité une fois que nous aurons suffisamment affiné son concept.

Pour que vos équipes puissent démarrer de cette manière, vous devez séparer
l'essentiel du superflu. Séparer les choses qui sont vraiment primordiales de
celles qui sont simplement <q>une idée qu'on a eu pour y parvenir</q>.

Une simple décision relative à l'interface utilisateur peut entrainer une
semaine de travail inutile. Un développeur peut batailler avec la
refactorisation d'une partie du code JavaScript pour ensuite s'apercevoir que ce
point de détail n'était pas vraiment primordial pour le concept envisagé. Le
designer avait simplement opté pour cette interaction sans avoir aucune idée du
coût engendré.

En pratique, cela veut dire qu'on donne le pouvoir aux équipes de redéfinir le
périmètre d'intervention. Certaines choses sont essentielles, d'autres non.
L'équipe doit être capable de faire la différence et de faire les choix en
fonction. Afin que ceci soit bien clair pour tout le monde, nous donnons aux
équipes des ébauches sommaires dessinées à la main en début de cycle et passons
plus de temps sur la définition des enjeux de cette fonctionnalité plutôt que
sur les détails spécifiques d'implémentation de l'interface.

{% cloudinary /assets/img/2017/11/esquisse.png
 caption="Une des ébauches de Jason pour l'équipe en charge du développement [des groupes de TODO](https://m.signalvnoise.com/new-in-basecamp-3-to-do-groups-6e19efc65fcc). L'équipe a fini par choisir de ne pas développer les boutons `ajouter` en dessous de chaque groupe." %}

### Stratégies progressives

Les équipes qui suivent la *vélocité* et les *points de story* considèrent le
développement comme un travail linéaire. Or, le développement logiciel n'a rien à
voir avec le déplacement d'un tas de pierres.

{% cloudinary /assets/img/2017/11/deplacer-des-pierres.png %}

Si c'était le cas, on pourrait compter le nombre de pierres, mesurer le temps
nécessaire pour en déplacer une, faire nos calculs et ce serait terminé.

Une tâche qui nécessite de résoudre un problème ressemble plus à une colline. Il
y a une phase ascendante dans laquelle on doit comprendre ce qu'il faut faire.
Puis arrivé au sommet, on peut voir l'autre versant et le chemin qu'il reste à
parcourir.

{% cloudinary /assets/img/2017/11/uphill-strategy.png %}

La phase ascendante est pleine de faux pas, de boucles et d'impasses. C'est là où
on se confronte à l'inattendu. Le développeur dit "OK, ça va prendre deux jours"
mais ensuite il va toucher au code et la réalité va s'avérer bien plus complexe.
Ou bien le designer va dire "cette interaction sera parfaite" et quand il la
testera sur un appareil, il se rendra compte que ce n'est pas ce à quoi il
s'attendait.

La question la plus importante pour une équipe n'est pas <q>Que reste-t-il à
faire ?</q> mais <q>Qu'est-ce qu'on ne sait pas encore ?</q> Avez-vous examiné
le problème sous tous les angles&nbsp;?
Avez-vous poussé le concept et vu tout ce qui a besoin d'être modifié&nbsp;?
La seule manière d'en être sûr est de relever ses
manches et d'aller se confronter à la réalité des problématiques.

Chez Basecamp, nos équipes partent en quête des recoins inexplorés les plus
effrayants et travaillent en priorité dessus. Ce travail en amont nécessite
d'adopter des stratégies. Nous les avons évoquées dans [Getting
Real](https://basecamp.com/books/getting-real). Ouvrez votre éditeur de code,
concevez quelque chose de fonctionnel, utilisez de vraies données et testez
votre concept. Lorsque la fonctionnalité est trop importante pour être déclinée
en prototype, sélectionnez les parties les plus importantes et affinez-les.

{% cloudinary
 /assets/img/2017/11/phases-de-travail.png
 caption="Les différentes phases du travail en amont et en aval" %}

La phase ascendante, c'est celle où vous prenez connaissance des difficultés et
où vous portez des jugements de valeur. C'est à ce moment-là que vous décidez
quelles sont les **exigences modifiables** car vous connaissez les coûts réels
et les opportunités dans l'implémentation. Apprendre en amont demande du temps
et de la concentration. Ce sont des ressources qui doivent être **allouées de
manière réfléchie** aux équipes.

Nous travaillons de manière informelle depuis de nombreuses années en nous
focalisant sur les inconnues et en nous y attaquant en priorité. Nous avons
récemment formalisé cela avec le *graphique de la colline*. Une question que nous
nous posons beaucoup ces temps-ci est <q>Où est-ce que cela se situe sur la
colline&nbsp;?</q>.

Voici une capture d'écran de la fonctionnalité du projet de [recherche
intégrée](https://m.signalvnoise.com/new-search-and-more-in-basecamp-3-2a34020be96)
que nous avons livré en octobre.

{% cloudinary
  /assets/img/2017/11/search-in-place-graph.png
  caption="D'abord nous avons retravaillé les résultats de recherche, puis nous les avons déplacé dans la navigation." %}

Voici quelques-unes des étapes du projet sur les [groupes de To-Do](https://m.signalvnoise.com/new-in-basecamp-3-to-do-groups-6e19efc65fcc).

{% cloudinary
 /assets/img/2017/11/to-do-groups-graph.png
 caption="Les trois parties les plus importantes ont passé le sommet en premier." %}

{% cloudinary
 /assets/img/2017/11/to-do-groups-october-graph.png
 caption="Fin de la descente" %}

### Livrer est l'affaire de tous

Que les équipes travaillent en cycles ou non, ne dit pas tout de l'histoire. Une
équipe *agile* n'ira pas très loin si le management ne protège pas le temps
alloué. Et si l'équipe ne peut pas changer les contraintes pendant qu'elle
apprend, c'est l'assurance de passer des nuits courtes et de livrer en retard.

Les designers et les développeurs peuvent apprendre les stratégies progressives
dans [Getting Real](https://basecamp.com/books/getting-real) afin de gagner en
assurance au lieu de se contenter d'espérer en croisant les doigts. La personne
qui définit les besoins peut donner aux équipes la marge de manœuvre nécessaire
en les délimitant clairement pendant la phase exploratoire. Et les personnes qui
allouent les ressources peuvent davantage se responsabiliser pour faire en sorte
de maintenir l'attention de leurs équipes sur le projet en cours.

Cela fait 15 ans que nous procédons de la sorte. Nous espérons que le fait de
partager quelques-unes de ces techniques vous aidera à en faire de même.
