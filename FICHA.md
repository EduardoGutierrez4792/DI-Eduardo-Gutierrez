# Ficha de mi aplicación · Hito 0

- **Alumno/a:** Eduardo Gutierrez
- **Temática:** Mi aplicacion va sobre un gestor de suscripciones
- **Qué gestiona:** Suscripciones

## Campos

Al menos 7. Como mínimo: 2 de texto · 1 número entero · 1 número decimal · 1 opción de una lista · 1 opción entre 2 o 3 · 1 sí/no.

| # | Campo | Tipo de dato | Componente | Ejemplo de valor / opciones |
|---|-------|--------------|------------|-----------------------------|
| 1 | Nombre de usuario | texto | campo de texto | `juan_perez` |
| 2 | Nombre del servicio | texto | campo de texto | `Netflix` |
| 3 | Edad | entero | selector numérico | `21` |
| 4 | Precio mensual (€) | decimal | selector numérico | `12,99` |
| 5 | Ciclo de pago | lista | lista desplegable | Mensual / Trimestral / Semestral / Anual |
| 6 | Método de pago | opción | botones de opción | Tarjeta / PayPal / Bizum |
| 7 | Avisar antes de la renovación | sí/no | casilla | Sí |

Tipos de dato: `texto`, `entero`, `decimal`, `lista`, `opción`, `sí/no`.
Componentes: `campo de texto`, `selector numérico`, `lista desplegable`, `botones de opción`, `casilla`.

## Pantallas

Las fotos de tus bocetos, en la carpeta `bocetos/` con estos nombres (`.jpg` o `.png`):

| Pantalla | Foto |
|----------|------|
| Inicio de sesión | `bocetos/1_inicio_sesion.jpg` |
| Ventana principal | `bocetos/2_ventana_principal.jpg` |
| Formulario de alta | `bocetos/3_formulario.jpg` |

### Ventana principal

- **Menús y sus opciones:**
  - Archivo: Nueva suscripción · Cerrar sesión · Salir
  - Editar: Editar suscripción · Eliminar suscripción
  - Ayuda: Acerca de

- **Columnas de la tabla:** 
 Servicio · Precio mensual (€) · Ciclo de pago · Método de pago · Próximo pago · Aviso

### Qué hace cada botón

- **Siguiente** (inicio de sesión): comprueba el usuario y la contraseña y, si son correctos, abre la ventana principal.
- **No tienes cuenta?** (inicio de sesión): abre la pantalla de registro.
- **Registrarse** (registro): crea la cuenta con los datos introducidos y vuelve al inicio de sesión.
- **Flecha atrás** (inicio de sesión / registro): vuelve a la pantalla anterior.
- **Cerrar sesión** (ventana principal): cierra la sesión y vuelve al inicio de sesión.
- **+ Nueva suscripción** (ventana principal): abre el formulario de alta.
- **Lápiz** (fila de la tabla): abre el formulario con los datos de esa suscripción para editarlos.
- **Papelera** (fila de la tabla): elimina la suscripción tras pedir confirmación.
- **Añadir** (formulario): guarda la suscripción y la muestra en la tabla.
- **Cancelar / X** (formulario): cierra el formulario sin guardar.

### Mensajes

- Si el usuario o la contraseña están mal: «La contraseña o el usuario estan incorrectos»
- Si falta un campo obligatorio en el formulario: «Debes introducir algo en todos los campos obligatorios»