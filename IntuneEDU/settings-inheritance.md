---
title: "Che cos'è l'ereditarietà delle impostazioni?"
titleSuffix: Intune for Education
description: Informazioni su come gestire le impostazioni per i gruppi di dispositivi con Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope: IntuneEDU
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="what-is-settings-inheritance"></a>Che cos'è l'ereditarietà delle impostazioni?

Le impostazioni vengono applicate ai gruppi. Poiché i gruppi vengono impostati come gerarchie, con un gruppo di un altro, le impostazioni applicate a un gruppo vengono ereditate da tutti i relativi sottogruppi. Questo rende più semplice applicare le impostazioni a gruppi di utenti, applicazioni e dispositivi di grandi dimensioni.

  ![Una struttura ad albero dei gruppi di e sottogruppi.](./media/groups-002-inheritance.png)

Ciò significa che per qualsiasi gruppo con un sottogruppo sottostanti, il sottogruppo erediterà automaticamente le modifiche apportate al gruppo di sopra di esso. Si tratta di _ereditarietà_.

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>È possibile configurare sottogruppi in modo diverso dopo che eredita le impostazioni da un altro gruppo?

Sottogruppi possono essere configurati singolarmente, anche se si siano ereditando impostazioni dal gruppo di sopra di essi. È possibile eseguire l'override di impostazioni ereditate semplicemente la configurazione delle impostazioni necessarie e quindi salvarle.

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>È possibile mai preservata con le impostazioni che non funzionano insieme?

Quando più impostazioni sono state applicate allo stesso gruppo, ogni impostazione viene analizzata separatamente da Intune per l'istruzione. Alcune impostazioni che agli utenti di richiedere un intervento per rendere i dispositivi conformi con le impostazioni di forzare sempre avrà la precedenza sulle altre impostazioni.

Si consideri un sottogruppo, *dodicesimo livello AP Computer Science*, al gruppo *livello dodicesimo*. Si sa che la classe di analisi scientifica dei computer di punto di accesso sarà necessario scaricare alcuni file JavaScript che non richiedono l'analisi di sicurezza, ma si desidera assicurarsi che il livello di intero non tenta di eseguire la stessa operazione. Se non si esegue l'override di ereditarietà delle impostazioni, le più restrittive *livello dodicesimo* impostazione verrà applicata agli utenti in *dodicesimo livello AP Computer Science*.

## <a name="find-out-more"></a>Altre informazioni

  - [Individuare che informazioni sui gruppi di completo esperienza in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
