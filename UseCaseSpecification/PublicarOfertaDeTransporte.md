# Especificación de casos de uso: Publicar oferta de transporte

## 1. Descripción breve

El ciudadano ingresa a la página para publicar una oferta de transporte.

## 2. Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano desea publicar en la página una oferta de transporte.
2. (INCLUDE) El ciudadano ingresa a la página.
3. El ciudadano ingresa a la sección para publicar una oferta de transporte.
4. La página le solicita nombre, teléfono, email, dirección, espacio disponible y brinda un espacio de texto opcional.
5. El ciudadano ingresa los datos solicitados.
6. La página genera el posteo, colocando solo visible la zona geográfica, espacio disponible y el texto libre.
7. La página muestra un aviso informando que el posteo se realizó de forma exitosa.
8. El caso de uso finaliza.



## 3. Cursos alternativos

#### 5.1. La página detecta datos inválidos.

1. La página notifica cuál de los dato ingresados resulta insuficiente. (por ejemplo, si el volumen ingresado no es válido para ninguna categoría)
2. La página le ofrece al usuario modificar los datos si lo desea.
3. El usuario vuelve a ingresar los datos.
4. La página verifica nuevamente los nuevos datos ingresados, si siguen siendo incorrectos el curso alternativo se repite, de lo contrario continua en el paso 6 del curso básico.

## 4. Suposiciones

El ciudadano tiene un vehículo con espacio disponible.

## 5. Precondición

El usuario tiene una cuenta en la página de la cooperativa.

## 6. Postcondición

El posteo fue cargado a la cartelera en base a lo proporcionado por el usuario; y otros ciudadanos pueden verlo y postularse.