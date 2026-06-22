# Historia de Usuario 5: Realizar pedido

**Como** un cliente con productos en el carrito de compras,  
**Quiero** confirmar mi orden, simular el método de pago y procesar la solicitud,  
**Para** obtener mi número de orden y pasar a recoger el pedido al local.

### Criterios de Aceptación:
* **Escenario: Confirmación de orden exitosa**
    * **Dado que** el usuario está en la pantalla de revisión del carrito de compras.
    * **Cuando** selecciona el método de pago simulado y hace clic en "Confirmar Pedido".
    * **Entonces** el sistema procesa la transacción, vacía el carrito y muestra una pantalla de confirmación con el número de orden único.
