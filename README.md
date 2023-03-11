# Laborarorio 1 - Robótica Industrial No.1

### Equipo (Grupo de laboratorio Viernes 2-4PM)
- Christian Camilo Cuestas Ibáñez
- José Daniel Suárez Vásquez
- Hector Daniel Vargas Berdejo

## Diseño de herramienta
Para la fabricación de la herramienta se utilizaron partes recicladas en impresión 3D de PLA. Se hizo la calibracion en el laboratorio, dando los siguientes valores:

- Max error   1.43106mm
- Min Error   0.4260973mm
- Mean Error  0.7954232mm
- X:          88.20625mm
- Y:          -8.343822mm
- Z:          117.4335mm

<img src="HERRAMIENTA/Mecanizado 1.jpeg"  width="530" height="300">

## Descripción de solución planteada
Para el laboratorio se hizo una Simulación usando el Robostudio. En este se importó una archivo CAD que contiene las letras que se van a plasmar en el tablero. Y sé puso un marco de referencia sobre este archivo CAD. A continuación se crearon targets para cada una de las letras  y se hizo una rutina escribir. También se crearon unas trayectorias para ir a home de maquina y para acercarse al tablero. Esto lo podemos ver en el código RAPID.


### Simulación

- [Ver video simulación](/MULTIMEDIA/Simulacion.mp4)

### Resultado

<img src="MULTIMEDIA/Resultado2.jpg"  width="300" height="400">

- [Ver video 1 escribiendo](/MULTIMEDIA/PrimeraEscritura.mp4)
- [Ver video 2 escribiendo](/MULTIMEDIA/SegundaEscritura.mp4)
