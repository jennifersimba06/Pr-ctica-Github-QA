# Historia de Usuario 2: Inicio de sesión

**Como** un cliente registrado de LePetitDep,  
**Quiero** iniciar sesión de forma segura con mis credenciales,  
**Para** acceder a mis datos guardados y realizar compras.

### Criterios de Aceptación:
* **Escenario: Inicio de sesión exitoso**
    * **Dado que** el usuario está en la pantalla de Login.
    * **Cuando** ingresa sus credenciales correctas (email y contraseña).
    * **Entonces** el sistema valida la identidad y le da acceso a la plataforma.
* **Escenario: Validación de credenciales erróneas**
    * **Dado que** el usuario ingresa un correo o contraseña incorrectos.
    * **Cuando** intenta iniciar sesión.
    * **Entonces** el sistema debe mostrar un mensaje de error claro ("Credenciales incorrectas") y bloquear el acceso.
