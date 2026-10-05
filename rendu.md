# 1.2 

Pour chaque triplet de points possible sur une frame, on définit a, b les deux points les plus éloignés dans le triplet, et c le point intermédiaire.
On calcule ensuite le déterminant entre AB et AC, on définit la déviation = déterminant / norme(AB) 
Si cette déviation est inférieure à un epsilon de tolérance, on garde le triplet comme candidat.
Le triplet choisi finalement est le triplet avec la plus petite déviation.