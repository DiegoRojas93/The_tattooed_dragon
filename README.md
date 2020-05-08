# Framework Foundation

### Agregando un menú lateral off-canvas

Foundation tiene componentes para que incorpores elementos off-canvas de navegación, Off-canvas significa todo aquello que está fuera de tu visión.

Esto quiere decir que podemos hacer que aparezca un menú desplegable de forma lateral haciéndolo aparecer con un solo click. Por ejemplo un botón de menú o un burger button.

https://get.foundation/sites/docs/off-canvas.html

```
<body>
  <div class="off-canvas position-left" id="offCanvas" data-off-canvas>
    <!-- puedes meter el listado en html-->
  </div>
  <div class="off-canvas-content" data-off-canvas-content>
    <!-- Puedes poner el codigo de todo el cuerpo o body de tu html -->
  </div>
</body>
```

**position-left**: puedes enviar la posición de tu menú desplegable ya sea en la sigientes posiciones: -left ; -right; -top ; -bottom.

**data-toggle="offCanvas"**: Este atributo debe ser añadido a la etiqueta que desee hacer la acción de aparecer el menú desplegable, Por ejemplo un botón de menú o un burger button.
