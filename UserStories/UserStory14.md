# User Story N°14: Como cartonero quiero obtener un listado de los recorridos, para saber los lugares donde debo ir durante mi jornada.

## Descripción

Para el caso de los cartoneros, es importante registrar el peso de lo que lleva, ya que es lo que define la paga que va a recibir si se lograra vender el tipo de materiales reciclables que lleva.

### Criterios de aceptación

- El listado debe generarse de lunes a viernes a las 8hs.
- El listado debe llegar sin falta a todos los cartoneros antes del inicio de su jornada.
- El listado debe ser equitativo con todos los cartoneros registrados.
- Lo asignado a cada cartonero es en base a lo que pueda llevar su vehículo; y el recorrido no puede superar los 6 km.
- Si el volumen de los materiales a retirar es "a", solo se realizan en recorridos en camino a otros destinos con materiales de volumen "b", "c" o "d".
- Los lugares no visitados en recorridos anteriores deben ser prioridad para ser agregados al proximo.

### Tareas para su realización

1. Generar lista de recorridos a las 8 hs.
1. Enviar a los cartoneros al inicio de su jornada.
1. Registrar lugares no visitados al final de la jornada.

### Nota

Este caso sería un evento de reloj.