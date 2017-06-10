## ¿Qué es?

 Simula una situacion de guerra entre humanos y hormigas mutantes.

## ¿Como funciona?

 Los agentes tienen asignado varios atributos, como vida o ataque. Estos se mueven aleatoriamente hasta que aparezca un enemigo en su rango de vision, entonces se acercan a el. Cuando estan muy cerca, comienzan a bajarle la vida en funcion de su ataque. Cuando la vida de un agente llega a cero, este muere.

## Uso

 Se eligen el numero de hormigas y de supervivientes (humanos), tambien se fijan sus atributos (barras de la derecha). A continuación se clica en setup (asi aparecen en pantalla), y por ultimo clicamos en go para que comiencen a actuar.

## Opciones

 Lider: A la izquierda podemos elegir si poner lider (aparecera en verde), este hace que todos los humanos que le vean le siguan (ademas de tener el doble de ataque).
 
 Monstruo: Podemos elegir si poner un monstruo de parte de las hormigas (no pasara desapercibido). Este no liderara a las hormigas, pero se puede seleccionar su daño y su vida de forma que arrase con los humanos.

## Atributos

 Vida: indica la cantidad de daño que puede absorver un agente.

 Ataque: indica el daño maximo que puede producir un agente.

 Velocidad: indica la velocidad del agente.

 Rango: indica la distancia apartir de la cual un agnente comienza a producir daño.
 
 Vision: indica la distancia apartir de la cual un agente intercactua con los que le rodean.

 Angle: indica el angulo maximo con el que gira cuando esta moviendose aleatoriamente.

 Covardia: cuando la vida de un agente esta por debajo de esta, su ataque se ve reducido a la mitad, y mantiene un movimiento constante hasta que deja de ver enemigos.



## Extension del modelo

 Seria interesante crear un modelo analogo pero con varios tipos de humanos ( o hormigas), que interactuen de distintas maneras. En particular, se podrian crean personajes del señor de los anillos (hobbits, montaraces, orcos, trolls...) cada uno con caracteristicas particulares, y efectos particulares en los agentes que les rodean.

 Tambien seria interesante añadir escenario, con muros y zonas en las que curarse. Y podria extenderse a un modelo de supervivencia, en el que la vida aumente cuando se derrota a un enemigo, y disminuya automaticamente con el paso del tiempo.