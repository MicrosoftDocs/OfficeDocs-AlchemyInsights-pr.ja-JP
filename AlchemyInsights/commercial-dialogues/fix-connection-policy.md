---
title: 接続 ポリシーを修正
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 0b6286350e706e493f6d30b7978aacedc02daff5
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2021
ms.locfileid: "50751417"
---
# <a name="fix-connection-policy"></a>接続 ポリシーを修正

送信 IP アドレスは、接続フィルター ポリシーで安全とマークされたため、メールは安全とマークされ、ユーザーの受信トレイに配信されました。 ポリシーを確認するには、次の操作を行います。

1. [ Office 365 セキュリティ/コンプライアンス センター](https://go.microsoft.com/fwlink/p/?linkid=2077143)に移動し、**[脅威の管理]** > **[ポリシー]** > [[スパム対策]](https://go.microsoft.com/fwlink/?linkid=2101518)に移動します。
2. **[カスタム]** タブで、 **[接続フィルターポリシー]** 選択し、 **[ポリシーの編集]** を選択します。
3. **[IP 許可]** リストを確認します。 **[セーフ リスト]** が有効になっていることを確認します。

    > [!NOTE]
    > Microsoft は、信頼できる送信者のサード パーティ ソースにサブスクライブしています。 **[セーフ リスト]** 有効になっている場合、信頼できる送信者に誤ってスパムのマークをつけないようにします。 このオプションを選択すると、誤検知 (スパムとして分類される正常なメール) の受信数が減少するため、選択することをお勧めします。
