


# Privacy Policy 

[🇪🇸 Español](#español) | [🇮🇹 Italiano](#italiano)

---

## Español
– Reserve bot
Última actualización: 24/03/2026

1. La aplicación está diseñada para ayudar a las personas en su vida privada o laboral a programar automáticamente citas mediante mensajes de mensajería recibidos en aplicaciones de mensajes (por ejemplo WhatsApp, Facebook, Instagram, etc.). La aplicación Reserve bot escucha las notificaciones del sistema, recibidas en el dispositivo del usuario. Primero, el usuario elije las aplicaciones de mensajería que debe responder el bot, el bot interactuará con estos contactos a través de una secuencia de preguntas predeterminadas, y según las respuestas recibidas, el bot recogerá los datos necesarios para fijar una cita, como el nombre, la fecha y la hora guardándolos exclusivamente en una base de datos local (SQLite). Entonces, todos los datos procesados por la aplicación permanecen unicamente en el dispositivo del usuario

2. Informamos que la aplicación Reserve bot ha sido diseñada de tal manera que técnicamente no puede conectarse al exterior para enviar datos. Por lo tanto, la aplicación no recoge, transmite, o comparte datos personales y cualquier tipo de datos a terceros o servidores externos. Todos los datos personales y de mensajería permanecen exclusivamente en el dispositivo del usuario, en la base de datos local (SQLite) y no son compartidos por nosotros de ninguna manera. Sin embargo, la aplicación utiliza servicios de terceros (Google Firebase Crashlytics y Remote Config) exclusivamente para recopilar informacion técnica de diagnóstico (como registros de errores e información del dispositivo) para mejorar la estabilidad de la aplicación y gestionar actualizaciones. Estos datos técnicos no están relacionado con los mensajes que llegan al dispositivo o a cualquier datos personales como por ejemplo los contactos. Esto garantiza la máxima privacidad para el usuario y sus contactos. Además, compartir los datos almacenados en la base de datos local, solo está permitido al usuario, interactúando con nuestra aplicación, "Reserve bot", mediante un botón (por ejemplo, "compartir reservas"). Asimismo, el usuario puede decidir de forma independiente si desea compartir su lista de citas con sus contactos, gracias a diversas "Intent" de Android, entre la cual : Intent(Intent.ACTION_SEND), que interactúa con las aplicaciones instaladas en el dispositivo del usuario. Actualmente no se aplica cifrado a nivel de base de datos, pero los datos están protegidos por los mecanismos de seguridad del sistema operativo Android. Alentamos a los usuarios a proteger el acceso físico al dispositivo (por ejemplo, PIN, huella dactilares, contraseña). "
a) Contactos del dispositivos: la aplicación puede acceder a los contactos del dispositivo únicamente con el permiso explícito del usuario. El propósito es permitir al usuario seleccionar los contactos con los que el bot puede interactuar. Los contactos se leen sólo localmente. No son enviados, salvados o procesados por nosotros en servidores externos. 
b) Notificaciones: La aplicación "Reserve bot" utiliza un servicio de escucha de notificación para leer mensajes entrantes de aplicaciones de mensajería. Esto es indispensable para activar las respuestas automáticas del bot. La aplicación "Reserve bot" lee el contenido de notificación únicamente para el tratamiento inmediato, y no almacena el historial del chat. No se transmiten ni guardan datos, ni contenido de notificaciones en servidores externos. 
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

                                                                                                                 
INTERNET : Necesario para el motor Flutter, y para el uso de servicios técnicos de diagnóstico (Google Firebase). Aunque la aplicación tiene permiso para conectarse a Internet, todas las funcionalidades del app opera estrictamente de forma local, de hecho, todos los datos que pasan por la aplicación no se transmiten a través de Internet, como los datos personales y todos los demás datos y nunca se envían a la nube . 

**Privacidad de los Niños**
Esta aplicación no está dirigida a menores de edad. Dado que la aplicación funciona de manera completamente local y no transmite datos personales a servidores externos, no recopilamos ni almacenamos información personal de ningún usuario, incluidos los menores. 

READ_CONTACT:
La aplicación "Reserve Bot" requiere permiso para acceder a los contactos, pero esto solo ocurrirá si el usuario elige WhatsApp como plataforma de respuesta automática. Este permiso permite al usuario seleccionar cuales contactos de WhatsApp pueden interactuar con el bot, para programar una cita. No almacenamos datos de contacto en servidores externos ni los compartimos de ninguna manera. 

RECIBIVE_BOOT_COMPLETED : 
Para reactivar la aplicación "Reserve bot" inmediatamente al encender el dispositivo, permitiendo al usuario de no perder citas y garantizando que el bot pueda responder a las preguntas que se hayan acumulado en la cola, debido al cierre intencional o accidental del dispositivo por parte del usuario.


BIND_NOTIFICATION_LISTENER_SERVICE: Este permiso es esencial para el funcionamiento de la aplicación. Debe ser activado manualmente por el usuario. Permite leer las notificaciones del sistema siempre e iniciar el proceso de reserva automática de forma continua, incluso en segundo plano, garantizando que la aplicación "Reserve Bot" pueda escuchar y responder de forma fiable, incluso cuando no esté en primer plano. Además, muestra una notificación permanente para informar al usuario que la aplicación "Reserve Bot" está siempre activa en primer plano.


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

1. L'applicazione è progettata per aiutare le persone, nella loro vita personale o professionale, a prenotare automaticamente appuntamenti tramite le app di messaggistica (ad esempio, WhatsApp, Facebook, Instagram, ecc.).

L'applicazione "Reserve Bot" ascolta le notifiche di sistema ricevute sul dispositivo dell'utente e risponderà automaticamente solo ai contatti e alle app di messagistica decise dall' utente in app, per poi agendare appuntamenti attraverso una sequenza di domande predefinite e, in base alle risposte ricevute, raccoglierà i dati necessari come nome, data e ora, salvandoli esclusivamente in un database locale (SQLite), quindi tutti i dati elaborati dall'applicazione "Reserve bot" rimangono unicamente sul dispositivo dell'utente.

2. Si prega di notare che l'applicazione "Reserve Bot" è stata progettata in modo tale da non essere in grado tecnicamente di collegarsi a fonti esterne per inviare dati. Pertanto, l'applicazione non raccoglie, trasmette o condivide dati personali o qualsiasi altro tipo di dato con terze parti o server esterni. Infatti, tutti i dati trattati rimangono esclusivamente sul dispositivo dell'utente, nel database locale (SQLite), e non possono essere visualizzati da noi in alcun modo, ne da persone reali ne da sistemi tecnologici. Inoltre le notifiche di sistema che verranno trattate dal bot saranno solo quelle riferenti a WhatsApp, Facebook ed Instagram, tutte le altre notifiche (provenienti da altre fonti) saranno scartate dal filtro eseguito con codice Kotlin. Tuttavia, l'applicazione utilizza servizi di terze parti (Firebase Crashlytics e Remote Config) esclusivamente per ottenere informazioni tecniche diagnostiche (come log degli errori, informazioni sul dispositivo e gestioni delle versioni) solo al fine di risolvere eventuali crash dell'applicazione e gestire gli aggiornamenti. Ovviamente, In questi dati tecnici sono esclusi tutti i dati presenti sul dispositivo dell'utente. Ciò garantisce la massima privacy per l'utente e i suoi contatti. Inoltre, la condivisione dei dati (memorizzati nel database locale) è consentito solo all'utente, interagendo con la nostra applicazione, "Reserve bot", tramite un pulsante (ad esempio, "condividi prenotazioni"). Infatti l'utente può decidere autonomamente se condividere la sua lista degli appuntamenti con altri suoi contatti, grazie agli "Intent" di Android, tra cui : Intent(Intent.ACTION_SEND), che interagisce con le applicazioni installate sul dispositivo. Attualmente non viene applicata la crittografia a livello di database, ma i dati sono protetti dai meccanismi di sicurezza del sistema operativo Android. Incoraggiamo gli utenti a proteggere l'accesso fisico al dispositivo (ad esempio, PIN, impronta digitale, password).
 
Contatti del dispositivo: l'applicazione può accedere ai contatti del dispositivo solo con l'esplicito consenso dell'utente. Lo scopo è consentire all'utente di selezionare i contatti con cui il bot può interagire. I contatti vengono letti solo localmente, sul dispositivo dell' utente. Non vengono letti, inviati, salvati o elaborati da noi su server esterni.


3. Autorizzazioni necessarie per il corretto funzionamento: l'applicazione richiede le seguenti autorizzazioni Android:


BIND_NOTIFICATION_LISTENER_SERVICE: Questa autorizzazione è indispensabile per il funzionamento dell'applicazione. Deve essere abilitato manualmente dall'utente. Consente di leggere sempre le notifiche di sistema in arrivo e avviare il processo di prenotazione automatica, in maniera continuativa anche in background, garantendo che l' applicazione "Reserve Bot" possa ascoltare e rispondere in modo affidabile, anche quando non è in primo piano. 


FOREGROUND_SERVICE:
Attiva un servizio essenziale ed indispensabile per il funzionamento continuo dell'applicazione "Reserve bot", dandogli una priorità rispetto alle altre applicazioni, limitando la chiusura della stessa, per questioni di risparmio energetico o ottimizzazione della batteria. Ciò garantisce che l'applicazione possa ascoltare e rispondere in modo continuativo. Visualizza inoltre una notifica persistente per informare l'utente che l'applicazione "Reserve bot" è sempre attiva in primo piano.


FOREGROUND_SERVICE_REMOTE_MESSAGING: serve a gestire la ricezione e l'invio di messaggi in tempo reale, che richiedono una connessione costante e immediata, senza che il sistema possa "addormentare" l'app.

POST_NOTIFICATIONS: è un'autorizzazione che deve essere concessa dall'utente per consentire all'applicazione "Reserve bot" di visualizzare una notifica permanente, indispensabile per utilizzare le autorizzazioni FOREGROUND_SERVICE e FOREGROUND_SERVICE_REMOTE_MESSAGING.

WAKE_LOCK: Utilizzato esclusivamente per garantire la corretta elaborazione dei messaggi e il salvataggio dei dati nel database locale, impedendo l'interruzione del servizio quando il dispositivo entra in modalità di risparmio energetico o a schermo spento.

INTERNET: L'accesso alla rete è limitato esclusivamente alla telemetria tecnica anonima e per l'utilizzo dei servizi di diagnostica tecnica (Firebase Crashlytics, Remote Config). Sebbene l'applicazione abbia l'autorizzazione a connettersi a Internet, tutte le funzionalità dell'app operano esclusivamente in locale, infatti tutti i dati che transitano all'interno dell'applicazione non vengono trasmessi in Internet. Dunque, i dati personali e tutti gli altri dati non vengono mai inviati all'esterno.

READ_CONTACT:
L'applicazione "Reserve bot" richiede l'autorizzazione di accesso per leggere i contatti presenti nella rubrica, però ciò accadrà esclusivamente se l'utente sceglie "WhatsApp" come piattaforma di risposta automatica, infatti tale autorizzazione consente all'utente di scegliere quali dei suoi contatti di "WhatsApp" può interagire con il bot per fissare un'appuntamento. I dati dei contatti non vengono da noi memorizzati su server esterni né condivisi in alcun modo.

RECEIVE_BOOT_COMPLETED:
Importante per riattivare l' applicazione "Reserve bot" immediatamente all'avvio del dispositivo, consentendo all' utente di non perdere appuntamenti, facendo in modo che il bot possa rispondere ai messaggi che si sono accumulati in coda per la chiusura voluta o accidentale del dispositivo dell' utente.



4. Privacy dei minori
Questa applicazione non è destinata ai minori. Poiché l'applicazione opera interamente in locale e non trasmette dati personali a server esterni, non raccogliamo né memorizziamo informazioni personali di alcun utente, inclusi i minori.

5. Sicurezza dei dati locali: Nessun dato viene memorizzato su server esterni o nel cloud. L'applicazione memorizza i dati esclusivamente localmente utilizzando un database SQLite. L'app utilizza le misure di sicurezza standard del sistema operativo Android per proteggere i dati memorizzati localmente da accessi non autorizzati. Tuttavia, è responsabilità dell'utente proteggere fisicamente il proprio dispositivo (password, blocco schermo, ecc.).

6. Diritti di accesso e cancellazione dei dati: È possibile disabilitare tutti i permessi concessi dall'utente in qualsiasi momento tramite le impostazioni del dispositivo. L'utente ha il controllo completo sui dati salvati dall'applicazione nel database locale del dispositivo, infatti l'utente può gestire, modificare o eliminare questi dati direttamente dall'interfaccia dell'app Reserve bot oppure può farlo dalle impostazioni del dispositivo semplicemente disinstallando l'applicazione.

7. Affiliazioni: Questa applicazione (Reserve bot) è un prodotto indipendente e non è affiliata, supportata o sponsorizzata da WhatsApp, Facebook, Instagram o qualsiasi altra applicazione di messaggistica, e non richiede l'accesso interno alle API ufficiali. I nomi menzionati servono esclusivamente come riferimento tecnico per l'utente.

8. Modifiche alla presente Informativa sulla privacy: Ci riserviamo il diritto di aggiornare la presente Informativa sulla privacy di tanto in tanto. Qualsiasi modifica a questa informativa verrà comunicata tramite aggiornamenti dell'applicazione. Ti invitiamo a rivedere la presente Informativa sulla privacy ogni volta che viene rilasciata un aggiornamento della nostra applicazione. L'utilizzo continuato dell'applicazione Reserve bot implica l'accettazione delle modifiche.

9. Contatti: Per qualsiasi domanda o suggerimento sulla nostra Informativa sulla privacy, non esitare a contattarci: Email: autoreservebot@gmail.com



