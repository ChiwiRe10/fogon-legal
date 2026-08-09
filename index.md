---
layout: default
title: Politica de privacidad de Fogon
---

# Política de privacidad de Fogón

**Última actualización: 8 de agosto de 2026**

Fogón es un recetario que funciona en tu móvil. No tiene cuentas, no tiene
servidor propio y no lleva publicidad ni analítica.

Esta política describe exactamente lo que hace la app. Si algo de aquí no
coincide con lo que ves, escríbenos: es un error y queremos corregirlo.

## Quién responde de esta app

Fogón la desarrolla y publica **ChiwiRe**, desarrollador independiente radicado
en **Venezuela**. Contacto: **chiwire.dev.contact@gmail.com**.

No hay ninguna otra empresa, socio ni proveedor implicado en el tratamiento de
datos, porque no hay tratamiento de datos: la app no dispone de servidores y
nada de lo que hagas en ella nos llega.

## Resumen

- **No recogemos ningún dato tuyo.** No hay registro, no hay cuenta, no hay
  perfil, no hay identificadores publicitarios.
- **Tus recetas viven en tu móvil**, no en un servidor nuestro. No existe un
  servidor nuestro.
- **No hay publicidad ni analítica**: la app no incluye ningún SDK de
  seguimiento, medición o atribución.
- Algunas funciones que tú eliges usar sí envían información **a terceros**.
  Están todas listadas abajo, una por una.

## Qué se guarda en tu móvil

Todo esto se queda en el dispositivo y solo lo puede leer Fogón:

| Qué | Dónde |
|---|---|
| Tus recetas, categorías, favoritas y la papelera | Base de datos local `fogon.db` |
| Tus preferencias: tema, ajustes de voz | La misma base de datos |
| Las fotos de portada que descargas o eliges | Ficheros en el almacenamiento privado de la app |
| Tu clave de la API de Gemini, si decides poner una | Almacén cifrado del sistema (Android Keystore) |

Para borrarlo todo, desinstala la app. Las recetas sueltas se borran desde la
papelera, y la clave de Gemini desde «Funciones con IA → Quitar».

## Qué sale de tu móvil, y cuándo

Fogón no envía nada por su cuenta a ningún servidor nuestro, porque no lo hay.
Lo que sale va **directo desde tu móvil al tercero correspondiente**:

### 1. Fotos de las recetas de ejemplo — automático

Al abrir la biblioteca, la app descarga las fotos de las recetas de ejemplo
desde **Wikimedia Commons** (`upload.wikimedia.org`, `commons.wikimedia.org`).
Es una petición normal de imagen: se envía la dirección de la foto y tu
dirección IP, como al abrir cualquier página web. No se envía nada tuyo.

### 2. Buscar recetas en internet — cuando tú buscas

Si usas el buscador de recetas de fuera, **el texto que escribes se envía a los
sitios de cocina** que se consultan (recetasgratis.net, pequerecetas.com,
cookpad.com, recetasderechupete.com, comedera.com, cocina-familiar.com,
lacocinadefrabisa.lavozdegalicia.es, thermorecetas.com, mycookrecetas.com,
cocinaconpoco.com y laroussecocina.mx). Cada uno aplica su propia política de
privacidad.

### 3. Importar una receta por URL — cuando tú la pegas

La app descarga la página que le indiques, para leer la receta. Se envía esa
dirección al sitio correspondiente, y nada más.

### 4. Funciones con IA — solo si tú las activas

La capa de inteligencia artificial es **opcional** y está apagada mientras no
hagas nada. Hay tres vías, y en las tres el destinatario es Google:

- **Receta desde un vídeo de YouTube.** Requiere que hayas puesto tu propia
  clave de la API de Gemini. Se envía la dirección del vídeo a
  `generativelanguage.googleapis.com` y, antes, a `youtube.com` para comprobar
  que el vídeo existe.
- **Receta desde una foto, usando la app de Gemini.** La foto que hagas se
  comparte con la app de Gemini que tengas instalada, mediante el selector de
  Android. A partir de ahí la trata Google conforme a las condiciones de esa
  app, no las nuestras.
- **Comprobar tu clave.** Envía una frase fija de prueba, sin ningún dato tuyo.

> **Importante.** Con una clave del plan gratuito de Gemini, **Google puede usar
> lo que envíes para entrenar sus modelos.** La app te lo advierte en la propia
> pantalla antes de que introduzcas la clave. No envíes nada que no quieras que
> salga de tu móvil.
>
> Lo que hagas con tu clave se rige por la
> [Política de privacidad de Google](https://policies.google.com/privacy) y por
> las condiciones de la API de Gemini. Nosotros no vemos ni intermediamos esas
> peticiones: salen de tu móvil a Google directamente.

### 5. El asistente de voz — solo si lo usas

Cuando hablas al modo cocción, **el reconocimiento de voz lo hace Android, no
Fogón**. Según cómo tengas configurado tu móvil, ese reconocimiento puede
procesarse en el propio dispositivo o enviarse a Google. Fogón recibe únicamente
el texto ya transcrito, y no lo guarda ni lo envía a ningún sitio.

Puedes desactivar el asistente por completo en **Ajustes → Asistente de voz**.
Con él apagado, la app no pide el micrófono ni lo usa.

## Permisos que pide la app

- **Internet**: para descargar fotos, importar recetas y, si la activas, la
  capa de IA.
- **Micrófono**: solo para el asistente de voz durante la cocción. Android te lo
  pide la primera vez que pulsas el micrófono, no al instalar. Es opcional: la
  app funciona entera sin concederlo.

La app **no** pide acceso a la cámara ni a tu galería. Cuando haces una foto o
eliges una imagen, se usan el selector y la cámara del propio Android, que solo
nos entregan la imagen concreta que tú elijas.

## Copias de seguridad

Si tienes activada la copia de seguridad de Android, **tus recetas** (`fogon.db`)
se incluyen en ella y se guardan en tu Google Drive, bajo tu propia cuenta y
sujetas a las condiciones de Google.

**Tu clave de Gemini queda excluida de las copias de seguridad** de forma
deliberada: no se copia ni a Drive ni al transferir el móvil.

## Menores

Fogón no está dirigida a menores de 13 años y no recoge datos de nadie, con
independencia de su edad.

## Tus derechos

Como no recogemos ni conservamos datos personales, no tenemos nada tuyo que
mostrarte, rectificar o borrar. Todos tus datos están en tu dispositivo y bajo
tu control: puedes consultarlos, modificarlos o eliminarlos desde la propia app,
o borrarlos todos desinstalándola.

Sobre los datos que puedan tratar Google, Wikimedia o los sitios de cocina como
consecuencia de las funciones descritas arriba, debes dirigirte a cada uno de
ellos.

## Cambios en esta política

Si la app pasa a hacer algo distinto con la información, actualizaremos esta
página y cambiaremos la fecha de arriba antes de publicar esa versión.

## Contacto

**chiwire.dev.contact@gmail.com**

Escríbenos para cualquier duda sobre privacidad, o para reportar una receta
generada por IA que sea ofensiva, falsa o peligrosa. También puedes hacerlo
desde la app, en **Ajustes → Legal → Reportar una receta de la IA**.
