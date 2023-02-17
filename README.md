# M413 - TD1 : Réponses aux Questions

➢ Quel sera l’évènement qui déclenchera l’appelle de votre fonction ?
OnLoad.

➢ Quelle méthode avez-vous utilisée pour récupérer l’objet représentant votre balise <h1> ?
document.getElementById("title");

➢ Quelle propriété de l’objet représentant votre balise <h1> avez-vous utilisée pour récupérer le texte de celui-ci ?
textContent;

➢ Quelle(s) méthode(s) avez-vous utilisée pour récupérer l’objet représentant la première balise <h2> ?
document.querySelector("h2")

➢ Comment faire pour connaitre le nombre de balise <h2> du document ?
il suffit de prendre les elements avec le tag h2 et prendre la longueur du tableau retourné : document.getElementsByTagName("h2").length;

➢ Quelle méthode avez-vous utilisée pour récupérer les objets de votre classe ?
getElementsByClassName.

➢ Comment avez-vous déterminé si un nombre est pair ?
document.getElementsByClassName("firstOrLast") % 2.

➢ Quelles différences existe-t-il entre les 3 propriétés innerHTML, innerText et textContent ?
textContent prend uniquement le texte en ignorant les balises.
innerHTML prend en compte le texte et les balise.
innerText prend en compte le texte et son formattage (majuscule minuscule etc..).

➢ Comment modifier votre code pour qu’il permette de sélectionner le 1
er auteur de la liste ? On peut faire un querySelectorAll afin d'obtenir un tableau et sélectionner le premier élément.

➢ Même question avec le dernier auteur de la liste
On peut faire un querySelectorAll afin d'obtenir un tableau et sélectionner le dernier élément.

➢ Comment obtenez-vous le nombre de jours ?
J'obtiens le nbr de jours en calculant l'écart entre la date actuelle et la date ciblée.

➢ Comment faites-vous la mise à jour du texte ?
Grâce à l'évènement onClick.

➢ Laquelle des deux méthodes de l’objet window avez-vous utilisé ? 
Je n'ai pas utilisé l'objet windows directement, j'ai fait des fonctions avec setInterval et setTimeout.

➢ Quel évènement avez-vous utilisé ?
J'ai ajouté un listener sur l'evenement input.

➢ Comment avez-vous fait changer la couleur du champ texte ?
J'ai redéfinis className.