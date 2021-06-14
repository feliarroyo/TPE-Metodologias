# Especificación de caso de uso

## Nombre de caso de uso
Ingresar a la página

## Descripción
El ciudadano accede a la página, ingresando los datos correspondientes.

## Actor primario
Ciudadano

## Curso básico de eventos
1. El caso de uso comienza cuando el ciudadano quiere ingresar a la página
2. La página solicita el identificador único de la cuenta.
3. El ciudadano ingresa el DNI y una contraseña.
4. La página verifica los datos ingresados.
5. Si los datos son válidos, el usuario inicia sesión exitosamente en la página.
6. El caso de uso finaliza.

## Cursos alternativos
_(A partir del paso 4, si la página detecta que la contraseña ingresada es incorrecta)_
1. La página verifica los datos ingresados.
2. La página no pudo realizar correctamente la verificación.
3. Se vuelve al paso 2 del curso básico.

_(A partir del paso 4, si la página no reconoce el DNI ingresado)_
1. La página verifica los datos ingresados.
2. Se le informa al usuario que no hay cuenta registrada con dicho DNI.
3. [PTO EXT] Necesita registrarse.
4. Luego de haberse creado el usuario, se inicia sesión automáticamente en este.
5. El caso de uso finaliza.

## Precondición
Ninguna.

## Suposiciones
El servidor de la página está en línea.

## Postcondición
El ciudadano ha iniciado sesión en su usuario designado.