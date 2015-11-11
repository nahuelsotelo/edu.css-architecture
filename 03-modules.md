# 3. Componentes modulares

### ¿Qué es un componente/módulo/objeto?:

“It's a repeating visual pattern, that can be abstracted into an independent snippet of HTML, CSS and possibly JavaScript.”
- _Nicole Sullivan_


### Características de un componente:

- Los componentes son pequeños trozos de funcionalidad.
- Tienen sentido independientes de su contexto.
- Tienen que ser *predecibles*. Al cambiarlos de contexto no deben comportarse de maneras inesperadas.
- No deben estar condicionados por su contexto ni afectar al resto de componentes de la página si lo hacen debe ser siempre de a misma manera. Separar componentes de layout.
- Sus estilos deben ser autocontenidos, no se filtran al scope global.
- El CSS de un componente tiene que tener una logica interna, que debe apreciarse leyendo el código.
