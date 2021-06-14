# Especificación de casos de uso

## Nombre de caso de uso
Postular a oferta de transporte

## Descripción

El ciudadano desea postularse a una oferta de transporte, a través de la página, donde en dicha página busca la oferta que más le convenza y selecciona esta misma.

## Actor primario
Ciudadano

## Actor secundario
Generador de la oferta (Ciudadano)

## Trigger
El caso de uso comienza cuando el ciudadano desea postularse a una oferta de transporte.

## Curso básico de eventos
1. El caso de uso comienza cuando el ciudadano desea postularse a una oferta de  transporte. 
1. [INCLUDE] Ingresar a la página.
1. El ciudadano ingresa a la sección correspondiente para ver las ofertas de transporte que se encuentren disponibles.
1. La página lista las categorías posibles para el volumen de los materiales.
1. El ciudadano selecciona el volumen correspondiente.
1. La página muestra las ofertas disponibles.
1. El ciudadano selecciona la oferta disponible que más le convenza.
1. La página solicita nombre, teléfono, dirección.
1. El ciudadano ingresa los datos mencionados.
1. La página reenvía los datos del ciudadano al generador de la oferta.
1. La página detecta que el generador de la oferta aceptó la postulación.
1. La página envía (por email) al ciudadano el nombre, teléfono, dirección y email del generador.
1. La página muestra un aviso de que la postulación fue exitosa y se notifica el envío del email.
1. El caso de uso finaliza.

## Cursos alternativos
_(A partir del paso 11, el generador de la oferta rechaza la postulación)_
## 11. La página detecta que el generador de la oferta rechazó la postulación.
1. La página envía un email al ciudadano notificando la denegación de solicitud.
2. El caso de uso finaliza.

## Precondición
El usuario tiene cuenta en la página de la cooperativa. 

## Suposiciones
Hay al menos una oferta para la cual postularse.

## Postcondición
El usuario se postuló a una oferta y fue aceptado/rechazado por el generador de ella. Ambos son notificados al respecto.

## Caso de uso incluido/que incluye
Ingresar a la página