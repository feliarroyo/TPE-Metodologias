# Especificación del caso de uso

## Nombre de caso de uso
Solicitar recolección

## Descripción
El ciudadano ingresa a la página, ingresa los datos correspondientes y solicita la recolección de los materiales reciclables que posee.

## Actor primario
Ciudadano

## Actor secundario
Sistema de geolocalización

## Trigger
El caso de uso comienza cuando el ciudadano quiere solicitar recolección de elementos.

## Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano quiere solicitar recolección de elementos.
2. [INCLUDE] Ingresar a la página.
3. El ciudadano ingresa a la sección correspondiente para solicitar una recolección.
4. La página solicita nombre, apellido, dirección, teléfono, franja horaria para retirar y opcionalmente una foto. 
5. El ciudadano ingresa los datos solicitados.
6. La página toma el dato de la dirección y, interactuando con el sistema de geolocalización, verifica la distancia con el centro de acopio.
7. La página muestra las opciones de categoría, según el volumen de elementos.
8. El ciudadano selecciona la opción correspondiente.
9. La página notifica que la solicitud se registró con éxito.
10. El caso de uso finaliza.


## Cursos alternativos
_(Si la página detecta que la dirección está ubicada a más de 6km del centro de acopio)_
### 6. La página toma el dato de la dirección y, a través de la geolocalización, verifica la distancia con el centro de acopio.
1. La página no realizó la verificación correctamente debido a que hay más de 6 km entre el centro de acopio y la dirección brindada por el Ciudadano. 
2. La página notifica 	que se rechazó la solicitud de recolección.
3. La página envía un email al ciudadano informando la denegación.
4. El caso de uso finaliza.

## Precondición
El usuario debe haber iniciado sesión en su cuenta.

## Suposiciones
El usuario cuenta con materiales para reciclar.

## Postcondición
El usuario ha ingresado una solicitud para recoger materiales reciclables en su domicilio.

## Caso de uso incluido/que incluye
Ingresar a la página