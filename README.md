# projet-individuel
Je suis ravie de te présenter un exercice que j'ai réalisé toute seule en utilisant JavaScript, HTML et CSS. 
Cet exercice consiste en un traducteur de latin en morse et vice versa, J'ai utilisé JavaScript pour gérer les interactions et la logique de traduction, tandis que HTML et CSS m'ont permis de créer une interface utilisateur réactive.

Dans ce code, j'ai utilisé plusieurs fonctionnalités pour réaliser cette traduction, permet-moi de t'expliquer brièvement comment ça fonctionne :

Tout d'abord, j'ai créé une fonction nommée "getLatinCharacterList" qui prend une chaîne de caractères en paramètre et la divise en un tableau contenant chaque caractère, cela nous permet de travailler sur chaque caractère individuellement.

Ensuite, j'ai ajouté un dictionnaire nommé "latinToMorse" qui contient la correspondance entre les caractères de l'alphabet latin et leur équivalent en morse, cela nous aide à traduire chaque caractère correctement.

J'ai également créé une fonction appelée "translateLatinCharacter" qui prend un caractère en paramètre et renvoie sa correspondance en morse en utilisant le dictionnaire "latinToMorse", cette fonction s'assure également que tous les caractères soient en majuscules pour correspondre au dictionnaire.

Dans l'étape suivante, j'ai implémenté une fonction "encode" qui prend une chaîne de texte en latin et utilise la fonction "getLatinCharacterList" pour obtenir une liste de caractères, ensuite, pour chaque caractère, j'utilise la fonction "translateLatinCharacter" pour obtenir son équivalent en morse, le résultat est stocké dans une variable "morseText" qui contient la traduction complète.

Dans l'étape 4, j'ai ajouté une fonction "getMorseCharacterList" qui divise une chaîne de caractères en morse en un tableau contenant chaque caractère morse, cela nous permet de travailler sur chaque caractère morse individuellement.

J'ai également créé un dictionnaire "morseToLatin" qui contient la correspondance entre les caractères morse et leur équivalent en alphabet latin. 

La fonction "translateMorseCharacter" prend un caractère morse en paramètre et renvoie sa correspondance en alphabet latin en utilisant ce dictionnaire.

La fonction "decode" prend une chaîne de texte en morse et utilise la fonction "getMorseCharacterList" pour obtenir une liste de caractères morse, ensuite, pour chaque caractère morse, j'utilise la fonction "translateMorseCharacter" pour obtenir son équivalent en alphabet latin, le résultat est stocké dans une variable "morseText" qui contient la traduction complète du morse en latin.

Finalement, j'ai créé des fonctions "translateToMorse" et "translateToLatin" qui sont appelées lorsque l'utilisateur souhaite traduire du texte en morse ou en latin à l'aide des boutons correspondants; ces fonctions récupèrent le texte entré par l'utilisateur, l'envoient à la fonction appropriée (encode ou decode), puis affichent le résultat dans une zone de texte dédiée.

J'espère que cette présentation de mon exercice t'a donné un aperçu de son fonctionnement, j'ai vraiment apprécié travailler sur ce projet et explorer les différentes fonctionnalités de JavaScript, HTML et CSS pour créer un traducteur pratique.
