---
title: 予定表のアクセス許可
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3800009"
- "611"
ms.openlocfilehash: 78f27014c60badc801212177dd455ef2a0de5a9e
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/23/2020
ms.locfileid: "44862284"
---
# <a name="calendar-permissions"></a>予定表のアクセス許可

ユーザーは、自分の予定表のアクセス許可を Web 上の Outlook または他のクライアントで変更することができますが、管理者として、調査が必要な場合もあります。  
Exchange PowerShell コマンドレットを使用すると、ユーザーの予定表に対するアクセス許可が表示されます。

`Get-MailboxFolderPermission <SMTPAddress>:\Calendar | FT -a`

詳細については、以下を参照してください。

- [Add-mailboxfolderpermission](https://docs.microsoft.com/powershell/module/exchange/get-mailboxfolderpermission?view=exchange-ps)

- [Add-mailboxfolderpermission](https://docs.microsoft.com/powershell/module/exchange/set-mailboxfolderpermission?view=exchange-ps)

- [Add-mailboxfolderpermission](https://office.visualstudio.com/DefaultCollection/MAX/_queries/query/Add-MailboxFolderPermission)

予定表のアクセス許可は、予定表の共有で使用され、Outlook 予定表の共有についての詳細を確認するには、次の記事を参照してください。

- [他のユーザーと Outlook 予定表を共有する](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)
- [Outlook on the web の自分の予定表を仕事のために共有する](https://support.office.com/article/7ecef8ae-139c-40d9-bae2-a23977ee58d5)

予定表のアクセス許可のトラブルシューティングを行うには、[サポート/回復アシスタント](https://support.microsoft.com/office/e90bb691-c2a7-4697-a94f-88836856c72f)ツールを使用できます。