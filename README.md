# Vida Artificial 

## Integrantes
- Carlos Eduardo Guerrero Jaramillo
- Jorge Augusto Estacio Almeciga
- Santiago Pérez Pino

Universidad del Valle - Sede Tuluá
2024


## Instrucciones para ejecutar el código

Para ejecutar este modelo en NetLogo, se deben seguir los siguientes pasos:

1. **Instalar NetLogo:**
   - Descarga e instala NetLogo desde el sitio oficial: [NetLogo Downloads](https://ccl.northwestern.edu/netlogo/download.shtml).

2. **Descargar Modelo:**
    - Descarga el archivo `EjemploPatchesReglasTransicion.nlogo` que se encuentra en este repositorio.

2. **Abrir el proyecto:**
   - Una vez que NetLogo esté instalado, abrir la aplicación NetLogo.
   - En la aplicación, selecciona `Archivo > Abrir...` y navega hasta el archivo `.nlogo` del proyecto.
  
4. **Ejecutar el modelo:**
   - Haz clic en el botón `Inicializar` para inicializar la simulación.
   - Luego, haz clic en el botón `Avanzar` para comenzar la simulación. La simulación continuará ejecutándose en bucle hasta que hagas clic en el botón `Avanzar` nuevamente para detenerla.

## Descripción del modelo

Este modelo utiliza un enfoque de autómatas celulares bidimensional para simular la segregación económica en una ciudad. Cada `patch` representa una celda en la cuadrícula, que puede pertenecer a uno de varios estratos económicos. Los `patches` pueden cambiar de estado (color) basado en las reglas de transición que consideran la mayoría de los vecinos y su estrato económico.
