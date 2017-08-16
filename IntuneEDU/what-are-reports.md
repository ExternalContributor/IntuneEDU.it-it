---
title: Quali sono i report?
titleSuffix: Intune for Education
description: "Informazioni su come report consentono di comprendere l'attività in Intune per l'istruzione."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope: IntuneEDU
ms.reviewer: travisj
ms.openlocfilehash: b1a7a0a574982a48f46559ae0577e6663491b8b3
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-reports-in-intune-for-education"></a>Quali sono i report in Intune per l'istruzione?

Intune per l'istruzione fornisce report che consentono di visualizzare determinate attività dai dispositivi e App gestite con Intune per l'istruzione. È possibile scaricare questi report per esaminarle offline.

Esistono attualmente tre tipi di report che è possibile visualizzare in Intune per l'istruzione: __inventario dei dispositivi__, __inventario delle applicazioni__, e __errori di impostazione__.

1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, scegliere **report** nella barra di spostamento a sinistra.

2. Selezionare il report che si desidera visualizzare. I report seguenti sono disponibili in Intune per l'istruzione:

  * **Inventario dei dispositivi** , ovvero un elenco di dispositivi gestiti da Intune per l'istruzione.

  ![Schermo del dispositivo inventario report, che mostra un elenco di dispositivi in Intune per la gestione di formazione.](./media/reports-001-device-inventory.png)

  * **Inventario delle applicazioni** , ovvero un elenco delle applicazioni installate nei dispositivi gestiti da Intune per l'istruzione, incluso il numero di dispositivi con app installate.

  ![L'applicazione inventario report schermata che mostra un elenco di App in Intune per la gestione di formazione.](./media/reports-002-app-inventory.png)

  * **Errori di impostazione** , ovvero un elenco di impostazioni che sono [attualmente in conflitto](settings-inheritance.md) per tutti i gruppi nella gerarchia.

  ![Schermata che mostra un elenco di conflitti nell'impostazione del report errori di impostazione.](./media/reports-003-settings-error.png)

  È anche possibile selezionare il tipo di app (app web, app Desktop, app Store di Microsoft) per visualizzare solo le informazioni su tale tipo specifico di app.

## <a name="download-reports"></a>Scaricare report

È anche possibile scaricare Intune per i report di formazione. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, trovare il report si è interessati durante il download. Scegliere il **scaricare report** pulsante per esportare e scaricare un report come file delimitato da virgole (CSV) che può essere visualizzato e modificato in un'app di foglio di calcolo, ad esempio [Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba).

## <a name="find-out-more"></a>Altre informazioni

- [Scopri l'esperienza di creazione report completa in Intune](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports)
- [Ulteriori informazioni su reporting con Microsoft Graph](https://developer.microsoft.com/graph/docs/overview/overview)
