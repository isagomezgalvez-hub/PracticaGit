#  Práctica Git
## Respuestas Ejercicio 1


### ¿Qué comando utilizaste en el paso 11? ¿Por qué? 

El comando que utlicé para deshacer el último commit fue:

``` git reset --hard HEAD~1 ´´´

He utilizado este comando en concreto porque se nos pedía deshacer los cambios
tanto del Working copy como del Stagin Area.

<br/>
 
### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Utilicé ``` git reflog ´´´ para  ver el identificador  del commit.
Una vez que lo tenía localizado utilicé ``` git reset --hard número identificador ´´´  
He utilizado el comando reset --hard porque necesitaba que me restaurase también los cambios en el working copy ya que en el paso anterior los había borrado.


### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, me mostró el mensaje **Already up to date** Indicamndome que la rama master ya era padre de la rama styled


### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí, se ha produjo un conflicto y creo un nuevo commit.


### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, porque se creo un merge *fast-forward* y la referencia de la 
rama master se movío a la referencia de la rama style.


### ¿Qué comando o comandos utilizaste en el paso 25?

Utilicé: ```git log --graph --decorate --pretty=oneline´´´

La idea era  mostrar el grafo y luego lo guardé con  un alias para poderlo usar
 en el futuro de una forma más directa.<br/>
Para guardar el alias use : ``` git config alias.graph "log --graph --decorate -- pretty=oneline´´´

De tal forma que si en un futuro uso git graph podré ver el grafo en este espacio de trabajo sin necesidad de utilizar todo el comando mostrado al inicio


###  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, Porque los commits están en una lista y se hubiese podido hacer fast foward sin problema. 
Aunque en este paso hemos creado un no fast foward y se ha creado un commit nuevo 


###  ¿Qué comando o comandos utilizaste en el paso 27?

```git reset HEAD~1´´´

### ¿Qué comando o comandos utilizaste en el paso 28?

``` git restore git-nuestro.md´´´


### ¿Qué comando o comandos utilizaste en el paso 29?

He utilizado ```Git branch -d title´´´ y me ha pedido que
 para confirmar el borrado teclease ```git branch -D title´´´

### ¿Qué comando o comandos utilizaste en el paso 30?

He utilizado **Git reflog** para ver los hast de los commit
**Git reset --hard*** y el numero del indentificador del commit

### ¿Qué comando o comandos usaste en el paso 32?

He usado **git reflog** para ver los identificadores de los diferentes commit
 y **git reset --hard** con el identificador del primer commit que es cuando se creo el poema.

### ¿Qué comando o comandos usaste en el punto 33? 

Para voler al estado final donde pusimos el titulo del poema. He utilizado 
**git reflog**  para ver los diferentes pasos.
**git reset --hard** identificador para volver al commit en el que se le añadío el titulo al poema. 




