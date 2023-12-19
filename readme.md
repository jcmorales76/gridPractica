Conceptos
Resumen:

Para diseñar utilizando Grid CSS, es esencial comprender algunos conceptos clave:

1. **Contenedor:** El elemento padre que define la cuadrícula.
2. **Ítem:** Cada hijo dentro del contenedor de la cuadrícula.
3. **Celda (grid cell):** La unidad mínima de la cuadrícula.
4. **Área (grid area):** Una región o conjunto de celdas en la cuadrícula.
5. **Banda (grid track):** Una banda horizontal o vertical de celdas.
6. **Línea (grid line):** El separador horizontal o vertical entre celdas.

Para implementar Grid CSS, se sigue el siguiente formato en HTML:

```html
<div class="grid"> <!-- contenedor -->
  <div class="item item-1">Item 1</div>
  <div class="item item-2">Item 2</div>
  <div class="item item-3">Item 3</div>
  <div class="item item-4">Item 4</div>
</div>
```

La activación de la cuadrícula se realiza mediante la propiedad `display` en el elemento contenedor, con valores como `grid` o `inline-grid`. Estos valores determinan cómo la cuadrícula se comportará en relación con el contenido exterior, ya sea apareciendo encima/debajo (en bloque) o a la izquierda/derecha (en línea).

Resumen:

En Grid CSS, la definición explícita de filas y columnas es esencial para establecer la estructura de la cuadrícula. Esto se logra mediante las propiedades `grid-template-columns` y `grid-template-rows`, que especifican los tamaños respectivos de las columnas y las filas. Por ejemplo:

```css
.grid {
  display: grid;
  grid-template-columns: 50px 300px;
  grid-template-rows: 200px 75px;
}
```

En este código, la propiedad `display: grid` indica la intención de crear una cuadrícula, mientras que `grid-template-columns` y `grid-template-rows` definen los tamaños de las columnas y las filas, respectivamente. Este enfoque permite establecer una cuadrícula con cuatro celdas en total.

