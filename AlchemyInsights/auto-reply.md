---
title: 'Microsoft 365 グループに送信されるすべての電子メールの自動返信を構成するには:'
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8586"
- "9003200"
ms.openlocfilehash: c3c1d4e6b16b54d92771d7bdecdc9cb12bbf888c
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2021
ms.locfileid: "50484061"
---
# <a name="to-configure-auto-reply-for-all-emails-sent-to-microsoft-365-group"></a>Microsoft 365 グループに送信されるすべての電子メールの自動返信を構成するには:

**テナント管理者アカウントを使用して EXO PowerShell に接続し、次のコマンドを使用します**。

`Set-MailboxAutoReplyConfiguration -Identity groupmailbox -AutoReplyState Enabled -InternalMessage "Internal auto-reply message." -ExternalMessage "External auto-reply message`

> [!NOTE]
> **groupmailbox** を、自動応答を構成するグループ名に変更します。

