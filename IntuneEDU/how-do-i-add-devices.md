---
title: Aggiungere i dispositivi
titleSuffix: Intune for Education
description: Informazioni su come configurare i dispositivi Windows 10 per Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.contentlocale: it-it
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-devices-to-intune-for-education"></a>Come è possibile aggiungere dispositivi in Intune per l'istruzione?

Dopo aver configurato Intune per l'istruzione con le informazioni necessarie, quali record degli studenti, App e impostazioni per i dispositivi, è necessario connettere i dispositivi in Intune per l'istruzione. È possibile farlo come parte dell'esperienza di installazione per i nuovi dispositivi Windows 10.


> [!NOTE]
> I dispositivi richiedono l'accesso a Internet e l'account deve disporre di sufficiente Intune per la formazione dispositivo disponibili licenze da completare l'installazione. È possibile trovare ulteriori informazioni su questa funzione è presente il nostro [licenze docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).

## <a name="add-devices-to-intune-for-education"></a>Aggiungere i dispositivi a Intune per l'istruzione

È necessario portare eseguire le operazioni seguenti per gestire i dispositivi Windows 10 gestione Intune per l'istruzione:

1. Attivare il nuovo dispositivo Windows 10 e avviare l'installazione di Windows standard. Quando si raggiunge il **proprietario questo PC?** selezionare **aziendale o dell'istituto di istruzione appartiene**.

  ![Schermata del "proprietario questo PC?" schermata di installazione di Windows](./media/devices-001-who-owns-this-pc.png)

2. Nel **scegliere come si accede** selezionare **aggiungere Azure AD**.

  ![Schermata dello schermo "Scegliere la modalità di connessione" nel programma di installazione di Windows](./media/devices-002-how-you-connect-pc.png)

3. Immettere i dettagli dell'account per i criteri di Intune per l'amministrazione di formazione o **altro utente state impostate le autorizzazioni di registrazione** e selezionare **Avanti**.

Il dispositivo verrà [l'autenticazione con Azure AD](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access) e riceverà le impostazioni e le applicazioni assegnate una volta completata l'installazione.

È possibile registrare i dispositivi tramite il [libero __impostare dell'istituto di istruzione PC__ app](how-should-i-enroll-devices.md) configurare rapidamente i PC con una chiave USB. 

## <a name="find-out-more"></a>Altre informazioni
- [Per ulteriori informazioni sul **impostare dell'istituto di istruzione PC** app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [Scopri l'esperienza completa di aggiunta di dispositivi in Intune](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

