---
title: Exchange Online PowerShell のマイクロ遅延またはスロットル
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2020
ms.locfileid: "44012647"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a><span data-ttu-id="581f5-102">Exchange Online PowerShell のマイクロ遅延またはスロットル</span><span class="sxs-lookup"><span data-stu-id="581f5-102">Micro delays or throttling in Exchange Online PowerShell</span></span>

<span data-ttu-id="581f5-103">Exchange Online でスクリプトとコマンドレットを実行すると、 "マイクロ遅延が適用されました" と警告または遅延が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="581f5-103">You might see "Micro delay applied" warnings or delays when you run scripts and cmdlets in Exchange Online.</span></span> <span data-ttu-id="581f5-104">これに関連する2つの提案は次の通りです。</span><span class="sxs-lookup"><span data-stu-id="581f5-104">Here are two suggestions related to this:</span></span>

- <span data-ttu-id="581f5-105">[Exchange Online v2 PowerShell モジュール](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps)を使用してみることをお勧めします。これには REST API に基づくコマンドレットが含まれており、格段に高性能です。</span><span class="sxs-lookup"><span data-stu-id="581f5-105">You might want to try using the [Exchange Online v2 PowerShell module](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), which includes CMDlets that are based on REST API and are significantly more performant.</span></span> <span data-ttu-id="581f5-106">これは、頻繁に使用される多くの Get- CMDlets に最適なソリューションになることがあります。</span><span class="sxs-lookup"><span data-stu-id="581f5-106">This might be a great solution for a lot of Get- CMDlets that are frequently used.</span></span>
- <span data-ttu-id="581f5-107">まだ v2 モジュールには含まれていないコマンドレットを使用する必要がある場合は、「[Office 365 の PowerShell コマンドレットを実行している場合](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#)」を参照してください。これは、Exchange Online で想定される PowerShell スロットル制限について説明します。</span><span class="sxs-lookup"><span data-stu-id="581f5-107">If you need to use CMDlets that are not covered in the v2 module yet, please see [Running PowerShell cmdlets for large numbers of users in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), which talks about how to get around expected PowerShell throttling limits in Exchange Online.</span></span>