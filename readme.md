

**RESPUESTAS DE LA PRACTICA**


*¿Qué comando utilizaste en el paso11?¿por que?*

-- Se usa el comando "git reset --hard HEAD~1", 
ya que con el deshacemos el ultimo commit 
descartando todos los cambios.

*¿Qué comando o comandos utilizaste en el paso 12?¿Por qué?*

-- Primero se debe utilizar el "git reflog", para poder 
ubicar el punto exacto en el que necesitamos recuperar 
el archivo o sus modificaciones, luego con el comando "git restore <file>"
recuperamos los cambios que habia tenido el archivo en ese momento.

*El merge del paso 13, ¿Causó algún conflicto?¿Por qué?

-- En principio solo por encontrarme mal ubicado en la rama 
debida para hacer el merge, pero una situado en la rama correcta, tanto 
con el comando git merge, como con el comando git reset he podido 
conseguir el mismo resultado.

*El merge del paso 19, ¿Causó algún conflicto?¿Por qué?*

-- No, al ser un merge de tipo fast Forward styled asumio 
automaticamente todos los cambios realizados por la rama htmlify

*El merge del paso 21, ¿Causó algún conflicto?¿Por qué?*

-- No, ya que master no ha realizado ningun cambio 
en el archivo, simplemente sube y se posiciona con 
las demas branch en el mismo commit con los mismos cambios

*¿Qué comando o comandos utilizaste en el paso 25?*

-- El comando "git log --graph"

*El merge del paso 26, ¿Poría ser fast forward?¿Por qué?

-- No, debido a que aunque se han realizado algunos 
cambios en el archivos y se ha creado otra Branch nueva,
igualmente no se ha realizado ningun commit, por lo que 
estan todas las branch en el mismo punto.

*¿Qué comando utilizaste en el paso 27?*

-- Ninguno, como he dicho antes las branch no se han 
movido ni se han hecho commit de los cambios.

*¿Qué comando utilizaste en el paso 28?*

-- git restore git-nuestro.md descartando los cambios realizados
por la rama title.

*¿Qué comando utilizaste en el paso 29?*

-- git branch -d title.

*¿Qué comando utilizaste en el paso 30?*

-- ninguno, no hay merge reciente.

*¿Qué comando o comandos utilizaste en el paso 32?*

-- git checkout main
-- git branch -D styled
-- git branch -D htmlify 

*¿Qué comando o comandos utilizaste en el paso 33?*

-- git reset <codigo reflog>
