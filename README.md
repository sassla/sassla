![SASSLA](https://github.com/sassla/sassla/blob/main/sassla_web_logo.png)
# SASSLA: Plataforma de monitoreo sísmico
### Monitorea la actividad sísmica en México y entérate cuando se activa la Alerta Sísmica oficial.

![SASSLA](https://github.com/sassla/sassla/blob/main/sassla_header.jpeg)

[![SASSLA en Twitter](https://img.shields.io/twitter/follow/SafeLiveAlert?style=social)](https://twitter.com/SafeLiveAlert)
[![Alertas SASSLA en Twitter](https://img.shields.io/twitter/follow/SafeLiveAlerter?style=social)](https://twitter.com/SafeLiveAlerter)
[![Creador de SASSLA en Twitter](https://img.shields.io/twitter/follow/ClasicalRaptor?style=social)](https://twitter.com/ClasicalRaptor)
[![SASSLA en YouTube](https://img.shields.io/youtube/channel/subscribers/UC49UkokxDbkf64NPbjfh_0Q?style=social)](https://youtube.com/UC49UkokxDbkf64NPbjfh_0Q?sub_confirmation=1)

SASSLA es un proyecto de iniciativa privada orientado a la Protrección Civil en México. Ofrecemos en un sólo lugar la información oficial emitida por las autoridades competentes en el ámbito sísmico y volcánico.

## Objetivo:
México posee el mejor Sistema de Alerta Temprana para Terremotos de todo el mundo, el [**Sistema de Alerta Sísmica Mexicano (SASMEX)**](http://www.cires.org.mx/sasmex_n.php).

Nuestro objetivo es llevar la señal oficial a la mayor cantidad de personas posible a través de medios confiables y así promover la cultura de prevención y proteger a los ciudadanos del riesgo sísmico al que se enfrenta México.

## Logros:
Hoy [**SASSLA App**](https://www.sassla.mx/sasslaapp) es la única que permite entregar alertas tempranas de forma crítica, simultánea y sin retrasos, gracias a la [tecnología dedicada](https://www.sassla.mx/sasslaapp) a la recepción de la Alerta Sísmica de México que hemos desarrollado a lo largo de 8 años.

[Conoce la historia completa de SASSLA y sus desarrollos.](https://www.sassla.mx/nosotros)

## Alertas en Tiempo Real:
### Redes sociales
Nuestras cuentas publican automáticamente al momento de un sismo. Te indican:

- Posible epicentro
- Pronóstico de intensidad en cada localidad
- Tiempo Estimado de Llegada
- Avance del sismo en tiempo real

![SASSLA en redes sociales](https://github.com/sassla/sassla/blob/main/sassla_social.png)

- Twitter: [*@SafeLiveAlert*](https://twitter.com/SafeLiveAlert)
- Telegram: [*@SASSLA*](https://t.me/sassla)

### SASSLA App
Para uso personal. La app de monitoreo sísmico más confiable de México.
Recibe alertas en tu celular hasta 120 segundos antes de un sismo fuerte, sin retrasos y de forma crítica.

![SASSLA App](https://github.com/sassla/sassla/blob/main/sassla_app.png)

SASSLA App está disponible en iOS y Android. Es compatible con celulares y tablets Android, iPhone, iPod Touch, iPad y Apple Watch.
Requiere iOS 15.0 y Android 5.0 o superior.

Descárgala gratis aquí:

- [**iOS**](https://apps.apple.com/mx/app/sassla-sismos-en-tiempo-real/id1454877768)
- [**Android**](https://play.google.com/store/apps/details?id=com.safelivealert.earthquake)

Estadísticas:

- Más de 1.5 millones de descargas.
- La mejor según los usuarios: 4.7/5.0 de calificación en tiendas.
- Más de mil sismos registrados en SASSLA.

## Soluciones en Alertamiento Temprano:
SASSLA utiliza infraestructura y tecnología dedicada para la difusión masiva de la Alerta Sísmica oficial de México a través de internet.

### Sistema de Alerta Pública Masiva (SAP)
En SASSLA desarrollamos tecnología única en el mundo para transmitir alertas de emergencia vía internet, con infraestructura dedicada y ultra baja latencia.

Esta plataforma es ideal para advertir amenazas que requieren de acción rápida, como los terremotos, ya que es capaz de enviar millones de mensajes en poco más de 500 ms (milisegundos), con la posibilidad de escalar rápidamente su potencia si se requiere.

Además, es posible regionalizar la transmisión a zonas específicas, ya sea a escala local, regional o nacional. También, la plataforma tiene la capacidad de enviar un mensaje distinto a cada localidad en la misma transmisión.

Ésta es una solución robusta, confiable y totalmente personalizable para la advertencia de desastres y crisis a través de apps móviles y dispositivos IoT.


### Protocolo de Alertamiento Crítico (PAC)
El Protocolo de Alertamiento Crítico (PAC) de SASSLA consiste en una serie de acciones que ejecuta el teléfono celular, las cuales permiten advertir de forma crítica al usuario cuando se recibe un mensaje de emergencia. Iniciamos el desarrollo del PAC a inicios de 2018.

El PAC se ejecuta en el celular de cada usuario y funge como receptor / decodificador de los mensajes emitidos por el Sistema de Alerta Pública Masiva (SAP).
A diferencia de una notificación push normal, cuando el PAC recibe un mensaje de alerta sísmica, puede utilizar de forma exclusiva recursos reservados del sistema de cada teléfono (iOS y Android) detallados a continuación:


- INTERRUPCIÓN DE CUALQUIER ACTIVIDAD, AVISO Y/O ALERTA VIGENTE:
El PAC interrumpe cualquier aplicación en primer plano (apps, videos, juegos, música, etc.) para mostrar un rectángulo color rojo a pantalla completa con la información del sismo detectado. En caso que el teléfono celular se encuentre bloqueado o en reposo, el PAC tiene la capacidad de encender la pantalla.


- BRILLO MÁXIMO EN PANTALLA:
La pantalla roja con la información del evento se ilumina con el brillo máximo que permita el dispositivo móvil, con el fin de facilitar la lectura en situaciones donde hay mucha luz ambiental.


- SONIDO DE ALERTA A MÁXIMO VOLUMEN:
El PAC puede controlar el audio y volumen del teléfono celular. Cuando se recibe una alerta sísmica se interrumpe cualquier sonido en progreso, ya sea de música, video, llamada, juego, sonido de notificaciones, etc.

    Posteriormente, el volumen se establece al máximo nivel y se habilitan todas las bocinas disponibles (algunos celulares tienen 2 bocinas) para reproducir el sonido de alerta durante 60 segundos.

    Si el teléfono tiene activo el “Modo Silencio” y/o “Modo No Molestar”, el PAC puede ignorar la indicación y reproducir el sonido de alerta normalmente.

    Este protocolo utiliza un canal de audio de alta prioridad, es decir, el sonido de alerta sísmica no se interrumpirá bajo ningún motivo a menos que el usuario lo detenga manualmente, a diferencia de una notificación push tradicional.

    Si el usuario tiene audífonos en el momento de una alerta sísmica, el sonido se activará en el celular y en los auriculares simultáneamente. En el teléfono móvil siempre sonará a máximo volumen, en audífonos o altavoces externos se utilizará el nivel de volumen establecido por el usuario en ese momento.


- VIBRACIÓN INTERMITENTE:
El PAC encenderá el vibrador repetidamente con su máxima intensidad, para que el usuario pueda notar el mensaje de alerta incluso en situaciones en las que no es posible hacerlo de forma audiovisual.


- LUZ ESTROBOSCÓPICA:
Las luces led del teléfono celular se encenderán simulando una luz estroboscópica, con el fin de que el usuario note el aviso de alerta sísmica de forma visual.


## Servicios Adicionales:

### Alertas de Familia:
SASSLA también te permite recibir alertas cuando un sismo pueda afectar a la localidad de un ser querido.
En tiempo real y sin retrasos serás notificado cuando un sismo fuerte esté por impactar las zonas que elijas.

![Alertas de Familia](https://github.com/sassla/sassla/blob/main/sassla_family_alerts.png)

### SASSLA en tus Redes Sociales
Con el fin de promover la cultura de prevención en México, desarrollamos "SASSLA en tus Redes Sociales", función que permite conectar tus cuentas de Twitter y Telegram con nuestro sistema de alertas.

En caso de un sismo fuerte, SASSLA publicará en tiempo real y simultáneamente en todas las cuentas registradas. Este servicio es gratuito y se puede activar fácilmente.

![SASSLA en tus Redes Sociales](https://github.com/sassla/sassla/blob/main/sassla_tweet_services.png)

## Prensa:
SASSLA es reconocida en múltiples medios de comunicación (nacionales e internacionales) por su buen desempeño a lo largo de 8 años.

![SASSLA en los medios](https://github.com/sassla/sassla/blob/main/sassla_media.png)

## Contacto y soporte:
- Email: [app@sassla.mx](mailto:app@sassla.mx)
- WhatsApp: [+52 55 4447 1236](https://wa.me/message/YEKWA4Y2UCV4B1)
- Facebook: [@SafeLiveAlertMX](https://facebook.com/SafeLiveAlertMX)
- Twitter: [@SafeLiveAlert](https://twitter.com/SafeLiveAlert)
