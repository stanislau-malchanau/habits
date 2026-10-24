---
title: Política de privacidad de Habit Tracker
lang: es
---

# Política de privacidad de Habit Tracker: Game & Friends

*Esta es una traducción. Si difiere de la [versión en inglés](../privacy), prevalece la versión en inglés.*

Fecha de entrada en vigor: 2026-10-23

Esta política explica cómo Habit Tracker: Game & Friends (que aparece como «Hábitos» en su pantalla de inicio, la «App»), creada por Stanislau Malchanau («nosotros»), trata su información. En resumen: **no recopilamos, vendemos ni compartimos sus datos personales. Sus hábitos permanecen en su dispositivo y en su propia cuenta de iCloud.**

## 1. Datos que almacena la App

La App almacena lo siguiente en su dispositivo: sus hábitos (nombre, icono, color, tipo, calendario, objetivo y horas de los recordatorios), sus marcas de cada día, las pausas y los días de descanso, su pueblo (en qué parcela está la casita de cada hábito y cuánto ha crecido) y su configuración. Su Apple Watch guarda una copia de los mismos datos para mostrar y marcar sus hábitos.

No operamos servidores que reciban estos datos y no tenemos acceso a ellos. Las excepciones son los horarios de una actividad en vivo en curso (sección 5) y las señales de uso anónimas (sección 8).

## 2. Sincronización con iCloud

Si ha iniciado sesión en iCloud, la App sincroniza sus datos a través de CloudKit de Apple, en la base de datos privada de su propia cuenta de iCloud, para que su iPhone, su iPad y su Apple Watch muestren los mismos hábitos. Apple almacena y protege estos datos conforme a la Política de privacidad de Apple (https://www.apple.com/legal/privacy/). No podemos verlos, leerlos ni exportarlos. Puede desactivar la sincronización en iOS, en Configuración > [su nombre] > iCloud.

## 3. Hábitos compartidos con amigos

Puede invitar a amigos a un hábito compartido. Un hábito compartido se guarda en una zona compartida de su cuenta de iCloud mediante la función para compartir de CloudKit de Apple. Las personas que usted invita, y solo ellas, ven el nombre, el icono, el calendario y las marcas de ese hábito, así como el nombre que cada participante tiene en iCloud. Sus demás hábitos nunca se comparten. Cada participante puede salir de un hábito compartido en cualquier momento, y su propietario puede quitar a un participante o dejar de compartirlo; a partir de entonces, sus copias dejan de actualizarse. No podemos ver los hábitos compartidos ni quién participa en ellos.

## 4. Movimiento de los audífonos y sonido espacial

Con AirPods u otros audífonos compatibles, la App puede usar el movimiento de su cabeza para que los sonidos del pueblo se mantengan en su lugar cuando usted se gira. Estos datos de movimiento se procesan en su dispositivo en tiempo real, nunca se almacenan y nunca salen de su dispositivo.

## 5. Notificaciones, actividad en vivo y widgets

Los recordatorios, el resumen matutino y el recordatorio previo al fin de una prueba gratuita se crean en su dispositivo. Los widgets y las complicaciones del Apple Watch leen sus hábitos en su dispositivo.

La App puede mostrar una actividad en vivo de su rutina de la mañana en la pantalla bloqueada y en la Dynamic Island. Para que pueda empezar a la hora de la rutina y siga avanzando mientras la App está inactiva, la App envía a nuestro pequeño servidor de retransmisión los tokens de notificaciones push que Apple le asigna para las actividades en vivo (uno para iniciar la actividad en vivo de la rutina y otro para la actividad en vivo en curso) y el calendario: las horas, identificadores aleatorios de los hábitos que la forman y sus números (cuántos están hechos, un contador y su objetivo). No se envía ningún nombre de hábito, texto que usted haya escrito, nombre, correo electrónico ni identificador de cuenta o de dispositivo. En cada momento del calendario, el servidor pide al servicio de notificaciones push de Apple que inicie o actualice la actividad en vivo, y elimina lo que guarda en cuanto se envía la notificación programada o termina la actividad en vivo. El servidor funciona en Cloudflare Workers; como cualquier servicio de internet, Cloudflare ve la dirección IP de la solicitud mientras la entrega, y nosotros no la almacenamos. Si desactiva las actividades en vivo para la App en iOS, en Configuración, no se envía nada.

## 6. Game Center

Si ha iniciado sesión en Game Center, sus logros se envían a Game Center de Apple y se tratan conforme a la Política de privacidad de Apple. No recibimos su identidad de Game Center.

## 7. Compras

Apple vende y procesa las suscripciones a través del App Store. No recibimos sus datos de pago. Apple solo informa a la App si su suscripción está activa.

## 8. Análisis de uso e informes de fallos

Para saber qué funciones son útiles y dónde la App le estorba, la App envía señales de uso anónimas a TelemetryDeck, un servicio de análisis de TelemetryDeck GmbH (Augsburgo, Alemania) con servidores en la UE. Una señal indica una acción en la App: por ejemplo, que se completó un paso del primer inicio, que se mostró la pantalla de suscripción o se inició una suscripción, que la App pidió una valoración o que falló la sincronización con iCloud. Va acompañada de una marca de tiempo redondeada a la hora y de datos técnicos generales: las versiones de la App y de iOS, el modelo del dispositivo, el idioma, la región y la zona horaria, y la configuración de pantalla y de accesibilidad, como el modo oscuro o el tamaño del texto.

Una señal nunca contiene los nombres de sus hábitos ni ningún otro texto que usted escriba, ni tampoco su nombre, su correo electrónico, su Cuenta de Apple, sus amigos o su ubicación. Su instalación se identifica únicamente mediante un identificador aleatorio al que la App aplica un hash con sal antes de enviarlo, de modo que las señales no pueden vincularse con usted ni seguirse entre apps. TelemetryDeck no almacena direcciones IP ni usa cookies. Solo examinamos estas señales como estadísticas para mejorar la App; no las vendemos, no las compartimos con anunciantes ni las usamos para rastrear su actividad. La App no contiene código de publicidad ni de rastreo, y no rastrea su actividad en otras apps o sitios web.

Aparte de esto, si decide compartir análisis con los desarrolladores de apps en iOS, en Configuración > Privacidad y seguridad > Análisis y mejoras, Apple puede proporcionarnos estadísticas de uso agregadas y anónimas, así como informes de fallos. Estos datos no permiten conocer su identidad.

## 9. Lo que la App no usa

La App no solicita su ubicación, sus contactos, sus fotos, la cámara, el micrófono ni sus datos de salud. El día y la noche del pueblo siguen el reloj y la zona horaria de su teléfono.

## 10. Niños

La App es apta para todas las edades y no recopila a sabiendas información personal de nadie, incluidos los niños menores de 13 años (o de la edad equivalente en su país).

## 11. Conservación y eliminación de datos

Los datos se conservan mientras usted los mantenga. Puede eliminar en cualquier momento un hábito y sus marcas en la App, y todo eliminando la App y, en el caso de los datos sincronizados, en iOS, en Configuración > [su nombre] > iCloud > Administrar almacenamiento de la cuenta > Hábitos. Como no conservamos ninguna copia, no tenemos nada más que eliminar. El servidor de retransmisión conserva los tokens y el calendario de una actividad en vivo solo hasta que se envía la notificación programada o termina esa actividad en vivo. Las señales de uso son anónimas y no pueden vincularse con usted, por lo que no existe ningún registro personal de ellas que consultar o eliminar.

## 12. Sus derechos

Según el lugar donde viva (por ejemplo, en virtud del GDPR en la UE, el UK GDPR, la CCPA/CPRA en California, la APPI en Japón, la PIPA en Corea o la LGPD en Brasil), es posible que tenga derecho a acceder a sus datos personales, rectificarlos, suprimirlos o solicitar su portabilidad, así como a oponerse a su tratamiento o a limitarlo. Como no conservamos sus datos, puede ejercer estos derechos directamente en su dispositivo y en iCloud, como se describe arriba. También puede contactarnos con cualquier solicitud o pregunta, y puede presentar una reclamación ante su autoridad local de protección de datos.

No vendemos ni compartimos información personal en el sentido definido por la CCPA/CPRA.

## 13. Cambios

Si esta política cambia, actualizaremos la fecha de entrada en vigor indicada arriba y, en caso de cambios sustanciales, se lo comunicaremos en la App.

## 14. Contacto

Stanislau Malchanau, Belarús
Correo electrónico: 7tam.official@gmail.com
