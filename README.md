# Tags
The purpose of a tag, how to create a tag, and how to download old versions of the .do files (_Français ci-dessous_)

_Video:_ [Tags](https://www.youtube.com/watch?v=1jFSUrNIu5M&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=14&t=0s)


### Summary 
Tags are used to mark certain commits to make them easier to re-identify in the commit history. For example, tags should be used to mark the production of data products, such as the 2-pagers or SOI tables when they are published on the PMA website

#### By the end of this video, you should be able to:
- Identify a tag in GitKraken
- Understand when PMA uses tags
- Understand why PMA uses tags
- Create an annotated tag
- Follow PMA protocols to name a tag
- Follow PMA protocols to annotate a tag
- Download tagged .do files as a .zip file from GitHub.com


### How to
#### How to create a tag:
1. Right click on the commit where you want to create the tag, and select “Create Annotated Tag Here” from the menu
    - This should be the last commit before the data product was produced
2. Tag Name: R#_DataProduct_v#
    - RoundNumber_DataProductName_VersionNumber
      - R7_2pager_v1
    - The version number is the website version, not the version number of the document itself
      - If it is the first time the Round 7 2-pager is being published on the website, it is v1
      - If it is the second time (due to an update or the use of publicly available data), it is v2
      - Etc.
3. Click “Enter”
4. Annotation Message: Name of the dataset used to produce the data product. Potential Datasets include
    - WealthWeightAll or SDP_Clean_Data
    - Analysis
5. Click “Enter”
6. The tag will appear in the commit graph, and on the left panel under “Tags”
7. Right click, or control click, the tag and select “Push tag name to origin” from the menu

#### How to download the .do files sotred within a tag:
1. Navigate to the repository page on [GitHub](https://www.github.com)
2. Click on “Releases”
3. GitHub will display a list of the tags stored in the repository
    - Three dots (…): Clicking on the three dots will display the annotation
    - Zip: Allow you to download all the .do files as they were when the tag was created in a .zip file


### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Branch | A branch is a parallel version of a repository that allows you to work freely without disrupting the master version of a file. PMA uses branches to update .do file content and prepare .do files for round specific data collection |
| Commit | A commit is a way to save a change to a file that also stores information on what changes were made, when and by who. PMA uses commits to systematically document changes to .do files |
| Organization | A workspace where teams can collaborate across many projects at once. PMA uses organizations to organize .do files by purpose and country. |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |
| Tag | Active points to commits that do not move. PMA tags the final commit before releasing data products so the version of the specific .do file can be easily referenced for future use |


_________________________________________________________________


# Tags
But d’un tag, comment le créer, et comment télécharger les anciennes versions des .do files. 

_Vidéo:_ [Tags](https://www.youtube.com/watch?v=z3_f7fNE7No&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=13)


### Résumé  
Les tags sont utilisés pour étiqueter certains commits et les rendre plus faciles à ré-identifier dans l’historique du commit. Par exemple, les tags devraient être utilisés pour étiqueter les produits de données, comme les résumés de 2 pages et les Tableaux des indicateurs une fois publiés sur le site internet de PMA.

#### A la fin de la vidéo, vous devriez être en mesure de :
- Identifier un tag dans GitKraken
- Comprendre quand PMA utilise des tags
- Comprendre pourquoi PMA utilise des tags
- Créer un tag annoté
- Suivre les protocoles de PMA pour nommer un tag
- Suivre les protocoles de PMA pour annoter un tag
- Télécharger les .do files taggés en tant que fichier .zip sur GitHub.com


### Comment Faire
#### Comment créer un tag :
1. Cliquez-droit sur le commit pour lequel vous souhaitez créer un tag, et sélectionnez “Create Annotated Tag Here” (Créer un tag annoté ici) dans le menu
    - Cela devrait être le dernier commit avant que le produit de données ait été réalisé 
2. « Tag Name » (Nom du tag) : R#_DataProduct_v#
    - RoundNumber_DataProductName_VersionNumber
      - R7_2pager_v1
    - Le numéro de la version est la version du site internet, pas le numéro de version du document lui-même. 
      - Si c’est la première fois que le résumé de 2 pages de la septième vague d’enquête est publié sur le site internet, ce chiffre sera v1. 
      - Si c’est la deuxième fois (en raison d’une mise à jour ou de l’utilisation de données publiquement disponibles), ce sera v2. 
      - Et ainsi de suite.
3. Cliquez sur “Enter”
4. « Annotation Message » : Nom de l’ensemble de données utilisé pour préparer le produit de données. Ensembles de données potentiels :
    - WealthWeightAll ou SDP_Clean_Data
    - Analysis
5. Cliquez sur “Enter”
6. Le tag s’affichera dans le graphique des commits, et sur le panel de gauche sous “Tags”
7. Cliquez-droit/ contrôle sur le tag et sélectionnez “Push tag name to origin” dans le menu

#### Comment télécharger les .do files stockés sous un tag :
1. Allez sur la page du repository sur [GitHub](https://www.github.com)
2. Cliquez sur “Releases” (Publications)
3. GitHub affichera une liste de tags stockés dans le repository
    - Points de suspension (…) : Cliquez sur les points de suspension permet d’afficher l’annotation 
    - Zip : Vous permet de télécharger tous les .do files tels qu’ils étaient lorsque le tag a été créé dans un fichier .zip 


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Branch | Version parallèle d’un repository permettant de travailler librement sans perturber la version master d’un fichier. PMA utilise des branches pour mettre à jour le contenu des dofiles et les préparer pour la collecte de données d’une vague d’enquête spécifique. |
| Commit | Manière de sauvegarder une modification d’un fichier en stockant aussi des informations sur les changements qui ont été faits, quand et par qui. PMA utilise des commits pour documenter systématiquement les modifications des .do files |
| Organization | Espace de travail où les équipes peuvent collaborer sur différents projets en même temps. PMA utilise des organizations pour organiser ses .do files selon leur objectif et par pays |
| Push | Envoyer des modifications d’un commit vers une version remote (à distance) d’un repository. GitKraken push (pousse) les données sur GitHub pour que les deux plateformes soient synchronisées. |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
| Tag | Points actifs des commits qui ne bougent pas. PMA attribue un tag au commit final avant de publier les produits de données pour que la version spécifique d’un .do file soit référencée et puisse être facilement utilisée plus tard |
