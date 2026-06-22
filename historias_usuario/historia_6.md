# Historia de Usuario 6: Historial de pedidos

**Como** un cliente recurrente de LePetitDep,  
**Quiero** consultar un registro de mis órdenes anteriores,  
**Para** verificar mis consumos pasados o volver a pedir los mismos productos de forma rápida.

### Criterios de Aceptación:
* **Escenario: Consultar historial con órdenes previas**
    * **Dado que** el usuario se encuentra en la sección "Mi Historial".
    * **Cuando** la página carga por completo.
    * **Entonces** el sistema debe desplegar una lista cronológica (de la más reciente a la más antigua) con la fecha, el número de orden, el total pagado y los productos de cada pedido.
