


# Privacy Policy 

[🇪🇸 Español](#español) | [🇮🇹 Italiano](#italiano)

---

## Español
– Reserve bot
Última actualización: 24/03/2026



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



