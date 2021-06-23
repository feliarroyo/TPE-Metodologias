# Sprint Retrospective (Resumen 23-06-21)

## Toma de nota

### Devolución de segunda entrega
- "Backlog, refinamiento, etc" está todo bien.
- Hay una duda con el diagrama de clases: La herencia de ciudadano con cuenta.
- Tiene conflicto con un diagrama de secuencia: el de registrarse.
- El ciudadano le dice validarCuenta, pero en el diagrama de clases el ciudadano _hereda_ de cuenta.
- Para arreglarlo, debería ser una flecha normal (nunca lo pensamos como herencia).
- En ciudadano: hay que verificar que los tipos estén bien expresados (ej: nombre: String)
- Los métodos que no sean void debe ponerse el retorno.

### Para la tercer entrega
- La consulta del lunes seguramente se mueva debido a que el recuperatorio cae en el horario habitual, con la misma separación de grupos habitual.
- Los diagramas a realizar son de Registrarme (1A) y la generación de recorridos (3B).
- Recordar que probablemente el cartonero no genera sus propios recorridos a la hora de hacer el modelado.
- Se generan, lo guardan y se los llevan.
- El que genera le puede decir a cada cartonero "acá está su recorrido"; _O_ el cartonero lo va a buscar y lo toma.
- "Extensión interna": Hasta el martes habría tiempo.

## ACTION ITEMS
- Verificar que en los nodos del diagrama de clases estén bien escritos los atributos (especialmente el ciudadano) 
- Continuar con el refinamiento.
- Realizar diagramas de secuencia de cartonero: Registrarme (1A) y la generación de recorridos (3B).