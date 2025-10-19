# **Privacy Policy AutoReserveBot**

Privacy Policy – Reserve bot 

Ultimo aggiornamento: 19/10/2025


1. Finalità dell'app

L’app è progettata per aiutare le persone nella loro vita privata o lavorativa per
agendare automaticamente appuntamenti tramite messaggi ricevuti su app di messaggistica (es. WhatsApp, Telegram, ecc.). 
L’app ascolta le notifiche di sistema ricevute sul dispositivo dell'utente. Innanzitutto l'utente imposta in app a quali contatti il bot deve rispondere, il bot interagirà quindi solo con questi contatti attraverso una sequenza di domande predefinite, ed in base alle risposte ricevute,il bot raccoglierà i dati necessari per fissare un appuntamento, come nome, data e orario salvandoli in un database locale (SQLite).
Tutti i dati elaborati dall’app restano esclusivamente sul dispositivo dell’utente. 


2. Dati trattati

Premettiamo che l'app è stata progettata in modo tale da non poter essere in grado tecnicamente di collegarsi all'esterno per l'invio di dati.
Quindi l’app non raccoglie, né trasmette, né condivide dati personali e dati di qualsiasi genere a terze parti o server esterni.
Tutti i dati restano esclusivamente sul dispositivo dell’utente nel database locale (SQLite) e non vengono condivisi in alcun modo da noi.
Questo garantisce la massima privacy per l'utente e per i suoi contatti.
D'altra parte, l’accesso ai dati (salvati nel database locale) è possibile solo da parte dell’utente, che interagendo con l'interfaccia usuario della nostra app con un pulsante (es. 'Condividi lista prenotazioni') potrà decidere di sua iniziativa di condividere con altre app le informazioni raccolte dal bot. 
Non viene attualmente applicata una crittografia a livello di database, ma i dati sono protetti dai meccanismi di sicurezza del sistema operativo Android. Invitiamo gli utenti a proteggere l’accesso fisico al dispositivo (es. PIN, impronta, password)."


 a) Contatti della rubrica del dispositivo: 

L’app può accedere ai contatti del dispositivo solo previa autorizzazione esplicita da parte dell’utente.
Lo scopo è consentire all’utente di selezionare i contatti con cui il bot potrà interagire.
I contatti vengono letti soli in locale.
Non vengono da noi inviati, salvati o elaborati su server esterni.

b) Notifiche:
L’app utilizza un servizio di ascolto notifiche per leggere i messaggi in arrivo dalle app di messaggistica.
Questo è necessario per attivare le risposte automatiche del bot.
l'app legge il contenuto delle notifiche solo per l'elaborazione immediata, e non salva la cronologia completa delle chat.
Nessun dato o contenuto delle notifiche viene trasmesso o salvato da noi in server esterni.

c) Dati inseriti nel database locale e dati propri dell’utente:

I dati propri dall'utente come I dati dei contatti dell'utente che poi vengono salvati nel database(SQLite) locale sul dispositivo dell’utente, non vengono da noi inviati, salvati o elaborati su server esterni.


3. Permessi richiesti

Per funzionare correttamente, l'app richiede i seguenti permessi Android:

READ_CONTACT:
L’app richiede il permesso di accesso ai contatti al solo scopo di consentire all’utente di selezionare con quali numeri telefonici il bot potrà interagire.
I dati dei contatti non vengono salvati da noi su server esterni né condivisi in alcun modo.
L’app filtra i contatti in base alle etichette associate alle app di messaggistica (es. WhatsApp) esclusivamente in locale.

 BIND_NOTIFICATION_LISTENER_SERVICE: Questo permesso è fondamentale per il funzionamento dell'App. Ci permette di leggere i messaggi in arrivo e di avviare il processo di prenotazione automatica.
Deve essere attivato manualmente dall’utente.
 

FOREGROUND_SERVICE: 
Mantiene attivo un servizio essenziale per il funzionamento continuo dell’app,
Per garantire che l'App possa svolgere il suo lavoro di ascolto e risposta in modo affidabile, anche quando non la si sta usando attivamente.
Mostra una notifica permanente per informare l’utente che l'app è attiva in foreground.

FOREGROUND_SERVICE_DATA_SYNC : 
Per Interagire con il database interno (SQLite) e con i contatti dell’agenda in locale, anche quando l’app è in background.

WAKE_LOCK : 
Per evitare che il dispositivo si addormenti durante l’elaborazione di messaggi.

REQUEST_IGNORE_BATTERY_OPTIMIZATIONS :
Per garantire il funzionamento affidabile anche con le ottimizzazioni della batteria attive.

RECEIVE_BOOT_COMPLETED :
Per riattivare il bot all’avvio del telefono, se l’utente ha scelto l’attivazione automatica.

INTERNET :
Necessario al motore Flutter, e
sebbene l'app abbia il permesso di connettersi a internet, tutte le funzionalità del bot e la gestione dei dati all'interno dell'app non fanno uso di internet, infatti i dati personali come anche tutti gli altri dati non vengono mai inviati all'esterno.


POST_NOTIFICATIONS: 
Necessario per usare i permessi BIND_NOTIFICATION_LISTENER_SERVICE e FOREGROUND_SERVICE precedentemente dichiarati. POST_NOTIFICATIONS è un permesso che deve essere dato personalmente dal'utente per consetire che l'app possa mostrare una notifica.

4. Sicurezza dei Dati Locali:
Nessun dato viene salvato da noi su server esterni o su cloud. 
l’app esclusivamente salva i dati in locale usando un database SQLite. 
L'App utilizza le misure standard di sicurezza del sistema operativo Android per proteggere i dati archiviati localmente da accessi non autorizzati.
Tuttavia, è responsabilità dell’utente proteggere fisicamente il proprio dispositivo (password, blocco schermo, ecc.).


5. Diritti e eliminazione dei Dati:
L’utente può disattivare l’accesso ai permessi in qualsiasi momento tramite le impostazioni del dispositivo.
L'utente ha il pieno controllo sui dati salvati dall'app sul database locale del dispositivo. L'utente può gestire, modificare o eliminare tali dati del database direttamente dall'interfaccia dell'App, o puo farlo dalle impostazioni del suo dispositivo semplicemente disinstallando l'App.


6. Condivisione dei dati:
Noi non condividiamo nessun dato con sviluppatori, partner o terze parti. Nessuna informazione raccolta viene trasmessa da noi a server esterni. Solo l'utente Invece può essere in grado (interagendo con un pulsante all'interno dell'app es. 'Condividi lista prenotazioni'), può decidere di sua iniziativa di condividere i dati con altre app installate sul suo dispositivo.



7. Affiliazioni:
Questa applicazione (Reserve bot) è un prodotto indipendente e non è in alcun modo affiliato, supportato o sponsorizzato da WhatsApp, Telegram, Facebook Messenger o qualsiasi altra app di messaggistica e non richiede accessi interni ad API ufficiali. I nomi citati servono solo come riferimento tecnico per l'utente.

8. Modifiche a questa Informativa sulla Privacy:
Ci riserviamo il diritto di aggiornare la nostra Informativa sulla Privacy di volta in volta. Eventuali modifiche a questa informativa saranno comunicate tramite aggiornamenti dell’app.
Ti invitiamo a rivedere ad ogni aggiornamento dell'app questa Informativa sulla Privacy per eventuali modifiche.
L’uso continuato dell’app implica l’accettazione delle modifiche.


9. Contatti:
Se hai domande o suggerimenti riguardo la nostra Informativa sulla Privacy, non esitare a contattarci:
 * Email: [autoreservebot@gmail.com
