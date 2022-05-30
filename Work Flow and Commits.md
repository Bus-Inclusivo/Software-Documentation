# Branches
**Main Branch:** 
Sera la rama principal donde se desarrollará el proyecto y estará en producción (su versión final y disponible para el usuario). Por ello, en esta rama solo se agregará funciones que ya esté debidamente probadas y se hayan evaluado que no traerán problemas para el proyecto. 
**Relasses Branch:**
En estas ramas se integrará las nuevas funcionalidades de la rama Develop para una posterior integración con la rama principal en la siguiente versión. En estas ramas ya no se tienen que diseñar nuevas funcionalidades; sin embargo, se pueden crear ramas Hotfix para reparar posibles errores.  
**Develop Branch:**
Sera la 2 rama más importante donde estarán las funcionalidades ya desarrolladas de las ramas Features y estas serán validadas. Esta rama partirá de la rama principal.
**Feature branches:**
Crearemos una rama por cada Feature. En estas ramas desarrollaremos las nuevas características o funcionalidades del proyecto para posteriormente integrarlo a la rama de Develop. 
**Hotfix branches**
Serán las ramas que utilizaremos para reparar errores que encontremos en el desarrollado en la rama principal o en las ramas Relases. Las usaremos en caso de un problema o error que haya surgido de manera imprevista. Tendrán un tiempo de vida corto y se eliminara una vez que su función haya terminado.

# Versionado
Como el proyecto está en una fase temprana se empezará desde la versión 0.0.0.
El versionado tendrá la forma **X.Y.Z**. En donde:
Donde **Z** incrementara en los Hotfix. Que serán las correcciones o parches para arreglar lo que ya se implementó del proyecto.
Donde **Y** incrementara en cada Relase. En donde se están implementando las nuevas funcionalidades.
Donde **X** solo se incrementará cuando se desarrolle una nueva versión del producto que se incompatible con las anteriores y haya agregado una gran cantidad de nuevas funciones. 
Se creará la versión **1.0.0** cuando tengamos todas las funcionalidades mínimas para la aplicación. De esta versión en adelante se continuará con el mismo versionado. 

# Convenciones 
En el proyecto utilizara la siguiente las siguientes convenciónes:

**Todos los commits se tendrán que escribir en inglés para tener un lenguaje uniforme.**

En los **Feature** debido a que estar en su etapa inicial no es necesario detallar el alcance o que segmento que afecto la modificación. La estructura será la siguiente:
*feat: (added or created) changes made. Reviewed-by: who developed it*

Para los **Hotfix** ya que serán soluciones que se apliquen por emergencia tendrá la convención:  
*fix: (repaired or modified) changes made.Reviewed-by: who developed it* 

Para las ramas **Releases** se usará las convenciones de los Feature, Hotfix y si agregamos o modificamos una gran parte del código que afecte al producto se utilizará BREAKING CHANGE.
*fix, feat or  BREAKING CHANGE: changes made. Reviewed-by: who developed it*

Finalmente dependiendo de lo desarrollado se puede variar en las palabras siempre que se respeten los convencional commits. 

Ejemplos:
feat: created Option to register private vehicles. Reviewed-by: Andree
feat: added Option to define the destination. Reviewed-by: Yoimer
fix:  repaired Rating system. Reviewed-by: Angel