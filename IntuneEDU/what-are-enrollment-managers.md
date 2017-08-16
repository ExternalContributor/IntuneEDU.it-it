---
title: Quali sono i manager di registrazione?
titleSuffix: Intune for Education
description: Informazioni su come usare i manager di registrazione in Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope: IntuneEDU
ms.openlocfilehash: a593eefcc965537949ec57f6a325d25859801355
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-enrollment-managers-in-intune-for-education"></a>Quali sono i manager di registrazione in Intune per l'istruzione?

Uso di Intune per l'istruzione per registrare un numero elevato di dispositivi può essere eseguita con un account utente singolo o solo alcuni. Il _Manager di registrazione_ è uno speciale account utente che possono registrare dispositivi fino a 1.000. Richiedere un utente esistente e renderli un Manager di registrazione per consentire loro di funzionalità di registrazione speciali.

  ![Lato sinistro del dashboard](./media/dashboard-002-left-sidebar-list.png)

Il Manager di registrazione del processo che consentono di registrare più dispositivi condivisi suddividendo il carico tra più utenti. Quando si seleziona __Manager di registrazione__ dal menu laterale, verrà visualizzato l'elenco di Manager di registrazione attualmente autorizzato.

  ![Elenco di Manager di registrazione corrente, un utente rappresentato](./media/enroll-mgrs-001-current-list-of-mgrs.png)

Selezionare la persona che si desidera verificare un Manager di registrazione, quindi selezionare __salvare__.

## <a name="removing-enrollment-managers"></a>Rimozione di Manager di registrazione

Utilizzare lo stesso elenco per rimuovere l'accesso utente di registrazione dei singoli. Individuare il nome del Manager di registrazione che si desidera rimuovere, quindi selezionare **rimuovere le autorizzazioni di registrazione**.

  ![Rimuovere pulsante autorizzazioni di registrazione selezionato durante la visualizzazione del Manager di registrazione una singola pagina](./media/enroll-mgrs-003-remove-enrollment-permissions.png)

Anche se tale utente non è più un Manager di registrazione, i dispositivi che vengono registrate anche se si trattasse di Manager di registrazione rimarrà gestiti da Intune per l'istruzione.

## <a name="find-out-more"></a>Altre informazioni

- [Individuare che informazioni sulla gestione registrazione completa esperienza in Intune](https://docs.microsoft.com/intune/deploy-use/enroll-corporate-owned-devices-with-the-device-enrollment-manager-in-microsoft-intune)
