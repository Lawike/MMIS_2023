# Représentation de volumes :

- Voxel grid - Implicit

- Tetrahedral meshes - parametric

Implcit : on a pas une description formelle de la forme de l'objet.

Parametric : on a une représentation qu'on passe en paramètre.

## Voxel

![](C:\Users\doken\OneDrive\Documents\MMIS\Computer%20graphics%202A\Cours_2_assets\voxel.png)

Plus la valeur de retour de la function (R3 -> R) est elevé (proche de 1), plus ça signifie qu'il y'a de la matière en ces coordonnées. (Valeur de densité)

Pour les formes complexes c'est pas terrible.

Il peut y avaoir du gachi d'espace mémooire sur la majeur partie de la forme au final.

## Tetrahedral meshes

<img src="file:///C:/Users/doken/AppData/Roaming/marktext/images/2022-09-18-16-35-52-image.png" title="" alt="" width="796">

<img src="file:///C:/Users/doken/AppData/Roaming/marktext/images/2022-09-18-16-36-03-image.png" title="" alt="" width="771">

Ici on a des "aires" occupées et pas juste des "points". Ces aires sont des tétrahèdres ici.

# Représentation de surfaces

C'est un plan 2D plongé dans R3 et qui est orientable. C'est donc les frontière d'un solide 3D.

Orientable ça veut dire qu'on doit pouvoir différencier clairement l'intérieur de l'extérieur.

# Implicit Level Sets

Contrairement au voxel, on a pas une valeur de densité, mais une valeur de 'profondeur' par rapport à la surface. (C'est ma distance en gros).

![](C:\Users\doken\AppData\Roaming\marktext\images\2022-09-18-16-54-06-image.png)

## Parametric surface representations

Notre surface est définie dans R2 et est transformée en des points dans R3 :

![](C:\Users\doken\AppData\Roaming\marktext\images\2022-09-18-17-08-54-image.png)

## Spline surfaces




