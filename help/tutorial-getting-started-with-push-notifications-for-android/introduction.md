---
title: Introducción a las notificaciones push para Android, presentación
description: Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android.
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 100%

---

# Introducción a las notificaciones push para Android, presentación

Adobe Campaign permite enviar notificaciones [!DNL push] personalizadas y segmentadas a dispositivos móviles [!DNL iOS] y [!DNL Android]. En este tutorial, se explican los pasos necesarios para enviar notificaciones [!DNL push] de Adobe Campaign a una aplicación de [!DNL Android].

## Requisitos previos

Antes de empezar, deberá tener lo siguiente:

1) **Aplicación móvil de Android**

   Este tutorial no cubre los pasos detallados necesarios para configurar la aplicación móvil. Necesitará tener una aplicación móvil **[!DNL Android]con el [!DNL Campaign SDK] integrado**.

   Puede encontrar la descripción detallada de los pasos necesarios en la documentación del producto:

   [Integración del SDK de Campaign en la aplicación móvil](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=es)

   También puede utilizar el SDK de Experience Platform Mobile. Para obtener más información, vea el vídeo del tutorial:

   [Configuración del canal push mediante el SDK de Experience Platform Mobile](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=es)

2) El paquete **[!DNL Mobile App channel]instalado**

   El paquete [!DNL Mobile App channel] debe estar instalado en su instancia [!DNL Campaign]. El siguiente vídeo explica cómo comprobar si [!DNL Mobile App channel] está instalado en la instancia y, en caso contrario, cómo instalarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## Información general del tutorial

Queremos enviar una notificación [!DNL push]promocional personalizada a los suscriptores de la aplicación móvil [!DNL Neotrip] [!DNL Android]. La aplicación [!DNL Neotrip] está configurada con [!DNL Campaign SDK] y nos aseguramos de que el [!DNL Mobile App channel] esté activado en la instancia de [!DNL Campaign].

Se requieren los siguientes pasos para la configuración:

### Paso 1: Ampliar del esquema de suscripción de la aplicación para personalizar las notificaciones [!DNL push]

Como queremos personalizar la notificación [!DNL push], primero [ampliaremos el esquema de suscripción de la aplicación](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) para poder almacenar los valores de personalización que recibimos de la aplicación cuando el usuario se suscribe al servicio.

### Paso 2: Configurar el servicio de Android y crear la aplicación móvil en Campaign

A continuación, debemos [configurar el servicio de Android y crear la aplicación móvil en Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). En este paso definiremos la aplicación [!DNL Neotrip] como el destinatario para la notificación push.

### Paso 3: Configurar y enviar la notificación push

A continuación, estamos listos para [configurar y enviar la notificación push](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Inicio del tutorial

Paso 1: [Ampliar el esquema de suscripción de la aplicación](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
