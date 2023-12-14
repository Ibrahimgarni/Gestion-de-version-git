# Gestion-de-version-git
TP GIT
Travail Pratique : Gestion de Version avec Git et GitHub


Contexte

Vous travaillez en équipe de 3 personnes.
Votre tâche consiste à apporter des modifications à une application web. Ces modifications sont divisées en 6 tickets (2 par membre de l'équipe).
Pour collaborer efficacement, vous utiliserez Git. Chaque ticket correspond à une branche distincte.
Toutes ces branches devront être fusionnées dans la branche principale, 'Main', qui contiendra le code intégrant toutes les modifications. Pour maintenir un historique clair des fusions, utilisez exclusivement des fusions 'merge no fast forward', créant ainsi un commit de fusion, plutôt que des fusions 'merge fast forward'.
La gestion des conflits est un aspect important de ce travail : les tickets sont conçus pour que vous modifiez parfois les mêmes lignes de code sur des branches différentes, entraînant des conflits. Vous êtes encouragés à documenter votre gestion des conflits par des captures d'écran et des explications, ce qui sera valorisé dans l'évaluation.


Livrables

Vous devez publier votre code et son historique, y compris toutes les branches, sur GitHub. Envoyez-moi par mail le lien de votre dépôt. Assurez-vous que votre dépôt soit public pour que je puisse accéder à votre code.
En plus, compressez votre dossier contenant le code source et le dossier .git, ainsi qu'un document explicatif (si vous en avez rédigé un, par exemple sur la gestion des conflits), et uploadez-le sur MyGes.


Informations supplémentaires

Votre évaluation portera sur votre maîtrise de Git, ainsi que sur l'application des meilleures pratiques et le respect des conventions de nommage. Cependant, la qualité du code fourni ne sera pas un critère d'évaluation.


Liste des tickets

Ticket 1: Remplacement de Texte dans l'Application
● Description : Dans toutes les pages, remplacer le terme "événement" par "fête" (incluant le texte, les titres, le menu, etc.).

Ticket 2: Correction de Bug sur la Page de Détails
● Description : Sur la page de détails de l'événement, corriger le bug affectant l'affichage du pseudo de l'utilisateur ayant créé l'événement (vérifier la ligne 83 du fichier).

Ticket 3: Correction de Style sur le Bouton 'Supprimer'
● Description : Sur la page "Mes événements", ajuster le style du bouton "Supprimer". Lors du survol, le bouton devient orange au lieu de rouge vif. Le code couleur doit être #ff0f0f (Vérifiez le fichier root.css).

Ticket 4: Correction du Titre sur la Page Liste des Événements
● Description : Sur la page listant les événements, le titre actuel est incorrect.
Il doit être changé de "FestiPlan" à "Liste des fêtes".

Ticket 5: Correction de Lien dans le Menu
● Description : Dans le menu, le lien "Liste des événements" redirige actuellement vers une page inexistante. Ce lien doit être modifié pour rediriger vers "event-list.php".

Ticket 6: Correction de Fautes de Frappe et d'Orthographe
● Description : Sur la page de création d'un événement, corriger les fautes de frappe et d'orthographe dans plusieurs labels des champs de saisie.
