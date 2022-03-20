# ACP-Method
TP 1 : ACP
 • PrincipedeACP:
• Data set utiliser :
La base de donnée utiliser est une version aplatie de la base de données nationale des éléments
nutritifs de l'USDA. Il est extrait de la base de données MongoDB créée dans un projet Lien de base de données : Lien
• La Première méthode - EXCEL : 1. Étape 1 :
 
ACP est une méthode de la famille de l'analyse des données et plus généralement de
la statistique multivariée, qui consiste à transformer des variables liées entre elles (dites
« corrélées » en statistique) en nouvelles variables décorrélées les unes des autres. Ces nouvelles
variables sont nommées « composantes principales », ou axes principaux. Elle permet au praticien
de réduire le nombre de variables et de rendre l'information moins redondante.
       
2. Étape 2 :
   On remplit les champs de la fenêtre ci-dessous :
Variables
 Observations
  3. Étape 3 :
 On remplit les champs de la fenêtre(outputs) ci-dessous :
 4. Résultats:
 - confirmer les axes ACP pour lesquels vous souhaitez afficher des graphiques 2D.
- Dans cet exemple, le pourcentage de variabilité représenté par les deux premiers facteurs n'est pas très élevé (36,8 %).


  • Une table contenant quelques informations sur les variables : moyenne , maximum , min...
• la matrice de corrélation.
• Les valeurs propres, qui reflètent la qualité de la projection du tableau initial à 38 dimensions vers un nombre inférieur de dimensions.
   

On a trouvé que la variabilité cumule pour les 10 premiers composants égale a 81.147%.
• La Deuxième méthode - Python : 1. Importation de librairies :
   2. Importation des données :
  3. Vérification des données :
   

4. Prétraitement :
  5. Normalisation:
  

6. ACP :
  7. Graphiques des valeurs propres :
  

8. Graphiques des valeurs propres :
  9. Interprétation des composantes : • Premier Composant :
   • Deuxième Composant :
  

• Conclusion:
On constate qu’on a trouvé les mêmes résultats (variabilité cumule = 81,147% et les valeurs propres ) que ça soit avec EXCEL ou Python, donc on a atteint l’intérêt de l’ACP et on a arrivé à réduire le nombre des axes de 38 à 10.
  
