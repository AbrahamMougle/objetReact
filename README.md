### 📝 Mettre à jour les objets d'un état (Défi 1 sur 3) : Corriger les mises à jour incorrectes de l'état

- **Problème résolu :** Correction de trois bugs majeurs de mise à jour d'état : le bouton de score modifiait directement l'objet existant (mutation) sans déclencher de rendu, le champ prénom fonctionnait par chance mais masquait le bug précédent, et le champ nom de famille écrasait tout l'objet en oubliant de copier les autres propriétés, ce qui faisait disparaître le prénom et le score.
- **Compétence acquise :** Application stricte de l'immutabilité des objets dans un état React en combinant l'utilisation du spread operator (`...player`) pour préserver les données existantes et l'appel systématique à la fonction de mise à jour (`setPlayer`) pour déclencher les rendus nécessaires.
- **Lien vers le code :** [Cliquez ici pour voir l'exercice](https://fr.react.dev/learn/updating-objects-in-state)
