- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	git reset --hard HEAD~1

	porque así vuelvo un paso atrás y además deshago los cambios del working copy


- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	git reflog: para mirar el identificador del commit al que quiero volver)
	git reset --hard <identificador>: para volver a dejar todo incluido working copy como estaba en ese commit

	
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No, porque master es padre de la rama styled y el archivo en master no ha sufrido ninguna modificación.


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	Sí, porque el archivo había sido modificado en ambas ramas y git no sabe con qué datos se tiene que quedar, nos pide que miremos el archivo y manualmente lo modifiquemos nosotros para que él pueda guardar los cambios correctos en cada línea comprometida.


- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No, es un merge fast forward. Simplemente, avanza posiciones.


- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph
	git log --graph --pretty=oneline: use los dos porque quería ver cómo se veía de las dos formas.


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	Sí, porque el gráfico se ve muy lineal, por lo que avanzando posiciones con la rama master ya tendría acceso a los cambios en tittle.


- ¿Qué comando o comandos utilizaste en el paso 27?
	git reset HEAD~1


- ¿Qué comando o comandos utilizaste en el paso 28?
	git restore git-nuestro.md


- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title


- ¿Qué comando o comandos utilizaste en el paso 30?
	git reflog
	git reset --hard <identificador de reflog>


- ¿Qué comando o comandos usaste en el paso 32?
	git log
	git checkout <identificador primer commit>


- ¿Qué comando o comandos usaste en el punto 33?
	git reflog
	git checkout <identificador commit>
