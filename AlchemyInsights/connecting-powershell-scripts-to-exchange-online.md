---
title: PowerShell スクリプトを Exchange Online に接続する
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6069"
- "3500011"
ms.openlocfilehash: 3a8383a57bc1267311daf03c78841070cca8fb8f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/14/2020
ms.locfileid: "47748069"
---
# <a name="connecting-powershell-scripts-to-exchange-online"></a>PowerShell スクリプトを Exchange Online に接続する

Exchange Online の基本認証は廃止されます。今後の方法は、スクリプトおよび無人タスクに証明書ベースの認証を使用して接続することです。 詳細については、[「EXO V2 モジュールの無人スクリプトのアプリ専用の認証」](https://docs.microsoft.com/powershell/exchange/app-only-auth-powershell-v2) を参照してください。