**Specifiche dei Requisiti per RubiksApproach - Servizio di Coaching Online sul Cubo di Rubik**

1. Scopo del Servizio:(utente, funzionale)
Il servizio mira a trasformare i clienti da principianti a professionisti del cubing attraverso l'apprendimento strutturato e il supporto degli esperti.
RubiksApproach offre un servizio di coaching online riguardante il cubo di rubik. Partendo dalle basi e dalle nozioni più banali riguardanti questo mondo ogni cliente avrà la possibilità di intraprendere un percorso insieme ai nostri coach che lo porteranno dal non sapere a come impugnare e risolvere il cubo a delle risoluzioni avanzate e sofisticate come un vero professionista.

2. Accesso utente all'applicazione: (utente, funzionale)
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


3. Tipologie di Cubi Trattati:(sistema, funzionale)
L'app tratterà principalmente di cubo 3x3 2x2 e pyramynx, soprattutto agli inizi. Il cliente avrà poi la possibilità di apprendere i metodi risolutivi anche di cubi più complessi quali 4x4 5x5 e 6x6.


4. Pacchetti offerti:(utente, funzionale)
L'app mette a disposizione vari pacchetti per i clienti a seconda del persorso che desidereranno conseguire, ovvero uno sul cubo 3x3, uno sul cubo 2x2 e uno sulla pyramynx. Ogni pacchetto comprenderà 10 lezioni registrate sull'argomento scelto e un numero a scelta di lezioni in videochiamata con i coach del nostro team in cui si avrà la possibilità e il piacere di apprendere, allenarsi e migliorare insieme a degli esperti attraverso un approcio aperto e amichevole.
Sarà possibile anche modificare i pacchetti per soddisfare gli obiettivi specifici di apprendimento del cliente in questione.


5. Community Interattiva:(utente, non funzionale)
Il servizio mette a disposizione un servizio 24h su 24 per domande o curiostià relative al mondo del cubing, una sezione dove i clienti possono interagire fra di loro e una pagina con collegamenti esterni sempre riguardanti le notizie e le scoperte più recenti sul mondo del cubing.


6. Pravicy e sicurezza dei dati: (dominio)
RubiksApproach implementa misure robuste per garantire la privacy e la sicurezza dei dati dei clienti. Ciò include l'adozione di protocolli di crittografia per la trasmissione dei dati, l'accesso limitato alle informazioni personali solo al personale autorizzato e la definizione di politiche chiare in merito alla gestione e alla protezione dei dati sensibili. Inoltre, la politica di privacy è conforme alle leggi e ai regolamenti vigenti in materia di privacy dei dati ed è chiaramente disponibile ed accessibile ai clienti per un eventuale consultazione.


<img src="https://yuml.me/diagram/scruffy/usecase/[utente]-(avvia app),(avvia app)<(esegue la registrazione),(esegue la registrazione)>(inserisce nome utente),(esegue la registrazione)>(inserisce una password),(avvia app)<(richiede recupero password),(avvia app)>(inserisce credenziali),[sistema]-(verifica credenziali login),(verifica credenziali login)>(autorizza accesso),(inserisce credenziali)<(logout),(inserisce credenziali)<(accesso area riservata),(verifica credenziali login)>(gestisce errori di accesso),(gestisce errori di accesso)<(invio email reset password),(gestisce errori di accesso)>(fornisce messaggio di errore),[sistema]-(verifica nome utente e password dei sign up),[sistema]-(processa ordine pacchetti)">


<img src="https://yuml.me/diagram/scruffy/usecase/[Cliente]-(Sfoglia Pacchetti),(Sfoglia Pacchetti)>(Visualizza Pacchetto 2x2),(Visualizza Pacchetto 2x2)<(Compra pacchetto),(Sfoglia Pacchetti)>(Visualizza Pacchetto 3x3),(Visualizza Pacchetto 3x3)<(Compra pacchetto),(Sfoglia Pacchetti)>(Visualizza Pacchetto pyramynx),(Visualizza Pacchetto pyramynx)<(Compra pacchetto),(Sfoglia Pacchetti)<(Modifica Pacchetto),(Modifica Pacchetto)<(Compra pacchetto),(Compra pacchetto)>(Checkout),(Checkout)<(Aggiungi Carta),[Cliente]-(Visualizza Lezioni Registrate),(Visualizza Lezioni Registrate)<(Pone Domande sulla lezione),[Cliente]-(Richiede Videochiamata),[Coach]-(Conduce Videochiamata),[Coach]-(Risponde alle domande sulle lezioni)">

-----------------------------------------------------------------------------------------

*User Story* 

Come principiante nel cubing, quindi come utente, desidero accedere all'applicazione tramite un sistema di autenticazione sicuro, così posso iniziare il mio percorso di apprendimento. (13 ore)

Come utente già registrato, voglio poter recuperare la mia password tramite un'email di reset nel caso la dimentichi, garantendo l'accesso continuo ai servizi offerti. (13 ore)

Come utente registrato, vorrei avere a disposizione una panoramica dei vari pacchetti presenti nel corso e personalizzare le lezioni di quest'ultimo, adattando il mio percorso di apprendimento alle mie esigenze specifiche. (16 ore)

Come cliente interessato ai pacchetti di coaching offerti da RubiksApproach, desidero poter effettuare pagamenti sicuri e affidabili per l'acquisto dei pacchetti, garantendo un'esperienza di transazione fluida e protetta durante il processo di acquisto. (10 ore)

Come utente che ha acquistato un pacchetto, voglio poter accedere alle lezioni preregistrate e avere la possibilità di fissare le date in cui si svolgeranno le videochiamate con i coach in modo da usufuire a 360 gradi dei servizi acquistati. (13 ore)     

Come utente già registrato, mi aspetto di poter accedere alla pagina dedicata alla community interattiva in modo da poter pubblicare domande o rispondere ad altrettante poste da altri utenti del servizio o anche da utenti esterni e discitere sulle ultime novità del mondo del cubing. (13 ore)

Come utente, desidero essere in grado di accedere a un servizio di supporto 24/7, in modo da poter avere risposte e chiarimenti in qualsiasi momento riguardo ai metodi di risoluzione dei cubi. (10 ore)

Come esperto in crescita nel cubing, desidero avere accesso a risorse avanzate per risolvere cubi più complessi come il 4x4 o il 5x5, così da poter migliorare continuamente le mie abilità. (13 ore)

In quanto amministratore dell'app, preoccupato per la sicurezza dei dati, voglio implementare in RubiksApproach protocolli di crittografia avanzati e politiche chiare sulla privacy, proteggendo le informazioni personali di tutti i clienti e garantendo la conformità alle leggi sulla privacy. (16 ore)

Per gestire in modo efficace lo sviluppo dell'applicazione RubiksApproach, le ore complessive di tutte le fasi (117 ore) verranno divise in tre split, ciascuno della durata di una settimana (circa 40 ore). La suddivisione del progetto in split temporali viene adottata al fine di facilitare la gestione delle attività, monitorare lo stato di avanzamento, adattare la pianificazione in base alle necessità e ridurre i rischi, consentendo così un controllo più efficace e una gestione più flessibile del lavoro

---------------------------------------------------------------------------------


