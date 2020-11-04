# Testing-random-Number-generators-using-Khi-2-and-Kolmogorov-Smirnov


&emsp; Notre but est de comparer les générateurs utilisés par les logiciels étudiés (Matlab, R, Excel,SPSS, Linéaire, Hamlili) à la lumière de tests qui visent à quantifier leur qualité, en l'occurrence le test Khi-2 et le test Kolmogorov-Smirnov.</br> </br> 
&emsp; L'un cherche à savoir si un échantillon d'une loi discrète suit bien la répartition à laquelle on s'attendrait en théorie pour un échantillon de cette taille, l'autre cherche à savoir si un échantillon d'une loi continue est assez conforme pour être utilisé comme approximation de cette dernière.</br></br> 
&emsp;Ensuite, il est pertinent de se demander s'il existe une corrélation entre les résultats des deuxtests sur un même échantillon qui pour l'un reste intact et pour l'autre subit une transformation inverse.</br> </br> 
&emsp;Enfin, on cherchera à savoir quelle propriété rentre en jeu pour déterminer la valeur de K dans le test Kolmogrow-Smirnov, et on cherchera à établir un algorithme qui permet de relier les valeurs de cette propriété, nommément la discrépance, à la valeur plus ou moins bonne de K.
