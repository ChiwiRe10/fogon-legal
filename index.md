---
layout: default
title: Politica de privacidad de Fogon
---

# Política de privacidad de Fogón

**Última actualización: 17 de agosto de 2026**

Fogón es un recetario que funciona en tu móvil. No tiene cuentas, no tiene
servidor propio y no lleva analítica. Se mantiene con publicidad de Google
AdMob, que es lo único que trata datos de tu dispositivo y tiene su propia
sección más abajo.

Esta política describe exactamente lo que hace la app. Si algo de aquí no
coincide con lo que ves, escríbenos: es un error y queremos corregirlo.

## Quién responde de esta app

Fogón la desarrolla y publica **ChiwiRe**, desarrollador independiente radicado
en **Venezuela**. Contacto: **chiwire.dev.contact@gmail.com**.

La app no dispone de servidores propios y nada de lo que hagas en ella nos
llega. El único proveedor implicado en un tratamiento de datos es **Google**,
como proveedor de publicidad (AdMob), descrito en «Publicidad». Los demás
terceros que se nombran en esta política —Wikimedia, los sitios de cocina, la
API de Gemini y **la app de Gemini que tengas instalada**— reciben datos solo
cuando tú usas la función correspondiente, y tratan lo que reciben bajo sus
propias condiciones.

## Resumen

- **Nosotros no recogemos ningún dato tuyo.** No hay registro, no hay cuenta y
  no hay servidor nuestro: no tenemos dónde guardar nada.
- **Tus recetas viven en tu móvil.**
- **La app muestra anuncios**, servidos por Google AdMob. Ese sistema sí recoge
  datos —entre ellos el identificador de publicidad de tu móvil— y se explica
  entero en su propia sección más abajo.
- **No hay analítica**: la app no incluye ningún SDK de medición de uso ni de
  atribución, aparte de lo que necesita el propio sistema de anuncios.
- Algunas funciones que tú eliges usar envían información **a terceros**. Están
  todas listadas abajo, una por una.

## Qué se guarda en tu móvil

Todo esto se queda en el dispositivo y solo lo puede leer Fogón:

| Qué | Dónde |
|---|---|
| Tus recetas, categorías, favoritas y la papelera | Base de datos local `fogon.db` |
| Tu despensa, la lista de la compra y lo que se te ha acabado | La misma base de datos |
| Los temporizadores puestos, para que sigan contando si cierras la app | La misma base de datos |
| Tus preferencias: tema, ajustes de voz | La misma base de datos |
| Las fotos de portada que descargas o eliges, y la última foto que mandas a la app de Gemini mientras esperas su respuesta | Ficheros en el almacenamiento privado de la app |
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
hagas nada. En todas las vías el destinatario es Google, pero por **dos caminos
distintos** que conviene no confundir.

**A. Con tu propia clave de la API de Gemini**, si decides ponerla. Las
peticiones salen de tu móvil a `generativelanguage.googleapis.com` y no pasan
por nosotros.

- **Receta desde un vídeo de YouTube.** Se envía la dirección del vídeo y,
  antes, se consulta `youtube.com` para comprobar que el vídeo existe.
- **Comprobar tu clave.** Envía una frase fija de prueba, sin ningún dato tuyo.

**B. Con la app de Gemini que tengas instalada**, que no gasta tu clave ni la
necesita. En estos casos Fogón **comparte** el contenido con esa app mediante
el selector de Android —tú eliges a qué app va— y su respuesta vuelve pegada.
A partir del momento en que compartes, lo que hayas mandado lo trata Google
conforme a las condiciones de **esa app**, no las nuestras.

- **Receta desde una foto.** Se comparte la foto que hagas.
- **Apuntar la despensa con una foto.** Igual: se comparte la foto de la compra
  o de la nevera para que te diga qué hay y cuánto.
- **Preguntar una duda mientras cocinas.** Aquí, además de tu pregunta, **se
  comparte la receta entera** —título, ingredientes y pasos, con las cantidades
  tal y como las tengas en pantalla—, porque sin ella la respuesta no sirve. Si
  esa receta es tuya y no quieres que salga del móvil, no uses esta función.

En las dos que llevan foto, se hace con la **cámara del sistema** y se guarda en
el almacenamiento privado de la app mientras esperas la respuesta; la copia
temporal que deja el selector se borra en cuanto se ha leído. El texto de la
instrucción que acompaña a la foto se copia además **al portapapeles**, porque
la app de Gemini descarta el texto cuando recibe una imagen y hay que pegarlo a
mano; es un texto fijo, sin nada tuyo dentro.

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

### 6. Compartir una receta — cuando tú la compartes

Al compartir una receta, Fogón entrega el texto —o la imagen que genera con
él— a la app que tú elijas en el selector de Android: mensajería, correo, notas.
Va donde tú digas, y desde ahí se rige por las condiciones de esa app.

## Publicidad

Fogón es gratis y se mantiene con publicidad. Los anuncios los sirve **Google
AdMob**, y aparecen en dos momentos: al abrir la app y al terminar de importar
una receta. Nunca más de uno cada cinco minutos, y nunca mientras cocinas.

**Qué implica.** Para servir esos anuncios, Google recibe y trata datos de tu
dispositivo. Entre ellos:

- El **identificador de publicidad de Android**, un número que tu móvil asigna
  a las apps y que **puedes borrar o restringir** en cualquier momento desde
  *Ajustes de Android → Google → Anuncios*.
- Dirección IP, modelo de dispositivo, versión del sistema e idioma.
- Interacciones con el anuncio: si se muestra, si se cierra, si se pulsa.

Nosotros **no vemos esos datos**: no nos llegan ni pasan por ningún servidor
nuestro. Solo recibimos de Google un informe agregado de cuántos anuncios se
mostraron y cuánto se ha ganado, sin nada que identifique a nadie.

El tratamiento que hace Google se rige por su
[política de privacidad](https://policies.google.com/privacy) y por
[cómo usa Google los datos de las apps que utilizan sus servicios](https://policies.google.com/technologies/partner-sites).

**Tu consentimiento.** Si estás en el Espacio Económico Europeo, Reino Unido o
Suiza, la primera vez que abres la app te preguntamos si aceptas el uso de tus
datos para publicidad personalizada, mediante el sistema de consentimiento
oficial de Google. **Si no aceptas, la app funciona igual**: verás anuncios no
personalizados o ninguno, según lo que elijas. Puedes cambiar de opinión cuando
quieras en **Ajustes → Legal → «Privacidad de los anuncios»**, que vuelve a
abrir ese mismo formulario. Esa entrada solo aparece donde Google la exige, que
es donde hay algo que decidir.

Fuera de esos países no se muestra ese aviso, porque su normativa no lo exige.

## Permisos que pide la app

- **Internet**: para descargar fotos, importar recetas y, si la activas, la
  capa de IA.
- **Micrófono**: solo para el asistente de voz durante la cocción. Android te lo
  pide la primera vez que pulsas el micrófono, no al instalar. Es opcional: la
  app funciona entera sin concederlo.
- **Notificaciones**: para avisarte cuando se acaba un temporizador. Se pide la
  primera vez que pones uno. Sin él, el aviso solo se ve con la app abierta.
- **Alarmas exactas**: para que ese aviso suene **a su hora** aunque el móvil
  esté en reposo. Sin él, Android puede retrasarlo unos minutos, y la app te lo
  dice en vez de prometer una precisión que no tiene.

Los temporizadores son cuenta y aviso **dentro de tu móvil**: no salen de él, no
se envían a ningún sitio y no hacen falta ni conexión ni cuenta.

La app **no** pide acceso a la cámara ni a tu galería. Cuando haces una foto o
eliges una imagen, se usan el selector y la cámara del propio Android, que solo
nos entregan la imagen concreta que tú elijas.

## Copias de seguridad

Si tienes activada la copia de seguridad de Android, la base de datos
(`fogon.db`) se incluye en ella y se guarda en tu Google Drive, bajo tu propia
cuenta y sujeta a las condiciones de Google. Ahí va todo lo de la tabla de
arriba que vive en esa base: tus recetas, la despensa, la lista de la compra y
tus preferencias.

**Tu clave de Gemini queda excluida de las copias de seguridad** de forma
deliberada: no se copia ni a Drive ni al transferir el móvil.

## Menores

Fogón no está dirigida a menores de 13 años. Nosotros no recogemos datos de
nadie, con independencia de su edad; el sistema de anuncios sí trata los datos
descritos en «Publicidad», y por eso la app se declara para público general y
no para menores.

## Tus derechos

Como nosotros no recogemos ni conservamos datos personales, no tenemos nada
tuyo que mostrarte, rectificar o borrar. Todos tus datos están en tu
dispositivo y bajo tu control: puedes consultarlos, modificarlos o eliminarlos
desde la propia app, o borrarlos todos desinstalándola.

Sobre los datos que trate **Google como proveedor de publicidad**, tienes tres
vías, todas efectivas sin pasar por nosotros:

- Cambiar o retirar tu consentimiento en **Ajustes → Legal → «Privacidad de los
  anuncios»**.
- Borrar o restringir el identificador de publicidad en *Ajustes de Android →
  Google → Anuncios*.
- Ejercer tus derechos ante Google directamente, con los medios que indica su
  política de privacidad.

Sobre los datos que puedan tratar Wikimedia o los sitios de cocina como
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
