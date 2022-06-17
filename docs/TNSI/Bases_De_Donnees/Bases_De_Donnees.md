

<!--Testez :

{!{ sqlide titre="Tape ta requête SQL ici :" init="BDD/les_Aliens0.sql"}!}
-->

=== "Cours"
    Pour la gestion des accents sur les fichiers SQL clique [ICI](https://www.scriptol.fr/creation-site-web/accents-html.php){target=__blank}
    
    

=== "Exercices"
    !!! note "Agences de locations de voitures"
    
    Le schéma relationnel

    ![Schema_Relationnel_Locations](../../img/Schema_Relationnel_Locations.png)
    
    Visualiser toute la relation Agences

    Exemple : 
    ```sql
    SELECT *
    FROM vehicules
    WHERE kilometrage>10000
    ```

    {!{ sqlide titre="Tape ta requête SQL ici :" init="BDD1/locations.sql"}!}
    

[📄 Accueil](../../../){ .md-button }

