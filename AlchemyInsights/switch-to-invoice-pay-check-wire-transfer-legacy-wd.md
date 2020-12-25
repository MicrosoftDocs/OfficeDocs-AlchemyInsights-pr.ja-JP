---
title: 請求書による支払いへの切り替え (小切手/電信送金) - 従来の WD
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004168"
- "7343"
ms.openlocfilehash: 1be90771f994e832960383b1cb5e0bee8f5b08f8
ms.sourcegitcommit: b561c339926fad609950ac92744c3cd91e0a68fa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/21/2020
ms.locfileid: "49726181"
---
# <a name="switch-to-invoice-pay-chequewire-transfer---legacy-wd"></a><span data-ttu-id="ff194-102">請求書による支払いへの切り替え (小切手/電信送金) - 従来の WD</span><span class="sxs-lookup"><span data-stu-id="ff194-102">Switch to invoice pay (cheque/wire transfer) - Legacy WD</span></span>

<span data-ttu-id="ff194-103">請求書による支払いに切り替えると、請求書の日付から 30 日以内に請求書を支払うことになります。</span><span class="sxs-lookup"><span data-stu-id="ff194-103">If you switch to pay by invoice, that means you will pay your bill within 30 days of the invoice date.</span></span> <span data-ttu-id="ff194-104">請求書で Azure サブスクリプションの支払いを受ける資格を得るには、Azure サポートにリクエストを送信してください。</span><span class="sxs-lookup"><span data-stu-id="ff194-104">To become eligible to pay for your Azure subscription by invoice, submit a request to Azure support.</span></span> <span data-ttu-id="ff194-105">リクエストが承認されると、 [Azure portal](https://portal.azure.com/) でサブスクリプションを請求書による支払いに切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="ff194-105">Once your request is approved, you can switch a subscription to invoice pay in the [Azure portal](https://portal.azure.com/).</span></span>

<span data-ttu-id="ff194-106">**先に進む前に、請求書による支払いオプションのリクエストに関する次の要件および制限を確認してください。**</span><span class="sxs-lookup"><span data-stu-id="ff194-106">**Before you proceed further, review the following requirements/limitations on requesting invoice payment option:**</span></span>

- <span data-ttu-id="ff194-107">[Azure portal](https://portal.azure.com/) にログインし、支払方法に移動します。</span><span class="sxs-lookup"><span data-stu-id="ff194-107">Log in to [Azure portal](https://portal.azure.com/) and navigate to payment methods.</span></span> <span data-ttu-id="ff194-108">請求書による支払いがすでに事前承認されているかどうかを確認してください。</span><span class="sxs-lookup"><span data-stu-id="ff194-108">Check if you are already pre-approved for invoice payment.</span></span>
- <span data-ttu-id="ff194-109">請求書の支払いは、個人アカウントではなく、ビジネス アカウントでのみ利用できます。</span><span class="sxs-lookup"><span data-stu-id="ff194-109">Invoice pay is only available for business accounts, not for personal accounts.</span></span>
- <span data-ttu-id="ff194-110">請求書支払いに切り替える前に、すべての未払い料金を支払う必要があります。</span><span class="sxs-lookup"><span data-stu-id="ff194-110">You must pay all outstanding charges before switching to invoice pay.</span></span>
- <span data-ttu-id="ff194-111">サポートチームはアカウントを確認して、請求書による支払いの対象かどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="ff194-111">The support team will review the account to determine if it is eligible for invoice mode of payment.</span></span>
- <span data-ttu-id="ff194-112">請求書による支払いモードは、Marketplace のサード パーティ サービスではサポートされていません。現在のサブスクリプションを Marketplace またはサード パーティのサービスを含む請求書に切り替える場合は、切り替える前にこれらのサービスを削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ff194-112">Invoice mode of payment is not supported for marketplace 3rd party services; if you intend to switch a current subscription to an invoice that contains marketplace or 3rd party services, these services must be deleted before switching.</span></span> <span data-ttu-id="ff194-113">今後の Marketplace のサービスについては、最初にクレジット カードで個別のサブスクリプションを購入してから、Marketplace のサード パーティ サービスを購入または展開します。</span><span class="sxs-lookup"><span data-stu-id="ff194-113">For future marketplace services, purchase a separate subscription on credit card first and then purchase or deploy marketplace 3rd party services.</span></span>
- <span data-ttu-id="ff194-114">請求書による支払いに切り替えると、クレジット カードまたはデビット カードによる支払いに戻すことはできません。</span><span class="sxs-lookup"><span data-stu-id="ff194-114">Once you switch to invoice pay, you can't switch back to credit or debit card payment.</span></span>

<span data-ttu-id="ff194-115">*請求書による支払いが承認されたら*、 [Azure portal](https://portal.azure.com/) で小切手または電信送金を介して Azure サブスクリプションを請求書による支払いに切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="ff194-115">*Once you're approved to pay by invoice*, you can switch your Azure subscription to the invoice pay via cheque or wire transfer in the [Azure portal](https://portal.azure.com/).</span></span>
<span data-ttu-id="ff194-116">それには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="ff194-116">To do that:</span></span>

1. <span data-ttu-id="ff194-117">アカウント管理者として  [Azure ポータル](https://portal.azure.com/) にサインインします。</span><span class="sxs-lookup"><span data-stu-id="ff194-117">Sign in to the [Azure portal](https://portal.azure.com/) as the Account Administrator.</span></span> <span data-ttu-id="ff194-118">" **コストの管理と課金**" を検索して選択します。</span><span class="sxs-lookup"><span data-stu-id="ff194-118">Search for and select **Cost Management + Billing**.</span></span>
2. <span data-ttu-id="ff194-119">請求書による支払いに切り替えるサブスクリプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="ff194-119">Select the subscription you would like to switch to invoice payment.</span></span> <span data-ttu-id="ff194-120">**支払方法** を選択します。</span><span class="sxs-lookup"><span data-stu-id="ff194-120">Select **Payment methods**.</span></span>
3. <span data-ttu-id="ff194-121">コマンド バーで **[請求書による支払い]** ボタンをクリックします。</span><span class="sxs-lookup"><span data-stu-id="ff194-121">In the command bar, click the **Pay by invoice** button.</span></span>

<span data-ttu-id="ff194-122">**おすすめのドキュメント**</span><span class="sxs-lookup"><span data-stu-id="ff194-122">**Recommended Documents**</span></span>

- [<span data-ttu-id="ff194-123">Azure の請求書と使用状況データをリクエスト/ダウンロード/表示する</span><span class="sxs-lookup"><span data-stu-id="ff194-123">Request/Download/View your Azure billing invoice and usage data</span></span>](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date)
- [<span data-ttu-id="ff194-124">Azure の請求書を受信トレイに直接送信する方法</span><span class="sxs-lookup"><span data-stu-id="ff194-124">How to email Azure invoices directly to your inbox</span></span>](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date)
- [<span data-ttu-id="ff194-125">請求書での支払い</span><span class="sxs-lookup"><span data-stu-id="ff194-125">Pay by invoice</span></span>](https://docs.microsoft.com/azure/billing/billing-how-to-pay-by-invoice)
- [<span data-ttu-id="ff194-126">使用料金の詳細を理解する</span><span class="sxs-lookup"><span data-stu-id="ff194-126">Understand detailed usage charges</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-your-bill)
- [<span data-ttu-id="ff194-127">請求書の用語を理解する</span><span class="sxs-lookup"><span data-stu-id="ff194-127">Understand terms on your invoice</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-your-invoice)
- [<span data-ttu-id="ff194-128">所有権を譲渡する方法</span><span class="sxs-lookup"><span data-stu-id="ff194-128">How to transfer ownership</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer)