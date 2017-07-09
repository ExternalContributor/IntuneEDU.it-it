---
title: "La modalità di installazione di App"
titleSuffix: Intune for Education
description: Informazioni su come gestire le app con Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: da398a88d1038d4e43a1a1e7a5df37018ac3f3a6
ms.contentlocale: it-it
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-install-apps-with-intune-for-education"></a>Come si installano le app con Intune per l'istruzione?

L'installazione di App nei dispositivi Windows 10 è uno dei modi che Intune per l'istruzione può consentire agli utenti di ottenere più eseguito. Le app vengono installate nei dispositivi dopo l'assegnazione a un gruppo. Alcune App comuni sono disponibili per impostazione predefinita, ma se non si trova l'app a cui si desidera assegnare, è necessario [aggiungerla a Intune per l'istruzione](how-to-add-apps.md) prima può essere assegnato.

Intune per l'istruzione in diversi modi per installare App nei dispositivi.

##  <a name="install-apps-for-groups"></a>Installare le App per i gruppi
Questo metodo consente di selezionare un gruppo e installare una o più App ai dispositivi in tale gruppo.

1. Nel [Intune per portale Education](https://intuneeducation.portal.azure.com), scegliere > **Gestisci gruppi** per aprire la **gruppi** blade.
2. Scegliere il gruppo a cui si desidera distribuire le app.
3. Scegliere **app** nella barra delle applicazioni nella parte superiore per visualizzare un elenco delle App disponibili.  
4. Scegliere le app che si desidera distribuire a quel gruppo. È possibile scegliere più app.
5. Scegliere **salvare** per distribuire le app selezionate in tale gruppo.

## <a name="install-apps-with-express-configuration"></a>Installare le app con la configurazione Express
Questo metodo consente di distribuire più App a un gruppo selezionato utilizzando il [Express configurazione](what-is-express-configuration.md) processo.

1. Nel [Intune per portale Education](https://intuneeducation.portal.azure.com), scegliere **Express configurazione**.  
2. Scegliere il **gruppo** si desidera aggiungere le app. Scegliere **Avanti**.
3. Scegliere le app che si desidera distribuire a quel gruppo. Scegliere **Avanti**.

## <a name="install-apps-to-multiple-groups"></a>Installare le applicazioni a più gruppi
Questo metodo consente di selezionare un'app e distribuirlo in uno o più gruppi.

1. Nel [Intune per portale Education](https://intuneeducation.portal.azure.com), scegliere **app**.
2. Nell'elenco delle App a sinistra, scegliere l'app da distribuire.
3. Scegliere **gruppi** dalle attività nella parte superiore, quindi scegliere **modificare le assegnazioni di gruppo**.
4. Nell'elenco, scegliere i gruppi a cui che si desidera distribuire l'app.

## <a name="find-out-more"></a>Altre informazioni

- [Trovare ulteriori informazioni sull'installazione di applicazioni usando l'esperienza di gestione completa di app in Intune](https://docs.microsoft.com/intune/deploy-use/deploy-apps)

