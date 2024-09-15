# Práctica Git & GitHub


**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

git reset --hard HEAD~1

*Porque con reset muevo HEAD y la rama, con --hard pierdo los cambios del working copy y con HEAD~1 indico que el número de commits a deshacer es 1.*

-------

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

git reflog

*Porque con git reflog puedo ver el histórico de movimientos de HEAD en los commits y así puedo encontrar un commit que no está en mi rama*

git reset 3c4f201

*Porque con reset ID_commit muevo HEAD y la rama al commit indicado. No hice --hard de primeras por si hacía falta mantener el working copy para posteriores pasos. Cuando vi que no hice* git restore git-nuestro.md.

-------

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

*No causa conflictos porque es un merge fast-forward*

-------

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

*Sí causa conflicto, porque en las mismas líneas del archivo hay texto/código diferente en cada rama.*

-------

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

*No causa conflictos porque es un merge fast-forward*

-------

**¿Qué comando o comandos utilizaste en el paso 25?**

git log --graph --decorate --pretty=oneline

-------

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

*Sí porque en el grafo, los commits que contiene la rama title son descendientes de los de la rama main.*

-------

**¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD~1

-------

**¿Qué comando o comandos utilizaste en el paso 28?**

git restore git-nuestro.md

-------

**¿Qué comando o comandos utilizaste en el paso 29?**

git branch -D title

-------

**¿Qué comando o comandos utilizaste en el paso 30?**

git reflog

git reset --hard ce825eb

*Como no menciona la creacion de la rama title de nuevo solo hago que main se posicione en el commit del merge.*

-------

**¿Qué comando o comandos usaste en el paso 32?**

git log

git checkout b7a8c82a2d8c147599c65865e151de6deaa735b6

-------

**¿Qué comando o comandos usaste en el punto 33?**

git reflog

git checkout 28f5417
