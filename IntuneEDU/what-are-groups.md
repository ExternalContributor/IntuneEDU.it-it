---
title: Quali sono i gruppi?
titleSuffix: Intune for Education
description: Informazioni su come gestire i gruppi di dispositivi con Intune per l'istruzione.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.contentlocale: it-it
ms.lasthandoff: 07/05/2017


---

# <a name="what-are-groups"></a>Quali sono i gruppi?

Utilizzare _gruppi_ per gestire utenti, applicazioni e dispositivi in Intune per l'istruzione. È possibile raggruppare gli utenti o dispositivi anziché dover gestire singolarmente ogni dispositivo. È possibile assegnare facilmente App e impostazioni a un numero elevato di utenti e dispositivi.

Quando si creano gruppi, considerare come si applicano le impostazioni e le app a utenti e dispositivi. È ad esempio, potrebbe essere necessario bloccare le app dall'utilizzo di servizi di posizione per tutti i dispositivi. Un'alternativa, è come specifici gruppi potrebbe essere necessario determinate operazioni, simile alla studenti tenendo [PA informatica](https://www.tealsk12.org) App per modificare il codice.

Le impostazioni vengono applicate ai gruppi. Poiché i gruppi vengono impostati come gerarchie, con un gruppo di sopra di un altro, [le impostazioni applicate a un gruppo vengono ereditate da tutti i relativi sottogruppi](settings-inheritance.md). Questo rende più semplice applicare le impostazioni a gruppi di utenti, applicazioni e dispositivi di grandi dimensioni.

Intune per l'istruzione crea automaticamente il __tutti i dispositivi__ e __tutti gli utenti__ gruppi quando viene creato il tenant. Questi gruppi predefiniti rappresentano le categorie più ampie di utenti e dispositivi nel scolastiche, o dell'istituto di istruzione e [non può essere spostato](what-are-groups.md#why-cant-i-move-certain-groups).


## <a name="managing-groups-and-subgroups"></a>La gestione dei gruppi e sottogruppi

È possibile creare gruppi, passare a **gruppi**, quindi selezionando **Crea gruppo** dall'inizio dell'elenco di gruppi. È possibile organizzare ulteriormente gruppi creando *sottogruppi* in qualsiasi gruppo, ad eccezione di __tutti i dispositivi__ o __tutti gli utenti__.

  ![Pagina Crea sottogruppo, con i due percorsi per la creazione di sottogruppo, nella parte superiore del nome del gruppo e l'intestazione laterale, racchiuso in un cerchio in rosso](./media/groups-007-create-subgroup.png)

1. Nel [Intune per la console di formazione](https://intuneeducation.portal.azure.com)selezionare **gestire gruppi di utenti e dispositivi**.
2. Selezionare il gruppo di sotto di cui si desidera creare un sottogruppo.
3. Fare clic su **crea sottogruppo**, quindi immettere il **nome gruppo**.

## <a name="making-changes-to-groups"></a>Apportare modifiche ai gruppi

Dopo aver creato un gruppo, è possibile che è necessario modificare l'appartenenza, ad esempio, se un dispositivo deve trasferito a un altro scuola la regione.

  ![La modifica in un gruppo di dispositivi](./media/groups-008-edit-group-membership.png)

1. Selezionare il gruppo i cui membri che si desidera modificare.
2. Selezionare il **dispositivi** scheda.
3. Selezionare il **modifica dispositivi** pulsante, quindi scegliere **aggiungere dispositivi** per aggiungere più dispositivi da un elenco o **X** accanto a un dispositivo per l'eliminazione.

Se è necessario rinominare un gruppo, selezionare il gruppo che deve essere rinominato il **rinominare** pulsante per modificare il nome.

## <a name="move-a-group"></a>Spostare un gruppo

È possibile spostare un gruppo all'interno della struttura di gruppo, o **gerarchia**.

  ![Pulsanti di spostamento gruppo racchiuso in un cerchio in rosso](./media/groups-010-move-groups.png)

1.  Nel [Intune per portale Education](https://intuneeducation.portal.azure.com), scegliere **Gestisci gruppi**.
2. Selezionare il gruppo che deve essere spostato.
3.  Fare clic su **Sposta gruppo** nell'elenco di menu o scegliendo il **Sposta gruppo** pulsante.
4.  Selezionare il percorso del gruppo a cui si desidera spostare il gruppo da una ricerca di un nome di gruppo o selezionarlo nella gerarchia.
5.  Selezionare **OK** per salvare le modifiche.

## <a name="why-cant-i-move-certain-groups"></a>Non è possibile spostare alcuni gruppi

Intune per l'istruzione offre un set di gruppi predefiniti che non possono essere spostati, **tutti gli utenti** e **tutti i dispositivi**, quando il [viene creato il tenant](what-are-tenants.md). **Tutti i docenti** e **tutti gli studenti** sono gruppi predefiniti che vengono creati dopo la sincronizzazione dati School importato dati studenti e insegnanti in Intune per l'istruzione.

Raramente, ciò potrebbe causare un problema in cui si rischia di con un sottogruppo di sotto di due gruppi.

  ![Viene visualizzato sottogruppo nel messaggio di errore più gruppi](./media/groups-012-subgroup-is-under-two-groups-warning.png)

In questo caso, è necessario scegliere un singolo gruppo per inserire sopra il sottogruppo.

## <a name="delete-a-group"></a>Eliminare un gruppo

Quando si elimina un gruppo, Intune per l'istruzione rimuove la raccolta di App e impostazioni in qualsiasi dispositivo che è un membro di tale gruppo. Eliminazione di un gruppo non rimuoverà gli utenti o i dispositivi dalla gestione.

  ![Eliminare i gruppi pulsanti racchiuso in un cerchio in rosso](./media/groups-011-delete-groups.png)

1.  Nel [Intune per portale Education](https://intuneeducation.portal.azure.com), scegliere **Gestisci gruppi**.
2. Selezionare il gruppo che si desidera eliminare
3.  Fare clic su **Elimina gruppo** uno nell'elenco attività.

## <a name="find-out-more"></a>Altre informazioni

- [Saperne di più sui gruppi di completo esperienza di gestione in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

