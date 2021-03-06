---
title: ネットワークの移行
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "716"
- "6000002"
ms.assetid: b5ab885c-3803-4cc8-adab-94848e226ffb
ms.openlocfilehash: 6f026f932bb35d12d32ce7eddf49e49a44db7f31
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/15/2020
ms.locfileid: "47799569"
---
# <a name="network-migration"></a>ネットワークの移行

ご使用の O365 テナントは 1 つのテナント内で複数の Yammer ネットワークに関連付けられている可能性があります (多数のネットワーク構成)。2018 年 10 月 16 日以降、Yammer は 1 つのテナントへの複数の Yammer ネットワークの関連付けをサポートしなくなりました。ネットワークの移行を行うことで、適切な 1 対 1 構成にすることができます。
  
- ご使用のテナントに関連付けられているネットワークのリストを表示するには、グローバル管理者として Yammer にログインし、**[ネットワーク管理者]**、**[ネットワーク移行]** の順に参照します。**[次へ]** を選択します。

- 手順 2/3 で複数のネットワークが一覧表示される場合は、ご使用の O365 テナントに複数のネットワークが関連付けられています。

- 構成を 1 対 1 に修正するには、引き続きネットワーク移行ツールを使用します。

- ネットワーク移行の詳細については、「[ネットワークの移行: 複数の Yammer ネットワークの統合](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks)」を参照してください。

次の点にご注意ください。
  
- **ネットワークの移行では、アクティブなユーザーおよび保留中のユーザーのみが移行されます。** アクティブなユーザーと共に、名前やプロファイル画像などのユーザー情報も移行されます。グループなどのネットワーク コンテンツは移行されません。

- **ネットワークの移行を取り消すことはできません。** 移行後は、ご使用の従属ネットワークとそのコンテンツにアクセスできなくなります。そのため、移行を検討する前に、慎重に計画を立てる必要があります。
