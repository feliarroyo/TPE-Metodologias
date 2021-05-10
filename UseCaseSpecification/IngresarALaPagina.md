# Especificación de caso de uso: Ingresar a la página

## 1. Descripción breve

El ciudadano accede a la página, ingresando los datos correspondientes.

## 2. Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano quiere ingresar a la página.
2. La página solicita el identificador único de la cuenta.
3. El ciudadano ingresa el DNI y una contraseña.
4. La página verifica los datos ingresados.
5. Si los datos son válidos, el usuario inicia sesión exitosamente en la página.
6. El caso de uso finaliza.


## 3. Cursos alternativos

### 4.1 La contraseña ingresada es incorrecta.

1. Se le informa al usuario que la contraseña no es válida, y se ofrece que intente de nuevo.
2. Se vuelve al paso 2 del caso de uso original.

### 4.2 La página no reconoce el DNI ingresado.

1. Se le informa al usuario que no hay cuenta registrada con dicho DNI.
2. (INCLUDE) Se lo redirige a “Registrarse al sistema”.
3. Luego de haberse creado el usuario, se inicia sesión automáticamente en este.
4. El caso de uso finaliza.

## 4. Suposiciones

Debe haber un ciudadano interesado en ingresar al sistema de nuestra cooperativa (que no tenga un usuario creado con anterioridad)

## 5. Precondición

Ninguna.

## 6. Postcondición

El ciudadano ahora tiene un usuario con el cual ingresar a la página y publicar o postularse a ofertas.