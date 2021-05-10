# Especificación del caso de uso: Verificar lejanía

## 1. Descripción breve

Este caso se utiliza para verificar la distancia que hay entre el centro de acopio y la casa del solicitante de la recolección, ya que si hay más de 6 km se debe rechazar la solicitud.


## 2. Curso básico de eventos

1. El caso de uso comienza cuando se quiere verificar la lejanía entre el centro de acopio y la casa del ciudadano. 
2. La página detecta la dirección ingresada por el usuario.
3. La página calcula la distancia con el centro de acopio.
4. Si la distancia está en lo aceptado por el centro (6 km o menos), el caso de uso finaliza.

## 3. Cursos alternativos

### 6.1. El ciudadano no está en el rango designado por la cooperativa como aceptable.

1. Si la distancia es mayor a 6 km, la página informa sobre el rechazo de la solicitud.
2. El caso de uso finaliza.


## 4. Suposiciones

El domicilio ingresado es válido y existente.

## 5. Precondición

El usuario debe haber solicitado la recolección de materiales en algún domicilio.

## 6. Postcondición

Fue verificado si el domicilio puede acceder a los servicios de la cooperativa o no.