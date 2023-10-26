Specifiche dei Requisiti per RubiksApproach - Servizio di Coaching Online sul Cubo di Rubik

Accesso utente all'applicazione: (utente, funzionale)
Gli utenti devono essere in grado di effettuare l'accesso all'applicazione utilizzando credenziali valide. Questo requisito implica la necessità di un sistema di autenticazione sicuro e affidabile per garantire che solo utenti autorizzati possano accedere ai servizi offerti da RubiksApproach.

- Pagina di Accesso: Quando un utente avvia l'applicazione RubiksApproach, viene presentata una schermata di accesso che richiede l'inserimento delle credenziali.
- Inserimento Credenziali: L'utente inserisce il proprio nome utente (o indirizzo email) e la password associata all'account.
- Verifica delle Credenziali: Il sistema verifica le credenziali inserite confrontandole con quelle registrate nel database. Se le credenziali sono corrette, l'accesso viene consentito.
- Accesso Autorizzato: Una volta verificate, l'utente viene autenticato e reindirizzato all'area riservata dell'applicazione, dove può accedere ai servizi di coaching e altre funzionalità.
- Gestione Errori di Accesso: Se le credenziali inserite non corrispondono a un account valido o se si verificano altri errori nell'accesso, il sistema fornisce un messaggio di errore appropriato e consente 
  all'utente di riprovare.
- Recupero Password (opzionale): Nel caso in cui un utente dimentichi la propria password, l'applicazione può offrire un meccanismo per il recupero della password, ad esempio attraverso l'invio di un'email di 
  reset della password.
- Sicurezza della Sessione: Durante la sessione di accesso, il sistema mantiene la sicurezza della connessione attraverso l'uso di protocolli crittografici per proteggere le informazioni trasmesse.
- Logout (opzionale): L'utente ha la possibilità di terminare la sessione di accesso in qualsiasi momento, ad esempio cliccando su un pulsante di "Logout". Questo assicura che l'utente esca in modo sicuro 
  dall'applicazione.

1. Scopo del Servizio:(utente, funzionale)
Il servizio mira a trasformare i clienti da principianti a professionisti del cubing attraverso l'apprendimento strutturato e il supporto degli esperti.
RubiksApproach offre un servizio di coaching online riguardante il cubo di rubik. Partendo dalle basi e dalle nozioni più banali riguardanti questo mondo ogni cliente avrà la possibilità di intraprendere un percorso insieme ai nostri coach che lo porteranno dal non sapere a come impugnare e risolvere il cubo a delle risoluzioni avanzate e sofisticate come un vero professionista.

2. Tipologie di Cubi Trattati:(sistema, funzionale)
Si tratterà principalmente di cubo 3x3 2x2 e pyramynx, soprattutto agli inizi. Si avrà poi la possibilità di apprendere i metodi risolutivi anche di cubi più complessi quali 4x4 5x5 e 6x6.

3. Pacchetti offerti:(utente, funzionale)
Ci saranno a disposizione vari pacchetti per i clienti a seconda del persorso che desidereranno conseguire, ovvero uno sul cubo 3x3, uno sul cubo 2x2 e uno sulla pyramynx. Ogni pacchetto comprenderà 10 lezioni registrate sull'argomento scelto e un numero a scelta di lezioni in videochiamata con i coach del nostro team in cui si avrà la possibilità e il piacere di apprendere, allenarsi e migliorare insieme a degli esperti attraverso un approcio aperto e amichevole.
Sarà possibile anche modificare i pacchetti per soddisfare gli obiettivi specifici di apprendimento del cliente in questione.

4. Community Interattiva:(utente, non funzionale)
Il servizio mette a disposizione un servizio 24h su 24 per domande o curiostià relative al mondo del cubing, una sezione dove i clienti possono interagire fra di loro e una pagina con collegamenti esterni sempre riguardanti le notizie e le scoperte più recenti sul mondo del cubing.

5. Pravicy e sicurezza dei dati: (dominio)
RubiksApproach implementa misure robuste per garantire la privacy e la sicurezza dei dati dei clienti. Ciò include l'adozione di protocolli di crittografia per la trasmissione dei dati, l'accesso limitato alle informazioni personali solo al personale autorizzato e la definizione di politiche chiare in merito alla gestione e alla protezione dei dati sensibili. Inoltre, la politica di privacy è conforme alle leggi e ai regolamenti vigenti in materia di privacy dei dati ed è chiaramente disponibile ed accessibile ai clienti per un eventuale consultazione.

<img src="https://yuml.me/diagram/scruffy/usecase/[utente]-(avvia app),(avvia app)<(esegue la registrazione),(esegue la registrazione)>(inserisce nome utente),(esegue la registrazione)>(inserisce una password),(avvia app)<(richiede recupero password),(avvia app)>(inserisce credenziali),[sistema]-(verifica credenziali),(verifica credenziali)>(autorizza accesso),(inserisce credenziali)<(logout),(inserisce credenziali)<(accesso area riservata),(verifica credenziali)>(gestisce errori di accesso),(gestisce errori di accesso)<(invio email reset password),(gestisce errori di accesso)>(fornisce messaggio di errore)">

<img src="https://yuml.me/diagram/scruffy/usecase/[Cliente]-(Sfoglia Pacchetti),(Sfoglia Pacchetti)>(Visualizza Pacchetto 2x2),(Visualizza Pacchetto 2x2)<(Compra pacchetto),(Sfoglia Pacchetti)>(Visualizza Pacchetto 3x3),(Visualizza Pacchetto 3x3)<(Compra pacchetto),(Sfoglia Pacchetti)>(Visualizza Pacchetto pyramynx),(Visualizza Pacchetto pyramynx)<(Compra pacchetto),(Sfoglia Pacchetti)<(Modifica Pacchetto),(Modifica Pacchetto)<(Compra pacchetto),[Cliente]-(Visualizza Lezioni Registrate),(Visualizza Lezioni Registrate)<(Pone Domande sulla lezione),[Cliente]-(Richiede Videochiamata),[Coach]-(Conduce Videochiamata),[Coach]-(Risponde alle domande sulle lezioni)">
