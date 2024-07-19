---
title: Configuración de campañas de correo electrónico recurrentes y continuas
description: Aprenda a configurar un envío recurrente y continuo, y comprenda las diferencias entre los dos enfoques.
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 100%

---

# Configuración de campañas de correo electrónico recurrentes y continuas

Este tutorial explica cómo configurar un envío recurrente y continuo, y las diferencias entre los dos enfoques.

## Seguimiento de envío recurrente y continuo {#recurring-and-continuous-delivery-tracking}

Los envíos recurrentes y continuos difieren en la forma en que se administran los datos de contacto:

* Los **envíos continuos** le permiten añadir destinatarios nuevos a un envío existente, lo que evita tener que crear un envío nuevo cada vez que se añade un nuevo destinatario. Puede actualizar el elemento creativo directamente en el flujo de trabajo de campaña para que se actualice la plantilla en la carpeta Recurso de plantilla de envíos.

  Un envío continuo creará un envío ÚNICO y registros de envío (broadLog) y registros de seguimiento que hacen referencia a que se agrega un envío cada vez que se ejecuta.

  ![Entrega continua](/help/assets/delivery_continuous.jpg)

* Un **envío recurrente** creará una nueva instancia de envío cada vez que se ejecute. Por ejemplo, si el flujo de trabajo está programado para ejecutarse una vez a la semana, el resultado sería de 52 envíos al cabo de un año. Esto también significa que el registro y los registros de seguimiento generales se separarán por cada instancia de envío.

  ![Entrega recurrente](/help/assets/delivery_recurring.jpg)

## Configuración de un envío recurrente {#how-to-set-up-a-recurring-delivery}

En este vídeo se explica cómo configurar un envío recurrente y una actividad de planificador.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on){transcript=true}

## Configuración de envíos continuos {#how-to-set-up-a-continuous-delivery}

Este vídeo muestra cómo configurar un envío continua con una consulta incremental.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on){transcript=true}
