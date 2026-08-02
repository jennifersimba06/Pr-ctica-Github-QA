# Casos de prueba - Historia 1: Registro de usuario

## Caso de prueba 1

**ID del caso:** TC-001

**Título:** Registro exitoso de usuario

**Objetivo:** Validar que un usuario pueda crear una cuenta con datos válidos.

**Precondiciones:**
- La aplicación está disponible.
- El usuario no posee una cuenta registrada.

**Datos de prueba:**
- Correo: usuario@test.com
- Contraseña: Password123

**Pasos:**
1. Abrir la aplicación.
2. Seleccionar la opción "Registrarse".
3. Ingresar el correo electrónico.
4. Ingresar la contraseña.
5. Presionar el botón "Crear cuenta".

**Resultado esperado:**
La cuenta se registra correctamente y el usuario recibe un mensaje de confirmación.

**Resultado obtenido:**
Pendiente.

**Estado:**
Pendiente.

**Notas/Evidencias:**
Pendiente.

---

## Caso de prueba 2

**ID del caso:** TC-002

**Título:** Registro con correo inválido

**Objetivo:** Validar que el sistema rechace un correo con formato incorrecto.

**Precondiciones:**
- La aplicación está disponible.

**Datos de prueba:**
- Correo: usuario
- Contraseña: Password123

**Pasos:**
1. Abrir la aplicación.
2. Seleccionar "Registrarse".
3. Ingresar un correo inválido.
4. Ingresar una contraseña válida.
5. Presionar "Crear cuenta".

**Resultado esperado:**
El sistema muestra un mensaje indicando que el correo es inválido y no crea la cuenta.

**Resultado obtenido:**
Pendiente.

**Estado:**
Pendiente.

**Notas/Evidencias:**
Pendiente.
