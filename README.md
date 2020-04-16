# HashSet #

### Concepto ###

HashSet es una de las implementaciones de la interfaz "Set". No permite manejar nada con respecto al orden de los elementos.
Almacena sus valores en una *tabla hash*, que es una tabla que permite guardar elementos por función hash(función que recoge elementos que queremos insertar y devuelve valor único).

HashSet no permite elementos repetidos, para asegurarse de no ingresar objetos repetidos se decidió utilizar un HashMap internamente el cual tampoco permite objetos repetidos.

Proporciona la mayoría de operaciones de acceso en tiempo constante, entonces la eficiencia es más rapida.

