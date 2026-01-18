# TP : Composants React

### 1. Décomposer le JSX en plusieurs composants
1.1. A partir du code fournit dans le fichier `src/App.tsx` et notamment du JSX. 
Créez 3 nouveaux composants Header, Main et Section que vous appelerez dans le composant principal App.

1.2. La bonne pratique pour organiser ses composants et de créer un dossier components et d'y placer les 
fichiers des différents composants. Pour les 3 composants créés précédemment, placez les chacun dans des
fichiers à part puis importez les dans App.tsx.

### 2. Ajouter du contenu dynamique

2.1. Dans le composant Header, créer une nouvelle fonction getRandomString. 
Cette fonction prendra en entrée un tableau de string.
Elle devra retourner un élément au hasard de ce tableau de string.
Pour cela vous pourriez être intéressé d'utiliser 
Math.random() qui retourne un nombre flottant pseudo-aléatoire entre 0 (inclus) et 1 (exclus)

2.2. Utilisez cette fonction pour afficher aléatoire dans la balise h2 du header une technologie parmis React, Typescript, Vite, CSS et d'autres.

### 3. Import d'image dans un composant

3.1. D'après le cours utiliser la méthode appropriée pour importer le logo React dans le composant Header.

### 4. Utilisation des props

Nous allons construire une liste applatie des concepts vu dans ce cours : 

4.1. Ajoutez une nouvelle balise section native (et non le composant personnalisé que vous avez créé précédemment).
A cette section ajoutez l'id "core-concepts" pour quelle obtienne les attributs css nécessaires.
Ajoutez un titre h2 "Concepts importants".
Placez 2 balises (ouvrante et fermante) ul.

4.2. Créez un nouveau composant CoreConcept qui prend en tant que props un titre, une description et une image. 
N'oubliez pas de typer les props du composant. Pour cela vous pouvez créer un type CoreConceptProps.

Ce composant agira comme un élément de notre liste, donc utilisez les balises les plus judicieuses. 
L'image s'affichera en haut, puis en dessous le titre et enfin la description. 

4.3. Utilisez le tableau dans le fichier data.ts pour créer 4 composants chacun représentant un concept clé de React.

4.4. Trouvez un moyen d'afficher tout ces composants avec une seule ligne de code (vous pouvez vous aidez en cherchant dans les rappels Javascript).



