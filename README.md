


Política de privacidad

– Reserve bot
Última actualización: 19/10/2025

1. La aplicación está diseñada para ayudar a las personas en su vida privada o laboral a programar automáticamente citas mediante mensajes de mensajería recibidos en aplicaciones de mensajes (por ejemplo WhatsApp, Telegram, etc.). 
La aplicación Reserve bot escucha las notificaciones del sistema, recibidas en el dispositivo del usuario. Primero, el usuario elije las aplicaciones de mensajería que debe responder el bot, el bot interactuará con estos contactos a través de una secuencia de preguntas predeterminadas, y según las respuestas recibidas, el bot recogerá los datos necesarios para fijar una cita, como el nombre, la fecha y la hora guardándolos en una base de datos local (SQLite). Todos los datos procesados por la aplicación permanecen exclusivamente en el dispositivo del usuario

2. Informamos que la aplicación Reserve bot ha sido diseñada de tal manera que técnicamente no puede conectarse al exterior para enviar datos. Por lo tanto, la aplicación no recoge, transmite, o comparte datos personales y cualquier tipo de datos a terceros o servidores externos. Todos los datos permanecen exclusivamente en el dispositivo del usuario, en la base de datos local (SQLite) y no son compartidos por nosotros de ninguna manera. Esto garantiza la máxima privacidad para el usuario y sus contactos. Por otra parte, el acceso a los datos (almacenados en la base de datos local) sólo es posible por el usuario, que interactúa con la interfaz de usuaria de nuestra aplicación con un botón (por ejemplo, «lista de reservas») puede decidir por iniciativa propia si compartir con otras aplicaciones la información recogida por el bot. Actualmente no se aplica cifrado a nivel de base de datos, pero los datos están protegidos por los mecanismos de seguridad del sistema operativo Android. Alentamos a los usuarios a proteger el acceso físico al dispositivo (por ejemplo, PIN, huella dactilares, contraseña). "
a) Contactos del dispositivos: la aplicación puede acceder a los contactos del dispositivo únicamente con el permiso explícito del usuario. El propósito es permitir al usuario seleccionar los contactos con los que el bot puede interactuar. Los contactos se leen sólo localmente. No son enviados, salvados o procesados por nosotros en servidores externos. 
b) Notificaciones: La aplicación utiliza un servicio de escucha de notificación para leer mensajes entrantes de aplicaciones de mensajería. Esto es necesario para activar las respuestas automáticas del bot. La aplicación lee el contenido de notificación únicamente para el tratamiento inmediato, y no almacena el historial del chat. No se transmiten ni guardan datos, ni contenido de notificaciones en servidores externos. 
c) Datos introducidos en la base de datos local y los propios datos del usuario: Sus datos personales, como los datos de contacto del usuario que se almacenan en la base de datos local (SQLite) en su dispositivo, no son enviados, almacenados o procesados por nosotros en servidores externos. 


3. Permisos requeridos para funcionar correctamente, la aplicación requiere los siguientes permisos Android:
 
FOREGROUND_SERVICE:
Mantiene activo un servicio esencial para el funcionamiento continuo de la aplicación.
Esto garantiza que la aplicación pueda escuchar y responder de forma persistente, incluso cuando no se utiliza activamente.
Muestra una notificación persistente para informar al usuario de que la aplicación está activa en primer plano.

FOREGROUND_SERVICE_DATA_SYNC : Interactuar con la base de datos interna (SQLite) y con los contactos localmente, incluso cuando la aplicación está en Background.


POST_NOTIFICATIONS : 
POST_NOTIFICATIONS , es un permiso que debe ser otorgado personalmente por el usuario para permitir que la aplicación “Reserve bot” pueda mostrar una notificación.
Necesaria para usar los permisos BIND_NOTIFICATION_LISTENER_SERVICE y FOREGROUND_SERVICE. 



WAKE_LOCK : Para evitar que el dispositivo se duerma mientras procesa mensajes.
 REQUEST_IGNORE_BATTERY_OPTIMIZATIONS: 
Para garantizar un funcionamiento fiable incluso con optimizaciones de batería activa. 

INTERNET : Necesario para el motor Flutter, y aunque la aplicación tiene permiso para conectarse a Internet, toda la funcionalidad del bot y la gestión de los datos dentro de la aplicación no utilizan Internet, de hecho, datos personales y todos los demás datos nunca se envían fuera. 

READ_CONTACT:
La aplicación requiere permiso de acceso para leer los contactos con el único propósito de permitir al usuario de seleccionar con qué números de teléfono puede interactuar el bot. Los datos de contacto no son almacenados por nosotros en servidores externos o compartidos de ninguna manera. 

RECIBIVE_BOOT_COMPLETED : 
Para reactivar el bot cuando el teléfono comienza, si el usuario ha elegido activación automática. 


BIND_NOTIFICATION_LISTENER_SERVICE: Este permiso es esencial para el funcionamiento de la aplicación. Nos permite leer mensajes entrantes y iniciar el proceso de reserva automática. Debe ser activado manualmente por el usuario. Mantiene un servicio esencial para el funcionamiento continuo de la aplicación, para garantizar que la aplicación pueda realizar su labor de escucha y respuesta de forma fiable, incluso cuando no lo utilice activamente. Mostrar una notificación permanente para informar al usuario de que la aplicación está activa en primer plano.






 4. Seguridad de datos locales:
No se guardan datos en servidores externos o en la nube. la aplicación guarda exclusivamente datos localmente utilizando una base de datos SQLite. La App utiliza las medidas de seguridad estándar del sistema operativo Android para proteger los datos almacenados localmente contra el acceso no autorizado. Sin embargo, es responsabilidad del usuario proteger físicamente su dispositivo (contraseña, bloqueo de pantalla, etc.).

 5. Derechos y Supresión de datos: Usted puede desactivar el acceso a los permisos en cualquier momento a través de la configuración de su dispositivo. El usuario tiene el control completo de los datos guardados de la aplicación en la base de datos local de dispositivos. El usuario puede gestionar, editar o borrar estos datos  directamente de la interfaz de la App Reserve bot, o puede hacerlo desde la configuración de su dispositivo simplemente desinstalando la aplicación.

 

6. Afiliaciones: Esta aplicación (Reserve bot) es un producto independiente y no está afiliado de ninguna manera, apoyado o patrocinado por WhatsApp, Telegram, Facebook Messenger o cualquier otra aplicación de mensajería y no requiere acceso interno a API oficiales. Los nombres mencionados sirven sólo como referencia técnica al usuario. 

7. Cambios a esta Política de Privacidad: 
Nos reservamos el derecho de actualizar nuestra Política de Privacidad de vez en cuando. Cualquier cambio en esta política se comunicará mediante actualizaciones de la aplicación. Le animamos a revisar esta Política de Privacidad cada vez que haya una actualización de  nuestra aplicación. El uso continuo de la aplicación Reserve bot implica la aceptación de cambios. 

8. Contactos: Si tiene alguna pregunta o sugerencia sobre nuestra Política de Privacidad, no dude en ponerse en contacto con nosotros:  Correo electrónico:  autoreservebot@gmail.com




