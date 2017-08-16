---
title: Quali sono le impostazioni?
titleSuffix: Intune for Education
description: Informazioni su come gestire le impostazioni tramite Intune per i criteri di istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope: IntuneEDU
ms.openlocfilehash: c7308ab88970c335a0c43d20f4558a54c9143fd9
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-settings"></a>Quali sono le impostazioni?

_Impostazioni_ vengono utilizzati per definire l'utilizzo con i propri dispositivi. Questo può modificare come dispositivo risponde a un utente sta tentando di eseguire l'azione, o arrestando semplicemente effettuando un'operazione su un dispositivo di un utente. Intune per le impostazioni di formazione consentono di gestire le funzionalità nei dispositivi dell'istituto di istruzione.

Le impostazioni vengono applicate ai gruppi. Poiché i gruppi vengono impostati come gerarchie, con un gruppo di sopra di un'altra, qualsiasi [applicate a un gruppo di impostazioni vengono ereditate da tutti i relativi sottogruppi](settings-inheritance.md). Questo rende più semplice applicare le impostazioni a gruppi di utenti, applicazioni e dispositivi di grandi dimensioni.

## <a name="manage-settings"></a>Gestire le impostazioni

Esistono tre modi per gestire le impostazioni di Intune per l'istruzione:

* __Express configurazione__: una selezione delle impostazioni di uso più comune dell'istituto di istruzione vengono resi disponibili in [Express configurazione](how-do-i-manage-settings.md#manage-settings-with-express-configuration) pertanto gli studenti possono essere produttivi usando i dispositivi in classi e protetto.

* __Gruppi__: tutte le impostazioni possono essere gestite per ogni singolo gruppo. Si tratta di un elenco di impostazioni rispetto a quelli disponibili nella configurazione Express espanso. Scoprire [impostazioni sono disponibili qui](available-settings.md).

* __Impostazioni tenant__: le impostazioni del Tenant influiscono su tutti gli utenti e dispositivi nella gestione. Queste impostazioni possono essere gestiti solo da alcuni amministratori con il [appropriati a livello di accesso al tenant di](what-are-tenants.md).

Impostazioni possono essere impostate e assegnate a utenti e dispositivi tramite i gruppi. Assegnate agli utenti in un gruppo di impostazioni verranno trattate con l'utente, indipendentemente dal dispositivo in uso. Assegnato ai dispositivi in un gruppo di impostazioni verranno applicate nel dispositivo, indipendentemente da chi effettua l'accesso al dispositivo.

## <a name="find-out-more"></a>Altre informazioni

- [Ulteriori informazioni su come proteggere App e dati con l'esperienza di gestione complete in Intune](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
