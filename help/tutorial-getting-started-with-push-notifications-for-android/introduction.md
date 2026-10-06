---
title: Introducción a las notificaciones push para Android, presentación
description: Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android.
feature: Push
jira: KT-5951
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
TQID: 'https://experienceleague.adobe.com/TT6QItpOh4g1nyiefu-aK5h0kUV0y-uwgKlNbk-KNwY'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: a4671286-a59f-47e3-b97b-90627a1977d5
    internal-label: Communication channels
subfeature_v2:
  - id: a4657621-810c-498b-8a27-7ced9c176dda
    internal-label: Push notifications
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '388'
ht-degree: 100%
---
# Introducción a las notificaciones push para Android

Adobe Campaign permite enviar notificaciones [!DNL push] personalizadas y segmentadas a dispositivos móviles [!DNL iOS] y [!DNL Android]. En este tutorial, se explican los pasos necesarios para enviar notificaciones [!DNL push] de Adobe Campaign a una aplicación de [!DNL Android].

## Requisitos previos

Antes de empezar, deberá tener lo siguiente:

1) **Aplicación móvil de Android**

   Este tutorial no cubre los pasos detallados necesarios para configurar la aplicación móvil. Necesitará tener una aplicación móvil **[!DNL Android]con el [!DNL Campaign SDK] integrado**.

   Puede encontrar la descripción detallada de los pasos necesarios en la documentación del producto:

   [Integración del SDK de Campaign en la aplicación móvil](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=es)

   También puede utilizar el SDK de Experience Platform Mobile. Para obtener más información, vea el vídeo del tutorial:

   [Configuración del canal push mediante el SDK para móviles de Experience Platform](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=es)

2) El paquete **[!DNL Mobile App channel]instalado**

   El paquete [!DNL Mobile App channel] debe estar instalado en su instancia [!DNL Campaign]. El siguiente vídeo explica cómo comprobar si [!DNL Mobile App channel] está instalado en la instancia y, en caso contrario, cómo instalarlo.

>[!VIDEO](https://video.tv.adobe.com/v/340427?captions=spa&quality=12&learn=on){transcript=true}

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
