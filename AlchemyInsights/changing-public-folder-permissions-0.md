---
title: パブリック フォルダーのアクセス許可の変更
ms.author: dmaguire
author: msdmaguire
manager: dansimp
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "633"
- "3500007"
ms.assetid: 0c37ab75-c81c-44e7-bda8-ea43263f9fdf
ms.openlocfilehash: a2a902e8fdfd8628772364c173979c633d25a169
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/14/2020
ms.locfileid: "47714252"
---
# <a name="changing-public-folder-permissions"></a>パブリック フォルダーのアクセス許可の変更

パブリック フォルダーのアクセス許可は、Outlook のユーザーと管理者が変更できます。管理者は、次の手順を実行して Exchange 管理センター (EAC) からアクセス許可を制御することもできます。
  
1. Microsoft 365 管理センターで、[**管理センター**] \> [**Exchange**] の順に移動します。

2. **パブリック フォルダー**を選択します。

3. そこから、セキュリティ グループをアクセス許可に割り当てることで、個々のパブリック フォルダーに対するアクセス許可を変更できます。エンド ユーザーがパブリック フォルダーのアクセス許可を変更するには、そのユーザーがそのフォルダーの所有者権限を持っている必要があります。

パブリック フォルダーのアクセス許可の問題のトラブルシューティングを行うには、「[パブリック フォルダーのアクセス許可の問題を診断および修正する方法](https://docs.microsoft.com/exchange/troubleshoot/public-folders/public-folder-permission-issues)」に記載されている手順に従ってください。

**メモ**: パブリック フォルダーのアクセス許可を変更しようとする際に発生する可能性がある既知の問題がいくつかあります。 詳細については、次の記事を参照してください。

- [EAC でパブリック フォルダーのサブフォルダーにアクセス許可を適用できない](https://docs.microsoft.com/exchange/troubleshoot/public-folders/can%E2%80%99t-apply-permissions-public-folder-subfolders)

- [パブリック フォルダーへアクセスすると "メールボックスがローカル フォレストで見つかりません" というエラーが表示される](https://docs.microsoft.com/exchange/troubleshoot/public-folders/mailbox-not-found-local-forest-public-folder)
