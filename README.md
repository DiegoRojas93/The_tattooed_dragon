# Framework Foundation

### Agregar Smooth Navigation

Smooth-scroll es un atributo que nos perminte un desplazamiento suave cuando hacemos un click a un enlace interno de la pagina web. Es muy utilizado para un listado de links.

Simplemente agregue el atributo data-smooth-scroll al contenedor principal como nuestro meno, oseas a la etiqueta ul.

https://get.foundation/sites/docs/smooth-scroll.html

**Nota:** podemos salirnos del offcanvas con al hacer click al un link de la pagina web. Esto lo hacemos con agregando el sigiente codigo al archivo app.

```
$('#offCanvasMenu li a').click(() =>{
  $('#offCanvas').foundation('close')
})
```
La lista del menu del offcanvas debe tener un id con este valor (offCanvasMenu) y el codigo que esta en el app.js debera eatar referenciado en cada anchor del lstado para que escuche cada click de cada uno de los links.

// #offCanvasMenu li a

el codigo base del Of canvas debera tener un id para que la fuencion de cerrar el offcanvas actue sobre él.


https://get.foundation/sites/docs/off-canvas.html#js-functions
