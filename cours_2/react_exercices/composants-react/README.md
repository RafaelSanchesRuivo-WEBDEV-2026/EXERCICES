# TP : Composants React

### 1. Décomposer le JSX en plusieurs composants
1.1. A partir du code fournit dans le fichier `src/App.tsx` et notamment du JSX. 
Créez 3 nouveaux composants Header, Main et Section que vous appelerez dans le composant principal App.

1.2. La bonne pratique pour organiser ses composants et de créer un dossier components et d'y placer les 
fichiers des différents composants. Pour les 3 composants créés précédemment, placez les chacun dans des
fichiers à part puis importez les dans App.tsx.

### 2. Ajouter du contenur dynamique

2.1. Dans le composant Header, créer une nouvelle fonction getRandomString. 
Cette fonction prendra en entrée un tableau de string.
Elle devra retourner un élément au hasard de ce tableau de string.
Pour cela vous pourriez être intéressé d'utiliser 
Math.random() qui retourne un nombre flottant pseudo-aléatoire entre 0 (inclus) et 1 (exclus)

2.2. Utilisez cette fonction pour afficher aléatoire dans la balise h2 du header une technologie parmis React, Typescript et Vite.

