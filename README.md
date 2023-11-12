# M1

## Propósito 
Conocer y aplicar una herramienta para la implementación de sistemas multiagentes.

## Instrucciones 
Para este problema, deberás entregar, de manera individual, un informe en PDF que estudie las estadísticas de un robot de limpieza reactivo, así como el enlace al repositorio en Github del código desarrollado para esta actividad. El código debe ajustarse al estilo solicita en el siguiente documento.

## Dado:
  - Habitación de MxN espacios.
  - Número de agentes.
  - Porcentaje de celdas inicialmente sucias.
  - Tiempo máximo de ejecución.

## Realiza la siguiente simulación:
  - Inicializa las celdas sucias (ubicaciones aleatorias).
  - Todos los agentes empiezan en la celda [1,1].
  - En cada paso de tiempo:
  - Si la celda está sucia, entonces aspira.
  - Si la celda está limpia, el agente elije una dirección aleatoria para moverse (unas de las 8 celdas vecinas) y elije la acción de movimiento (si no puede moverse allí, permanecerá en la misma celda).
  - Se ejecuta el tiempo máximo establecido.

## Para un espacio de 100x100, considera los siguientes escenarios:
  - Escenario 1: 1 agente, 90% de celdas sucias.
  - Escenario 2. 2 agentes, 90% de celdas sucias.

## Deberás resolver las siguientes preguntas:
  - ¿Cuántos pasos de simulación toma limpiar todo el espacio?
  - ¿Qué porcentaje de celdas sucias queda con los siguientes pasos de simulación: 100, 1000, 10000?
  - A continuación, determina cuál es la cantidad óptima de aspiradoras que debe de tener para realizar la limpieza en el menor tiempo posible. Considera que tenemos un máximo de 10 aspiradoras disponibles.

### Desarrollar un informe con lo observado.
