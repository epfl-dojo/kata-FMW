# Kata FBI Most Wanted (FMW)

Le but de ce kata est d'exercer vos connaissances web en créant un quiz 
interactif sur les criminels les plus recherchés par le [FBI].

Ce kata est une suite logique au [Kata-APOD] et fait partie de la collection de
[kata du dojo de l'EPFL].


## À disposition

Le [FBI] tient à jour une page listant les 10 criminels les plus recherchés 
(<https://www.fbi.gov/wanted/topten>) dont les informations sont également 
disponibles via une API (à vrai dire un fichier JSON), disponible sur 
<https://www.fbi.gov/wanted/api>.


## Réalisation

En récupérant les données du JSON, le quiz doit être crée dynamiquement à partir
des données.

Le quiz doit être composé de 5 questions distinctes. Chaque question affiche la
photo (aka mugshot) du criminel et 3 options de réponse : deux noms de criminels
erronés et le nom correct, celui correspondant à la photo (réponse correcte).

En plus de la photo, vous êtes invité à afficher d'autres informations qui
seraient mises à disposition depuis l'API.

Lorsque toutes questions ont été répondues, l'utilisateur est noté (score)
et peut visualiser ses réponses afin de savoir pour lesquelles il a répondu
correctement et savoir quelle était la réponse correcte pour celles où il s'est
trompé.

Il n'y a pas de consigne sur la façon dont sont présentées les questions ; il
est par exemple possible de toutes les afficher sur une même page, ou de créer
un système permettant de voir une question après l'autre, c'est au choix de la
personne réalisant le kata.

Lorsque votre travail est terminé, vous êtes invité à le rendre disponible
sur une [page GitHub](https://pages.github.com/) et à proposer une [pull
request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
sur à dépôt afin de compléter le paragraphe "[Je l'ai fait 💪](#je-lai-fait-)"
ci-dessous, afin que d'autres personnes puissent apprécier votre effort.


## Je l'ai fait 💪

* [@octocat](https://github.com/octocat): [code](https://#) / [app](https://#)  
  Une petite présentation de votre version, par exemple quelles technologies
  vous avez utilisées, qu'est-ce que votre version a spécial, etc...


[FBI]: https://www.fbi.gov
[Kata-APOD]: https://github.com/epfl-dojo/Kata-APOD
[kata du dojo de l'EPFL]: https://github.com/topics/epfl-dojo-kata
