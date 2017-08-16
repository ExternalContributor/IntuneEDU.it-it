---
title: "Che cos'è la configurazione Express?"
titleSuffix: Intune for Education
description: Utilizzare la configurazione Express configurare rapidamente i gruppi in Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope: IntuneEDU
ms.openlocfilehash: 796782e6c0cf9fa975bd9c8f3a94314bb00d8d89
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="what-is-express-configuration"></a>Che cos'è la configurazione Express?

Configurazione Express è una delle sezioni che viene visualizzato quando prima accedere a Intune per l'istruzione.

  ![Il riquadro Configurazione Express che afferma Avvia configurazione di Express - fare clic qui per scegliere le App e impostazioni per un gruppo.](./media/express-config-001-launch-tile.png)

Configurazione Express consente di fornire rapidamente gli utenti e dispositivi con le impostazioni che necessarie e di App. Non è un elemento che si è limitati all'uso solo una volta. è possibile utilizzarlo ogni volta che si desidera apportare modifiche a qualsiasi gruppo che gestione. Abbiamo scelto alcune App e le impostazioni predefinite che si ritiene che si sono disponibili utili. È possibile modificare queste scelte in base alle esigenze.

## <a name="choose-a-group"></a>Scegliere un gruppo

Si inizierà selezionando un gruppo per configurare.

  ![Schermata di gruppo Scegli, che richiede agli utenti di selezionare un gruppo.](./media/express-config-004-choose-group.png)

Oggetto _gruppo_ in Intune per Education è una raccolta di dispositivi o utenti che sono organizzati per renderlo più facili da capire chi o cosa si sta configurando nella console. Potrebbe trattarsi di dispositivi (ad esempio _sesto livello Computer carrello_) o gli utenti (ad esempio _studenti di quarto livello_ o _insegnanti biologia_). Intune per l'istruzione preconfigurata con gruppi in base alle informazioni dell'istituto di istruzione che ci hai fornito. Abbiamo ulteriori informazioni sui gruppi disponibili nel nostro [gruppi di articoli](what-are-groups.md).

È consigliabile avviare tramite l'assegnazione di impostazioni che si è certi **tutti gli utenti** sarà necessario, ad esempio i requisiti della password o il blocco popup in Microsoft Edge.

Selezionare un gruppo per configurare, quindi scegliere **Avanti** per continuare.

## <a name="choose-apps"></a>Scegli le app

A questo punto, si sceglierà di App per assegnare a questo gruppo.

  ![Schermata di assegnazione di app. Le app sono organizzate per l'assegnazione per tipi diversi, tra cui le applicazioni web e Microsoft Store per le app di formazione.](./media/express-config-005-choose-apps.png)

Esistono alcuni tipi di App che è possibile installare nei dispositivi:

* [App Web](how-to-add-apps.md#add-web-apps)
* [Applicazioni desktop](how-to-add-apps.md#add-desktop-apps)
* [Microsoft Store per le app di formazione](acquire-store-apps.md)

Intune per l'istruzione Visualizza anche [più comuni App dallo Store Microsoft per l'istruzione](how-to-add-apps.md#add-popular-apps) da tra tutti Intune per gli utenti di formazione.

Selezionare le app da assegnare al gruppo, quindi scegliere **Avanti** per continuare.

## <a name="choose-settings"></a>Scegliere le impostazioni

Successivamente, si sceglierà le impostazioni da applicare ai dispositivi o utenti del gruppo.

  ![Schermata delle impostazioni di scegliere. Le impostazioni sono organizzate in un elenco compresso, inclusi i reparti, ad esempio la condivisione di dispositivo, le impostazioni di base del dispositivo, le impostazioni dell'app, impostazioni del browser e altro ancora.](./media/express-config-006-choose-settings.png)

Configurazione Express Mostra le impostazioni che si consiglia di ottenere i gruppi di procedere. Abbiamo scelto queste impostazioni per renderne più semplice per gli utenti iniziare rapidamente con i dispositivi. Non è necessario apportare modifiche se si desidera utilizzare questi consigli oppure è possibile personalizzare queste impostazioni per soddisfare esigenze specifiche.

È possibile modificare le selezioni di configurazione Express in qualsiasi momento in base a tutte le modifiche è necessario creare e personalizzare le impostazioni di utilizzo ulteriormente la completa [elenco delle impostazioni disponibili come parte di Intune per l'istruzione](available-settings.md).

## <a name="finish-up"></a>Terminare

Dopo aver effettuato le selezioni, è la possibilità di esaminare le App e impostazioni scelte. È quindi possibile scegliere di **fine** pulsante o tornare indietro per tutti i passaggi per modificare queste impostazioni.

  ![La revisione dello schermo di scelte. Mostra l'App e impostazioni selezionate durante la configurazione Express.](./media/express-config-007-save-changes.png)

Dopo aver scelto **fine**, è possibile **configurare più gruppi** o essere **fatto**.

  ![Schermata di completamento. Mostra la configurazione più gruppi e le opzioni completate. L'opzione All Done offre una breve spiegazione della prossima fase del processo, inclusa l'aggiunta di dispositivi in Intune per l'istruzione unendoli in Azure Active Directory.](./media/express-config-008-all-done.png)

Al termine, verrà visualizzata di Intune per il dashboard di istruzione in cui è possibile continuare a gestire i dispositivi, utenti e applicazioni. È possibile tornare alla configurazione Express qualsiasi momento dal dashboard o il menu di navigazione per aggiungere, rimuovere o modificare le impostazioni per i gruppi e App.

## <a name="next-steps"></a>Passaggi successivi

Dopo aver impostato i gruppi con le impostazioni che necessarie e di App, si è pronti per iniziare a usare i dispositivi con Intune per l'istruzione.

## <a name="find-out-more"></a>Altre informazioni
- [Maggiori informazioni sulle impostazioni disponibili nell'esperienza di gestione complete in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
