---
title: PST インポートに関する問題のトラブルシューティング
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1225"
ms.openlocfilehash: 58fdd509fae5e87bf5ae72db5d8926c4367cdd64
ms.sourcegitcommit: 87aa36e3ff4835efb120a320c5169bfa77199ec4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2020
ms.locfileid: "44012667"
---
# <a name="troubleshooting-pst-import-issues"></a><span data-ttu-id="70644-102">PST インポートに関する問題のトラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="70644-102">Troubleshooting PST import issues</span></span>

- <span data-ttu-id="70644-103">Outlook クライアント自体でインポートしている場合は、「[Outlook .pst ファイルにインポートするときの問題を解決する](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70644-103">If you are importing within the Outlook client itself, please see [Fix problems importing an Outlook .pst file](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e).</span></span>

- <span data-ttu-id="70644-104">インポート サービスを使用していて、それがスタックしている場合、Azure Storage の場所にアップロードするそれぞれの PST ファイルは 20 GB 以下である必要があります。</span><span class="sxs-lookup"><span data-stu-id="70644-104">If you are using Import Service and it is stuck, please note that each PST file that you upload to the Azure Storage location should be no larger than 20 GB.</span></span> <span data-ttu-id="70644-105">PST ファイルが 20 GB を超える場合、PST インポート プロセスのパフォーマンスに影響を与える場合があります。</span><span class="sxs-lookup"><span data-stu-id="70644-105">PST files larger than 20 GB may impact the performance of the PST import process.</span></span>

- <span data-ttu-id="70644-106">特定のインポート ジョブの状態を確認したい場合、[Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest) を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="70644-106">If you want to verify the status of a specific Import job, you can use [Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span></span>

- <span data-ttu-id="70644-107">インポート サービスの詳細については、「[組織の PST ファイルのインポートの概要](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70644-107">For full details on the import service, please see [Overview of importing your organization's PST files](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide).</span></span>