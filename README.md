# Testing con Junit

Este es un ejemplo sencillo de pruebas unitarias usando Junit 5

Observa que este proyecto no tiene ninguna clase con el método `main`, no nos hace fatal. Además, tampoco tiene ningún `scanner` ni ningún `print`.

Haz un fork de este proyecto en tu repositorio de Github y contesta a las siguientes preguntas:

1. ¿Qué sentido puede tener este proyecto y para que lo podrías usar?
Este proyecto usa maven y se puede usar para practicar pruebas unitarias con Junit 5 y Desarrollo guiado de por pruebas(TDD).

2. Revisa las pruebas de la suma y comenta lo que te parezca de interés
En asertAll se agrupan varias pruebas, se ejecutan todas y si falla una la prueba da error.
Se usan distintos tipos de asserts y la única pruba que esta mal es sumaPositivosMal().


3. Realiza un estudio de caja negra de la división e implementa las pruebas en junit: Se realizará en markdown.

| Entrada | Resultado esperado |
|---------|--------------------|
| 10/2    | 5                  |
| -10/2   | -5                 |
| 10/-2   | -5                 |
| -10/-2  | 5                  |
| 0/5     | 0                  |
| 10/0    | Excepción          |



## Instrucciones

El alumno deberá hacer un fork de este proyecto e implementar la solución solicitada (preguntas y código).

>Se deberá utilizar este fichero, y los artefactos de código del proyecto, para resolver el ejercicio.


**Si no se puede acceder al repositorio la evaluación del ejercicio será de 0. No se evaluarán entregas modificadas/entregadas fuera del plazo establecido en la tarea**