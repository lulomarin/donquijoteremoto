# PracticaGit - Respuestas
#Marin Forés, Lucía

--

**1.¿ Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque es la unica forma de borrar un commit perdiendo aquello que teniamos en el working copy

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` `git reset 1a8a7ec` 

Para conseguir deshacer el paso anterior y volver a tener dicho commit

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, ya que el archivo estaba editado en la misma linea

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

En este paso si que se ha producido un conflicto ya que el archivo lo habiamos editado en la misma linea en dos ramas diferentes

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, porque el archivo está editado en la misma línea

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?** 

`git log --graph`

--
**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**


**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--
**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD~2`

--
**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--
**11.  ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` > busco el código correcto > `git reset 75cb642`

--
**12. ¿Qué comando o comandos usaste en el paso 32** 

`git reflog` > busco el código correcto > `git checkout 8a63735`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` > busco el código correcto > `git checkout cd7a280`

