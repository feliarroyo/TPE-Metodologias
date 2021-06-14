# Especificación de casos de uso

## Nombre de caso de uso
Publicar oferta de transporte

## Descripción
El ciudadano ingresa a la página para publicar una oferta de transporte.

## Actor primario
Ciudadano

## Actor secundario
Sistema de geolocalización

## Curso básico de eventos
1. El caso de uso comienza cuando el ciudadano desea publicar en la página una oferta de transporte.
2. [INCLUDE] Ingresar a la página.
3. El ciudadano ingresa a la sección para publicar una oferta de transporte.
4. La página le solicita nombre, teléfono, email, dirección, espacio disponible y brinda un espacio de texto opcional.
5. El ciudadano ingresa los datos solicitados.
6. La página, interactuando con el sistema de geolocalización, detecta la zona geográfica (a partir de la dirección ingresada).
7. La página genera el posteo, colocando solo visible la zona geográfica, espacio disponible y el texto libre (por motivos de privacidad).
8. La página muestra un aviso informando que el posteo se realizó de forma exitosa.
9. El caso de uso finaliza.

## Cursos alternativos

_(A partir del paso 6, si la página no detecta automáticamente la zona geográfica)_
### 6. La página, interactuando con el sistema de geolocalización, detecta la zona geográfica (a partir de la dirección ingresada).
1. La página no pudo detectar la zona geográfica a partir de la dirección.
2. La página notifica al ciudadano y comunica que la ingrese manualmente.
3. El ciudadano ingresa la zona geográfica.
4. La página guarda la zona geográfica y se vuelve al paso 7 del flujo básico.

## Precondición
El usuario tiene una cuenta en la página de la cooperativa.

## Suposiciones
El ciudadano tiene un vehículo con espacio disponible.

## Postcondición
El posteo fue cargado a la cartelera en base a lo proporcionado por el usuario; y otros ciudadanos pueden verlo y postularse.

## Caso de uso incluido/que incluye
Ingresar a la página