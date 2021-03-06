---
title: 1490 電子情報開示のエラーのトラブルシューティング
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1490"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: ff28f96d64ec14980e9a47b630246b394faf4610
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277823"
---
# <a name="troubleshoot-content-search-errors"></a>コンテンツ検索のエラーをトラブルシューティングする

コンテンツ検索で問題が発生したり、検索結果をエクスポートする際にエラーを取得したりしている場合。

たとえば、検索の実行時に、次のようなことになる場合がありますか?

- CS008 または CS012 エラー

- サーバー ビジー/タイムアウト エラー

- アプリケーション エラーが発生

または、多数のメールボックス (100,000 を超えるメールボックス) を検索したり、検索結果をエクスポートするときに、エクスポート エラーが発生しますか。

このようなエラーの場合は、失敗したコンテンツの場所の検索を再試行してください。詳細については、[この記事](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search)を参照してください。

10 万個以上のメールボックスをエクスポートする場合は、次の Powershell を使用し、エクスポート結果をダウンロードする必要があります: 「[10 万個以上のメールボックスから結果をエクスポートする](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes)」。
