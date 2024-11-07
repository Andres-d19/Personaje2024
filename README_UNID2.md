# Unidad2PersonajeNavideño
Evidencias de la Unidad, videos de las actividades realizadas, capturas de los examenes del curso de python y el avance del proyecto

## Ejercicio Practico Integral
https://drive.google.com/drive/folders/1tJtQNnNsFxeqqkcsQ3xyFzvcwzW-D6PN?usp=sharing

EXPLICACION
11. Alarma de Seguridad para Zona Restringida
Componentes: HC-SR04, buzzer, LED RGB, OLED
Descripcion: Si alguien cruza la zona restringida, el buzzer emite una alarma, 
el LED RGB parpadea en rojo, y la distancia del intruso se muestra en la OLED

## Ejercicios en Clase

LA EXPLICACION DE CADA EJERCICIO SE ENCUENTRA EN SU RESPECTIVA CARPETA 
https://drive.google.com/drive/folders/10wt11mgyVxfgfTNA8foS2NPJdw6Lk_1y?usp=sharing


## Avance del Proyecto Navideño
En este proyecto, se ha utilizado lo aprendido en el curso de Python para desarrollar un sistema que controla las acciones de un personaje, el alcalde de El Extraño Mundo de Jack, en un robot basado en la plataforma ESP32. Para organizar el código de manera eficiente, se han implementado diversas clases, como BrazoRobot, MotorDePasos y RobotPrincipal, que gestionan el control de movimientos del brazo, la cabeza y las simulaciones de parpadeos y guiños. Esta estructura modular es similar al enfoque que se usa en Python con funciones y clases para organizar la lógica de los programas.

Mediante el uso de condicionales y bucles, el robot es capaz de realizar acciones como bailar, moviendo sus brazos y cabeza, además de reproducir melodías a través de un buzzer. Esta integración de estructuras de control refleja el enfoque de programación en Python.

La captura de eventos, como la presión de un botón para iniciar las secuencias de movimiento y sonido, es otro aspecto que se maneja de manera similar a la entrada de usuario en Python. Finalmente, se ha incorporado temporización utilizando la función delay(), que cumple una función similar a time.sleep() en Python, para controlar la velocidad de las animaciones y garantizar que los movimientos y los sonidos se sincronicen adecuadamente, ofreciendo una experiencia interactiva y dinámica.

link:https://drive.google.com/drive/folders/17NAv0qxOg28YExctW9QrpUbVLTV71zuI?usp=sharing

Coevaluación
Lo que se hizo bien:
Estructura del Código:
El uso de clases y funciones para modularizar el proyecto es muy adecuado, lo que hace que el código esté bien organizado y sea fácil de entender. Además, la implementación de las funciones de movimiento y animación (bailar, parpadear, guiñar) se realizó de forma clara y eficiente.

Manejo de Entradas:
La utilización del botón para activar las secuencias de acciones es correcta y eficiente, permitiendo una interacción clara y directa con el usuario.

Sincronización de Acciones:
Las animaciones y los sonidos están bien sincronizados, lo que contribuye a una experiencia fluida y dinámica.

Áreas de mejora:
Comentarios en el Código:
Sería útil agregar más comentarios explicativos en el código para facilitar su comprensión, especialmente para aquellos que no están familiarizados con el proyecto. Detallar el propósito de cada función y explicar el rol de las variables importantes ayudaría a mejorar la legibilidad y la comprensión general del código.

Optimización de Temporización:
El uso de la función delay() para gestionar las animaciones y los sonidos puede bloquear otras partes del código, lo que podría afectar la fluidez de la ejecución. Una mejora en este aspecto sería utilizar funciones como millis() para gestionar las temporizaciones de forma no bloqueante, evitando que el código se "congele" mientras espera.

Revisión del Control de Hardware:
Aunque el código controla adecuadamente los servos y el motor de pasos, sería importante verificar que el hardware utilizado (como los servos, LEDs, etc.) tenga suficiente alimentación. Esto garantizaría que no haya fallos o comportamientos inesperados en el sistema.

Aspectos Técnicos y de Calidad a Resaltar:
Uso Correcto de la Programación Orientada a Objetos:
El uso de clases para gestionar los distintos componentes del robot (brazos, cabeza, ojos) muestra un buen manejo de la programación orientada a objetos, lo que facilita la organización y la extensión del proyecto.

Funcionalidad Robusta:
El proyecto está funcionando correctamente, y todas las animaciones se realizan tal como se esperaba. La implementación ha sido eficaz y cumple con los objetivos planteados.

## Capturas de Evaluaciones de Curso de Python
https://drive.google.com/drive/folders/1Nh_edk_xUWbrq-ghn5cRnI_C3ToqTn2c?usp=sharing
