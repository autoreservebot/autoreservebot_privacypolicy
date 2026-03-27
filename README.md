


# Privacy Policy 

[🇪🇸 Español](#español) | [🇮🇹 Italiano](#italiano)

---

## Español
– Reserve bot
Última actualización: 24/03/2026

1. La aplicación está diseñada para ayudar a las personas, tanto en su vida personal como profesional, a reservar citas automáticamente a través de aplicaciones de mensajería (por ejemplo, WhatsApp, Facebook, Instagram, etc.).

La aplicación "Reserve Bot" escucha las notificaciones del sistema recibidas en el dispositivo del usuario y responderá automáticamente solo a los contactos y app. de mensajería que el usuario ha especificado en nuestra app. "Reserve bot", para poder programarar las citas mediante una serie de preguntas predefinidas, y en función de las respuestas recibidas, recopilará los datos necesarios, como nombre, fecha y hora, y los guardará exclusivamente en una base de datos local (SQLite). Por lo tanto, todos los datos procesados, ​​por la aplicación "Reserve Bot" permanecen únicamente en el dispositivo del usuario.

2. Tenga en cuenta que la aplicación "Reserve Bot" está diseñada para que técnicamente no pueda conectarse a fuentes externas para enviar datos. Por lo tanto, la aplicación no recopila, transmite ni comparte datos personales ni ningún otro tipo de datos con terceros ni servidores externos. De hecho, todos los datos procesados ​​permanecen exclusivamente en el dispositivo del usuario, en la base de datos local (SQLite), y no podemos acceder a ellos de ninguna manera, ni con personas reales ni con sistemas tecnológicos. Además, las notificaciones del sistema procesadas por el bot serán únicamente las que son provenientes de WhatsApp, Facebook e Instagram; todas las demás notificaciones (de otras fuentes) serán descartadas por el filtro ejecutado con código Kotlin. Sin embargo, la aplicación utiliza servicios de terceros (Firebase Crashlytics y Remote Config) exclusivamente para obtener información de diagnóstico técnico (como registros de errores, información del dispositivo y gestión de versiones del app.) con el único fin de solucionar cualquier fallo de la aplicación y gestionar las actualizaciones. Obviamente, estos datos técnicos excluyen todos los datos almacenados en el dispositivo del usuario. Esto garantiza la máxima privacidad para el usuario y sus contactos. Además, los datos (almacenados en la base de datos local) solo pueden ser compartidos por el usuario, interactuando con nuestra aplicación, "Reserve bot", a través de un botón (por ejemplo, "Compartir reservas"). De hecho, los usuarios pueden decidir de forma independiente si desean compartir su lista de citas con sus contactos, gracias a los "Intent" de Android, que incluyen: Intent(Intent.ACTION_SEND), que interactúa con las aplicaciones instaladas en el dispositivo. Actualmente no se aplica cifrado a nivel de base de datos, pero los datos están protegidos por los mecanismos de seguridad del sistema operativo Android. Recomendamos a los usuarios proteger el acceso físico al dispositivo (por ejemplo, mediante PIN, huella digital o contraseña).

Contactos del dispositivo: La aplicación solo puede acceder a los contactos del dispositivo con el consentimiento explícito del usuario. Esto permite al usuario seleccionar los contactos con los que el bot puede interactuar. Los contactos se leen únicamente de forma local en el dispositivo del usuario. No los leemos, enviamos, guardamos ni procesamos en servidores externos.

3. Permisos necesarios para su correcto funcionamiento: La aplicación requiere los siguientes permisos de Android:

BIND_NOTIFICATION_LISTENER_SERVICE: Este permiso es esencial para el funcionamiento de la aplicación. Debe ser habilitado manualmente por el usuario. Permite leer las notificaciones entrantes del sistema e iniciar el proceso de reserva automática de forma continua, incluso en segundo plano, garantizando que la aplicación "Reserve Bot" pueda escuchar y responder de forma fiable, incluso cuando no esté en primer plano.

FOREGROUND_SERVICE: Activa un servicio esencial para el funcionamiento continuo de la aplicación "Reserve Bot", dándole prioridad sobre otras aplicaciones y limitando su cierre, cuando el dispositivo requiere ahorrar energía u optimizar la batería. Esto garantiza que la aplicación pueda escuchar y responder de forma continua. También muestra una notificación permanente para informar al usuario de que la aplicación "Reserve bot" siempre está activa en primer plano.

FOREGROUND_SERVICE_REMOTE_MESSAGING: Este permiso gestiona la recepción y el envío de mensajes en tiempo real, que requieren una conexión constante e inmediata, evitando que el sistema suspenda la aplicación.

POST_NOTIFICATIONS: El usuario debe otorgar este permiso para que la aplicación "Reserve bot" pueda mostrar una notificación persistente, necesaria para usar los permisos FOREGROUND_SERVICE y FOREGROUND_SERVICE_REMOTE_MESSAGING.

WAKE_LOCK: Se utiliza exclusivamente para garantizar el correcto procesamiento de mensajes y el almacenamiento de datos en la base de datos local, evitando la interrupción del servicio cuando el dispositivo entra en modo de ahorro de energía o la pantalla está apagada.

INTERNET: El acceso a la red se limita exclusivamente a la telemetría técnica anónima y al uso de servicios de diagnóstico técnico (Firebase Crashlytics, Remote Config). Aunque la aplicación tiene permiso para conectarse a Internet, todas sus funciones operan exclusivamente de forma local; ningún dato dentro de la aplicación se transmite a través de Internet. Por lo tanto, los datos personales y cualquier otro dato nunca se envían fuera de la aplicación.

READ_CONTACT: La aplicación "Reserve bot" solicita permiso para acceder a los contactos de la agenda, pero esto solo ocurrirá si el usuario elige WhatsApp como plataforma de respuesta automática. Este permiso permite al usuario seleccionar qué contactos de WhatsApp pueden interactuar con el bot para programar una cita. Los datos de contacto no se almacenan en servidores externos ni se comparten de ninguna manera.

RECEIVE_BOOT_COMPLETED:
Importante para reactivar la aplicación "Reserve bot" inmediatamente al encender el dispositivo, asegurando que el usuario no pierda citas, permitiendo al bot de contestar a los mensajes acumulados en la cola debido al cierre intencional o accidental del dispositivo.

4. Privacidad de los menores
Esta aplicación no está destinada a menores de edad. Dado que la aplicación funciona completamente de forma local y no transmite datos personales a servidores externos, no recopilamos ni almacenamos información personal de ningún usuario, incluidos los menores.

5. Seguridad de los datos locales: No se almacenan datos en servidores externos ni en el cloud. La aplicación almacena los datos exclusivamente de forma local mediante una base de datos SQLite. La aplicación utiliza las medidas de seguridad estándar del sistema operativo Android para proteger los datos almacenados localmente contra el acceso no autorizado. Sin embargo, es responsabilidad del usuario proteger físicamente su dispositivo (contraseña, bloqueo de pantalla, etc.).

6. Derechos de acceso y eliminación de datos: el usuario puede desactivar todos los permisos otorgados en cualquier momento accediendo en la configuración de su dispositivo. El usuario tiene el control total sobre los datos que la aplicación guarda en la base de datos local del dispositivo. Puede administrar, editar o eliminar estos datos directamente desde la interfaz de la aplicación "Reserve Bot", o bien, desinstalar la app. "Reserve Bot" desde la configuración de su dispositivo.

7. Afiliaciones: Esta aplicación (Reserve Bot) es un producto independiente y no está afiliada, respaldada ni patrocinada por WhatsApp, Facebook, Instagram ni ninguna otra aplicación de mensajería, y no requiere acceso interno a las API oficiales. Los nombres mencionados son solo para referencia del usuario.

8. Cambios en esta Política de Privacidad: Nos reservamos el derecho de actualizar esta Política de Privacidad periódicamente. Cualquier cambio se comunicará mediante las actualizaciones de la aplicación. Le recomendamos revisar esta Política de Privacidad cada vez que se publique una actualización de nuestra aplicación. El uso continuado de la aplicación "Reserve Bot" implica la aceptación de los cambios.

9. Contacto: Si tiene alguna pregunta o sugerencia sobre nuestra Política de Privacidad, no dude en contactarnos: Correo electrónico: autoreservebot@gmail.com


<br><br>

---

## Italiano

– Reserve Bot

Ultimo aggiornamento: 24/03/2026

1. L'applicazione è progettata per aiutare le persone, nella loro vita personale o professionale, a prenotare automaticamente appuntamenti tramite le app di messaggistica (ad esempio, WhatsApp, Facebook, Instagram, ecc.).

L'applicazione "Reserve Bot" ascolta le notifiche di sistema ricevute sul dispositivo dell'utente e risponderà automaticamente solo ai contatti e alle app di messagistica decise dall' utente in app, per poi agendare appuntamenti attraverso una sequenza di domande predefinite e, in base alle risposte ricevute, raccoglierà i dati necessari come nome, data e ora, salvandoli esclusivamente in un database locale (SQLite), quindi tutti i dati elaborati dall'applicazione "Reserve bot" rimangono unicamente sul dispositivo dell'utente.

2. Si prega di notare che l'applicazione "Reserve Bot" è stata progettata in modo tale da non essere in grado tecnicamente di collegarsi a fonti esterne per inviare dati. Pertanto, l'applicazione non raccoglie, trasmette o condivide dati personali o qualsiasi altro tipo di dato con terze parti o server esterni. Infatti, tutti i dati trattati rimangono esclusivamente sul dispositivo dell'utente, nel database locale (SQLite), e non possono essere visualizzati da noi in alcun modo, ne da persone reali ne da sistemi tecnologici. Inoltre le notifiche di sistema che verranno trattate dal bot saranno solo quelle riferenti a WhatsApp, Facebook ed Instagram, tutte le altre notifiche (provenienti da altre fonti) saranno scartate dal filtro eseguito con codice Kotlin. Tuttavia, l'applicazione utilizza servizi di terze parti (Firebase Crashlytics e Remote Config) esclusivamente per ottenere informazioni tecniche diagnostiche (come log degli errori, informazioni sul dispositivo e gestioni delle versioni dell' app) solo al fine di risolvere eventuali crash dell'applicazione e gestire gli aggiornamenti. Ovviamente, In questi dati tecnici sono esclusi tutti i dati presenti sul dispositivo dell'utente. Ciò garantisce la massima privacy per l'utente e i suoi contatti. Inoltre, la condivisione dei dati (memorizzati nel database locale) è consentito solo all'utente, interagendo con la nostra applicazione, "Reserve bot", tramite un pulsante (ad esempio, "condividi prenotazioni"). Infatti l'utente può decidere autonomamente se condividere la sua lista degli appuntamenti con altri suoi contatti, grazie agli "Intent" di Android, tra cui : Intent(Intent.ACTION_SEND), che interagisce con le applicazioni installate sul dispositivo. Attualmente non viene applicata la crittografia a livello di database, ma i dati sono protetti dai meccanismi di sicurezza del sistema operativo Android. Incoraggiamo gli utenti a proteggere l'accesso fisico al dispositivo (ad esempio, PIN, impronta digitale, password).
 
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



