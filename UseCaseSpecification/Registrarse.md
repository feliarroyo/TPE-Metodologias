# Especificación de caso de uso

## Nombre de caso de uso
Registrar

## Descripción
El ciudadano crea un usuario, donde ingresa sus datos personales y define cómo quiere que sean los retiros de sus materiales.

## Actor primario
Ciudadano

## Curso básico de eventos
1. El caso de uso comienza cuando el ciudadano quiere registrarse a la página de la cooperativa.
2. La página solicita los datos personales.
3. El ciudadano ingresa su nombre, apellido, dirección, teléfono y fecha de nacimiento. Opcionalmente, podría ingresar una imagen.
4. La página solicita un identificador único.
5. El ciudadano ingresa su DNI y una contraseña.
6. La página verifica los datos ingresados.
7. La página guarda los datos de la cuenta del ciudadano.
8. El caso de uso finaliza.

## Cursos alternativos
_(A partir del paso 4, si el DNI ya tiene un usuario asociado)_
1. Se le informa al usuario que ya hay una cuenta registrada con dicho DNI.
2. El caso de uso finaliza.

## Precondición
Ninguna.

## Suposiciones
Debe haber un ciudadano interesado en ingresar al sistema de nuestra cooperativa (que no tenga un usuario creado con anterioridad)

## Postcondición
El ciudadano ahora tiene un usuario con el cual ingresar a la página y publicar o postularse a ofertas.

## Caso de uso extendido
Extiende al caso de uso Ingresar a la página. Cuando se necesita registrar a un ciudadano, en el PTO EXT [Necesita registrarse].