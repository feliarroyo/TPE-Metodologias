# Especificación del caso de uso: Solicitar recolección de materiales

## 1. Descripción breve

El ciudadano ingresa a la página, ingresa los datos correspondientes y solicita la recolección de los materiales reciclables que posee.


## 2. Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano quiere solicitar recolección de elementos.
2. (INCLUDE) El ciudadano ingresa a la página.
3. El ciudadano ingresa a la sección correspondiente para solicitar una recolección.
4. La página solicita nombre, apellido, dirección, teléfono, franja horaria para retirar y opcionalmente una foto. 
5. El ciudadano ingresa los datos solicitados.
6. (INCLUDE) Verifica lejanía del usuario al centro de acopio.
7. La página muestra las opciones de categoría, según el volumen de elementos.
8. El ciudadano selecciona la opción correspondiente.
9. La página notifica que la solicitud se registró con éxito.
10. El caso de uso finaliza.

## 3. Cursos alternativos

### 6.1. El ciudadano no está en el rango designado por la cooperativa como aceptable.

1. Se le informa al usuario que su solicitud fue rechazada por ello.
2. El caso de uso finaliza.

## 4. Suposiciones

El usuario cuenta con materiales para reciclar.

## 5. Precondición

El usuario debe haber iniciado sesión en su cuenta.

## 6. Postcondición

El usuario ha ingresado una solicitud para recoger materiales reciclables en su domicilio.