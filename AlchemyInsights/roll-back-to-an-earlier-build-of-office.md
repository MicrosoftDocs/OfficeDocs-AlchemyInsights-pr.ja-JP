---
title: 以前の Office のビルドにロールバックする
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/24/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1741"
- "9000140"
ms.openlocfilehash: 8c7d019ec1aa6c26cffebbcd2c3e5751c853e3a4
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/28/2020
ms.locfileid: "45440597"
---
# <a name="roll-back-to-an-earlier-build-of-office"></a><span data-ttu-id="70c92-102">以前の Office のビルドにロールバックする</span><span class="sxs-lookup"><span data-stu-id="70c92-102">Roll back to an earlier build of Office</span></span>

<span data-ttu-id="70c92-103">以前の Microsoft 365 Apps ビルドまたはバージョンに戻すには、「[Office を以前のバージョンに戻す方法](https://support.microsoft.com/help/2770432/how-to-revert-to-an-earlier-version-of-office-2013-or-office-2016-clic)」 を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c92-103">To revert to an earlier Microsoft 365 Apps build or version, see [How to revert to an earlier version of Office](https://support.microsoft.com/help/2770432/how-to-revert-to-an-earlier-version-of-office-2013-or-office-2016-clic).</span></span> <span data-ttu-id="70c92-104">ある Microsoft 365 サブスクリプションから別のサブスクリプションに切り替えるには、「[別の Microsoft 365 for Business プランに切り替える](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c92-104">To switch from one Microsoft 365 subscription to another, see  [Switch to a different Microsoft 365 for business plan](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).</span></span>

- <span data-ttu-id="70c92-105">現在使用する Office のバージョンを確認するには、「[使用している Office のバージョンを確認する方法](https://support.office.com/article/about-office-what-version-of-office-am-i-using-932788b8-a3ce-44bf-bb09-e334518b8b19)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c92-105">To find the version of Office you are currently using, see [About Office: What version of Office am I using?](https://support.office.com/article/about-office-what-version-of-office-am-i-using-932788b8-a3ce-44bf-bb09-e334518b8b19).</span></span>
- <span data-ttu-id="70c92-106">ロールバックするビルドを決定するには、「[Microsoft 365 Apps の更新履歴 (日付別の一覧)](https://docs.microsoft.com/officeupdates/update-history-office365-proplus-by-date?redirectSourcePath=%252fen-us%252farticle%252fae942449-1fca-4484-898b-a933ea23def7)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c92-106">To determine the build you want to roll back to, see [Update history for Microsoft 365 Apps (listed by date)](https://docs.microsoft.com/officeupdates/update-history-office365-proplus-by-date?redirectSourcePath=%252fen-us%252farticle%252fae942449-1fca-4484-898b-a933ea23def7).</span></span>
- <span data-ttu-id="70c92-107">[以前のバージョンの Office に戻す方法](https://support.microsoft.com/help/2770432/how-to-revert-to-an-earlier-version-of-office-2013-or-office-2016-clic)または[Office コンテンツ配信ネットワーク (CDN) の使用時に半期チャネルからの機能更新プログラムの受信を延期する](https://docs.microsoft.com/deployoffice/delay-receiving-feature-updates-from-deferred-channel-for-office-365-proplus#delay-receiving-feature-updates-from-semi-annual-channel-when-using-the-office-content-delivery-network-cdn)方法で、 **TargetVersion**設定を構成し以前のビルドに戻します。</span><span class="sxs-lookup"><span data-stu-id="70c92-107">Configure the **TargetVersion** setting to revert to the earlier build by using [How to revert to an earlier version of Office](https://support.microsoft.com/help/2770432/how-to-revert-to-an-earlier-version-of-office-2013-or-office-2016-clic) or [Delay receiving feature updates from Semi-Annual Channel when using the Office Content Delivery Network (CDN)](https://docs.microsoft.com/deployoffice/delay-receiving-feature-updates-from-deferred-channel-for-office-365-proplus#delay-receiving-feature-updates-from-semi-annual-channel-when-using-the-office-content-delivery-network-cdn).</span></span></br>
    <span data-ttu-id="70c92-108">対象バージョンを設定しましたら、Office は次に更新を検索するときにそのバージョンに更新します。</span><span class="sxs-lookup"><span data-stu-id="70c92-108">When the target version is set, Office updates to that version the next time it looks for updates.</span></span>