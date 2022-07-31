# Periodic Vehicle Routing Problem (PVRP)

En France les patients effectuant la dialyse à domicile sont gérés par un "Home Healthcare" (HHC Company)
qui assure les services logistiques nécessaires. Cette entreprise est responsable de l’acquisition et l’installation
du générateur chez le patient à son domicile et de la livraison des consommables aux patients. Traditionnellement,
le patient est approvisionné une fois par mois. Ceci nécessite incontestablement un espace de stockage considérable.

Selon Rein Echos [2], l’une des barrières qui empêchent de nombreux patients d'accéder à la dialyse à domicile est le manque
d'espace pour stocker les consommables.
L’objectif est de satisfaire à la fois l’entreprise en réduisant la distance parcourue par période et le patient en réduisant
le coût de stockage chez le patient.
Toutefois, un modèle mathématique permet de résoudre des problèmes de petite taille. Ainsi, des heuristiques sont nécessaires
pour résoudre des problèmes de grande taille.

Le problème est de trouver un compromis entre l’augmentation de nombre des clients qui nécessite une augmentation des fréquences
de visites et le coût de transport qui exige que la fréquence de visite soit faible.

Nous sommes donc amenés à résoudre un problème de tournées de véhicules périodiques (PVRP pour Periodic Vehicle Routing Problem
en anglais).

![image](https://user-images.githubusercontent.com/57875839/182021140-fc50889b-d857-47c7-a2f5-18a527b41d1d.png)

Mots clés : Python, Clustering, K-Means, Optimisation, Gurobi
