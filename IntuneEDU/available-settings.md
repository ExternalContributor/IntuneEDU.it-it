---
title: Impostazioni disponibili
titleSuffix: Intune for Education
description: Ulteriori informazioni sulle impostazioni disponibili per Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: d37a43ff1488c54745daf6109d650a4183d14471
ms.contentlocale: it-it
ms.lasthandoff: 07/05/2017


---

# <a name="available-settings-for-intune-for-education"></a>Impostazioni disponibili per Intune per l'istruzione

Configurazione delle impostazioni è uno dei modi principali, è possibile proteggere i dispositivi Windows 10 e creare i tipi di accesso per migliorare l'esperienza di apprendimento corretti. Intune per l'istruzione fornisce molte impostazioni che consentono di personalizzare queste esperienze, sia per i singoli gruppi e i relativi sottogruppi.

La maggior parte delle impostazioni configurate in uno **blocco** o **Consenti** accesso a determinate funzionalità dispositivo, in cui **non configurato** è l'impostazione predefinita del dispositivo o un setting scelti dall'utente.

> [!NOTE]
> Queste impostazioni utente, app e dispositivi diversi da [impostazioni tenant](what-are-tenants.md).

È possibile trovare queste impostazioni, selezionare prima un **gruppo**, scegliendo **impostazioni**.

  ![La pagina Impostazioni per un gruppo](./media/settings-001-list-of-settings.png)

Le informazioni nel **funzionamento** colonna può essere rilevata anche in Intune per la console di formazione; questo formato è progettato per semplificare la ricerca tramite le impostazioni per elementi specifici.

## <a name="basic-device-settings"></a>Impostazioni di base del dispositivo

|Impostazioni|Descrizione|
|---|---|
|Fotocamera|Bloccare l'accesso utente per la fotocamera del dispositivo.|
|Archivi rimovibili|Impedire agli utenti di utilizzare archivi rimovibili, ad esempio le unità USB e dischi rigidi esterni.|
|Data e ora|Impedire agli utenti di modificare il dispositivo impostazioni data e ora.|
|Nome dispositivo|Impedire agli utenti di modificare il nome del dispositivo.|
|Impostazione della lingua|Impedire agli utenti di modificare la lingua del dispositivo.|
|Annullare la registrazione di dispositivi|Impedire agli utenti di registrare manualmente i dispositivi dalla gestione.|
|Inviare dati diagnostici|Specificare se si desidera raccogliere e inviare dati di utilizzo anonimi a Microsoft per contribuire al miglioramento di Windows.|
|Aggiungere pacchetti di provisioning|Impedire agli utenti dall'aggiunta di aggiunta nuovi pacchetti di provisioning che contiene le impostazioni del dispositivo.|
|Rimuovere i pacchetti di provisioning|Impedire agli utenti di rimozione provisioning i pacchetti che contengono le impostazioni del dispositivo.|
|Servizi di posizione|Bloccare le app di usare servizi di posizione per accedere al percorso del dispositivo.|
|La condivisione Internet|Impedire agli utenti di utilizzare la condivisione Internet per Condivisione connessione Internet del dispositivo.|
|Cortana|Cortana blocco, l'Assistente digitale incorporati in Windows 10 che è possibile rispondere alle domande ed eseguire attività.|
|Impostazioni del dispositivo area|Impedire agli utenti di modificare le impostazioni di area, ad esempio paese e lingua.|
|Salvare i file disco rigido locale|Impedire agli utenti di salvare i file in locale.|
|Impostazioni di risparmio energia e sospensione|Impedire agli utenti di modificare power e le impostazioni di sospensione.|
|Dimensione del menu Start|Definire se forzare schermo intero di visualizzare il menu Start.|
|Contenuti in evidenza di Windows|Bloccare tutte le funzionalità di Windows Spotlight su questi dispositivi.|
|Sincronizzazione OneDrive|Blocco di sincronizzazione di OneDrive per questi dispositivi e utenti.|

## <a name="microsoft-edge-settings"></a>Impostazioni di Microsoft Edge

|Impostazioni|Descrizione|
|---|---|
|Popup|Bloccare siti Web da aprire nuove finestre.|
|Intestazioni-non-Track|Richiedono Microsoft Edge richiedere che i siti Web non tenere traccia dei dati utente.|
|Cookie|I cookie possono memorizzare le impostazioni del sito Web o il comportamento delle esplorazioni dell'utente di tenere traccia.|
|Le voci di form il riempimento automatico|Blocco di salvataggio dei dati immessi in un campo modulo online.|
|Gestione password|Bloccare l'utilizzo di gestione password per salvare le password.|
|Strumenti di sviluppo|Impedire agli utenti di accedere a strumenti di sviluppo.|
|Estensioni del browser|Impedire agli utenti di utilizzo delle estensioni di personalizzare Edge con funzionalità aggiunte da Microsoft e altre origini.|
|InPrivate browsing|Impedire agli utenti di usare InPrivate browsing, che impedisce il salvataggio dei dati a bordo, ad esempio visualizzazione cronologia e i cookie.|
|L'accesso a informazioni su: pagina di flag|Bloccare l'accesso per sulle: pagina flag, che include funzionalità e impostazioni sperimentale.|
|Sostituzione di SmartScreen|Impedire agli utenti di ignorare questi avvisi sui siti Web bloccati dal filtro SmartScreen.|
|Sostituzione SmartScreen per file|Impedire agli utenti di ignorare gli avvisi del filtro SmartScreen sul download di file non verificati.|
|Blocco del contenuto per adulti utilizzando un filtro di ricerca sicura strict|Impostazione di "Blocco" utilizzerà un filtro di ricerca sicura strict anziché moderato di bloccare il contenuto per adulti.|
|Suggerimenti di ricerca|Limite di blocco da suggerire siti Web possibili mentre si digita un termine di ricerca o URL.|
|Traffico Intranet in Internet Explorer|Se impostato su "Blocco", il traffico interno verrà inviato al bordo invece di Internet Explorer.|
|JavaScript|Impedire l'esecuzione in Edge JavaScript.|
|Motore di ricerca predefinito|Selezionare Google, Yahoo o Bing come il motore di ricerca predefinito per Microsoft Edge. Se si o un altro amministratore ha configurato un motore di ricerca personalizzato dell'esperienza completa di Intune, è possibile definire tale motore di ricerca personalizzato come l'impostazione predefinita.|
|Configura pagine iniziali di Microsoft Edge|Scegliere le pagine iniziali aprire ogni volta che un utente avvia una nuova sessione di esplorazione con Microsoft Edge.|
|Configurare Preferiti Microsoft Edge|Scegliere i siti Web da visualizzare nell'elenco Preferiti Microsoft Edge.|
|Blocco di modifica Preferiti|Impedire agli utenti di modificare i Preferiti del browser Edge.|

## <a name="user-access-to-device-settings"></a>Accesso alle impostazioni del dispositivo

|Impostazioni|Descrizione|
|---|---|
|Pannello di controllo|Bloccare l'accesso utente al pannello di controllo.|
|Impostazioni app|Bloccare l'accesso utente per l'app impostazioni. Se non si blocca questa impostazione, è possibile invece scegliere di bloccare singole parti dell'app impostazioni elencate nella parte restante della tabella.|
|Impostazioni di sistema|Blocco schermo, notifiche, App, impostazioni di risparmio energia.|
|Dispositivi|Blocco Bluetooth, stampanti e altro ancora.|
|Rete e Internet|Blocco Wi-Fi, modalità aereo e VPN.|
|Personalization|Blocco dello sfondo, schermata di blocco e modifiche di colore.|
|Account|Gli account utente di blocco, posta elettronica, sincronizzazione, lavoro e ad altre persone.|
|Ora e lingua|Dimensione del blocco, area e Data.|
|Accessibilità|Bloccare l'Assistente vocale, lente di ingrandimento e contrasto elevato.|
|Privacy|Posizione del blocco e fotocamera.|
|Aggiornamento e sicurezza|Blocco di Windows Update, ripristino e backup.|
|App|Blocco di disinstallazione, impostazioni predefinite e le funzionalità facoltative.|
|Modalità di gioco|Barra di gioco di blocco, DVR, la trasmissione e modalità di gioco.|


## <a name="device-update-settings"></a>Impostazioni di aggiornamento di dispositivo

|Impostazioni|Descrizione|
|---|---|
|Livello di conformità di branch|Definire se i dispositivi si trovano in Current Branch o Current Branch per gli aggiornamenti di Business per Windows.|
|Gli aggiornamenti e il periodo di manutenzione|Definire gli aggiornamenti e il periodo di manutenzione per l'installazione degli aggiornamenti.|
|Giorno di installazione pianificata|Definire il giorno della settimana in cui i dispositivi verranno aggiornati e riavviati.|
|Ora di installazione pianificata|Definire il tempo che i dispositivi verranno aggiornati e riavviati.|
|Aggiornare di fuori dell'orario pianificato|Abilitare i dispositivi che sono collegati (ad esempio, in un carrello) a essere aggiornate all'esterno di tempi di aggiornamento pianificato.|
|Rinviare gli aggiornamenti delle funzionalità|Definire il numero di giorni di attesa per applicare gli aggiornamenti di funzionalità per i dispositivi dopo che sono disponibili.|
|Rinviare gli aggiornamenti di qualità|Definire il numero di giorni di attesa per applicare gli aggiornamenti di qualità per i dispositivi dopo che sono disponibili.|
|Consentire agli utenti di scegliere di ricevere le build Insider Preview|Specificare se gli utenti possono effettuare i propri dispositivi disponibili per il download e installazione di software per l'anteprima.|
|Funzionalità di versioni non definitive|Definire weather gli utenti possono visualizzare le funzionalità non definitive per le impostazioni, impostazioni e sperimentazioni o nessuna funzionalità pre-release.|
|Ottimizzazione di recapito|Definire la modalità di recapito degli aggiornamenti per i dispositivi.|

## <a name="windows-defender-settings"></a>Impostazioni di Windows Defender

> [!NOTE]
> Sono disponibili in alcune impostazioni di Windows Defender di [tenant](what-are-tenants.md) livello.

|Impostazioni|Descrizione|
|---|---|
|Bloccare l'accesso utente alle impostazioni di Windows Defender|Impedire agli utenti di modificare le impostazioni di Windows Defender nel dispositivo.|
|Monitoraggio in tempo reale|Abilitare always-on per l'analisi del malware, spyware e altre minacce.|
|Monitoraggio del comportamento|Abilitare Defender verificare la presenza di determinati modelli di attività sospette.|
|Servizio di controllo di rete|Consente di proteggere i dispositivi dagli exploit basati sulla rete usando le firme di vulnerabilità note da Microsoft Endpoint Protection Center per rilevare e bloccare il traffico dannoso.|
|Analisi di tutti i file scaricati|Analizza automaticamente tutti i file scaricati per malware.|
|Analizzare gli script eseguibili nei browser web di Microsoft|Analisi di tutti gli script di che un sito Web tenta di eseguire in Edge e Internet Explorer.|
|Frequenza di aggiornamento|Definire la frequenza Defender verifica la presenza e scarica gli aggiornamenti di anti-malware.|
|Analisi di file e programmi|Analisi di malware quando file o programmi aperti e avvisa gli utenti di attività sospette.|
|Giorni prima della rimozione di malware in quarantena|Definire il numero di giorni per cui viene salvato un file prima di rimuovere (0 = eliminare immediatamente).|
|Protezione basata su cloud|Ottenere protezione in tempo reale quando Defender invia informazioni a Microsoft su potenziali minacce alla sicurezza. Questa funzionalità funziona meglio con "Richiedere agli utenti per l'invio di esempio" set per l'invio automatico di esempi.|
|Richiedere agli utenti per l'invio di esempio|Definire se i file che potrebbero richiedere un'ulteriore analisi vengono automaticamente inviati a Microsoft.|
|Rilevare e blocco potenzialmente indesiderato applicazioni|Defender avviserà l'utente e il blocco è stato eseguito un tentativo di installazione nei dispositivi software potenzialmente indesiderato.|
|Escludere i file con queste estensioni di analisi e la protezione in tempo reale|Definire i tipi di file che si desidera che gli utenti siano in grado di accedere senza effettuare la ricerca di minacce per la sicurezza.|

## <a name="wireless-settings"></a>Impostazioni wireless

|Impostazioni|Descrizione|
|---|---|
|Dati mobili cellulari|Bloccare i dispositivi di uso piani di rete dati durante il roaming.|
|Bluetooth|Bloccare i dispositivi da tramite Bluetooth.|
|Esposizione al rilevamento Bluetooth|Bloccare i dispositivi da viene impostata come individuabile mediante Bluetooth.|
|Annunci con Bluetooth|Bloccare i dispositivi di ricevere annunci tramite Bluetooth.|
|Wi-Fi|Bloccare i dispositivi da tramite Wi-Fi.|
|Connettersi automaticamente per aprire hotspot Wi-Fi|Se è stata abilitata **Wi-Fi**, è possibile scegliere se bloccare i dispositivi di connettersi automaticamente agli hotspot Wi-Fi.|
|Rileva automaticamente impostazioni proxy|Se l'installazione di proxy per gestire il traffico di rete di dispositivo, è possibile scegliere se i dispositivi di rilevare automaticamente le impostazioni del proxy quando si è connessi.|
|Utilizzare uno script proxy|Abilitare l'utilizzo di uno script proxy per i dispositivi. Se si **Consenti** questa impostazione, sarà necessario fornire un **indirizzo script del programma di installazione**.|
|Utilizzare la configurazione manuale di proxy server|Se l'installazione di un proxy manuale, è possibile definire impostazioni di seguito. Se si **Consenti** questa impostazione, sarà necessario fornire il **indirizzo del server Proxy**, **porta**, **eccezioni Proxy**e se **Usa server proxy per le connessioni locali (intranet)**.|


## <a name="device-sharing-settings"></a>Dispositivo impostazioni di condivisione

|Impostazioni|Descrizione|
|---|---|
|Ottimizzare i dispositivi per la condivisione|Configura le impostazioni consigliate per i dispositivi condivisi, ad esempio potenza e la gestione degli aggiornamenti e consentendo a più utenti per accedere allo stesso dispositivo.|
|Impedire agli utenti guest|Se è stata abilitata **ottimizzare i dispositivi per la condivisione**, è anche possibile scegliere se bloccare l'accesso ai dispositivi degli utenti guest. Se è bloccato, solo gli utenti di dominio possono accedere.|
|Cambio rapido utente|Consentire agli utenti di passare rapidamente da un account utente dal menu Start.|

## <a name="app-settings"></a>Impostazioni delle app

|Impostazioni|Descrizione|
|---|---|
|Microsoft Store per le app di formazione|Impedire agli utenti di installare le app da Microsoft Store per l'istruzione.|
|Richiedono Microsoft Store per le app di formazione per essere installata dall'archivio privato|Consentire agli utenti di installare le app da Microsoft Store per l'istruzione che ha configurato l'organizzazione.|
|App attendibili|Definire se gli utenti possono installare le app attendibili firmate da Microsoft.|
|Applicazioni non attendibili|Definire se gli utenti possono installare App non firmate o le applicazioni firmate da origini esterne che non sono considerati attendibili da Microsoft.|
|Aggiornamenti delle app automatico|Blocco di Microsoft Store per le app di formazione vengano aggiornati automaticamente.|
|Dati di app condiviso tra gli utenti|Consentire a più utenti di dispositivi condivisi condividere i dati dell'app.|

## <a name="sign-in-settings"></a>Impostazioni di accesso

|Impostazioni|Descrizione|
|---|---|
|Accedi con account Microsoft|Impedire agli utenti di accedere con l'account Microsoft.|
|Accedi con l'account non Microsoft|Impedire agli utenti di accedere con un account diverso dal proprio account Microsoft. Utilizzare questa impostazione se si desidera imporre agli utenti di accedere, tra gli altri account Microsoft, l'account di Office 365.|

## <a name="windows-interface-customizations"></a>Personalizzazioni dell'interfaccia Windows

|Impostazioni|Descrizione|
|---|---|
|Utilizzati più di App nel menu Start|Bloccare le app più usate da mostrare nel menu Start.|
|Recentemente aggiuntiva app nel menu Start|Blocco app aggiunto di recente da visualizzare nel menu Start.|
|Elementi negli elenchi di salto dal menu Start aperti di recente|Blocco di elementi aperti di recente in elenchi di salto da mostrare nel menu Start e nella barra delle applicazioni.|
|Elenco di App nel menu Start|Bloccare l'elenco di tutte le app nel dispositivo da visualizzare nel menu Start.|
|Menu di alimentazione menu Start|Bloccare il menu di power (ad esempio, riavviare, arresto verso il basso) da visualizzare nel menu Start.|
|Icona utente nel menu Start|Bloccare le informazioni dell'utente corrente visualizzati nel menu Start.|
|Immagine di sfondo schermata di blocco personalizzati|Configurare un'immagine di sfondo personalizzato nella schermata di accesso. È possibile scegliere un file con estensione jpg o PNG inferiore a 20MB di dimensioni.|
|Immagine di sfondo del desktop personalizzato|Configurare un'immagine di sfondo personalizzato sul desktop. È possibile scegliere un file con estensione jpg o PNG inferiore a 20MB di dimensioni.|
|Scegliere le cartelle visualizzati nel menu Start|È possibile scegliere **Esplora File**, **impostazioni**, **documenti**, **Scarica**, **musica**, **immagini**, **video**, **HomeGroup**, **rete**, e **cartella personale**.|
|Scegliere le impostazioni vengono visualizzati nel riquadro utente nel menu Start|È possibile scegliere **modificare le impostazioni dell'account**, **blocco**, e **Disconnetti**.|
|Applica un layout personalizzato dal menu Start|Applica un layout di menu di avvio personalizzato utilizzando un file XML. È possibile caricare un file con estensione XML, minore di 2MB di dimensioni.|
|Siti Web di pin come riquadri nel menu Start|Aggiungere siti Web come riquadri nel menu di avvio tramite un file XML. È possibile caricare un file con estensione XML, minore di 2MB di dimensioni.|

## <a name="email-settings"></a>Impostazioni di posta elettronica

|Impostazioni|Descrizione|
|---|---|
|Configurare le impostazioni di posta elettronica|Scegliere se si desidera configurare le impostazioni di posta elettronica per questo gruppo. Queste impostazioni vengono applicate all'app di posta elettronica di Windows 10. Se non si **configura** questa impostazione, nessuna delle altre impostazioni di posta elettronica in questa tabella saranno disponibile.|
|Nome account|Gli studenti e docenti sarà in grado di vedere questo nei propri dispositivi.|
|Server di posta elettronica|Immettere il nome del server che ospita la posta elettronica.|
|Nome utente|Scegliere l'attributo che Intune verrà utilizzato da Azure Active Directory quando si applicano le impostazioni di nome utente per profili di posta elettronica.|
|Indirizzo di posta elettronica|Scegliere l'attributo che Intune verrà utilizzato da Azure Active Directory quando l'applicazione delle impostazioni di indirizzo di posta elettronica per i profili di posta elettronica.|
|Periodo di tempo per l'archiviazione di posta elettronica nei dispositivi|Scegliere il tempo per l'archiviazione di posta elettronica nei dispositivi.|
|Intervallo per la sincronizzazione di posta elettronica|Scegliere il tempo trascorso tra le sincronizzazioni di posta elettronica.|
|Sincronizzazione contatti|Informazioni di contatto di sincronizzazione.|
|Calendario di sincronizzazione|Sincronizzare le informazioni del calendario.|
|Attività di sincronizzazione|Informazioni sull'attività di sincronizzazione.|
|SSL|Utilizzare Secure Sockets Layer (SSL) per l'invio di messaggi di posta elettronica per una maggiore sicurezza.|

## <a name="wi-fi"></a>Wi-Fi

Impostazioni Wi-Fi sono diverse dalle impostazioni Wi-Fi, vedere **impostazioni Wireless**.

|Impostazioni|Descrizione|
|---|---|
|Nome rete|Specificare il nome della rete.|
|Tipo di sicurezza|Scegliere il protocollo di sicurezza utilizzato dalla rete Wi-Fi.|
|Password|Specificare la password della rete Wi-Fi.|
|Conferma password|Verificare la password della rete Wi-Fi.|

## <a name="edition-upgrade"></a>Aggiornamento dell'edizione

Utilizzare queste impostazioni per aggiornare i dispositivi di questo gruppo a un'edizione di Windows diverso selezionando il **edizione di aggiornamento** e fornendo il **codice Product key**.

## <a name="find-out-more"></a>Altre informazioni

- [Le informazioni di Windows 10 impostazioni gestione esperienza completa disponibile in Intune](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune)

