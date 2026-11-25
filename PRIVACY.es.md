# Privacidad — LD Studio

**Resumen: la app no recopila nada y no tiene permiso de internet.**

## Qué datos maneja

- **UID y contenido del tag NFC**: se leen en el teléfono para mostrar la información y escribir el
  tag. Nunca se envían a ningún servidor.
- **Idioma y UID de tags originales detectados**: se guardan **localmente** en el
  almacenamiento de la app (`localStorage` de la WebView) y en archivos internos.
- **Registro (log)**: se escribe localmente en `filesDir/ldstudio.log` y en logcat. Se puede
  exportar a la carpeta de la app (`Android/data/io.github.matcarfer.ldstudio/files/exports/`) o compartir por
  el selector de Android, siempre por acción tuya.
- **Diagnóstico**: modelo de teléfono, versión de Android, versión de la app y estado del tag. Se
  muestra en pantalla y solo sale del teléfono si lo exportás o compartís.

## Qué NO hace

- No pide permiso `INTERNET` (el manifiesto no lo declara).
- No usa analítica, publicidad, crash reporting ni cuentas.
- No lee contactos, ubicación, cámara, archivos personales ni mensajes.
- No accede a otros tags ni a otros datos del teléfono.

## Permisos declarados

| Permiso | Para qué |
|---|---|
| `android.permission.NFC` | Leer y escribir tags NFC. Es un permiso normal (no pide confirmación). |

## Borrar tus datos

- Desinstalar la app borra los registros internos.
- Los archivos exportados quedan en `Android/data/io.github.matcarfer.ldstudio/files/exports/` hasta que los
  borres a mano.

## Cambios

Cualquier cambio en esta política se publica en este repositorio.

