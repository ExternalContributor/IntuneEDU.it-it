---
title: Aggiungere app
titleSuffix: Intune for Education
description: Informazioni su come aggiungere App in Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope: IntuneEDU
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-add-apps-to-intune-for-education"></a>Come è possibile aggiungere le app a Intune per l'istruzione?

Prima di installare le app nei dispositivi dell'istituto di istruzione con Intune per l'istruzione, tali App devono essere aggiunte a Intune per conto di formazione.

Intune per l'istruzione supporta i tipi di App seguenti:
- Le app Web, ad esempio [Microsoft Word in linea](https://office.live.com/start/Word.aspx)
- Microsoft Store per le app di formazione, che sono stati [distribuite attraverso l'archivio di App universali](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- Le app desktop, ad esempio [autonomo di Microsoft Office](https://products.office.com/products)

Dopo aver aggiunto le app, è possibile [installano le app](install-apps.md) su gruppi di dispositivi.

Le impostazioni vengono applicate ai gruppi, inclusi i gruppi di App. Poiché i gruppi vengono impostati come gerarchie, con un gruppo di sopra di un altro, [qualsiasi App assegnata a un gruppo vengono ereditate da tutti i relativi sottogruppi](settings-inheritance.md).

## <a name="add-web-apps"></a>Aggiungere le app web

Oggetto _app web_ è un'app di cui si accede da parte degli utenti esclusivamente in un browser. Sono facili da assegnare in quanto è necessario inviare agli utenti vengono forniti collegamenti a siti Web, anziché inviare i file di installazione per i dispositivi.

È possibile assegnare le applicazioni web come collegamenti nel menu Start dei dispositivi Windows 10 con Intune per l'istruzione. Per assegnare un'applicazione, è necessario innanzitutto aggiungerla a Intune per l'istruzione nel **gestire le app** sezione.

  ![Aggiungi una nuova pagina di app web, che richiede agli utenti per le informazioni descritte nella procedura riportata di seguito.](./media/apps-001-add-webapp.png)

1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, scegliere **app**.

2. In **le app Web**selezionare **+ nuova app**, quindi immettere i dettagli seguenti:
 * **URL** : l'URL dell'app che si desidera assegnare
 * **Nome dell'app** : il nome dell'app visualizzato nel menu Start nei dispositivi
 * **Icona** : caricare un PNG o JPG dal computer da utilizzare come un'icona per l'app

3. Scegliere **Salva**. L'app web è pronta.

4. È ora possibile [installare l'app nei dispositivi](install-apps.md).

È possibile modificare l'applicazione in qualsiasi momento scegliendo **modifica**, che apre nuovamente la pagina dei dettagli.

## <a name="add-desktop-apps"></a>Aggiungere App desktop

È possibile installare le app desktop tramite l'interfaccia stessa nella **app** pagina. Questo processo è simile all'installazione di un'app web, ma comporta il file di installazione che non richiedono l'App web.

![La nuova schermata app desktop.](./media/apps-003-add-desktop-app.png)

1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, scegliere **app**.

2. In **App Desktop**selezionare **+ nuova app**. Verrà aperta la **nuove app desktop** schermata, quindi immettere i dettagli seguenti:
 * **Il file app** : caricare un programma di installazione MSI per l'app
 * **Nome dell'app** : il nome dell'app da visualizzare nei dispositivi
 * **Descrizione** , una descrizione dell'app per facilitare l'identificazione rapida dei quali app è
 * **Server di pubblicazione** : il nome del server di pubblicazione di app, per facilitare l'identificazione rapida dei che ha sviluppato l'app
 * **Icona** : caricare un PNG o JPG dal computer da utilizzare come un'icona per l'app

3. Scegliere **salvare e caricare file**.

  ![La nuova app desktop schermata di aggiunta, con tutti i campi vengono compilati per app di esempio, evernote.](./media/apps-004-filled-out-desktop-app.png)

4. L'app verrà quindi caricato in Intune per l'istruzione. Dopo il caricamento è completo, è possibile [installare l'app nei dispositivi](install-apps.md).

> [!NOTE]
> In alcuni casi è possibile eseguire in un messaggio di errore "l'app non include un file di installazione" o "è stato aggiunto alcun file di installazione di app". Ciò significa che il file non carica correttamente. Provare a salvare e caricare nuovamente il file per correggere l'errore.

## <a name="add-popular-apps"></a>Aggiungere più comuni App

È possibile installare anche rapidamente più comuni App didattici da Microsoft Store per l'istruzione. L'obiettivo è semplificare trovare e installare le app preferite per gli utenti. Queste applicazioni è consigliabile perché sono spesso utile educatori. È possibile trovare queste App nella configurazione Express o sotto il **gestire le app** riquadro.

  ![Selezione di più comuni App durante il processo di App Aggiungi configurazione Express.](./media/apps-005-popular-apps.png)

I criteri di Intune per portale Education vengono visualizzati i primi dodici didattici App web e le prime dodici didattici Microsoft Store per le app di istruzione che non sono stati aggiunti in **app** management.

> [!TIP]
> Se è stato impostato il Microsoft Store per conto di formazione per aggiungere le app a Intune per l'istruzione, è possibile trovare informazioni su come eseguire questa operazione [qui](acquire-store-apps.md).

1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, scegliere **Gestisci app** > **aggiungere app** > **più comuni app di aggiunta rapida**. Un elenco di **le app Web** e **App Microsoft Store** viene visualizzato.

  ![L'aggiunta dello schermo più comuni app.](./media/apps-006-add-popular-apps.png)

2. Selezionare le app che si desidera aggiungere, quindi scegliere **aggiungere app**.

  ![Selezione di più comuni app da aggiungere al portale.](./media/apps-007-select-multiple-popular-apps.png)

3. Le app verranno aggiunto in background e vengono visualizzati nella barra laterale sinistro, quando si è pronti.

  ![Le app vengono aggiunti dello schermo.](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>Altre informazioni

- [Scopri l'esperienza completa di gestione delle App con Intune](https://docs.microsoft.com/intune/deploy-use/add-apps)
