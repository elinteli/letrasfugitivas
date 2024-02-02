##Paso 1: diccionario.html
- Se agarran muchos txt / json con palabras en español y se unen para crear un diccionario con palabras comunes.
(Resultado: dicPaso1.json)

##Paso 2: filtrarPalabrasInventadas.html
- Se compara el diccionario anteriormente creado con el diccionario de la RAE y se eliminan los terminos que no existen.
(Resultado: dicPaso2.json)

##Paso 3: eliminarElementosDuplicados.html
- Se eliminan los elementos duplicados del diccionario:
(Resultado: dicModoClasico.json)

##Paso 4: crearParesMinimos.html
- Se comparan todos los elementos en busca de pares minimos (pareja de palabras que tienen solo un sonido distinto, ej: **P**elon, **T**elon)
(Resultado: paresMinimos.json)
