# Framework Foundation

### Adaptando el menú de navegación para dispositivos móviles

Las herramientas de prototypado son aquellas funcionalidades que podemos incorporar para darle un estilo mucho más personal a nuestos proyectos.

https://get.foundation/sites/docs/prototyping-utilities.html

**Las herramientas de prototipado estan desabitadas por defecto** para habilitarlas hay que descomentar el siguiente codigo en app.scss

```
@include foundation-prototype-classes;
```

Algunas de estas herramientas son:

-Mostrar items en tamaño de pantalla SMALL
```
<header class="show-for-small"></header>
```
-Ocultar items en tamaño de pantalla MEDIUM
```
<header class="show-for-medium"></header>
```
-Mostrar items SOLO en un tamaño de pantalla
```
<header class="show-for-small-only"></header>
<header class="show-for-medium-only"></header>
<header class="show-for-large-only"></header>
```
**Reordenar celdas**

Las celdas ocupan toda la fila y al ser re ordenadas se colocaran una encima de otra dependiendo del orden que se estableció.

```
<div class="cell small-12 small-order-3"></div>
<div class="cell small-12 small-order-2"></div>
<div class="cell small-12 small-order-1"></div>
```
