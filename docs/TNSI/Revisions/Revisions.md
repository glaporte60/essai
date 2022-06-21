---
description : Les programmes Python à maîtriser
---

# 🐍 Exercices - PYTHON

??? note "Exercice 1 : Somme d'éléments dans un tableau"
    Ecrire une fonction `somme` qui prend en paramètre une listte d'entier et qui renvoit la somme des éléments du tableau
    !!! example "Résultat à obtenir"
    ```python linenums="1"
    print(somme([1,2,3]))
    6   
    ```
    {{IDE('somme', MAX = 10, SANS = 'sum')}}

    

??? note "Exercice 2 : Recherche d'un maximum dans une liste"
    Ecrire une fonction `maximum` qui prend en paramètre une liste d'entier et qui renvoit la valeur maximum du tableau
    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    maximum([1,20,40,2,25,3])
    40
    maximum([120,20,40,2,25,3])
    120
    ```
    {{IDE('maximum', MAX = 10, SANS = 'max')}}
    
    ??? done "Solution"
        A venir


??? note "Exercice 3 : Miroir miroir"
    Ecrire une fonction `miroir` qui prend en paramètre une chaine de caractère et qui renvoit cette chaîne inversée
    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    miroir('Bonjour')
    ruojnoB
    ```
    {{IDE('miroir', MAX = 10, SANS = 'max')}}
    
    ??? done "Solution"
        A venir

??? note "Exercice 4 : Moi en premier!"
    Ecrire une fonction `indice` qui prend en paramètre une chaine de caractère et un caractère recherché et qui renvoit l'indice de la première occurrence du caractère recherché
    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    indice('Bonjour', 'o')
    1
    indice('Bonjour', 'r')
    6
    ```
    {{IDE('indice', MAX = 10, SANS = 'max')}}
    
    ??? done "Solution"
        A venir

??? note "Exercice 5 : Je sais compter"
    Ecrire une fonction `nombres_occurrences` qui prend en paramètre une chaine de caractère et un caractère et qui renvoit le nombre de fois qu'apparaît le caractère dans la chaîne de caractère
    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    nombres_occurrences('Mississippi', 'o')
    0
    nombres_occurrences('Mississippi', 'i')
    4
    nombres_occurrences('Mississippi', 'M')
    1
    ```
    {{IDE('nombres_occurrences', MAX = 10)}}
    
    ??? done "Solution"
        A venir

??? note "Exercice 6 : Palindrome"
    Un mot palindrome peut se lire de la même façon de gauche à droite ou de droite à gauche : bob, radar, et non sont des mots palindromes.
    De même certains nombres sont eux aussi des palindromes : 33, 121, 345543.
    
    L’objectif de cet exercice est d’obtenir un programme Python permettant de tester si un nombre est un nombre palindrome.
    
    Pour remplir cette tâche, on vous demande de compléter le code des trois fonctions ci-dessous sachant que la fonction `est_nbre_palindrome` s’appuiera sur la fonction `est_palindrome` qui elle-même s’appuiera sur la fonction `inverse_chaine`.
    
    La fonction `inverse_chaine` inverse l'ordre des caractères d'une chaîne de caractères __chaine__ et renvoie la chaîne inversée.

    La fonction `est_palindrome` teste si une chaine de caractères __chaine__ est un palindrome. Elle renvoie __True__ si c’est le cas et __False__ sinon. Cette fonction s’appuie sur la fonction précédente.
    
    La fonction `est_nbre_palindrome` teste si un nombre nbre est un palindrome. Elle renvoie __True__ si c’est le cas et __False__ sinon. Cette fonction s’appuie sur la fonction précédente.

    __Compléter__ le code des trois fonctions ci-dessous.
    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    >>>inverse_chaine('bac')
    'cab'
    ```
    {{IDE('inverse_chaine', MAX = 10)}}

    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    >>> est_palindrome('NSI')
    False
    >>> est_palindrome('ISN-NSI')
    True
    ```
    {{IDE('est_palindrome', MAX = 10)}}

    !!! example "Résultat à obtenir"
    ``` python linenums="1"
    >>> est_nbre_palindrome(214312)
    False
    >>> est_nbre_palindrome(213312)
    True
    ```
    {{IDE('est_nbre_palindrome', MAX = 10)}}
    
    ??? done "Solution"
        A venir

[📄 Accueil](../../../){ .md-button }