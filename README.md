La régression logistique binaire est un modèle statistique puissant couramment utilisé dans la détection de fraude par carte de crédit. Son efficacité repose sur sa capacité à prédire des résultats binaires, tels que "fraude" ou "non fraude", en fonction de diverses caractéristiques des transactions. En traitant les données transactionnelles comme des variables explicatives, la régression logistique peut identifier les relations entre ces variables et la probabilité qu'une transaction soit frauduleuse.
L'un des principaux avantages de la régression logistique est sa simplicité d'interprétation. Les coefficients du modèle indiquent l'influence relative de chaque variable sur la probabilité de fraude. Cela permet aux analystes de comprendre quels facteurs sont les plus déterminants dans la détection de comportements frauduleux, et de prendre des décisions éclairées sur les mesures de prévention à adopter pour limiter les risques.
De plus, la régression logistique binaire est bien adaptée aux ensembles de données déséquilibrés, ce qui est fréquent dans les scénarios de fraude. En ajustant le seuil de classification, les praticiens peuvent mieux gérer la sensibilité et la spécificité du modèle, optimisant ainsi sa performance pour détecter les cas de fraude tout en minimisant les faux positifs. Cela est crucial pour maintenir la confiance des clients et des institutions financières.
Enfin, la mise en œuvre de la régression logistique dans des systèmes de détection de fraude peut être réalisée relativement facilement à l'aide d'outils analytiques et de logiciels disponibles. Cette accessibilité combinée à sa robustesse fait de la régression logistique un choix privilégié pour les entreprises cherchant à renforcer leur défense contre la fraude par carte de crédit, permettant ainsi d'améliorer continuellement leurs algorithmes de détection à mesure que de nouvelles tendances émergent.
3.2.4 Architecture Materielle
Notre architecture s’articulera sur une étude simple et explicative du fait de la non accessibilité des informations de transactions dans le secteur bancaire .
A ce stade nous imaginons une architecture :
1 .Chargement des données transactionnelles dans le stockage local/Drive.
2. Prétraitement des données via le CPU.
3. Entraînement ou exécution des modèles sur GPU/TPU (selon la configuration).
4. Stockage des résultats (fichiers logs, modèles) dans Drive ou une base de données externe.
Par ailleurs Afin que notre système soit effectif et qu’il puisse être implémenter, il faudrait qu’il repose sur un support. Notre système sera utilisé par des banques ou des organismes interbancaires. Notre système pourra être hébergé sur des plateformes propres à chaque entreprise. Dans notre cas, notre système aura comme support le cloud5, pour permettre une gestion centralisée et rationnelle des fraudes. Ceci permettra aussi un accès facile et garantie.
En effet, notre système se connectera à des systèmes monétiques. Ces systèmes monétiques feront office de sources d’informations au système. La sécurité qui tournera autour de notre système serait celle du cloud. Des critères de sécurités qui seront mis en exergue ici seront celles utilisés par les fournisseurs de cloud dans le cas de systèmes critiques tel que par exemple :
-	Le chiffrement des données qui peut être géré selon le bon vouloir du client
-	Les options de connectivité autorisant les connexions privées, ou dédiées
-	Des services permettant de gérer des attaques de types ddos
-	Des services permettant de gérer les accès et identités
-	Etc.

