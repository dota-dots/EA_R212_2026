Rapport — [TD3]

- Points clés
1. [le modèle événement → état → rendu]

Nous avons pu voir au cours de ce TD3, les notions de base pour Java Script dont le modèle " événement → état → rendu "
Il permet de comprendre une partie du code en JS par plusieurs points :
 - "Evenement" : Quelle(s) action(s) est provoquée(s) ? 
 - "Etat" : Ou on en est ?
 -"Rendu" : Qu'est ce que ca à changer apres cette action ?
Par exemple, si nous prenons :

const bouton = document.querySelector('.changer');
const texte = document.querySelector('.message');

bouton.addEventListener('click', () => {
affichage.textContent = 'Salut';
}); 

L'evenement ici est lorsquon clique sur le bouton "click". L'Etat est lorsque ca change de texte quand l'action est exécuté. Le rendu est donc le texte changer qui est affiché "Salut"

2. [classList.toggle]

Expliquez en quoi classList.toggle est la passerelle entre JS et CSS
 Le JS ajoute/retire des classes, le CSS définit ce que ces classes changent visuellement.
classList.toggle est une passerelle entre JavaScript et CSS, car il permet d’ajouter ou de retirer une classe sur un élément HTML dans lequel le CSS applique le style associé à cette classe.

4. Modifier le contenu

[Explication en 1-2 phrases avec vos mots.]
### 3. [Titre du troisième point]

[Explication en 1-2 phrases avec vos mots.]
 
 Utilisation de l'IA
Démarche

[Quel outil avez-vous utilisé ? (modèle, version, interface) Dans quel but : comprendre un concept,
déboguer, générer du code, reformuler, autre ?]

### Apports et limites

[Ce que l'IA vous a aidé à faire. Ce qui n'a pas fonctionné ou
que vous avez dû corriger vous-même.]

### Prompts significatifs

1. "[Prompt]" → [Ce que ça a donné / pourquoi ce prompt était utile]
2. "[Prompt]" → [Ce que ça a donné]
3. "[Prompt]" → [Ce que ça a donné]

<!-- Si aucune IA n'a été utilisée, remplacez tout le bloc ci-dessus par :
"Aucune IA utilisée lors de cette séance." -->
