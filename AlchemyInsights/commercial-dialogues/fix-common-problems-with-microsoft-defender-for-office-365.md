---
title: Microsoft Defender for Office365 の一般的な問題を修正する
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
ms.openlocfilehash: 05fa518ece7ea40fd7b4cea57115d9cd60370b01
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2021
ms.locfileid: "50751428"
---
# <a name="fix-common-problems-with-microsoft-defender-for-office-365"></a>Microsoft Defender for Office365 の一般的な問題を修正する

Microsoft Defender for Office365 の一般的な問題に対するいくつかの解決策を次に示します。

- **メッセージの遅延:** メッセージの配信が遅れる問題が発生している場合は、安全な添付ファイル ポリシー内で **動的配信** オプションを使用します。 詳細については、「[安全な添付ファイル ポリシー内の動的配信](https://go.microsoft.com/fwlink/?linkid=2094106)」を参照してください。
- **誤検知または誤検知の結果を報告する:** 次のリンクを使用して Microsoft にメッセージを報告してください: [Microsoft Defender Response Portal](https://go.microsoft.com/fwlink/?linkid=2092835)。
- **安全なリンクの保護を有効にする:**
    1. [Office 365 セキュリティ/コンプライアンス センター](https://go.microsoft.com/fwlink/p/?linkid=2077143)にログインします。
    2. **[脅威管理]** > **[ポリシー]** > **[安全なリンク]** の順に移動します。
    3. **[特定の受信者に適用されるポリシー]** で、構成されたポリシーを開きます。
    4. **[設定]** の下側にある **[組織内で送信されるメッセージに安全なリンクを適用する]** を選択します。
