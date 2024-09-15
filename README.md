1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Utilicé este comando para deshacer el último commit y perder los cambios realizados en el working copy. El uso de --hard asegura que tanto el commit como los cambios locales sean revertidos.

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
git reset --hard el numero del commit
Primero utilicé git reflog para encontrar el commit. Después, utilicé git reset --hard numero del commit para rehacer ese commit.

3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causó conflictos.

 4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
 Sí, este merge causó conflictos. Ambos, htmlify y styled, tenían lo mismo en las mismas líneas de código.

5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No hay conflictos porque se resuelven antes.

6. ¿Qué comando o comandos utilizaste en el paso 25?
Reflog para poder visualizar el diagrama con –graph.

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

8. ¿Qué comando o comandos utilizaste en el paso 27?
git reset --soft HEAD~1

9. ¿Qué comando o comandos utilizaste en el paso 28?
git reset –hard

10. ¿Qué comando o comandos utilizaste en el paso 29?
 git branch -D title

11. ¿Qué comando o comandos utilizaste en el paso 30?
git merge --no-ff title

12. ¿Qué comando o comandos usaste en el paso 32?
git checkout 

13. ¿Qué comando o comandos usaste en el punto 33?
git checkout

