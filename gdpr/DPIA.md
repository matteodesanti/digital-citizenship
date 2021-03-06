---
title: Cittadinanza Digitale
subtitle: Valutazione d'impatto sulla protezione dei dati
author:
- Team per la Trasformazione Digitale
- Agenzia per L'Italia Digitale
date: \today
lang: it-IT
mainlang: italian
lot: true
lof: true
---

<!--
TODO: punto di vista dell'ente (esempio: superficie di attacco quando
l'ente esegue un invio massivo di messaggi)
TODO: flusso ente invio messaggi (se non ha email deve controllare se il cf ha un profilo)
-->

# Introduzione

Questo documento è una valutazione dell'impatto sulla protezione dei dati (DPIA)
che valuta il servizio di Cittadinanza Digitale che l'Agenzia per l'Italia
Digitale vuole offrire ai cittadini ed alle Pubbliche Amministrazioni italiane.

La DPIA è un'analisi delle attività di trattamento dei dati e copre i dettagli
dell'attività di elaborazione degli stessi e una valutazione dei rischi
associati al trattamento, comprese eventuali misure che devono essere adottate
per mitigare tali rischi. Contiene anche la decisione sull'avvio di una
consultazione preliminare con il _Data Protection Officer_ competente.

La presente DPIA viene prodotta ai sensi dell'articolo 35 del GDPR - laddove il
trattamento rischia di comportare un rischio elevato per i diritti e le libertà
delle persone fisiche, il responsabile del trattamento effettua una
valutazione dell'impatto dell'elaborazione prevista.

Le valutazioni hanno valore per gli individui, le organizzazioni e la società.
La presente DPIA valuta i rischi per la privacy personale e identifica le
misure, le salvaguardie e i meccanismi esistenti per mitigare tali rischi.

## Informazioni chiave

* **Titolare dei dati**: Agenzia per l'Italia Digitale (AgID), in co-titolarità
  con gli Enti Erogatori aderenti al servizio.
* **Descrizione del progetto**: Questo documento di analisi d'impatto riguarda il
  progetto di Cittadinanza Digitale descritto nel capitolo seguente.
* **Soggetti oggetto del trattamento dei dati**: Pubbliche Amministrazioni Italiane
  e Cittadini Italiani dotati di identità digitale (SPID).
* **Tipologie di dati personali**: Le tipologie di dati trattati in questo progetto
  includono informazioni personali quali nome, cognome, codice fiscale degli
  utenti del servizio e contenuto dei messaggi e documenti inviati dalle
  Pubbliche Amministrazioni ai cittadini - si faccia riferimento al §
  \vref{descrizione-flussi-informativi} per l'elenco completo dei dati personali
  trattati.
* **Categorie speciali di dati trattati**: Nessuna.
* **Soggetti che hanno accesso ai dati trattati**: I seguenti soggetti avranno
  accesso ai dati trattati dal sistema:
  * Soggetti gestori del servizio autorizzati.
  * Cittadini aderenti al servizio, per quanto riguarda i propri dati SPID e i
    dati ricevuto dai servizi erogati dagli Enti.
  * Enti Erogatori al servizio, per quanto riguarda i dati inviati ai cittadini
    e le preferenze condivise dai singoli cittadini con i servizi erogati
    dall'Ente - si faccia riferimento al § \vref{descrizione-flussi-informativi}
    per l'elenco completo dei soggetti coinvolti nel trattamento dei dati.

\pagebreak

# Il progetto Cittadinanza Digitale

La Presidenza del Consiglio dei Ministri, in collaborazione con l’Agenzia per
l’Italia Digitale, ha progettato e sviluppato un sistema applicativo che si
presenta come il punto di accesso ai servizi delle pubbliche amministrazione e
degli altri soggetti pubblici indicati all’articolo 2, comma 2, del CAD (di
seguito, “Enti Erogatori”), quali appunto le società a controllo pubblico, non
quotate, e i gestori di pubblici servizi.

Tale sistema applicativo è fruibile attraverso la relativa applicazione mobile,
scaricabile gratuitamente dallo store preferito dall’utente cittadino,
disponibile per piattaforma sia Android, sia iOS. Le funzionalità legate alla
gestione dell’account, della privacy e della sicurezza saranno disponibili
anche tramite browser web.

L’applicazione di Cittadinanza Digitale (CD) rappresenta un canale
complementare o alternativo agli altri canali digitali già utilizzati dagli
Enti Erogatori, attraverso cui gli enti stessi metteranno a disposizione
dell’utente le funzioni descritte in seguito e relative ai propri servizi.

CD infatti, attraverso un’unica piattaforma applicativa, consente al cittadino
d'interagire con le amministrazioni italiane, centrali, locali e con
tutti gli Enti erogatori di servizi digitali.
CD assume pertanto un duplice valore: da un lato abilita i
soggetti pubblici a utilizzare una serie di funzioni comuni a
tutti i servizi digitali, dall’altro offre agli utenti cittadini uno
strumento unico per fruire di queste stesse funzioni.

CD, nella sua funzione di punto di accesso, permette all’utente di accedere
facilmente e in modalità aggregata alle proprie informazioni e ai servizi
digitali che lo riguardano, indipendentemente da quali siano gli Enti Erogatori
di suo specifico interesse. CD non si sostituisce in alcun modo agli Enti
Erogatori che rimangono pertanto titolari delle informazioni in loro possesso,
dei relativi trattamenti di dati personali e dell’erogazione dei relativi
servizi, che restano nella loro disponibilità esclusiva. Per questo CD si
configura semplicemente come un canale supplementare che permette agli
utenti di raggiungere - più facilmente e in modalità più razionalizzata -
le informazioni e i servizi degli Enti Erogatori.

Ferma ogni possibile implementazione nel tempo da parte della Presidenza del
Consiglio dei Ministri di altre funzionalità, allo stato attuale
l’applicazione di CD si compone di 5 sezioni principali che corrispondono a
cinque funzioni base comuni a molti servizi digitali:

* Messaggi;
* portafoglio;
* documenti;
* preferenze;
* profilo.

L’utente, previo l’opportuno download dell’applicazione in un dispositivo
compatibile, potrà accedere ai servizi autenticandosi tramite SPID. Disporre
di un account SPID valido sarà quindi condizione necessaria e sufficiente per
utilizzare CD.

Si descrivono di seguito le sezioni principali di cui si compone CD, che
corrispondono ad altrettante funzioni disponibili ai soggetti pubblici.

## Servizio messaggi

La sezione messaggi consentirà all’utente di ricevere le comunicazioni a lui
indirizzate da parte degli Enti Erogatori che utilizzano le api messe a
disposizione da CD e dagli altri servizi collegati.

L’utente potrà ordinare e/o filtrare i messaggi ricevuti sulla base di distinti
parametri, quali, ad esempio, la data di invio del messaggio, l’identificativo
del servizio oggetto del messaggio, l’oggetto indicato nel messaggio, etc.
Altri metadati ed altre funzioni di ricerca/ordinamento potranno essere
integrate nelle successive versioni di CD.

L’utente, se lo desidera, potrà beneficiare di ulteriori funzionalità collegate,
quali la possibilità di gestire le preferenze di recapito per uno specifico
servizio, condividere con terzi il messaggio, ricevere degli avvisi in merito
alla scadenza del messaggio, etc.

Per gli Enti Erogatori che aderiscono a CD sarà possibile interrogare un
servizio per sapere se uno specifico cittadino ha attivato CD e se ha delle
preferenze relative all’ente stesso.

## Portafoglio

La sezione portafoglio, integrata con il Sistema pagoPA, consente di gestire le
transazioni economiche fra il cittadino e lo stato, gestire i propri metodi di
pagamento preferiti e di avere a disposizione la lista delle transazioni già
eseguite, al pari delle più comuni applicazioni per i servizi di home banking.

Le funzioni di pagamento consentiranno di eseguire le transazione economiche
anche all’interno della stessa app di CD.

Se l’utente è censito nel sistema pagoPA potrà trovare nell’app lo storico di
alcune delle transazioni effettuate e le relative ricevute anche prima
dell’attivazione di CD.

L’utente in CD potrà salvare e gestire i metodi di pagamento previsti dal
sistema PagoPA.

## Documenti

La sezione documenti consente all’utente di tenere raccolti e da lui
organizzati dentro CD tutti i documenti che gli sono stati inviati o messi a
disposizione dagli Enti Erogatori.

I documenti saranno filtrabili e ricercabili secondo una serie di parametri
descritti dalle specifiche tecniche di CD, quali ad esempio data, tipologia,
titolo, descrizione, etc.

Gli Enti Erogatori dovranno mettere a disposizione, oltre al documento, il set
di metadati che consentono una corretta indicizzazione e ricerca sul documento,
come descritto nelle specifiche tecniche di CD per le quali si rinvia
all’allegato tecnico.

I documenti (ad esempio: certificati) che non sono disponibili potranno essere
richiesti direttamente dall’utente all’interno di CD, a condizione che il
processo di definizione delle caratteristiche del documento stesso consentano
una esperienza d’uso semplice e adatta ad un dispositivo mobile.

Gli Enti Erogatori dovranno semplificare il più possibile il processo di
generazione del documento o del certificato, così da renderlo compatibile con la
richiesta e la distribuzione tramite CD, e dovranno censire nel sistema CD i
documenti che sono in grado di erogare attraverso il sistema stesso.

Eventuali costi associati alla generazione di alcuni di questi documenti e
certificati (come, ad esempio, marche da bollo e/o diritti di segreteria)
potranno essere sostenuti direttamente attraverso le funzioni di pagamento
disponibili nella sezione portafoglio di CD.

Tutti i documenti erogati dagli Enti Erogatori devono essere in formato
digitale, devono avere il set di metadati descritto nelle specifiche tecniche
di CD, e devono essere resi disponibili, altresì, in modo da garantire per
l’utente l’esperienza qui sopra descritta.

A titolo di esempio, si segnala l’integrazione con ANPR (Anagrafe Nazionale
della Popolazione Residente), che consentirà di inoltrare la richiesta di un
certificato anagrafico ai comuni già integrati con ANPR, ottenendo da essi il
certificato richiesto direttamente con l’applicazione di CD.

## Preferenze

La sezione preferenze consente all’utente di impostare quelle scelte di
carattere generale che risultano trasversali all’erogazione dei servizi da
parte della pubblica amministrazione. Alcune di queste scelte, una volta
inserite dall’utente potranno essere interrogate e utilizzate in tempo reale
dagli Enti Erogatori che aderiscono a CD.

Di seguito, si riportano a titolo di esempio alcune preferenze che potranno
essere definite dell’utente:

* Lingua, da scegliere tra italiano, inglese o tedesco (interrogabile);
* email personale dell’utente;
* elenco dei servizi che l’utente può attivare e relativa modalità di recapito
  da scegliere tra messaggio sull’applicazione mobile, notifica push sul
  cellulare, messaggio email;
* elezione, modifica o disattivazione del domicilio digitale dell’utente
  (interrogabile).

A ciascun Ente Erogatore sarà chiesto di fornire un insieme base di
informazioni che comporranno una scheda ente e un equivalente insieme di
informazioni base per ciascuno dei servizi che usano le funzioni di CD. Queste
informazioni potranno essere esposte in CD all’interno di una sezione dedicata
a ciascun ente/servizio, collegata alle preferenze di quel servizio stesso.

Con riferimento alla selezione delle preferenze, appare opportuno segnalare che:

* La selezione da parte dell’utente del servizio di inbox, determina l’invio
  da parte degli Enti Erogatori di un messaggio di notifica al cittadino che
  genera la presenza del messaggio nella schermata Messaggi dell’applicazione
  mobile di CD sullo smartphone dell’utente;
* la selezione da parte dell’utente del servizio di ricezione via email,
  determina l’invio da parte degli Enti Erogatori di un messaggio di notifica
  al cittadino che genera una email ricevuta nella casella di posta indicata
  dall’utente;
* la selezione da parte dell’utente del servizio di notifica push, determina
  l’invio da parte degli Enti Erogatori di un messaggio di notifica push sullo
  smartphone indicato dall’utente.

## Profilo

La sezione Pprofilo, che sarà disponibile anche tramite browser web, consente
all’utente di avere un riepilogo delle informazioni più tipicamente legate alla
propria identità.

In questa sezione, infatti, l’utente potrà accedere e
verificare i dati anagrafici acquisiti da CD tramite il login effettuato con
SPID.

L’eventuale aggiornamento di dati anagrafici in CD non verrà propagato agli
Identity Provider SPID.

Nella stessa sezione Profilo l’utente potrà gestire eventuali strumenti
complementari di identificazione e sicurezza quali PIN o, se abilitati
dall’utente sul proprio dispositivo, strumenti di identificazione biometrica, e
potrà interrompere la sessione attualmente attiva sull’applicazione (logout).

Nella sezione profilo l’utente potrà vedere le proprie informazioni anagrafiche
messegli a disposizione tramite un’integrazione con ANPR, a condizione
che il Comune di residenza dell’utente sia già subentrato in ANPR.

Nella sezione profilo l’utente potrà inoltre:

* verificare i termini e condizioni d’uso del servizio in vigore;
* consultare le informative sul trattamento dei dati personali degli Enti Erogatori e una breve informativa relativa a CD;
* chiedere la sospensione dell’account o la completa cancellazione dello stesso.

# Motivazioni alla base della valutazione d'impatto

## Gestione di dati personali

Tramite le funzionalità dei Messaggi e Documenti, la piattaforma informatica di
CD tratterà documenti personali e messaggi di cortesia equiparabili a messaggi
di posta elettronica. Inoltre, per quanto riguarda la funzionalità di Profilo,
la piattaforma informatica di CD tratterà metadati relativi ai servizi ed
Enti Erogatori da cui un cittadino a ricevuto messaggi di cortesia e avvisi di
pagamento.

## Trattamento di dati su larga scala

L'obiettivo di CD è quello di fornire un servizio a tutta la popolazione
italiana dotata di account SPID. Si concretizza quindi lo scenario del
trattamento di dati su larga scala.[^largascala]

[^largascala]: Cfr. _Linee guida sui responsabili della protezione dei dati (RPD)_ del WP29 - 16/EN WP 243.

\pagebreak

# Descrizione dei flussi informativi {#descrizione-flussi-informativi}

<!--
**TODO**
The collection, use and deletion of personal data should be described here and it may also be useful to refer to a flow diagram or another way of explaining data flows. You should also say how many individuals are likely to be affected by the project.

Explain how information will be obtained, used, and retained – there may be several options to consider. This step can be based on, or form part of, a wider project plan.

1. This process can help to identify potential ‘function creep’ - unforeseen or unintended uses of the data (for example data sharing)
1. People who will be using the information are consulted on the practical implications.
1. Potential future uses of information are identified, even if they are not immediately necessary.

* The collection, use and deletion of personal data should be described here
* how information will be obtained, used, and retained
* You should also say how many individuals are likely to be affected

-->

## Funzionalità preferenze

Questa funzionalità ha lo scopo di gestire le preferenze del
cittadino all'interno di CD. Le preferenze associate ad ogni cittadino
(Tabella \vref{tabella-preferenze}) guidano
molte delle logiche implementate in CD.
Inoltre alcune preferenze (dette pubbliche) vengono
condivise con gli Enti Erogatori allo scopo di essere utilizzate per la
personalizzazione dei servizi forniti da essi.

Table: Preferenze associate al cittadino.\label{tabella-preferenze}

Preferenza                            Provenienza         Pubblica?     Uso
-----------                           ------------        ----------    ----
Lingue preferite                      APP                 SI            UI e messaggi multilingua
Casella dei messaggi?[^pref-bool]     APP                 NO            Messaggi
Notifiche push?                       APP                 NO            Messaggi
Servizi abilitati?                    APP                 NO            Messaggi
Indirizzo email                       SPID                NO            Messaggi
Storico accessi                       Backend app         NO            Profilo

[^pref-bool]: Le preferenze nella forma di domanda sono preferenze di abilitazione (booleani).

Nel database delle preferenze vengono mantenute le informazioni descritte nella
Tabella \vref{tabella-preferenze} per ogni cittadino che si registra a CD e fino
a quando il cittadino non fa richiesta di rimozione dei suoi dati. Le preferenze
sono associate al cittadino usando il codice fiscale[^cf-chiave-primaria] come chiave primaria.

[^cf-chiave-primaria]: Potremmo anche usare la hash del codice fiscale.

### Creazione del profilo \label{scenario-creazione-profilo}

La creazione del profilo del cittadino (che contiene le preferenze), avviene
al primo accesso del cittadino all'APP tramite SPID.

Il flusso di creazione del profilo (Figura \vref{figura-profilo-creazione}) è il seguente:

1. Il cittadino apre l'APP e inizia il processo di autenticazione SPID
2. L'APP redirige il cittadino sull'IdP prescelto e il cittadino inserisce
   le credenziali di accesso.
3. Ad autenticazione avvenuta, l'IdP invia gli attributi SPID al backend
   dell'APP (che nel flusso di autenticazione SPID svolge il ruolo di
   _service provider_.
4. Il backend dell'APP invia gli attributi SPID alle API di gestione preferenze
   di CD, che li salva nel database delle preferenze.
5. L'app genera un identificativo di installazione univoco che viene comunicato
   al servizio di invio delle _notifiche push_, associandolo alla hash _SHA256_
   [^sha256] del codice fiscale del cittadino.

![Flusso di creazione del profilo del cittadino al primo accesso.\label{figura-profilo-creazione}](diagrams/profilo-creazione.svg)

[^sha256]: <https://en.wikipedia.org/wiki/SHA-2>

### Lettura delle preferenze pubbliche da parte dell'ente

Come descritto nella Tabella \vref{tabella-preferenze}, alcune preferenze vengono
definite _pubbliche_ e vengono condivise con gli enti che ne fanno richiesta.
Queste preferenze non contengono informazioni personali o sensibili ma sono
assimilabili a semplici indicazioni che il cittadino vuole condividere con gli
enti per essere usate come base per la personalizzazione dei servizi digitali.

Un servizio digitale fornito dall'ente al cittadino può interrogare le preferenze
pubbliche del cittadino sulla base del codice fiscale dello stesso e usare
le informazioni ottenute per fornire un servizio personalizzato, ad esempio
traducendo l'interfaccia utente del servizio fornito al cittadino sulla base
della preferenza di lingua.

La funzione Preferenze può inoltre essere utilizzata dal servizio dell'ente
per sapere se il cittadino non intende ricevere comunicazioni dal servizio.
Questa verifica è richiesta all'ente, prima dell'invio di una comunicazione
al cittadino attraverso la funzione Messaggi, secondo lo schema in Tabella
\vref{table-verifica-optout}.

Table: Verifica da parte del servizio del permesso di comunicare col cittadino.\label{table-verifica-optout}

Cit. iscritto a CD?       Opt-out al servizio?      Servizio può inviare messaggio?
--------------------      ---------------------     --------------------------------
NO                        /                         _Solo se censito indirizzo email_
SI                        NO                        **SI**
SI                        SI                        NO

\pagebreak

## Funzionalità Messaggi

La funzionalità Messaggi fornisce il servizio che permette agli Enti Erogatori
di inviare comunicazioni di cortesia e avvisi di pagamento ai cittadini.

Le comunicazioni di cortesia sono sempre inviate ad uno specifico cittadino
(identificato tramite codice fiscale) e scaturiscono da una pregressa
relazione individuale tra l'Ente e il cittadino. Da queste comunicazioni sono
quindi escluse comunicazioni non personali (_broadcast_). Si veda l'allegato
tecnico per alcuni esempi di tipologie di messaggi coperte
da questo servizio (Tabella \vref{tabella-esempi-messaggi}).

Quando l'Ente Erogatore invia un messaggio, comunica a CD i seguenti dati:

* **Identificativo del servizio** che ha generato il messaggio (es. servizio
  anagrafe).
* **Codice Fiscale** del cittadino a cui recapitare il messaggio.
* **Oggetto** del messaggio.
* **Contenuto** del messaggio.
* **Indirizzo email di default** del cittadino a cui inviare la comunicazione (opzionale,
  da usare nel caso il cittadino non abbia già un profilo su CD, vedere
  § \vref{scenario-messaggio-default_email-noprofile}).
* **Data** associata al messaggio (opzionale, nel caso si tratti di una
  scadenza).
* **Identificativo Unico di Versamento** (opzionale, nel caso si tratti di un
  avviso di pagamento).

Una volta ricevute queste informazioni, il servizio Messaggi di CD esegue delle
logiche di gestione del dato che variano a seconda della tipologia di messaggio
e della configurazione delle preferenze del cittadino a cui è indirizzato lo
stesso.

Possiamo classificare i possibili scenari in due macro gruppi:

1. La gestione del messaggio quando il cittadino destinatario NON ha ancora
   effettuato il primo accesso all'applicazione di CD;
1. La gestione del messaggio quando il cittadino destinatario ha già effettuato
   il primo accesso all'applicazione di CD.

Questa distinzione è importante poichè quando il cittadino non ha ancora
effettuato il primo accesso all'applicazione di CD, non esiste ancora un suo
profilo nel sistema e la funzionalità di invio messaggi di CD è equiparabile ad
un servizio di email transazionale.[^cosa-email-transazionale]

Prima di inviare una comunicazione al cittadino tramite la funzionalità
Messaggi, il servizio è tenuto a verificare la disponibilità del cittadino a
ricevere la comunicazione (come descritto precedentemente nella Tabella
\vref{table-verifica-optout}).

[^cosa-email-transazionale]: si veda per esempio il servizio
  [MailUP](https://www.mailup.it/funzionalita/email/smtp/) usato da molte
  Pubbliche Amministrazioni per l'invio di avvisi di cortesia via email ai
  cittadini.

### Invio di messaggi a cittadini senza un profilo CD

Nei seguenti scenari, il cittadino destinatario del messaggio non si è ancora
iscritto al servizio di Cittadinanza Digitale.

#### Scenario in cui il cittadino ha fornito all'Ente il proprio indirizzo email \label{scenario-messaggio-default_email-noprofile}

In questo scenario (Figura \vref{figura-messaggio-default_email-noprofile}), il
cittadino si è precedentemente accreditato presso il servizio dell'ente che
intende inviare il messaggio. Il cittadino ha quindi fornito il proprio indirizzo
email ed ha acconsentito l'ente a contattarlo per comunicazioni inerenti
al servizio d'interesse.

Il flusso dati è il seguente:

1. Il cittadino fornisce all'Ente Erogatore il proprio indirizzo email.
2. Quando il servizio dell'Ente Erogatore intende comunicare al cittadino,
   recupera l'indirizzo email di recapito dal propdio database di contatti.
3. Il servizio dell'Ente Erogatore invia (tramite le API Messaggi) il messaggio
   da recapitare al cittadino, con associato l'indizzo email fornitogli.
4. La logica delle API messaggi, non trovando le preferenze del cittadino nel
   proprio database (siamo nello scenatio di cittadini senza profilo CD),
   utilizza l'indirizzo email fornitogli dall'Ente Erogatore per recapitare
   il messaggio via email tramite uno dei servizi di invio email transazionale
   utilizzati da CD.
5. Il servizio di invio email transazionale invia l'email con il messaggio al
   fornitore email del cittadino.
6. Il cittadino trova il messaggio nella sua casella di posta.

![Flusso di invio messaggio quando l'Ente fornisce l'indirizzo email.\label{figura-messaggio-default_email-noprofile}](diagrams/messaggio-default_email-noprofile.svg)

#### Scenario in cui il cittadino non ha fornito all'Ente il proprio indirizzo email

In questo scenario (Figura \vref{figura-messaggio-noprofile}), il
cittadino non si è precedentemente accreditato presso il servizio dell'ente che
intende inviare il messaggio. Il servizio quindi tenta di inviare il messaggio
tramite il servizio Messaggi fornendo solo il codice fiscale del destinatario,
contando sul fatto che il destinatario possa aver espresso delle preferenze di
contatto nel suo profilo di CD. In questo caso però, il cittadino destinatario
del messaggio non si è ancora iscritto al servizio di Cittadinanza Digitale,
quindi il messaggio viene ignorato.

1. Il servizio dell'Ente Erogatore invia (tramite le API Messaggi) il messaggio
   da recapitare al cittadino.
2. L'API messaggi, non avendo preferenze di contatto per il cittadino
   destinatario, ignora il messaggio.

![Flusso di in cui il messaggio non viene recapitato.\label{figura-messaggio-noprofile}](diagrams/messaggio-noprofile.svg)

### Invio di messaggi a cittadini con un profilo CD {#invio-messaggio-profilo}

Quando il cittadino accede per la prima volta, attraverso SPID, all'app di CD,
viene creato un profilo di preferenze dentro CD associato al codice fiscale del
cittadino (§ \vref{scenario-creazione-profilo}). Gli scenari seguenti assumono
quindi l'esistenza di un profilo contente le preferenze del cittadino.

I seguenti scenari non sono mutuamente esclusivi e possono concretizzarsi
contemporaneamente all'invio di un messaggio, a seconda delle preferenze
espresse dal cittadino.

A tutti gli scenari viene applicato un filtro alla ricezione del messaggio che
verifica che il servizio mittente sia stato abilitato dal cittadino (preferenza
_Servizi abilitati_). Nel caso in cui il servizio non sia stato abilitato dal
cittadino, il messaggio viene scartato immediatamente.

#### Scenario in cui il cittadino ha abilitato la casella dei messaggi

La casella dei messaggi è un database che, se abilitato dal cittadino, archivia
i messaggi inviati dagli enti al cittadino stesso. Un messaggio archiviato nella
casella dei messaggi contiene i seguenti dati:

* **Identificativo del servizio** che ha generato il messaggio.
* **Oggetto** del messaggio.
* **Contenuto** del messaggio.
* **Data** associata al messaggio (se presente).
* **Identificativo Unico di Versamento** (se presente).

Nel caso in cui il cittadino abbia abilitato la casella dei messaggi nelle
proprie preferenze, all'invio di un messaggio da parte dell'ente avvengono i
seguenti passaggi (Figura \vref{figura-messaggio-profile-inbox}):

1. Il servizio dell'ente invia al servizio messaggi un messaggio associato al
   codice fiscale del cittadino.
2. Il servizio messaggi recupera le preferenze del cittadino destinatario.
3. Tra le preferenze troverà l'abilitazione della casella dei messaggi e
   procederà quindi a salvare il contenuto del messaggio nel database dei
   messaggi.
4. Quando il cittadino apre l'app nella schermata dei Messaggi, l'app farà una
   richiesta per ottenere il contenuto dei messaggi al backend dell'app.
5. Il backend dell'app farà a sua volta una richiesta al servizio Messaggi,
   ottenendo il contenuto dei messaggi ed il relativo mittente.
6. Il cittadino visualizza il contenuto dei messaggi nell'app.

Si noti che i passi 4-6 possono avvenire in un momento diverso rispetto
all'invio del messaggio da parte del servizio.

![Flusso di salvataggio del messaggio nel database dei messaggi.\label{figura-messaggio-profile-inbox}](diagrams/messaggio-profile-inbox.svg)

#### Scenario in cui il cittadino ha abilitato l'invio di email

Nel caso in cui il cittadino abbia abilitato il canale email nelle
proprie preferenze, avvengono i seguenti passaggi
(Figura \vref{figura-messaggio-profile-email}):

1. Il servizio dell'ente invia al servizio messaggi un messaggio associato al
   codice fiscale del cittadino.
2. Il servizio messaggi recupera le preferenze del cittadino destinatario,
   tra le quali troverà l'abilitazione alla notifica via email con
   associato l'indirizzo email su cui il cittadino vuole essere contattato.
3. Il servizio Messaggi invia il messaggio all'indirizzo email traimte uno dei
   servizi di invio email transazionale a disposizione.
4. Il servizio di invio email transazionali recapita il messaggio nella casella
   di posta elettronica del cittadino.
5. Il cittadino visualizza il contenuto del messaggi nel suo client di posta
   elettronica.

![Flusso di recapitato del messaggio all'indirizzo impostato nelle preferenze.\label{figura-messaggio-profile-email}](diagrams/messaggio-profile-email.svg)

#### Scenario in cui il cittadino ha abilitato l'invio di notifiche push all'app

Nel caso in cui il cittadino abbia abilitato l'invio di notifiche push nelle
proprie preferenze, avvengono i seguenti passaggi
(Figura \vref{figura-messaggio-profile-push}):

1. Il servizio dell'ente invia al servizio messaggi un messaggio associato al
   codice fiscale del cittadino.
2. Il servizio messaggi recupera le preferenze del cittadino destinatario.
3. Tra le preferenze troverà l'abilitazione della casella dei messaggi e delle
   notifiche push[^preferenze-notifiche-casella] e procederà quindi a salvare
   il contenuto del messaggio nel database dei messaggi.
4. Il servizio Messaggi invierà una notifica al backend dell'app, avvertendolo
   che è necessario inviare una notifica push all'app perché un nuovo messaggio
   è disponibile nella casella dei messaggi.
5. Il backend dell'app istruisce il servizio di invio di notifiche push ad
   inviare una notifica push all'app associata alla hash del codice fiscale.[^notifica-hash-cf]
6. Il servizio di notifica push invia una notifica all'app.[^notifica-ios-android]
7. Alla ricezione della notifica, quando il cittadino apre l'app, l'app farà una
   richiesta per ottenere il contenuto dei messaggi al backend dell'app. Il backend dell'app farà a sua volta una richiesta al servizio Messaggi,
   ottenendo il contenuto dei messaggi ed il relativo mittente.
8. Il cittadino visualizza il contenuto dei messaggi nell'app.

![Flusso di notifica push sull'app.\label{figura-messaggio-profile-push}](diagrams/messaggio-profile-push.svg)

[^preferenze-notifiche-casella]: L'invio delle notifiche push sull'app richiede che sia abilitata la casella dei messaggi, per permettere all'app di recuperare il contenuto del messaggio (che non viene inviato tramite la notifica push).

[^notifica-hash-cf]: Utilizziamo la hash del codice fiscale in modo che il dato in chiaro del codice fiscale del cittadino non venga salvato nel database del servizio di invio notifiche push (in questo modo il codice fiscale viene pseudoanonimizzato).

[^notifica-ios-android]: La notifica viene inoltrata ai servizi di notifica di Google o di Apple a seconda della tipologia di device su cui è stata installata l'app.

\pagebreak

## Funzionalità Portafoglio

La funzionalità _Portafoglio_ fornisce la possibilità di pagare tributi tramite
gli strumenti di pagamento forniti da pagoPA.

Nel contesto delle funzionalità di pagamento, consideriamo due macro flussi:

* La gestione preferenze di pagamento del cittadino (es. aggiunta di una carta
di credito).
* Il flusso di pagamento (es. da un avviso di pagamento digitale).

### Gestione preferenze di pagamento

Il flusso di pagamento prevede che il cittadino abbia preimpostati nel suo
portafoglio dei metodi di pagamento validi (es. carta di credito) da poter
utilizzare per effettuare il pagamento del tributo.

Attualmente la funzionalità portafoglio è progettata per gestire pagamenti
tramite carta di credito.

Le informazioni sui metodi di pagamento vengono gestite attraverso la componente
_Wallet_ di PagoPA che si occupa della gestione sicura delle informazioni
sensibili (es. dati della carta di credito).

#### Inserimento dati della carta di credito

L'inserimento dei dati della carta dicredito nell'app avviene attraverso una
componente applicativa (SDK) fornita e certificata da SIA SpA che permette di
presentare all'utente una form di inserimento, che comunica in modo sicuro
con il Wallet di PagoPA. I dati della carta di credito inseriti dall'utente
vengono inviati direttamente al sistema PagoPA senza passare dal sistema di CD.

Una volta salvati, i dati della carta di credito vengono associati ad un
identificativo numerico non correlato con il numero di carta di credito
(identificativo dello strumento di pagamento).

L'identificativo dello strumento di pagamento viene fornito all'app e utilizzato
nella scelta del metodo di pagamento durante il flusso di pagamento.

#### Riconciliazione profilo CD e profilo pagoPA

Le preferenze di pagamento gestite dal Wattet di PagoPA vengono associate ad
un indirizzo email, si richiede quindi un meccanismo di riconciliazione tra
i profili dei cittadini registrati sul Wallet e i cittadini che accedono
all'app di CD.

Questo meccanismo di riconciliazione si basa sull'indirizzo email fornito
dal cittadino sotto forma di attributo SPID.

Si delineano quindi due scenari in base alla presenza o meno di un profilo
nel Wallet di PagoPA corrispondente all'email associata all'account SPID
del cittadino.

##### Profilo Wallet presente

Nel caso sia presente nel Wallet, un profilo associato all'email del cittadino,
le interazioni con il Wallet attraverso l'app verranno resistrate esattamente
come se avvenissero da una qualsiasi app che integra l'SDK di PagoPA.

Questo meccanismo permette al cittadino di riutilizzare il suo profilo PagoPA
dall'APP IO in modo totalmente trasparente.

##### Profilo Wallet non presente

Nel caso non sia presente nel Wallet, un profilo associato all'email del cittadino,
il Wallet provvederà a creare un nuovo profilo [^wallet-nuovo-profilo]
all'inserimento del primo metodo di pagamento. Tutte le operazioni successive
ricadono nel caso precedente.

[^wallet-nuovo-profilo]: Flusso ancora da formalizzare.

### Pagamento

Il flusso di pagamento può scaturire da un avviso di pagamento digitale
(ricevuto quindi attraverso la funzionalità Messaggi) o da un avviso di
pagamento cartaceo (che fornisce un codice di pagamento numerico o tramite
un QR code).

#### Avvisi di pagamento digitali {#avvisi-pagamento-digitali}

Per l'invio di un avviso di pagamento digitale ad un cittadino da parte di un
servizio, viene usato il meccanismo dell'invio di un messaggio tramite l'API
Messaggi di CD (§ \ref{invio-messaggio-profilo}). In questo caso, oltre
all'oggetto ed al contenuto del messaggio vengono forniti dal servizio:

* **Numero Avviso**: si tratta di un codice numerico che identifica
  univocamente la posizione debitoria presso l'ente. [^pagopa-numero-avviso]
* **Ammontare**: l'ammontare della posizione debitoria in centesimi di Euro.[^nota-ammontare-attualizzare]

[^pagopa-numero-avviso]: Il numero avviso segue il formato
  `<cifra ausiliaria (1n)>[<codice applicativo> (2n)]<codice IUV (15|17n)>` -
  riferimento: <https://pagopa-specifichepagamenti.readthedocs.io/it/latest/_docs/Capitolo7.html>
[^nota-ammontare-attualizzare]: L'ammontare viene visualizzato all'interno
  dell'applicazione di CD insieme al messaggio e viene successivamente
  attualizzato all'atto del pagamento (§ \ref{pagopa-verifica-attualizzazione}).

#### Avvisi di pagamento cartaceo

Per quanto riguarda il pagamento di avvisi di pagamento cartacei, il cittadino
potrà effettuare il pagamento leggendo il codice QR [^avviso-codice-qr] stampato sull'avviso o
inserendo manualmente il Numero Avviso stampato anch'esso sull'avviso.

[^avviso-codice-qr]: Il codice QR stampato sull'avviso contiene il Numero Avviso.

#### Verifica e attualizzazione{#pagopa-verifica-attualizzazione}

Il flusso di verifica ed attualizzazione dell'avviso di pagamento viene iniziato
dall'app ogni volta che viene presentato l'ammontare attualizzato corrispondente
all'avviso di pagamento (tipicamente questo avviene come primo passo del
flusso di pagamento di un avviso).

Questo flusso prevede l'interazione con il nodo PagoPA attraverso il backend
dell'app secondo il diagramma in Figura \vref{figura-flusso-pagopa-verifica}.

![Flusso di verifica ed attualizzazione di un avviso di pagamento.\label{figura-flusso-pagopa-verifica}](diagrams/flusso-pagopa-verifica.svg)

#### Transazione

Il flusso di pagamento viene iniziato dall'app ed è composto da due fasi
distinte (Figura \vref{figura-flusso-pagopa-attiva}):

* Passi 1-3: l'app interagisce con il nodo PagoPA attraverso il backend per ottenere
  l'identificativo di pagamento associato all'avviso di pagamento.
* Passo 4: l'app interagisce con il Wallet per eseguire la transazione di pagamento
  a partire dall'identificativo ottenuto al passo precedente.

![Flusso di pagamento.\label{figura-flusso-pagopa-attiva}](diagrams/flusso-pagopa-attiva.svg)

#### Ricevuta di pagamento

Dopo che la transazione di pagamento dell'avviso viene ricevuta dal Wallet,
l'app interagisce nuovamente con il Wallet per recuperare lo storico delle
transazioni. Lo storico conterrà l'esito della transazione appena eseguita,
sotto forma di ricevuta di pagamento da presentare al cittadino.

\pagebreak

## Funzionalità Documenti

### Avviso disponibilità documento

### Visualizzazione documento

\pagebreak

# Processo di analisi

<!--
**TODO**
Explain what practical steps you will take to ensure that you identify and address privacy risks.
Who should be consulted, internally and externally?
How will you carry out the consultation?
You should link this to the relevant stages of your project management process.
Consultation can be used at any stage of the PIA process.
-->

Nel processo di analisi, andiamo a valutare il rischio per le persone fisiche,
(nel nostro caso i cittadini destinatari delle comunicazioni da parte degli
Enti Erogatori di servizi).

Altri rischi che si applicano all'organizzazione, ma che non incidono sulla
privacy, sono fuori portata. Ciò che è nel campo di applicazione di questa
analisi sono i rischi che potrebbero comportare danni fisici, materiali o
immateriali all'interessato, comprese eventuali discriminazioni, danni alla
reputazione, perdita di riservatezza dei dati protetti dal segreto professionale
o qualsiasi altro significativo svantaggio economico o sociale.

Nella nostra analisi, tutti i rischi sono associati ad una **probabilità**:

Probabile
  ~ Forte (alta) possibilità che lo scenario documentato possa
  verificarsi. Di tanto in tanto si verificano rischi elevati, ad esempio guasti
  alle apparecchiature in una situazione in cui non è prevista alcuna ridondanza.

Possibile
  ~ Possibilità media (neutra) che lo scenario documentato possa verificarsi.

Improbabile
  ~ Lo scenario è improbabile - non dovrebbe accadere più spesso di
  una volta in un decennio o meno.

Infine rischi sono anche associati ad un livello di **gravità**:

Critica
  ~ Vi è un danno significativo e reale a un gran numero di soggetti dei dati,
  ad esempio una violazione dei dati su larga scala.

Grave
  ~ Vi è un danno significativo e reale a uno o un numero limitato di soggetti
  dei dati o un danno minore a un gran numero di soggetti dei dati.

Moderata
  ~ Problema minore o procedurale che non comporta danni significativi.

\pagebreak

# Analisi dei rischi legati ai dati personali

<!--

**TODO**
Identify the key privacy risks and the associated compliance and corporate risks.

Record the risks to individuals, including possible intrusions on privacy where appropriate.

1. Assess the corporate risks, including regulatory action, reputational damage, and loss of public trust.
1. Conduct a compliance check against the Data Protection Act and other relevant legislation.
1. Maintain a record of the identified risks.
1. The process helps an organisation to understand the likelihood
   and severity of privacy risks.
1. An organisation is open with itself about risks and potential changes to a project.
-->

Prima di analizzare i rischi in dettaglio, dobbiamo considerare i possibili
scenari di rischio alla privacy dal punto di vista del soggetto interessato.

Di seguito elenchiamo i possibili scenari, raggruppati per tipologia:

* Violazione di riservatezza e integrità:
  * Divulgazione di dati personali: un cittadino considererà le informazioni
    trasmesse dagli Enti Erogatori come confidenziali e potrebbe essere in
    difficoltà o subire danni alla reputazione se le informazioni
    trapelassero impropriamente.
  * Integrità dei dati personali: una cittadino sarebbe preoccupato se ricevesse
    informazioni destinate ad un altro cittadino o se le informazioni indirizzate
    a lui venissero modificate in modo improprio o errato.
* Perdita o non disponibilità di dati personali:
  * Perdita di dati personali: se un cittadino ricevesse delle informazioni da un
    Ente e successivamente queste informazioni andassero perse, il cittadino
    perderebbe fiducia nel servizio. Il cittadino sarebbe preoccupato che le
    informazioni che gli Enti Erogatori gli inviano siano archiviate in modo
    sicuro per tutto il tempo necessario.
* Impossibilità di esercitare i diritti secondo la legge sulla protezione dei dati personali:
  * Mancanza di capacità di esercitare i diritti previsti dalla legge sulla
    protezione dei dati: una persona interessata ha molti diritti in base alla
    legge sulla protezione dei dati e potrebbe essere preoccupata per esempio di
    non essere in grado di ottenere copie dei propri dati personali.
* Incorretta identificazione dei soggetti coinvolti nella trasmissione di dati personali:
  * Qualcuno effettua un pagamenti per una posizioni debitorie di cui non è
    responsabile: ...
  * Qualcuno invia una comunicazione per conto di un servizio: ...

Le seguenti sezioni trattano i rischi relativi a questi scenari.

<!--
### (Oggetto)

Possibile ● Grave

**Natura del rischio**

**TODO**

**Misure atte a mitigare o prevenire il rischio**

**TODO**

**Efficacia delle misure**

is the risk eliminated, reduced, or accepted?

**Stato di approvazione e implementazione**

**TODO**

-->

## Rischi legati alla violazione di riservatezza e integrità di dati personali

Rischio                                 Probabilità   Gravità   Misure
--------                                ------------  --------  -------
\ref{r-intercettazione-api-gw-cd}       Possibile     Grave     Si
\ref{r-intercettazione-be-pagopa}       Probabile     Critica   Si
\ref{r-accesso-fisico}                  Improbabile   Critica   Si
\ref{r-vulnerabilita}                   Improbabile   Critica   Si
\ref{r-account-compromise}              Possibile     Critica   No

### Intercettazione della trasmissione tra le componenti esterne ed interne {#r-intercettazione-api-gw-cd}

**Natura del rischio**

Durante la trasmissione dei messaggi indirizzati ad un cittadino da parte
degli Enti Erogatori verso le API di CD, vi è la possibilità che il contenuto
della trasmissione possa essere intercettato tramite tecniche di intercettazione
passiva (_sniffing_[^sniffing]) o attacchi di tipo _man in the middle_.[^man-in-the-middle]

[^sniffing]: <https://it.wikipedia.org/wiki/Sniffing>

[^man-in-the-middle]: <https://it.wikipedia.org/wiki/Attacco_man_in_the_middle>

**Misure atte a mitigare o prevenire il rischio**

Tutte le trasmissioni tra le componenti esterne e interne di Cittadinanza Digitale
vengono criptate con il protocollo di trasporto di dati TLS 1.0 o superiore.[^transport-layer-security]

[^transport-layer-security]: <https://it.wikipedia.org/wiki/Transport_Layer_Security>

**Efficacia delle misure**

Il rischio è stato eliminato.

**Stato di approvazione e implementazione**

Il protocollo TLS è implementato:

* nelle trasmissioni verso l'API Gateway
* nelle trasmissioni verso il backend dell'app
* nelle trasmissioni verso il Wallet PagoPA

Si faccia riferimento al diagramma architetturale in figura \vref{figura-infrastruttura-rete}.

### Intercettazione della trasmissione tra il backend dell'app e il nodo PagoPA {#r-intercettazione-be-pagopa}

**Natura del rischio**

La medesima del rischio § \vref{intercettazione-api-gw-cd}.

**Misure atte a mitigare o prevenire il rischio**

Il backend dell'app e il nodo PagoPA comunicano attraverso un collegamento VPN
punto-punto criptato con le migliori pratiche di sicurezza[^vpn-pagopa] (Figura \vref{figura-infrastruttura-rete}).

[^vpn-pagopa]: algoritmo AES-256, chiave a 1024 bit, controllo d'integrità tramite hash SHA256 e _perfect forward secrecy_.

**Efficacia delle misure**

Il rischio è stato eliminato.

**Stato di approvazione e implementazione**

Il collegamento VPN è attualmente attivo.

### Accesso fisico ai dati archiviati nei server di Cittadinanza Digitale {#r-accesso-fisico}

**Natura del rischio**

Un attore malevolo che abbia accesso fisico ai server di Cittadinanza Digitale
dove risiedono i dati personali dei cittadini avrebbe la possibilità di
estrarre i dati dai server, provocando un _data breach_.

**Misure atte a mitigare o prevenire il rischio**

Il software applicativo di backend di Cittadinanza Digitale viene eseguito su
infrastruttura cloud Microsoft Azure.

Tutti i datacenter Microsoft Azure implementano meccanismi di controllo della
sicurezza allo stato dell'arte: sorveglianza 24x7x365, protezioni ambientali e
perimetrali e policy di accesso estese a tutto il personale.

Per maggiori dettagli si faccia riferimento al documento
_Microsoft Azure Security Overview_. [^azure-security-overview]

[^azure-security-overview]: <http://go.microsoft.com/?linkid=9740388>

**Efficacia delle misure**

Il rischio è stato ridotto.

**Stato di approvazione e implementazione**

Il software applicativo ed i dati sono attualmente ospitati nell'infrastruttura
cloud Microsoft Azure.

### Sfruttamento di vulnerabilità o malware per estrarre dati personali (_data breach_) {#r-vulnerabilita}

**Natura del rischio**

Vulnerabilità software, sistemi non aggiornati o malware possono essere sfruttati
da un attore malevolo per ottenere un accesso non autorizzato ai sistemi ed
estrarre dati personali di molti utenti (_data breach_).

**Misure atte a mitigare o prevenire il rischio**

TODO

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

TODO

### Un account amministrativo dell'infrastruttura viene compromesso {#r-account-compromise}

**Natura del rischio**

Le credenziali di un account di administratore vengono compromesse (rivelate
tramite forza bruta o ottenute con un attacco di phishing), garantendo
l'accesso ai dati di tutti i cittadini presenti nell'infrastruttura applicativa.

**Misure atte a mitigare o prevenire il rischio**

* Training del personale su sicurezza e attachi di phishing
* Limitare lo scope delle credenziali
* Autenticazione multi-fattore

**Efficacia delle misure**

Il rischio è ridotto.

**Stato di approvazione e implementazione**

\fcolorbox{red}{white}{Attualmente nessuna misura è stata implementata}

\pagebreak

## Rischi legati alla perdita o non disponibilità di dati personali

Rischio                                 Probabilità   Gravità   Misure
--------                                ------------  --------  -------
\ref{r-data-loss}                       Improbabile   Grave     Parziali
\ref{r-availability}                    Probabile     Moderata  Parziali
\ref{r-interruption}                    Probabile     Moderata  Parziali

### Perdita parziale o totale dei dati archiviati {#r-data-loss}

**Natura del rischio**

A causa di problemi all'hardware o al software dell'infrastruttura applicativa
una porzione di dati personali potrebbe andare persa, in particolare:

* Preferenze del cittadino
* Messaggi ricevuti dalle pubbliche amministrazioni

**Misure atte a mitigare o prevenire il rischio**

TODO

Per quanto riguarda fault hardware:

* Storage ridondato geograficamente

Per quanto riguarda fault software:

* repliche append-only
* backup giornalieri offsite
* restore test periodici

* backup periodico del database tramite snapshot
  di cosmosdb su un json nel blob storage
* storage dei log delle transazioni effettuate dall'ultimo snapshot

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### Problemi software o di rete impediscono l'accesso ai dati o operazioni sui dati {#r-availability}

**Natura del rischio**

La disponibilità dei servizi cloud infrastrutturali o la connettività di rete
viene temporaneamente interrotta risultando in un disservizio e
nell'impossibilità del cittadino di:

Per il cittadino:

* accedere ai propri dati
* ricevere informazioni da parte degli Enti
* effettuare pagamenti

Per l'Ente:

* inviare messaggi

**Misure atte a mitigare o prevenire il rischio**

TODO

* messaggi di alert in caso di downtime per ciascun ervizio PaaS utilizzato
* architettura ridondata multi-region / multi-az

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### Problemi software o di rete hanno l'effetto di interrompere o annullare le operazioni {#r-interruption}

**Natura del rischio**

Delle problematiche che possono sorgere durante un operazione effettuata dal
cittadino o dall'Ente (es. guasto hardware, interruzioni di rete, guasto software) possono
generare una perdita o una corruzione totale o parziale dei dati in transito e
la conseguente interruzione dell'operazione, costringendo il cittadino o l'Ente
a ripetere l'operazione.

**Misure atte a mitigare o prevenire il rischio**

TODO

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

\pagebreak

## Rischi legati all'incorretta identificazione dei soggetti coinvolti nella trasmissione di dati personali

Rischio                                 Probabilità   Gravità   Misure
--------                                ------------  --------  -------
\ref{r-service-id}                      Possibile     Critica   Parziali
\ref{r-api-id}                          Possibile     Critica   Parziali
\ref{r-cit-id}                          Possibile     Grave     Parziali

### Un attore malevolo impersona un Ente inviando illecitamente dati ai cittadini o accedendo ai messaggi inviati dall'Ente {#r-service-id}

**Natura del rischio**

TODO

**Misure atte a mitigare o prevenire il rischio**

TODO

* cifratura end to end dei messaggi
* restrizione sugli ip che possono accedere alle API

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### Un attore malevolo impersona le API di CD, intercettando i dati personali dei cittadini {#r-api-id}

**Natura del rischio**

TODO

**Misure atte a mitigare o prevenire il rischio**

TODO

* autenticazione server tramite certificato

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### Un attore malevolo impersona un cittadino accedendo ai suoi dati personali e compie operazioni a suo nome {#r-cit-id}

**Natura del rischio**

TODO

Se un attore malevolo riesce ad impersonare un cittadino, potrà:

* accedere a tutti i dati personali, email e preferenze del cittadino
* accedere a tutti i messaggi ricevuti dal cittadino
* effettuare pagamenti di avvisi (anche non indirizzati al cittadino) usando gli
  strumenti di pagamento salvato dal cittadino

**Misure atte a mitigare o prevenire il rischio**

TODO

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

\pagebreak

## Rischi legati all'impossibilità di esercitare i diritti secondo la legge sulla protezione dei dati personali

Rischio                                 Probabilità   Gravità   Misure
--------                                ------------  --------  -------
\ref{r-cit-data}                        Improbabile   Moderata  Parziali
\ref{r-processor-gdpr}                  Improbabile   Moderata  Parziali
\ref{r-data-retention}                  Improbabile   Moderata  Parziali

### Un cittadino non ha accesso a tutti i dati che CD ha raccolto su di lui {#r-cit-data}

**Natura del rischio**

TODO

**Misure atte a mitigare o prevenire il rischio**

TODO

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### I dati personali sono elaborati da entità non GDPR-compliant {#r-processor-gdpr}

**Natura del rischio**

TODO

**Misure atte a mitigare o prevenire il rischio**

TODO

* CD compliant con GDPR
* tutti service provider compliant

(aggiungere tabella)

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

### I dati personali sono archiviati oltre il tempo strettamente necessario {#r-data-retention}

**Natura del rischio**

TODO

**Misure atte a mitigare o prevenire il rischio**

TODO

* policy data retention

**Efficacia delle misure**

TODO

**Stato di approvazione e implementazione**

Implementazione parziale

\pagebreak

## Rischio residuo

TODO

------

\pagebreak

# Allegato tecnico

## Esempi di comunicazioni gestibili dal servizio Messaggi {#esempi-messaggi}

Table: Esempi di messaggi personalizzati.\label{tabella-esempi-messaggi}

Ente Erogatore                Oggetto
---------------               --------
Agenzia delle Entrate         Notifiche di cortesia cartelle esattoriali
Agenzia delle Entrate         Avvisi di cortesia scadenze
Agenzia delle Entrate         Visure catastali
Agenzia delle Entrate         Pagamento spese per immobili
Agenzia delle Entrate         Accredito rimborsi
Comune                        Avviso multa
Comune                        Avviso TARI
Comune                        Avviso scadenza rette scolastiche
Comune                        Mense scolastiche
Comune                        Scadenze documenti di identità
Comune                        Scadenza tessera elettorale
Ministero dei Trasporti       Scadenza revisione
Ministero dei Trasporti       Punti patente
Ministero dei Trasporti       Scadenza patente
ACI                           Bollo Auto

## Meccanismi di autenticazione

### Autenticazione app mobile

Il cittadino viene identificato dall'app di CD attraverso una combinazione di Autenticazione SPID e codice PIN.

I passi di autenticazione all'apertura dell'app comprendono
(Figura \vref{figura-flusso-autenticazione-app}):

* Verifica di una sessione attiva e valida con il backend dell'app.
* Autenticazione SPID Livello 2.
* Verifica ed accettazione della versione più recente dei termini d'uso del servizio e delle privacy policy.
* Impostazione e successiva verifica del codice PIN.

![Autenticazione utente nell'app.\label{figura-flusso-autenticazione-app}](diagrams/flusso-autenticazione-app.svg)

#### Autenticazione via PIN e Biometrico

Al fine di ottimizzare l'esperienza utente nell'applicazione mobile, al primo
accesso viene richiesto all'utente di impostare un codice PIN (ed opzionalmente
di configurare un codice di accesso biometrico se il dispositivo lo consente).

Nel caso in cui la sessione di autenticazione verso il backend dell'app è
ancora valida[^validita-sessione-backend], il codice PIN verrà richiesto
all'utente per sbloccare l'applicazione quando questa esce dal background.

[^validita-sessione-backend]: La durata del token di sessione è configurabile sul backend dell'app e attualmente è impostata a 30 giorni.

#### Autenticazione verso il backend dell'app {#autenticazione-app-backend}

L'app mantiene una sessione verso il backend creata al completamento con
successo dell'autenticazione SPID ma scollegata dalla sessione SPID che
l'utente stabilisce con l'Identity Provider.

Il flusso di autenticazione dell'app con il backend tramite la sessione è il
seguente:

1. L'utente inizia il processo di autenticazione SPID dall'interno dell'app.
1. Il backend da inizio al flusso di autenticazione SPID tramite l'Identity Provider (IdP)
   scelto dall'utente (Figura \vref{figura-flusso-autenticazione-app}).
1. Al termine del flusso di autenticazione SPID, il backend riceve l'asserzione
   SAML firmata dall'IdP e contente gli attributi SPID richiesti.
1. Gli attributi richiesti vengono salvati in un database locale ed associati
   al _token_ di sessione generato dal backend [^token-sessione] e condiviso con l'app.
1. L'app effettua una chiamata alle API del backend usando il _token_ di
   sessione come meccanismo di autenticazione _bearer_.[^autenticazione-bearer]
1. Il backend recupera gli attributi associati al _token_ ed esegue l'operazione
   richiesta, associandola all'utente SPID.
1. Se il _token_ risulta avere una vita superiore a quella limite, il backend
   risponderà all'app che il _token_ non è più valido e l'app chiederà
   all'utente di autenticarsi nuovamente con SPID.

[^token-sessione]: Il token di sessione è un numero casuale di 48 bytes
  generato da un algoritmo crittografico di generazione di dati pseudo-casuali -
  in particolaresi viene usata la funzione `randomBytes` della libreria `crypto`
  di Nodejs (<https://nodejs.org/api/crypto.html>).

[^autenticazione-bearer]: <https://swagger.io/docs/specification/authentication/bearer-authentication/>

#### Invalidazione delle sessioni attive

Per ottimizzare la privacy del cittadino, quando viene effettuata una nuova
autenticazione SPID dall'app e contestualmente creata una nuova sessione
(§ \ref{autenticazione-app-backend}), tutte le sessioni attive in quel momento
vengono annullate (comprese le sessioni verso il Wallet, § \ref{autenticazione-app-wallet}).

Il meccanismo di invalidazione delle sessioni dell'app, viene inoltre attivato
nel momento in cui un utente chiede la cancellazione del proprio account dalla
piattaforma CD.

### Autenticazione API CD

Tutti i servizi che interagiscono con le API di CD (inclusi i servizi forniti
dagli Enti Erogatori ed il backend dell'applicazione mobile di CD) si accreditano
sul portale degli sviluppatori di CD [^portale-dev-cd] ottenendo delle
credenziali (_chiave API_) per ogni servizio che viene registrato.
L'autenticazione delle chiamate alle API di CD
avviene quindi a livello di singolo servizio, permettendo a CD di applicare
delle policy di _throttling_ e di quota d'uso a livello di singolo servizio e,
in caso di abuso, disattivare l'accesso alle API da parte di un singolo servizio
erogato dall'ente.

L'accesso alle API di CD da parte dei servizi viene intermediato dal servizio
di _API Management_ (APIM) fornito da Azure [^apim-page] secondo il diagramma in
Figura \vref{figura-infrastruttura-apim}:

1. Il responsabile del servizio si accredita sul portale degli sviluppatori
   ricevendo la _chiave API_ per il servizio registrato. La _chiave API_ viene generata dal servizio di _API Management_ al momento della registrazione.
1. Il responsabile del servizio imposta la _chiave API_ nel servizio in modo
   che venga utilizzata per effettuare le chiamate alle API di CD.
1. Il servizio fornisce la _chiave API_ sotto forma di token di autenticazione
   _bearer_ nelle chiamate API verso l'API gateway.
1. L'API gateway valida la _chiave API_, raccogliendo l'identificativo del
   servizio associato alla chiave e i ruoli associati.
1. L'identificativo del servizio e i ruoli associati vengono passati insieme
   alla richiesta originaria alle API di CD.

L'APIM garantisce l'autenticazione di tutte le chiamate verso le API di CD e
comunica alle API di CD i ruoli associati al singolo servizio, fornendo
inoltre funzionalità di _throttling_, _rate limiting_ e _usage quota_.

Nella fase di accreditamento, ad ogni servizio vengono associati dei ruoli (Tabella \vref{table-api-roles})
che abilitano le operazioni fornite dalle API di CD. A seconda della tipologia
di servizio, possono venire associati combinazioni di ruoli diversi, e quindi
diverse funzionalità fornite dalle API di CD (Tabella \vref{table-api-service-roles}).

Table: Ruoli relativi alle API di CD che vengono associati ai servizi accreditati.\label{table-api-roles}

Ruolo                           Descrizione
------                          ------------
`ApiLimitedProfileRead`         Lettura delle preferenze di un cittadino
`ApiFullProfileRead`            Lettura profilo completo di un cittadino
`ApiProfileWrite`               Creazione/modifica profilo di un cittadino
`ApiServiceRead`                Lettura degli attributi di un servizio
`ApiServiceWrite`               Creazione/modifica di un servizio
`ApiMessageRead`                Lettura messaggio inviato dal servizio
`ApiMessageWrite`               Invio messaggio ad un cittadino
`ApiLimitedMessageWrite`        Invio messaggio ad un cittadino autorizzato
`ApiMessageWriteDefaultAddress` Invio messaggio fornendo indirizzo email
`ApiMessageList`                Lettura casella messaggi di un cittadino

Table: Conbinazione di ruoli associati alle diverse tipologie di servizi.\label{table-api-service-roles}

--------------------------------------------------
Tipologia servizio      Ruoli associati
-------------------     --------------------------
Servizio standard       `ApiLimitedProfileRead`
                        `ApiMessageRead`

Portale sviluppatori    `ApiServiceRead`
                        `ApiServiceWrite`
                        `ApiMessageWrite`[^role-limited-message-write]

Backend dell'app        `ApiFullProfileRead`
                        `ApiProfileWrite`
                        `ApiServiceRead`
                        `ApiMessageList`
--------------------------------------------------

[^portale-dev-cd]: <https://developer.cd.italia.it/>
[^apim-page]: <https://docs.microsoft.com/it-it/azure/api-management/api-management-key-concepts>
[^role-limited-message-write]: Durante la fase di test limitato del servizio,
  invece del ruolo `ApiMessageWrite` viene associato il ruolo `ApiLimitedMessageWrite` che
  limita il servizio all'invio di messaggi verso un insieme di cittadini pre-autorizzati,
  tipicamente i responsabili dello sviluppo del servizio.

![Autenticazione da parte del servizio verso le API di CD.\label{figura-infrastruttura-apim}](diagrams/infrastruttura-apim.svg)

### Autenticazione pagoPA

#### Autenticazione del'app verso il Payment Manager/Wallet PagoPA {#autenticazione-app-wallet}

L'app effettua delle chiamate direttamente alle API del Payment Manager/Wallet
di PagoPA, per la gestione dei metodi di pagamento e delle transazioni.

Queste chiamate devono contenere un token di autenticazione che permetta a
PagoPA di identificare il cittadino e riconiliare la sua identitità con
l'eventuale profilo già presente nel sistema PagoPA.

Il _token_ di autenticazione del Wallet ha lo stesso formato [^token-sessione]
e segue lo stesso ciclo di vita del _token_ di autenticazione del backend
dell'app (§ \ref{autenticazione-app-backend}).

#### Autenticazione del backend dell'app verso il nodo PagoPA

Per alcuni step del flusso di verifica di una posizione debitoria e di esecuzione
della transazione di pagamento, l'applicazione mobile di CD interagisce con il
Nodo PagoPA attraverso il proprio backend, che a sua volta si appoggia ad una
componente, chiamata _pagopa-proxy_, che ha il compito di convertire ed
instradare le richieste verso il Nodo PagoPA attraverso una VPN punto-punto
(Figura \vref{figura-infrastruttura-pagopa}).

L'interazione tra _pagopa-proxy_ e il Nodo PagoPA avviene tramite il protocollo
SOAP. L'autenticazione tra le due componenti è garantita da:

* A livello di rete, garantita dalla VPN punto-punto (criptata con chiave condivisa).
* A livello applicativo, garantita da una chiave condivisa fornita nei messaggi SOAP.

![Autenticazione del backend dell'app verso il nodo PagoPA.\label{figura-infrastruttura-pagopa}](diagrams/infrastruttura-pagopa.svg)

## Sicurezza

### Meccanismi di controllo dell'accesso

#### Accesso remoto ai sistemi

Le macchine virtuali che erogano i servizi della piattaforma di CD, sono
configurate per consentire l'accesso remoto tramite protocollo SSH e
autenticazione a chiave pubblica. Le macchine virtuali non sono dotate di IP
pubblico, per raggiungerle è necessario passare da un _bastion host_.[^bastion-host]

[^bastion-host]: Un _bastion host_ è un computer specializzato nell'isolare una rete locale da una connessione internet pubblica, creando uno scudo che permette di proteggere la rete locale da attacchi esterni - <https://it.wikipedia.org/wiki/Bastion_host>

#### Accesso alle risorse cloud

CosmosDB
  ~ L'accesso alle risorse _CosmosDB_ avviene tramite API REST, su protocollo HTTPS con firma HMAC derivata da un token segreto,
  generato alla creazione del database. Il token viene custodito nella configurazione applicativa delle API.[^accesso-cosmosdb]

Redis cache
  ~ L'accesso alle risorse _Redis cache_ avviene tramite protocollo Redis su trasporto TLS. Per leggere/scrivere il contenuto
  della cache è necessario fornire una password (token segreto) durante la connessione TCP. Il token è custodito
  nella configurazione applicativa del backend dell'applicazione mobile.[^accesso-redis]
  Le risorse Redis sono dispiegate su una Azure Virtual Network (VNET) che fornisce l'isolamento dalla rete pubblica.

Blob/Queue storage
  ~ Le risorse Blob/Queue Storage, che contengono il contenuto dei messaggi inviati, vengono accedute su protocollo HTTPS
  (cifratura in transito) fornendo un token segreto. Il token è custodito nella configurazione applicativa delle API.
  Tutti i dati memorizzati negli storage sono automaticamente cifrati (cifratura a riposo).[^accesso-storage]
  Le risorse Blob/Queue Storage sono dispiegate su una Azure Virtual Network (VNET) che fornisce l'isolamento dalla rete pubblica.

API gateway (Azure API management)
  ~ L'API gateway è esposto direttamente su internet, raggiungibile tramite una URL che identifica la risorsa.
  Per utilizzare le API è necessario ottenere un token (API key) dall'amministratore del sistema, durante
  la procedura di onboarding di un nuovo servizio. Il dialogo con i client avviene tramite procotollo HTTPS.
  Il dialogo con il componente Functions avviene tramite una Azure Virtual Network (VNET)[^accesso-api-gateway].

Functions
  ~ Le Azure Functions rappresentano l'ambiente "Serverless" Azure e implementano la logica applicativa delle API
  di notifica a preferenze. Vengono accedute su protocollo HTTPS, fornendo un token segreto, unicamente tramite l'API gateway.
  Il token è custodito nella configurazione applicativa dell'API gateway che si occupa di inoltrare le richieste
  provenienti dall'esterno (internet) verso le Functions dispiegate su una Azure Virtual Network (VNET),
  che fornisce quindi l'isolamento dalla rete pubblica.[^accesso-functions]

Notification Hub
  ~ L'endpoint del Notification Hub è esposto direttamente su internet.
  L'hub di notifica implementa uno schema di sicurezza denominato "firma di accesso condiviso" (SAS, Shared Access Signature).[^accesso-notification-hub]
  Il token di attivazione del Notification Hub è custodito nella configurazione applicativa del backend dell'App
  e da questo utilizzato per l'invio delle notifiche push. L'app mobile non accede pertanto direttamente alle funzionalità del Notification Hub.

Application Insights
  ~ I log applicativi vengono aggregati utilizzando Azure Application Insights.
  I log sono memorizzati in un account di archiviazione, valgono pertanto le stesse considerazioni sulla sicurezza
  summenzionate per gli Azure Blob Storage. Solo gli amministratori del sistema possono accedere al contenuto dei log,
  previo login tramite 2FA sul portale di Azure.[^accesso-application-insights]
  I componenti del sistema trasmettono i log ad AI tramite il protocollo HTTPS utilizzando un token segreto
  (_instrumentation key_) memorizzato nella configurazione applicativa di ogni componente.

[^accesso-cosmosdb]: <https://docs.microsoft.com/it-it/rest/api/cosmos-db/access-control-on-cosmosdb-resources>
[^accesso-redis]: <https://docs.microsoft.com/it-it/azure/redis-cache/cache-overview>
[^accesso-storage]: <https://docs.microsoft.com/it-it/azure/storage/common/storage-security-guide>
[^accesso-api-gateway]: <https://docs.microsoft.com/it-it/azure/api-management/api-management-using-with-vnet>
[^accesso-functions]: <https://docs.microsoft.com/it-it/azure/azure-functions/functions-overview>
[^accesso-notification-hub]: <https://docs.microsoft.com/it-it/azure/notification-hubs/notification-hubs-push-notification-security>
[^accesso-application-insights]: <https://docs.microsoft.com/it-it/azure/application-insights/app-insights-resources-roles-access-control>

#### Accesso a service provider esterni ad Azure

MailUp
  ~ Il service provider MailUp è utilizzato dalle API di notifica per l'invio delle email
  agli iscritti all'applicazione di Cittadinanza Digitale. Le credenziali per l'accesso al servizio
  (nome utente e password per l'accesso alle API) sono memorizzate nella configurazione applicativa delle Azure Functions.
  Il traporto dei messaggi inviati avviene utilizzando il protocollo HTTPS fino ai server di MailUp
  che ne effettuano il _dispatching_ tramite i server SMTP del service provider.[^accesso-mailup]
  Le credenziali per l'accesso al portale di amministrazione di MailUp sono custodite da AgID.

[^accesso-mailup]: <https://www.mailup.com/gdpr-infrastructure/>

#### Accesso alla configurazione cloud

L'accesso alla configurazione cloud Azure avviene attraverso due meccanismi:

* accesso interattivo alla dashboard Azure tramite account Microsoft (username e password)
* accesso via script di configurazione automatizzato (Terraform) tramite meccanismo _service principal_.[^azure-service-principal]

[^azure-service-principal]: <https://docs.microsoft.com/it-it/azure/azure-stack/azure-stack-create-service-principals>

I sistemi informativi AgID amministrano la sottoscrizione Azure e possiedono le credenziali
per accedere al portale di amministrazione con il massimo dei privilegi: creazione e rimozione delle risorse,
accesso in lettura e scrittura ai dati.

L'autenticazione, a due fattori, avviene tramite l'Active Directory AgID.

Gli account dei gestori della piattaforma (_contributor_, secondo la terminologia Azure)
sono anch'essi impostati nell'AD AgID e richiedono autenticazione tramite 2FA.
I _contributor_ possono accedere al portale di amministrazione e gestire in autonomia
le risorse PaaS fornite da Azure.

### Trasporto dati

**TODO**

### Verifica dell'integrità dei dati

**TODO**

## Diagrammi architetturali

Diagramma                   Figura
----------                  --------
Infrastruttura fisica       Figura \vref{figura-infrastruttura-fisica}
Infrastruttura sistema      Figura \vref{figura-infrastruttura-sistema}
Infrastruttura rete         Figura \vref{figura-infrastruttura-rete}
Infrastruttura piattaforma  Figura \vref{figura-infrastruttura-piattaforma}
Infrastruttura applicativa  Figura \vref{figura-infrastruttura-applicativa}
Infrastruttura dati         Figura \vref{figura-infrastruttura-dati}

![Diagramma di infrastruttura fisica.\label{figura-infrastruttura-fisica}](diagrams/infrastruttura-fisica.svg)

![Diagramma di infrastruttura di sistema.\label{figura-infrastruttura-sistema}](diagrams/infrastruttura-sistema.svg)

![Diagramma di infrastruttura di rete.\label{figura-infrastruttura-rete}](diagrams/infrastruttura-rete.svg)

![Diagramma di infrastruttura di piattaforma.\label{figura-infrastruttura-piattaforma}](diagrams/infrastruttura-piattaforma.svg)

![Diagramma di infrastruttura applicativa.\label{figura-infrastruttura-applicativa}](diagrams/infrastruttura-applicativa.svg)

![Diagramma di infrastruttura dati.\label{figura-infrastruttura-dati}](diagrams/infrastruttura-dati.svg)
