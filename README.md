# Framework Foundation

### Agregando el listado de productos

Es muy abitual que cuando escribimos codigo en foundation se cree una grilla dentro de otra, esto es llamado nesting, pero hacerlo demaciadas veces se vuelve muy inicesario.

https://get.foundation/sites/docs/grid.html#nesting
Hay un truco en Foundation que para hacer un que una celda repina N cantidad de veces con solamente un codigo, eso se puede hacer con los Handlebars!

```
{{repeat 25}}
  codigo...
{{/repeat}}
```

Foundation al igual que Boostrap podemos hacer badges o asi tambien llamados labels

```
<span class="label">Soy un Label</span>
```
https://get.foundation/sites/docs/label.html
