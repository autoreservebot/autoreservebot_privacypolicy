


# Privacy Policy 

[🇪🇸 Español](#español) | [🇮🇹 Italiano](#italiano)

---

## Español
– Reserve bot
Última actualización: 24/03/2026

1. La aplicación está diseñada para ayudar a las personas en su vida privada o laboral a programar automáticamente citas mediante mensajes de mensajería recibidos en aplicaciones de mensajes (por ejemplo WhatsApp, Facebook, Instagram, etc.). La aplicación Reserve bot escucha las notificaciones del sistema, recibidas en el dispositivo del usuario. Primero, el usuario elije las aplicaciones de mensajería que debe responder el bot, el bot interactuará con estos contactos a través de una secuencia de preguntas predeterminadas, y según las respuestas recibidas, el bot recogerá los datos necesarios para fijar una cita, como el nombre, la fecha y la hora guardándolos en una base de datos local (SQLite). Todos los datos procesados por la aplicación permanecen exclusivamente en el dispositivo del usuario

2. Informamos que la aplicación Reserve bot ha sido diseñada de tal manera que técnicamente no puede conectarse al exterior para enviar datos. Por lo tanto, la aplicación no recoge, transmite, o comparte datos personales y cualquier tipo de datos a terceros o servidores externos. Todos los datos personales y de mensajería permanecen exclusivamente en el dispositivo del usuario, en la base de datos local (SQLite) y no son compartidos por nosotros de ninguna manera.Sin embargo, la aplicación utiliza servicios de terceros (Google Firebase Crashlytics y Remote Config) exclusivamente para recopilar datos técnicos de diagnóstico (como registros de errores e información del dispositivo) para mejorar la estabilidad de la aplicación y gestionar actualizaciones. Estos datos técnicos son anónimos y no están vinculados a sus mensajes o contactos. Esto garantiza la máxima privacidad para el usuario y sus contactos. Por otra parte, el acceso a los datos (almacenados en la base de datos local) sólo es posible por el usuario, que interactúa con la interfaz de usuaria de nuestra aplicación con un botón (por ejemplo, «lista de reservas») puede decidir por iniciativa propia si compartir con otras aplicaciones la información recogida por el bot. Actualmente no se aplica cifrado a nivel de base de datos, pero los datos están protegidos por los mecanismos de seguridad del sistema operativo Android. Alentamos a los usuarios a proteger el acceso físico al dispositivo (por ejemplo, PIN, huella dactilares, contraseña). "
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

                                                                                                                 
INTERNET : Necesario para el motor Flutter, y para el uso de servicios técnicos de diagnóstico (Google Firebase). Aunque la aplicación tiene permiso para conectarse a Internet, toda la funcionalidad del app opera estrictamente de forma local y la gestión de los datos, dentro de la aplicación, no utilizan Internet, de hecho, los datos personales y todos los demás datos nunca se envían fuera. 

**Privacidad de los Niños**
Esta aplicación no está dirigida a menores de edad. Dado que la aplicación funciona de manera completamente local y no transmite datos personales a servidores externos, no recopilamos ni almacenamos información personal de ningún usuario, incluidos los menores. 

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


<br><br>

---

## Italiano

– Reserve Bot

Ultimo aggiornamento: 24/03/2026

1. L'applicazione è progettata per aiutare le persone, nella loro vita personale o professionale, a prenotare automaticamente appuntamenti tramite le app di messaggistica (ad esempio, WhatsApp, Facebook, Instagram ecc.).

L'applicazione Reserve Bot è in ascolto delle notifiche di sistema ricevute sul dispositivo dell'utente. Innanzitutto, l'utente sceglie le app di messaggistica a cui il bot deve rispondere. Il bot interagirà con questi contatti attraverso una sequenza di domande predefinite e, in base alle risposte ricevute, raccoglierà i dati necessari per programmare un appuntamento, come nome, data e ora, salvandoli in un database locale (SQLite). Tutti i dati elaborati dall'applicazione rimangono esclusivamente sul dispositivo dell'utente.

2. Si prega di notare che l'applicazione Reserve Bot è stata progettata in modo tale da non poter tecnicamente connettersi al mondo esterno per inviare dati. Pertanto, l'applicazione non raccoglie, trasmette o condivide dati personali o qualsiasi altro tipo di dato con terze parti o server esterni. Tutti i dati personali e di messaggistica rimangono esclusivamente sul dispositivo dell'utente, nel database locale (SQLite), e non vengono condivisi da noi in alcun modo. Tuttavia, l'applicazione utilizza servizi di terze parti (Google Firebase Crashlytics e Remote Config) esclusivamente per raccogliere dati diagnostici tecnici (come log degli errori e informazioni sul dispositivo) al fine di migliorare la stabilità dell'applicazione e gestire gli aggiornamenti. Questi dati tecnici sono anonimi e non sono collegati ai messaggi o ai contatti dell'utente. Ciò garantisce la massima privacy per l'utente e i suoi contatti. Inoltre, l'accesso ai dati (memorizzati nel database locale) è consentito solo all'utente che interagisce con l'interfaccia utente della nostra applicazione tramite un pulsante (ad esempio, "lista prenotazioni"). L'utente può decidere autonomamente se condividere le informazioni raccolte dal bot con altre applicazioni. Attualmente non viene applicata la crittografia a livello di database, ma i dati sono protetti dai meccanismi di sicurezza del sistema operativo Android. Incoraggiamo gli utenti a proteggere l'accesso fisico al dispositivo (ad esempio, PIN, impronta digitale, password).

a) Contatti del dispositivo: l'applicazione può accedere ai contatti del dispositivo solo con l'esplicito consenso dell'utente. Lo scopo è consentire all'utente di selezionare i contatti con cui il bot può interagire. I contatti vengono letti solo localmente. Non vengono inviati, salvati o elaborati da noi su server esterni.

b) Notifiche: l'applicazione utilizza un servizio di ascolto delle notifiche per leggere i messaggi in arrivo dalle applicazioni di messaggistica. Ciò è necessario per attivare le risposte automatiche del bot. L'applicazione legge il contenuto delle notifiche solo per l'elaborazione immediata e non memorizza la cronologia della chat. Nessun dato o contenuto delle notifiche viene trasmesso o salvato su server esterni.

c) Dati inseriti nel database locale e dati personali dell'utente: i dati personali dell'utente, come le informazioni di contatto memorizzate nel database locale (SQLite) sul dispositivo, non vengono inviati, memorizzati o elaborati da noi su server esterni.

3. Autorizzazioni necessarie per il corretto funzionamento: l'applicazione richiede le seguenti autorizzazioni Android:

FOREGROUND_SERVICE:
Attiva un servizio essenziale per il funzionamento continuo dell'applicazione.

Ciò garantisce che l'applicazione possa ascoltare e rispondere in modo continuativo, anche quando non viene utilizzata attivamente.

Visualizza una notifica persistente per informare l'utente che l'applicazione è attiva in primo piano.

FOREGROUND_SERVICE_DATA_SYNC: Interagisce con il database interno (SQLite) e i contatti localmente, anche quando l'applicazione è in background.

POST_NOTIFICATIONS: POST_NOTIFICATIONS è un'autorizzazione che deve essere concessa dall'utente per consentire all'applicazione "Reserve bot" di visualizzare una notifica.

Necessaria per utilizzare le autorizzazioni BIND_NOTIFICATION_LISTENER_SERVICE e FOREGROUND_SERVICE.

WAKE_LOCK: Impedisce al dispositivo di entrare in modalità sospensione durante l'elaborazione dei messaggi.

REQUEST_IGNORE_BATTERY_OPTIMIZATIONS: Garantisce un funzionamento affidabile anche con le ottimizzazioni della batteria attive.

INTERNET: Necessario per il motore Flutter e per l'utilizzo dei servizi di diagnostica tecnica (Google Firebase). Sebbene l'applicazione abbia l'autorizzazione a connettersi a Internet, tutte le funzionalità dell'app operano esclusivamente in locale e la gestione dei dati all'interno dell'applicazione non utilizza Internet. Infatti, i dati personali e tutti gli altri dati non vengono mai inviati all'esterno.

Privacy dei minori
Questa applicazione non è destinata ai minori. Poiché l'applicazione opera interamente in locale e non trasmette dati personali a server esterni, non raccogliamo né memorizziamo informazioni personali di alcun utente, inclusi i minori.

READ_CONTACT:
L'applicazione richiede l'autorizzazione di accesso per leggere i contatti al solo scopo di consentire all'utente di selezionare i numeri di telefono con cui il bot può interagire. I dati dei contatti non vengono da noi memorizzati su server esterni né condivisi in alcun modo.

RECEIVE_BOOT_COMPLETED:
Per riattivare il bot all'avvio del telefono, se l'utente ha scelto l'attivazione automatica.

BIND_NOTIFICATION_LISTENER_SERVICE: Questa autorizzazione è essenziale per il funzionamento dell'applicazione. Consente di leggere i messaggi in arrivo e avviare il processo di prenotazione automatica. Deve essere abilitato manualmente dall'utente. Mantiene un servizio essenziale per il funzionamento continuo dell'applicazione, garantendo che quest'ultima possa ascoltare e rispondere in modo affidabile, anche quando non viene utilizzata attivamente. Visualizza inoltre una notifica persistente per informare l'utente che l'applicazione è attiva in primo piano.

4. Sicurezza dei dati locali: Nessun dato viene memorizzato su server esterni o nel cloud. L'applicazione memorizza i dati esclusivamente localmente utilizzando un database SQLite. L'app utilizza le misure di sicurezza standard del sistema operativo Android per proteggere i dati memorizzati localmente da accessi non autorizzati. Tuttavia, è responsabilità dell'utente proteggere fisicamente il proprio dispositivo (password, blocco schermo, ecc.).

5. Diritti di accesso e cancellazione dei dati: È possibile disabilitare i permessi di accesso in qualsiasi momento tramite le impostazioni del dispositivo. L'utente ha il controllo completo sui dati salvati dall'applicazione nel database locale del dispositivo. L'utente può gestire, modificare o eliminare questi dati direttamente dall'interfaccia dell'app Reserve bot oppure può farlo dalle impostazioni del dispositivo semplicemente disinstallando l'applicazione.

6. Affiliazioni: Questa applicazione (Reserve bot) è un prodotto indipendente e non è affiliata, supportata o sponsorizzata da WhatsApp, Telegram, Facebook Messenger o qualsiasi altra applicazione di messaggistica, e non richiede l'accesso interno alle API ufficiali. I nomi menzionati servono esclusivamente come riferimento tecnico per l'utente.

7. Modifiche alla presente Informativa sulla privacy: Ci riserviamo il diritto di aggiornare la presente Informativa sulla privacy di tanto in tanto. Qualsiasi modifica a questa informativa verrà comunicata tramite aggiornamenti dell'applicazione. Ti invitiamo a rivedere la presente Informativa sulla privacy ogni volta che viene rilasciata un aggiornamento della nostra applicazione. L'utilizzo continuato dell'applicazione Reserve bot implica l'accettazione delle modifiche.

8. Contatti: Per qualsiasi domanda o suggerimento sulla nostra Informativa sulla privacy, non esitare a contattarci: Email: autoreservebot@gmail.com



