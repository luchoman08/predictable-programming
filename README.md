# predictable-programming
Este repositorio presenta algunos tipos y conceptos basicos de lo necesario para establecer una programación predecible.

Factores principales:


- Estado: representa un valor en un instante de tiempo, dicho valor es sujeto a modficaciones por medio de acciones y por medio de normas. 
- Idea: elemento base, con un nombre asociado e id unico asociado, es abstracto por ende no puede interferir con nada de lo "real" directamente, 
mas que por las distintas instancias de la Idea
> - Acción: cualquier ejecución de sentencias que terminen modificando un estado con tiempo de vida igual al tiempo de vida global
> - Norma: función descriptiva de el cambio de estados. Puede estar sujeta a precondiciones para poder aplicar la norma y una norma puede desencadenar 
directamente otras normas. Una acción puede o no desencadenar la ejecución de una norma. Una norma puede tener un conjunto 
de instancias asociadas las cuales seran afectados por dicha norma, o bien puede estar asociada a todo un conjunto de Ideas
> - Agente: elementos que emprenden una acción. Una instancia de una idea es un agente si tiene acceso almenos a una acción
> - Fuentes: proveedor de variables de estado consumibles y reglas que se aplican a esta, sin la capacidad propia de modificar las mismas. 
> - Recurso: elemento individual con caracteristicas 
