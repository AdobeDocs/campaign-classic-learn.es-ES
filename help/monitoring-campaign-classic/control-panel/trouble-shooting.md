---
title: Solución de problemas del Panel de control
description: El Panel de control de Campaign le permite supervisar y administrar su almacenamiento SFTP por instancia y lista de permitidos con direcciones IP.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 79%

---


# Solución de problemas [!UICONTROL Control Panel]

## Inicio de sesión y página de inicio

### Síntoma: no se puede iniciar sesión en Experience Cloud

**Qué hacer:**
el usuario debe localizar su identificador de organización de IMS (xxx). El administrador debe añadir el usuario al Perfil de productos “Campaign-xxx-Admins” para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: los vínculos de la página principal de Experience Cloud para acceder a [!UICONTROL Control Panel] no aparecen para un usuario.

**Causa:**
los usuarios no verán los vínculos hasta que se añadan como usuarios al Perfil de productos _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
el administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como &quot;usuario&quot;.

### Síntoma: una instancia no aparece en la lista de [!UICONTROL Control Panel]

**Causa:**
Es muy probable que el usuario deba añadirse como &quot;usuario&quot; al Perfil de productos _Campaign-xxx-Administradores/Admin_ para la instancia que falta

**Qué hacer:**
el administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como “usuario”.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/34929?quality=12&learn=on&captions=spa){transcript=true}

*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/34797?quality=12&learn=on&captions=spa){transcript=true}

*Cómo añadir un administrador a los administradores de perfil de productos para poder utilizarlo [!UICONTROL Control panel] (1:03 min)*

### Documentación útil

* [Descubra el panel de control de Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)
* [Administración de permisos para [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Allow listing] la dirección IP desde la que se está conectando al servidor SFTP.
* Par de claves públicas/privadas que debe registrarse con Adobe Campaign
* Si se conecta directamente al servidor SFTP, necesitará el software de cliente SFTP

### Documentación útil {#helpful-docs}

* [Inicio de sesión en el servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)

