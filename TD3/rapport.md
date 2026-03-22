Rapport — [TD3]

– Points clés

1. [le modèle événement → état → rendu]
Nous avons pu voir au cours de ce TD3 les notions de base pour Java Script, dont le modèle "événement → état → rendu".
Il permet de comprendre et de décomposer des interactions du code en JS par plusieurs points :

 – "Événement" : Quelle(s) action(s) est provoquée(s) ? 

 – "État" : où on en est ?

 – "Rendu" : qu'est-ce que ça a changé après cette action ?

Par exemple, si nous prenons :

const bouton = document.querySelector('.changer');
const texte = document.querySelector('.message');

bouton.addEventListener('click', () => {
affichage.textContent = 'Salut';
}); 

L'événement ici est lorsque l'on clique sur le bouton "click". L'État est lorsque ça change de texte quand l'action est exécutée Le rendu est donc le texte changé qui est affiché "Salut".

2. [classList.toggle]


 Le JS ajoute/retire des classes, le CSS définit ce que ces classes changent visuellement.
classList.toggle est une passerelle entre JavaScript et CSS, car il permet d’ajouter ou de retirer une classe sur un élément HTML dans lequel le CSS applique le style associé à cette classe.

3. [classList.add]

classList.add permet d'ajouter une classe où on le veut, comme dans body : "body.classList.add".
Il est lié au CSS car celui-ci doit créer une classe si elle est non existante.

 
Aucune IA utilisée lors de cette séance.


