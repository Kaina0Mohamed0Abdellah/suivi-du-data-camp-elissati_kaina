## Semaine 1:
- Importation du jeu de données
- Description des données pour avoir des idées sur la structure et détecter les failles de notre jeu de données
- Début de traitement des valeurs manquantes dans les dataframe
- Concaténer identity et transaction, puis faire extraire la variable cible et variables explicatives.

## L'objective de la semaine prochaine:
- Réduction de la mémoire(kaoutar)
- Traitement des valeur manquantes (Mohamed)
- Codage des variables nominatives

## Semaine 2:
- D'apès la visualisation de nos données on remarque que 97,19% des transaction sont non frauduleuses et juste 2,81% des transactions frauduleuses alors si on utilise cette base de données pour nos études avec les modèles prédictifs nous allons obtenir énormement d'erreurs.
- Le traitement des valeurs manquantes dans les dataframe et les doublantes:
 * Supprimer les doublant de train et test
 * Supprimer les colonnes qui ont plus de 90% des valeurs manquantes
 - Imputation des valeurs manquantes par la moyenne : nous allons remplir les valeurs manquantes en utilisant la technique du mode mais il faut faire attention au varaible qualitative qui sont inimputable par la moyenne
 - On a fait mapping et aggregation de E-mail et P-mail

## L'objective de la semaine prochaine:
- Imputaion des valeurs manquantes par KNN 
- Commencer la rédaction du rapport

## Semaine 3
- Imputaion des valeurs manquantes par KNN:
* Step1: Subsets the object's data types(all) into another container
* Step2: Change np.NaN into an object data type, say None. Now, the container is made up of only objects data types
* Step3: Change the entire container into categorical datasets
* Step4: Encode the data set(i am using .cat.codes)
* Step5: Change back the value of encoded None into np.NaN
* Step6: Use KNN (from fancyimpute) to impute the missing values
* Step7: Re-map the encoded dataset to its initial names

## L'objective de la semaine prochaine:
- Data exploration et visualisation
- Décodage des données qualitatives
- Etude de corrélation pour les variables imputées 
 - Continuer la rédaction du rapport 
 
## Semaine 4
- Data exploration et visualisation: estimation des distributions des variables continues pour isfraud = 0 et y 001, et réalisation de statistique bivariés
- Décodage des données qualitatives: transformation qualitatives en des variables binaire en eevitant la multicolinéarité.
- Etude de corrélation entre les variables de la base imputée par KNN et celle imputée par mode-mean

## L'objective de la semaine prochaine:
- Split
- Implémentation LGBM without ACP et submission 
- XGboost

## Semaine 4
- Implémentation lgbm sur la base mean_mode et LGBM sur la base KNN
- Implémentation lgbm avec hyper parametres sur la base mean_mode et LGBM sur la base KNN 
- Implémentation XGboost pour les mêmes bases 
