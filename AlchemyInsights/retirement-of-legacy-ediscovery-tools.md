---
title: 従来の電子情報開示ツールの廃止
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: af9a0bd8ff4294575ac68f37d4997bb50b132ce7
ms.sourcegitcommit: 9ab422063e5a474c92ed956d42d222b90336fecb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600379"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="75988-102">従来の電子情報開示ツールの廃止</span><span class="sxs-lookup"><span data-stu-id="75988-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="75988-103">Microsoft 365 コンプライアンス センターの電子情報開示機能が刷新され、機能が向上したことにより、次に挙げる従来の電子情報開示ツールおよびコマンドレットは今後数か月間の間に廃止されます。</span><span class="sxs-lookup"><span data-stu-id="75988-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="75988-104">Exchange 管理センターの[インプレース電子情報開示](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)および[インプレース ホールド](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds)。</span><span class="sxs-lookup"><span data-stu-id="75988-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="75988-105">インプレース電子情報開示およびインプレース ホールドをサポートしている、Exchange Online の PowerShell コマンドレット。</span><span class="sxs-lookup"><span data-stu-id="75988-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="75988-106">(これらのコマンドレットは、まとめて \*-MailboxSearch cmdlets と識別されます。) 次のコマンドレットが含まれます。</span><span class="sxs-lookup"><span data-stu-id="75988-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="75988-107">New-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="75988-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="75988-108">Start-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="75988-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="75988-109">Stop-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="75988-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="75988-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="75988-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="75988-111">Exchange Online PowerShell の [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) コマンドレット。</span><span class="sxs-lookup"><span data-stu-id="75988-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="75988-112">Exchange Web Services API での次の操作。</span><span class="sxs-lookup"><span data-stu-id="75988-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="75988-113">GetSearchableMailboxes</span><span class="sxs-lookup"><span data-stu-id="75988-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="75988-114">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="75988-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="75988-115">GetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="75988-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="75988-116">Office 365 Advanced eDiscovery v1.0</span><span class="sxs-lookup"><span data-stu-id="75988-116">Office 365 Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="75988-117">**廃止のタイムライン**:</span><span class="sxs-lookup"><span data-stu-id="75988-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="75988-118">2020 年 4 月 1 日: 新しい検索と保留リストを作成できなくなりますが、ユーザーの自己責任において、既存の検索の実行、編集、および削除は引き続き行えます。</span><span class="sxs-lookup"><span data-stu-id="75988-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="75988-119">Microsoft サポートによる Exchange 管理センターのインプレース電子情報開示およびインプレース ホールドのサポートが終了します。</span><span class="sxs-lookup"><span data-stu-id="75988-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="75988-120">2020 年 7 月 1 日: Exchange 管理センターのインプレース電子情報開示およびインプレース ホールドが読み取り専用モードに変更されます。</span><span class="sxs-lookup"><span data-stu-id="75988-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="75988-121">これにより、可能な操作は、既存の検索および保留リストの削除のみになります。</span><span class="sxs-lookup"><span data-stu-id="75988-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="75988-122">**詳細については、以下を参照してください。**</span><span class="sxs-lookup"><span data-stu-id="75988-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="75988-123">従来の電子情報開示検索と保持を Microsoft 365 コンプライアンス センターに移行する</span><span class="sxs-lookup"><span data-stu-id="75988-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="75988-124">従来の電子情報開示ツールの廃止</span><span class="sxs-lookup"><span data-stu-id="75988-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="75988-125">インプレース電子情報開示とインプレース ホールドに関するよくある質問</span><span class="sxs-lookup"><span data-stu-id="75988-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)


