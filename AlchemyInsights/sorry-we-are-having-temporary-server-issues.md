---
title: Microsoft 365 アプリの「申し訳ありませんが、一時的なサーバーの問題が発生しています」メッセージの修正
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 0adf1d66869051b9dd8290ef3466ef9b13aa2d41
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2021
ms.locfileid: "51835276"
---
# <a name="fixing-the-microsoft-365-apps-sorry-we-are-having-temporary-server-issues-message"></a>Microsoft 365 アプリの「申し訳ありませんが、一時的なサーバーの問題が発生しています」メッセージを修正

このメッセージが表示された場合は、次を試してください。

1. ファイアウォール、ウイルス対策ソフトウェア、プロキシ設定を確認し、インターネットが Microsoft 365 アプリにアクセスするのをそれらがブロックしていないことを確認します。 「 [URL と IP アドレスの範囲](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)」を参照してください。

2. [**開始**] > [**実行**] に移動して、**services.msc** と入力します。 次のサービスがすべて実行されていることを確認してください。
    - ネットワーク接続デバイスの自動セットアップ
    - ネットワーク リスト サービス
    - ネットワーク上の場所の認知
    - Windows イベント ログ

これらのサービスのいずれかが実行されていない場合は、開始してみてください。 サービスの開始に問題がある場合は、昇格されたアクセス許可でコマンド プロンプトを開いて次のコマンドを実行します。

**sfc /scannow**

このコマンドが終了したら、コンピューターを再起動します。

詳細については、「[ライセンス認証を行う際の ”申し訳ありませんが、アカウントに接続できません。しばらくしてからもう一度お試しください”](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365)」エラーを参照してください。