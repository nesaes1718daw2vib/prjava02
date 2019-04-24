# prjava02
1.
Crear una branca:
$sudo git branch branca00

Canviar de branca:
$sudo git checkout branca00

Per comprovar a quina branca et trobes:
$git status


5.
Canviar a la branca master:
$sudo git checkout master

Per veure l'historial:
$git log

10.
Per fusionar branques: Ens situem a una de les branques que volem fusionar i mencionem a laltre a la comanda.
$sudo git merge branca00

14.
Pujem el projecte mencionant la branca a on volem que estigui al repositori remot. En aquest cas volem pujar-ho a la branca01.
$sudo git push -u origin branca01

RESPOSTES:
6. No. Al crear una branca el que fem es crear un punter, una espècie d’instantània, quan ens movem a aquesta nova rama creada i modifiquem el codi, només haurà avançat la rama nova, pel que a l’hora de tornar a la branca master tornarem al estat en el que estava el nostre projecte abans de canviar de rama. 
Per tant, no podem veure la línia que hem afegit abans perquè l’hem afegit quan el punter estava apuntant a branca00.

7.Si, perquè el punter torna a enfocar a la branca, i amb ella totes les modificacions que hem fet desde que l’hem començat a usar. 

12.Perquè al fusionar la branca el projecte s’ha actualitzat a master i hem fet el push a master, no a la branca00.
