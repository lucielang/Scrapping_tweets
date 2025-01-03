# Etude de l'utilisation de Twitter par ses utilisateurs en 2024 :bird:

Bienvenue sur le Github présentant notre projet Python dans le cadre du cours Python pour la Data Science. 

L'objectif était, en récoltant par scraping les tweets contenant les mots clefs *Musk*, *Twitter* et des mots synonymes de *quit*, *leave* ou *stay*, d'obtenir une base de tweets avec les utilisateurs qui s'étaient exprimés sur la question de quitter ou non Twitter. Nous avons ainsi pu observer les tendances exprimées en 2024, puis fait de l'analyse textuelle en regardant les mots qui revenaient le plus souvent dans les tweets.
En passant par du NLP, nous avons classifié les tweets en 2 catégories (toxiques et non toxiques) et étudié via une analyse textuelle fréquentielle le registre employé dans chacune des catégories, puis avons finalement tenté d'identifier une corrélation entre les tweets qui exprimaient un soutien de Bluesky (réseau social souvent considéré comme une alternative à Twitter) et ceux qui critiquaient Twitter.

Pour trouver notre notebook final, il suffit de cliquer sur celui qui s'intitule **0_RAPPORT.ipynb**. 



### Récapitulatif des notebooks et des scripts présents sur notre Github : 

__0_RAPPORT.ipynb__ : Notebook final renvoyant aux autres notebooks.

# __0_notebooks__ : dossier qui rassemble tous nos notebooks
- __1_Script_scraping.ipynb__ : Script **à ne pas exécuter** qui a permis de récolter les tweets avec le nombre de likes, retweets et les informations jugées nécessaires à la constitution de notre base de données.
- __2_nettoyage.ipynb__ : Nettoyage de la base de données, classement des tweets par date et suppression des bots.
- __4_Statdesc.ipynb__ : Constitution de graphiques pour révéler les tendances des tweets en 2024.
- __4.5_Statdesc_violent.ipynb__ : Statistiques descriptives à partir de l'analyse de sentiments issue du NLP.
- __6_Analyse_textuelle.ipynb__ : Fait ressortir la fréquence et l'utilisation de certains mots dans les tweets en 2024.
- __7_Modelisation.ipynb__ : Régressions linéaires de la violence des tweets sur le sujet "Bluesky" sur la violence des tweets sur le sujet "leave Twitter".

# __1_Scripts__ : Dossier rassemblant les scripts 
- __3_NLP.py__ : Script pour créer le réseau de neurones et la tokenisation adaptée pour trier les tweets.
- __3.5_Data_sorting.py__ : Script afin de traiter une base de données avec le modèle créé dans le script précédent. 

# Dossiers rassemblant les tableaux de données
- __data_fin__ : Dossier avec les tableaux de données finals.
- __data_processing__ : Dossier contenant les sorties du scraping puis les tables intermédiaires lors du nettoyage des données.
- __training_data__ : Dossier contenant les fichiers liés au modèle utilisé pour le NLP et à la base d'entraînement.