---
title: Configuración de flujos de trabajo de validación en Adobe Campaign Classic
description: Obtenga información sobre cómo configurar diferentes flujos de trabajo de validación de aprobación.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 96%

---


# Creación de flujos de trabajo de validación

Adobe Campaign ofrece varias opciones para que los especialistas en marketing puedan revisar y proporcionar contenido de envío, objetivo de campaña, extracción de datos y aprobaciones de presupuesto.

Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.

## Requisito previo {#prerequisite}

Antes de activar los pasos de aprobación, el equipo de marketing debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (función de operador).
* Para permitir que los desarrolladores de campañas seleccionen a los revisores como aprobadores en una campaña o envío, un administrador debe configurar los grupos de revisores y revisores en Adobe Campaign.

## Configuración de aprobaciones para campañas  {#configuring-approvals-for-campaigns}

Si tiene el mismo conjunto de revisores para todas los envíos en el flujo de trabajo de la campaña, aplique la funcionalidad de aprobación de la campaña configurando las aprobaciones y los revisores en el nivel de campaña. Las tareas de aprobación y los revisores se envían a cada actividad de envío del flujo de trabajo una vez que se ejecuta el flujo de trabajo.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12&learn=on){transcript=true}

## Configuración de aprobaciones para entregas  {#configuring-approvals-for-deliveries}

También puede configurar aprobaciones en cuanto a envío. Si los pasos y revisores de las aprobaciones de envío difieren de los pasos y revisores de aprobación de campaña, la configuración de envío anula la configuración de la campaña.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12&learn=on){transcript=true}

## Configuración de una actividad de aprobación  {#configuring-an-approval-activity}

A diferencia del envío o las aprobaciones de campaña, la actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar el envío. También permite la aprobación en varios niveles dentro del flujo de trabajo si es necesario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12&learn=on){transcript=true}

Para obtener más información, consulte la [documentación de aprobación](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=es)
