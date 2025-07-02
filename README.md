# PREDICTION-DE-SALAIRE_ML

Prédiction de Salaires avec Machine Learning et Streamlit
Ce projet consiste à prédire le salaire d'un employé en fonction de certaines caractéristiques telles que :

Années passées dans l'entreprise
Niveau de satisfaction
Nombre moyen d'heures travaillées par mois
Les données sont analysées, des modèles de machine learning sont entraînés, et une application web interactive est déployée pour permettre des prédictions en temps réel.

## Structure du Projet

**Introduction**

Ce projet vise à résoudre un problème de régression en utilisant différents modèles de machine learning :

Régression Linéaire (Linear Regression)
Support Vector Regression (SVR)
Random Forest Regressor
Les performances des modèles sont comparées pour sélectionner celui offrant les meilleurs résultats. Le modèle final est intégré dans une application Streamlit pour un usage interactif.

**Fonctionnalités**

- Chargement et prétraitement des données (CSV).
- Exploration et normalisation des données.
- Entraînement et évaluation de modèles de machine learning.
- Sauvegarde et déploiement des modèles avec joblib.
- Création d'une interface utilisateur simple et intuitive avec Streamlit.

**Dataset & Feature	Description**

Les données incluent des informations sur les employés :

Age	Âge de l'employé.
Gender	Genre de l'employé (Male/Female).
Department	Département (e.g., Marketing, Sales).
Job_Title	Poste occupé.
Years_at_Company	Années passées dans l’entreprise.
Satisfaction_Level	Niveau de satisfaction (entre 0.0 et 1.0).
Average_Monthly_Hours	Nombre moyen d’heures travaillées par mois.
Promotion_Last_5Years	Promotion dans les 5 dernières années.
Salary	Salaire annuel.
Attrition	Indique si l'employé a quitté l'entreprise.

**Application Streamlit**

L'application interactive permet de prédire le salaire d'un employé :

Saisissez les informations suivantes :
Années d'expérience.
Niveau de satisfaction.
Heures travaillées.
Appuyez sur le bouton : "Press for predicting the salary".
Obtenez une estimation instantanée du salaire.

**Modèles Implémentés**

Le projet utilise plusieurs modèles pour prédire les salaires :

Régression Linéaire : Simple et efficace pour des relations linéaires.
SVR (Support Vector Regression) : Pour capturer les relations non linéaires.
Random Forest Regressor : Approche robuste basée sur des arbres décisionnels.
Optimisation : Les hyperparamètres des modèles SVR et Random Forest sont ajustés grâce à GridSearchCV pour de meilleures performances.

**Résultats**

Les performances des modèles sont évaluées avec les métriques suivantes :

Métrique	Description
Mean Absolute Error (MAE)	Indique la précision moyenne des prédictions.
Root Mean Squared Error (RMSE)	Mesure la dispersion des prédictions.
Le modèle final est sauvegardé sous le nom model.pkl.

**Dépendances**

Le projet utilise les bibliothèques suivantes :

pandas : Manipulation des données.
numpy : Calculs numériques.
scikit-learn : Algorithmes de machine learning.
joblib : Sauvegarde des modèles.
streamlit : Développement d'applications web interactives.


