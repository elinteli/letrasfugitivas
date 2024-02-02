# Letras Fugitivas

Este proyecto es un juego móvil en el que los usuarios deben encontrar la letra faltante en cinco palabras, siendo la misma letra para todas ellas. El juego se basa en un conjunto de pares mínimos comunes en español. Los pares minimos son parejas de palabras que tienen una sola letra diferente, como por ejemplo, **P**elon y **T**elon.

## Paso 1: Crear el diccionario

Hacemos un mezcla de palabras en español provenientes de archivos de texto, JSON y otros de internet (Ejemplo: 1000 palabras mas comunes en español). Básicamente, creamos un diccionario gigante que abarca términos comunes en español.

## Paso 2: Sacar palabras que no existan

No queremos que nuestro juego se llene de palabras que no existen, así que comparamos nuestro diccionario con el de la RAE y eliminamos lo que no esta.

## Paso 3: Eliminar Duplicados

Nos deshacemos de cualquier duplicado en el diccionario.

## Paso 4: Crear pares minimos

Comparamos cada palabra en busca de pares mínimos.

## Uso del JSON en el juego

Para crear el juego final, elegimos una letra aleatoriamente y elegimos 5 pares minimos que se puedan resolver con esa letra, luego el jugador va a tener que adivinar cual es la letra que completa las 5 palabras
