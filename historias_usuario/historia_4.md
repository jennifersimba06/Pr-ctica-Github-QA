# Historia de Usuario 4: Agregar productos al carrito

**Como** un cliente que explora el menú,  
**Quiero** seleccionar productos y especificar la cantidad para agregarlos a un carrito de compras,  
**Para** consolidar mi orden antes de realizar el pago.

### Criterios de Aceptación:
* **Escenario: Agregar un producto por primera vez**
    * **Dado que** el usuario está en el menú y selecciona un producto.
    * **Cuando** define una cantidad mayor a cero y presiona "Agregar al carrito".
    * **Entonces** el carrito debe actualizar el contador de ítems y reflejar el producto seleccionado.
