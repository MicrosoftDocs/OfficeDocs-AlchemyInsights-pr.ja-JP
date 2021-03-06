---
title: 'エラー: このコンピューターのルールは一致しません'
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "3518"
- "1800021"
ms.openlocfilehash: c46eb856baafbef9bc3b7fa34a0258ef16923fb8
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2021
ms.locfileid: "51782957"
---
# <a name="error-the-rules-on-this-computer-do-not-match"></a>エラー: このコンピューターのルールは一致しません

この既知の問題の最新の状態を確認するには、「[このコンピューターのルールが Microsoft Exchange のルールと一致しない](https://support.office.com/article/d032e037-b224-429e-b325-633afde9b5f0)」を参照してください。

Outlook チームは、ビルド 12928.10000 で修正プログラムを実装しました。 この修正プログラムは既に Insider ファーストで利用できます。また、2020 年 6 月後半には、月次チャネルでも利用可能になります。 修正プログラムのビルドが完了すると、「保持したいルールを選んでください」というメッセージが表示される場合があります。 メッセージが表示されたら、[サーバー] を選んでから、Outlook に戻り、無効になっていたルールを再び有効にします。

修正プログラムが使用可能になるまで、次の回避策を使用してください。

**回避策**: 最新のレポートでは、Outlook デスクトップでクライアント ルールを作成しただけのユーザーにこの問題が発生しています。 問題の発生が続く場合は、該当のルールを削除してから、OWA (Outlook Web App) で、問題が解消するまでルールを作成、編集します。

ルールを手動で削除できない場合は、Outlook を起動する時にOutlook.exe /cleanrules を実行することで Outlook のコマンドを実行できます。 これにより、クライアントとサーバー両方のルールが削除されます。 Outlook プロファイル内すべてのアカウントの全ルールが削除されます。 このコマンドについては詳しくは、コマンド ライン スイッチの記事に記載されています。

