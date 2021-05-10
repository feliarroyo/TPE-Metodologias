# Especificación de caso de uso: Registrarse en la página

## 1. Descripción breve

El ciudadano crea un usuario, donde ingresa sus datos personales y define cómo quiere que sean los retiros de sus materiales.

## 2. Curso básico de eventos

1. El caso de uso comienza cuando el ciudadano quiere registrarse a la página de la cooperativa.
2. La página solicita los datos personales.
3. El ciudadano ingresa su nombre, apellido, dirección, teléfono y fecha de nacimiento. Opcionalmente, podría ingresar una imagen.
4. La página solicita un identificador único.
5. El ciudadano ingresa su DNI y una contraseña.
6. La página verifica los datos ingresados.
7. La página guarda los datos de la cuenta del ciudadano.
8. El caso de uso finaliza.

## 3. Cursos alternativos

### 6.1 La contraseña ingresada es incorrecta

1. El DNI ya fue utilizado en otra cuenta.
2. Se le informa al usuario que ya hay una cuenta registrada con dicho DNI.
3. El caso de uso finaliza.

## 4. Suposiciones

Debe haber un ciudadano interesado en ingresar al sistema de nuestra cooperativa (que no tenga un usuario creado con anterioridad)

## 5. Precondición

Ninguna.

## 6. Postcondición

El ciudadano ahora tiene un usuario con el cual ingresar a la página y publicar o postularse a ofertas.