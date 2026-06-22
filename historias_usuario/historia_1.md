# Historia de Usuario 1: Registro de usuario

**Como** un nuevo cliente de LePetitDep,  
**Quiero** crear una cuenta utilizando mi correo electrónico y una contraseña,  
**Para** poder realizar pedidos y guardar mi historial en la plataforma.

### Criterios de Aceptación:
* **Escenario: Registro exitoso**
    * **Dado que** el usuario se encuentra en la página de registro.
    * **Cuando** ingresa un correo electrónico válido, una contraseña segura y hace clic en "Registrarse".
    * **Entonces** el sistema debe crear la cuenta y redirigir al usuario a la pantalla de inicio o menú principal.
* **Escenario: Registro con correo ya existente**
    * **Dado que** el usuario intenta registrarse con un correo electrónico que ya está en la base de datos.
    * **Cuando** hace clic en "Registrarse".
    * **Entonces** el sistema debe mostrar un mensaje de error indicando que el correo ya está en uso.
