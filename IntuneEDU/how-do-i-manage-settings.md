---
title: "Come è possibile gestire le impostazioni?"
titleSuffix: Intune for Education
description: Seguire questi passaggi per gestire le impostazioni tramite Intune per i criteri di istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope: IntuneEDU
.md#ms.tgt_pltfrm: 
ms.openlocfilehash: a8a9619476315459d49dc128e14c3bc0f2f7794e
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-manage-settings"></a>Come è possibile gestire le impostazioni?

È possibile gestire un'ampia gamma di impostazioni per gli utenti, applicazioni e dispositivi con Intune. È come verrà modificata come dispositivi possono rispondere alle azioni dell'utente.

Quando le impostazioni vengono applicate a un gruppo di dispositivi, gli utenti sono interessati quando accedono a un dispositivo da quel gruppo. Se un'impostazione viene applicata a un gruppo di utenti,

Le impostazioni del dispositivo applicano a tutti i dispositivi nel relativo gruppo. Impostazioni di **non configurato** consentono all'utente di definire le impostazioni nei dispositivi stessi.

## <a name="manage-settings-for-groups"></a>Gestire le impostazioni per i gruppi

Utilizzare la procedura seguente per gestire l'elenco completo delle impostazioni di Intune per l'istruzione:
1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, nel menu di navigazione di sinistra, scegliere **gruppi**.
2. Selezionare il gruppo di cui si desidera gestire le impostazioni. Per un elenco completo, vedere [impostazioni disponibili](what-are-settings.md).
3. Fare clic su **impostazioni** nella parte superiore della pagina per visualizzare l'elenco completo delle impostazioni disponibili.
4. Espandere le categorie e modificare le singole impostazioni per il gruppo selezionato.
5. Fare clic su **salvare** per salvare le modifiche per tale gruppo. Le impostazioni vengono inviate automaticamente ai dispositivi in tale gruppo.

## <a name="manage-settings-with-express-configuration"></a>Gestire le impostazioni con la configurazione Express

Configurazione Express consente di iniziare rapidamente, ma consente inoltre di apportare modifiche rapide nei dispositivi.

  ![Express correggere le impostazioni di configurazione](./media/express-config-006-choose-settings.png)

1. Nel [Intune per l'istruzione](https://intuneeducation.portal.azure.com) console, scegliere **Avvia configurazione Express**. Esaminare il **iniziale** pagina e selezionare **iniziare**.
2. Esaminare il **ottenere informazioni dell'istituto di istruzione** pagina. Se si sono già state aggiunte informazioni dell'istituto di istruzione, scegliere **Avanti**.
3. Selezionare il gruppo le cui impostazioni si desidera gestire e quindi scegliere **Avanti**.
4. Esaminare l'elenco di App e quindi scegliere **Avanti**.
5. Nel **impostazioni** espandere le categorie di impostazioni disponibili:
  * [Impostazioni di base del dispositivo](available-settings.md#basic-device-settings)
  * [Impostazioni di Microsoft Edge](available-settings.md#microsoft-edge-settings)
  * [Impostazioni di aggiornamento di dispositivo](available-settings.md#device-update-settings)
  * [Impostazioni wireless](available-settings.md#wireless-settings)
  * [Impostazioni dell'App](available-settings.md#app-settings)
  * [Impostazioni di accesso](available-settings.md#sign-in-settings)

  Espandere una categoria e attivare o disattivare il controllo per modificare le impostazioni e quindi scegliere **Avanti**.

6. Rivedere le scelte effettuate e quindi scegliere **fine** per salvare le modifiche aggiornarli nei dispositivi nel gruppo selezionato.

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>È possibile mai avere impostazioni che non funzionano insieme?

È possibile che le impostazioni non compatibili da applicare allo stesso gruppo. Queste incoerenze causare errori, quando un utente o un dispositivo viene configurato con impostazioni diverse in più posizioni. Ciò si verifica in seguito l'utente o il dispositivo è un membro di più gruppi.

Ad esempio, Esperanza è un membro del *livello 6* gruppo ed è anche un membro del gruppo denominato *Earth informatica*. Se si configura un'impostazione della home page e assegnare a *livello 6*, e si configura un'impostazione diversa home page e assegnarlo alla *Earth informatica*, giorgia ha ora due impostazioni home page in conflitto, assegnate a utente. Di conseguenza l'assegnazione non coerente delle impostazioni iniziali a un errore. È possibile trovare quali dispositivi e utenti hanno errori di impostazioni mediante il [report degli errori di impostazioni](what-are-reports.md).

## <a name="find-out-more"></a>Altre informazioni

- [Scopri l'esperienza di gestione completa dei criteri in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
