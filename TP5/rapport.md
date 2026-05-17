Rapport — [TP5]

1. [classList]

La classList permet d'acceder et de manipuler le CSS et le HTML. Il permet d'ajouter, de supprimer ou de modifier des classes, sans toucher à une propriété de classe spécifique

2. [aria-expanded]
   
Cet attribut d'accessibilité permet de contrôler un élément interactif et d'indiquer si cet élément est ouvert ou fermé. On le retrouve notamment utilisé sur les menus déroulants, accordéons, ou les questions dépliables.

3. [async function]

Utilisez pour les API ou les programmes qui demandent du temps à s’exécuter. C’est une fonction qui permet d’exécuter des opérations asynchrones sans bloquer le reste du programme.
 
 Utilisation de l'IA

1. J'ai utilisé l'IA de Visual Studio Code car je n'avais pas compris le problème : element.style.display = 'none';      // style inline au lieu de classList, il m'a donné :
"  document.getElementById("modale").classList.add("open");
      }

   function fermerModale() {
        document.getElementById("modale").classList.remove("open");
      }"

 CSS : " .modale-overlay.open {
            display: block;
          }"
Tout d'abord cela permet de séparer le JSS et le CSS qui étaient assemblés ensemble. De plus, cela a supprimé "none" car celui-ci écrase les autres styles, contrairement à "open" qui est plus facile à manipuler.

2. Mon focus sur les éléments de mon site ne se voit pas et je ne savais pas comment faire en sorte qu'on puisse le voir, donc j'ai demandé à l'IA de Visual Code. Il a tout d'abord remplacé tous les "span" par "button", logique car c'est une balise sémantique plus efficace et qui ne requiert pas d'attribut tabindex. Le résultat permet de voir l'élément sélectionné avec le tab.

"button:focus,
          .carte-bouton:focus,
          .modale-fermer:focus,
          .filtres-container button:focus {
            outline: 3px solid var(--color-secondary);
            outline-offset: 3px;
          }
"
