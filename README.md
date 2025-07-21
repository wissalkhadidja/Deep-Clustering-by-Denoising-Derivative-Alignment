# Deep-Clustering-by-Denoising-Derivative-Alignment
Cette approche propose de réaliser du clustering non-supervisé sans utiliser de distance explicite ni nombre de clusters prédéfini. L’idée principale est d’exploiter un modèle de débruitage pour approximer le gradient de densité des données, puis de révéler les “bassins d’attraction” comme clusters naturels.

Étapes principales

Chargement et prétraitement des données

Entraînement du modèle de débruitage

Entraînement d’un autoencodeur bruité 

Estimation des gradients de densité

Application du débruitage pour obtenir le champ de gradients

Suivi des trajectoires (gradient flow)

Déplacement des points de données selon leur gradient de densité pour révéler les bassins d’attraction

Détection des clusters

Assignation des points aux mêmes pics/attracteurs

Évaluation

Comparaison avec des labels si disponibles (NMI, Silhouette…)
