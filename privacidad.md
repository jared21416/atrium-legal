---
title: Política de privacidad
---

# Política de privacidad de Atrium

**Última actualización:** 11 de noviembre de 2026

Atrium es una aplicación para Android que organiza los archivos de tus
proyectos en tu teléfono, los sincroniza con tu Google Drive o tu OneDrive, y
te enseña tu agenda de Google Calendar u Outlook. Esta página explica qué datos usa Atrium, para qué y dónde quedan.

## Lo esencial

- **Atrium no tiene servidores.** No hay una nube de Atrium, ni analítica, ni
  publicidad, ni ningún servicio de terceros que reciba tus datos. La única
  salvedad es el escáner de documentos de Google, que envía a Google datos de
  diagnóstico —nunca tus documentos—; está explicado en «Fotos y escaneos».
- **Tus archivos y tu agenda van directamente entre tu teléfono y tu propia
  cuenta** de Google o de Microsoft, con tus credenciales. No pasan por ningún
  intermediario.
- **Atrium no vende ni comparte tus datos** con nadie.

## Qué datos usa y para qué

**Tus archivos.** Atrium lee y escribe solo en las carpetas que tú eliges en el
teléfono, para listarlas, abrirlas, ordenarlas y sincronizarlas. Las
calcomanías (tus notas) se guardan como archivos en `Documents/Atrium/Calcomanías`,
o en la carpeta que tú elijas.

**Fotos y escaneos.** Desde la portada de un proyecto puedes hacer una foto o
escanear un documento, y el resultado se guarda en la carpeta del proyecto. La
foto la hace la app de cámara de tu teléfono y el escaneo los servicios de
Google Play, cada uno con su propio permiso de cámara: Atrium no lo pide. El
escáner procesa el documento **en el propio teléfono**, sin enviarlo a ningún
sitio. Para funcionar, Google Play services puede enviar a Google datos de
diagnóstico del escáner —el modelo y la versión del teléfono, la versión de
Atrium, un identificador de la instalación y medidas de rendimiento—, cifrados
y sin compartirlos con terceros, según la
[divulgación de datos de ML Kit](https://developers.google.com/ml-kit/android-data-disclosure).
Si no usas el escáner, no se envía nada.

**Tus cuentas de Google y Microsoft**, solo si las conectas, y con los permisos
justos para cada función:

| Cuenta | Permiso | Para qué |
|---|---|---|
| Google | `drive.file` | Ver y modificar en tu Google Drive solo los archivos y carpetas que Atrium creó o que tú le entregaste con el selector de Google. |
| Google | `calendar.events` y `calendar.calendarlist.readonly` | Ver tus calendarios, y ver, crear, modificar y borrar sus eventos desde la agenda de Atrium. |
| Microsoft | `Files.ReadWrite` | Sincronizar las carpetas de tu OneDrive que vincules a un proyecto. |
| Microsoft | `Calendars.ReadWrite` | Ver, crear, modificar y borrar los eventos de tu calendario de Outlook. |
| Microsoft | `User.Read` | Saber qué cuenta conectaste, para enseñarla. |

Atrium no lee tu correo, tus contactos ni ningún otro dato de esas cuentas.

**Lo que Atrium guarda en tu teléfono**, en su propia base de datos, para
funcionar: tus proyectos y sus carpetas, el estado de la sincronización de cada
archivo y su historial, tus tareas, los horarios que le pones a un proyecto, la
fecha en que nació cada calcomanía, qué calcomanía enseña cada widget de tu
pantalla de inicio, y de cada cuenta conectada su correo, su nombre y su foto
para enseñarla. Nada de eso sale del teléfono, salvo el respaldo que tú
exportes (ver «Copias de seguridad»).

**Tus credenciales.** Atrium no ve ni guarda tus contraseñas. El inicio de
sesión lo hacen Google (a través de Google Play Services) y Microsoft (a través
de su biblioteca oficial, MSAL), que custodian los permisos en el propio
teléfono.

## Uso de los datos de Google

El uso y la transferencia a cualquier otra aplicación de la información
recibida de las API de Google se ajustará a la
[Política de datos de usuario de los servicios de API de Google](https://developers.google.com/terms/api-services-user-data-policy),
incluidos los requisitos de uso limitado. En concreto: los datos de Google
Drive y Google Calendar se usan solo para las funciones descritas arriba, no se
transfieren a nadie, no se usan para publicidad y ninguna persona los lee.

## Permisos del teléfono

- **Internet y estado de la red:** para hablar con Google y Microsoft, y para
  no sincronizar con datos móviles si así lo pides.
- **Notificaciones:** los avisos de sincronización, de lo que hay por revisar
  en la bandeja y de tus entregas. Se pueden apagar.
- **Servicio en primer plano, arranque y mantener activo:** para que una
  sincronización larga no se corte y para reprogramar los avisos al reiniciar el
  teléfono.
- **Ignorar la optimización de batería:** solo si lo aceptas, para que la
  sincronización automática funcione con la pantalla apagada.
- **Acceso a todos los archivos:** solo si lo aceptas, y solo para poder vigilar
  la carpeta de Descargas, que Android no deja elegir de otra forma. Se ofrece al
  tocar esa carpeta, nunca al instalar.
- **NFC, biometría y huella:** los declara la biblioteca de inicio de sesión de
  Microsoft para sus formas de autenticación. Atrium no los usa por su cuenta.

## Compartir

Cuando compartes una calcomanía o un archivo, Atrium lo entrega a la aplicación
que tú eliges en el menú de compartir de Android. No lo envía a ningún otro
sitio. Lo mismo la bitácora de un proyecto en PDF: se guarda donde tú elijas en
el selector de archivos de Android.

## Copias de seguridad

Los datos de Atrium están excluidos de las copias de seguridad de Android: no
se suben a tu copia de Google.

Puedes hacer tu propia copia desde **Configuración › Respaldo › Exportar
respaldo**: un archivo con tus proyectos y sus carpetas, sus descripciones, tus
tareas y tus horarios. Se guarda **donde tú elijas** en el selector de archivos
de Android —en el teléfono o en tu nube— y Atrium no lo envía a ningún otro
sitio. No lleva tus cuentas, tus contraseñas ni tus archivos. Es texto legible:
quien tenga ese archivo puede ver lo que contiene, así que guárdalo donde
guardarías tus documentos.

## Cómo borrar tus datos

- **Desconectar una cuenta** en Atrium la quita de la aplicación y cierra su
  sesión.
- **Quitar un proyecto** lo olvida en Atrium sin tocar los archivos de su
  carpeta, salvo que marques «Borrar también su carpeta del teléfono»: entonces
  la carpeta se borra del teléfono sin pasar por ninguna papelera. Lo que ya
  estaba en tu nube no se toca.
- **Desinstalar Atrium** borra todo lo que guarda en su base de datos: tus
  proyectos, tareas, horarios y cuentas conectadas. **Tus archivos y tus
  calcomanías no**: se quedan en sus carpetas, también en
  `Documents/Atrium/Calcomanías`, y se borran con cualquier explorador de
  archivos. En Android 10 o anterior las calcomanías viven en una carpeta de la
  aplicación que Android borra al desinstalar; la aplicación te avisa de ello.
- **Un respaldo exportado** es un archivo tuyo: sigue donde lo guardaste aunque
  desinstales Atrium, y se borra como cualquier otro.
- Lo que ya está en tu Google Drive, tu OneDrive o tus calendarios es tuyo y
  sigue ahí: se borra desde esos servicios.

## Menores

Atrium no está dirigida a menores de 13 años y no recoge datos de nadie a
sabiendas.

## Cambios

Si esta política cambia, la fecha de arriba cambia con ella. El uso de Atrium
se rige además por sus [términos de uso](terminos).

## Contacto

Para cualquier duda sobre esta política o sobre tus datos: [atriumofthought@gmail.com](mailto:atriumofthought@gmail.com).
