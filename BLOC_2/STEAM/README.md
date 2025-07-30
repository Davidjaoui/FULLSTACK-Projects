# Steam


Mon projet STEAM est visionable sur  :https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3315271947182280/1580014838534330/3718349118207812/latest.html

Ce notebook est divisé en 4 parties:

Part 1: IMPORT AND PREPROCESSING

Part 2: ANALYSE AU NIVEAU MACRO

Part 3: ANALYSE DES GENRES

Part 4: ANALYSE DES PLATEFORMES

-----


# Description de l'entreprise 📇

Steam est un service de distribution numérique et une boutique de jeux vidéo développé par Valve. Il a été lancé en tant que client logiciel en septembre 2003 afin de fournir automatiquement des mises à jour pour les jeux de Valve, puis s'est étendu à la distribution de titres tiers à partir de la fin de l'année 2005. Steam propose diverses fonctionnalités, notamment la gestion des droits numériques (DRM), l'association de joueurs sur des serveurs avec des mesures anti-triche Valve Anti-Cheat, des fonctionnalités sociales et des services de streaming de jeux.
Le client Steam permet l'automatisation des mises à jour de jeux, le stockage en cloud des progressions, ainsi que des fonctionnalités communautaires telles que la messagerie directe, des superpositions en jeu et un marché virtuel d'objets de collection.
________________________________________

# Projet 🚧
Vous travaillez pour Ubisoft, un éditeur français de jeux vidéo. Ubisoft souhaite sortir un nouveau jeu vidéo révolutionnaire ! Ils vous ont demandé de réaliser une analyse globale des jeux disponibles sur la marketplace de Steam afin de mieux comprendre l'écosystème du jeu vidéo et les tendances actuelles.
________________________________________

# Objectifs 🎯
L'objectif principal de ce projet est de comprendre quels facteurs influencent la popularité ou les ventes d’un jeu vidéo. Cependant, votre supérieur souhaite également profiter de cette occasion pour analyser le marché du jeu vidéo dans son ensemble.
Pour mener à bien ce projet, vous devrez adopter plusieurs niveaux d'analyse. Votre supérieur vous a fourni une liste d’exemples de questions intéressantes à explorer :

Analyse au niveau "macro"
•	Quel éditeur a publié le plus de jeux sur Steam ?
•	Quels sont les jeux les mieux notés ?
•	Y a-t-il des années avec plus de sorties ? Y a-t-il eu plus ou moins de sorties de jeux pendant la période Covid, par exemple ?
•	Comment les prix sont-ils distribués ? Y a-t-il beaucoup de jeux en promotion ?
•	Quelles sont les langues les plus représentées ?
•	Y a-t-il beaucoup de jeux interdits aux moins de 16/18 ans ?
Analyse des genres
•	Quels sont les genres les plus représentés ?
•	Y a-t-il des genres qui ont un meilleur ratio d’avis positifs/négatifs ?
•	Certains éditeurs privilégient-ils des genres spécifiques ?
•	Quels sont les genres les plus lucratifs ?
Analyse des plateformes
•	La majorité des jeux sont-ils disponibles sur Windows/Mac/Linux ?
•	Certains genres sont-ils davantage disponibles sur certaines plateformes ?

Vous êtes libre de suivre ces directives ou de choisir un autre angle d’analyse, tant que votre travail met en lumière des informations pertinentes et utiles. 🤓
________________________________________

# Périmètre du projet 🖼️
Vous devrez utiliser Databricks et PySpark pour réaliser cette analyse exploratoire des données (EDA). Plus particulièrement, vous devrez exploiter l’outil de visualisation de Databricks pour créer vos graphiques.
Le jeu de données est disponible dans notre bucket S3 à l’URL suivante :
s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json.
________________________________________

# Aides 🦮
Pour vous aider à mener à bien ce projet, voici quelques conseils utiles :
•	Pour adopter différents niveaux d’analyse, il peut être pertinent de créer plusieurs dataframes.
•	Le jeu de données étant semi-structuré avec un schéma imbriqué, les méthodes de PySpark comme getField() et explode() pourront vous être utiles.
•	Ce dataset contient des champs texte et date : PySpark propose des fonctions utilitaires pour manipuler ces types de données efficacement 💡
•	Vous pouvez utiliser des fonctions d’agrégation et groupBy pour effectuer des analyses segmentées.
________________________________________

# Livrables 📬
Pour finaliser ce projet, vous devez fournir :
✅ Un ou plusieurs notebooks contenant :
•	La manipulation des données avec PySpark
•	Des visualisations de données avec l’outil de tableau de bord de Databricks
✅ Publication des notebooks
•	Pour que le jury puisse consulter les visualisations, utilisez le bouton "publish" sur Databricks afin de générer une URL publique permettant d’accéder à une copie de votre notebook.
•	Si Databricks vous informe que votre notebook dépasse la taille maximale autorisée, divisez-le en plusieurs notebooks.
✅ Partage des notebooks
•	Copiez-collez les liens de vos notebooks publiés dans votre dépôt GitHub afin que le jury puisse y accéder facilement. 😌
