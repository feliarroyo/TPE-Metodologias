# Especificación de casos de uso: Postularse a oferta de transporte

## 1. Descripción breve

El ciudadano desea postularse a una oferta de transporte, a través de la página, donde en dicha página busca la oferta que más le convenza y selecciona esta misma.

## 2. Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano desea postularse a una oferta de  transporte. 
2. El ciudadano ingresa a la sección correspondiente de la pagina para ver las ofertas de transporte que se encuentren disponibles.
3. La página muestra las ofertas disponibles.
4. El ciudadano selecciona la oferta disponible que más le convenza.
5. La página solicita nombre, teléfono, dirección.
6. El ciudadano ingresa los datos mencionados.
7. La página lista las categorías posibles para el volumen de los materiales.
8. El ciudadano selecciona el volumen correspondiente.
9. La página reenvía los datos del ciudadano al generador de la oferta.
10. La página muestra un aviso de que la postulación fue exitosa.
11. El caso de uso finaliza.

## 3. Cursos alternativos

#### 10.1 El generador de la oferta rechaza al postulante.

1. La página envía una notificación al postulante de que fue rechazado.
2. El caso de uso finaliza.

## 4. Suposiciones

Hay al menos una oferta para la cual postularse.

## 5. Precondición

El usuario tiene cuenta en la página de la cooperativa. 

## 6. Postcondición

El usuario se postuló a una oferta y fue aceptado/rechazado por el generador de ella. Ambos son notificados al respecto.
