# Carlas-usuaris-i-grups

es comprova que els grups `devs`, `sysadmin` i `auditor` s'han creat correctament. També es poden veure els GID assignats a cada grup.

![](/imagenes/imagen1.png)
es mostra el fitxer de benvinguda que s'ha afegit al directori plantilla `/etc/skel`. Aquest fitxer es copiarà automàticament als nous usuaris quan es creïn.   
![](/imagenes/imagen2.png)  
En aquesta captura es comprova que el directori `/etc/skel` conté la carpeta `Documents` i el fitxer `benvinguda.txt`, que serviran com a plantilla per als usuaris nous. 

![](/imagenes/imagen3.png)

es mostra la configuració de l'àlies `ll` al fitxer `.bashrc` de `/etc/skel`. Això permetrà que els usuaris nous puguin utilitzar la comanda `ll` per mostrar els fitxers amb els seus detalls.   
![](/imagenes/imagen4.png)  
la shell configurada per defecte per als nous usuaris és `/bin/bash`. Aquesta configuració es troba al fitxer `/etc/adduser.conf`. 

![](/imagenes/imagen5.png)  
Comprovo la Prova09 la he esta creada

![](/imagenes/imagen6.png)

mostra l'eliminació de l'usuari de prova amb la comanda `deluser -r`. D'aquesta manera, s'elimina el compte de prova i el seu directori personal. 

![](/imagenes/imagen7.png)

# **TASCA 3\. Creació i configuració dels usuaris**

`creacio de laura_dev` mitjançant les comandes indicades a l'activitat. 

![](/imagenes/imagen8.png)  
`creacio de laura_dev` mitjançant les comandes indicades a l'activitat. 

![](/imagenes/imagen9.png)  
que s'han assignat les contrasenyes inicials als usuaris creats, seguint les indicacions de l'activitat. 

el resultat de la comanda `id marc_sys`, que permet consultar l'UID, el GID i els grups als quals pertany l'usuari. 

![](/imagenes/imagen10.png)  
la configuració perquè l'usuari `pau_dev` hagi de canviar la contrasenya en el pròxim inici de sessió.   
![](/imagenes/imagen11.png)  
s'han assignat les contrasenyes inicials als usuaris creats, seguint les indicacions de l'activitat. 

![](/imagenes/imagen12.png)

**TASCA 4\. Inspecció del sistema i fitxers de configuració** 

el resultat de la comanda `id marc_sys`, que permet consultar l'UID, el GID i els grups als quals pertany l'usuari.   
![](/imagenes/imagen13.png)

la informació de l'usuari `pau_dev` al fitxer `/etc/passwd`, on es poden consultar dades com l'UID, el GID, el directori personal i la shell.   
![](/imagenes/imagen14.png)

el bloqueig del compte de `pau_dev` per impedir temporalment que iniciï sessió. 

![](/imagenes/imagen15.png)

![](/imagenes/imagen16.png)  
la informació relacionada amb les contrasenyes dels usuaris al fitxer `/etc/shadow`. Aquest fitxer té permisos restringits perquè conté informació sensible relacionada amb l'autenticació. 

![](/imagenes/imagen17.png)  
es comprova al fitxer `/etc/shadow` que el compte de `pau_dev` està bloquejat. 

![](/imagenes/imagen18.png)  
es mostra la configuració del directori plantilla `/etc/skel`, que s'utilitza per proporcionar fitxers i configuracions als usuaris nous.   
![](/imagenes/imagen19.png)

![](/imagenes/imagen20.png)  
es mostra el desbloqueig del compte de `pau_dev`, de manera que pugui tornar a iniciar sessió. 

![](/imagenes/imagen21.png)

![](/imagenes/imagen22.png)  
es mostra l'eliminació del compte `auditor`, juntament amb el seu directori personal i la seva bústia de correu.   
![](/imagenes/imagen23.png)  
**TASCA 6\. Personalització de l'entorn d'usuari**   
captura es mostra la instal·lació del paquet `fish`, que permet utilitzar aquesta shell alternativa a Bash. 

![](/imagenes/imagen24.png)  
captura es comprova que la shell de l'usuari `laura_dev` s'ha canviat a `fish` mitjançant la configuració corresponent.   
![](/imagenes/imagen25.png)  
![](/imagenes/imagen26.png)


























