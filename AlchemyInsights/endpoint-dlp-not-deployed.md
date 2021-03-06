---
title: エンドポイント DLP がユーザーのデバイスに展開されていません
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 05/27/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11470"
- "9000292"
ms.openlocfilehash: 948835f5468b480536c176bfdf3b4eefb76b3bdb
ms.sourcegitcommit: c32233a1b7e6f1b07913d25f90189a58a8de2560
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/27/2021
ms.locfileid: "52732078"
---
# <a name="endpoint-dlp-not-deployed-to-users-device"></a>エンドポイント DLP がユーザーのデバイスに展開されていません

エンドポイント データ損失防止 (DLP) 設定がユーザーのデバイスに適用されていない場合は、次の要件を満たしていることを確認してください。

- Windows 10 x64 ビルド 1809 以降がデバイスにインストールされています。
- マルウェア対策クライアント バージョン 4.18.2009.7 以降がインストールされています。
- デバイスは次の **いずれか** です。
    
    - Azure Active Directory (Azure AD) への参加
    - Hybrid Azure AD への参加
    - AAD の登録

- ポリシー アクションを適用するには、Microsoft Chromium Edge ブラウザーがエンドポイント デバイスにインストールされていることを確認してください。

エンドポイント DLP を展開するための追加要件については、「[エンドポイント データ損失防止を開始する](/microsoft-365/compliance/endpoint-dlp-getting-started#prepare-your-endpoints)」を参照してください。