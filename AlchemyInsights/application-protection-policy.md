---
title: アプリケーション保護ポリシー
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/22/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1073"
- "6700006"
ms.openlocfilehash: 7fed65e6749f72e6264070b360a52e72968fc8da
ms.sourcegitcommit: 6f7cbf1dc28c0693009ddf03d9768c1c65018964
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/22/2020
ms.locfileid: "45424305"
---
# <a name="application-protection-policy"></a><span data-ttu-id="fe068-102">アプリケーション保護ポリシー</span><span class="sxs-lookup"><span data-stu-id="fe068-102">Application protection policy</span></span>

<span data-ttu-id="fe068-103">アプリケーション保護ポリシー (APP) を初めて使用する場合は、[「アプリ保護ポリシーの概要」](https://docs.microsoft.com/intune/apps/app-protection-policy) を確認してください。</span><span class="sxs-lookup"><span data-stu-id="fe068-103">If you're new to Application protection policy (APP), check out the [App protection policies overview](https://docs.microsoft.com/intune/apps/app-protection-policy).</span></span>

<span data-ttu-id="fe068-104">APP の使用を開始するには、[「アプリ保護ポリシーを作成して割り当てる方法」](https://docs.microsoft.com/intune/app-protection-policies) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fe068-104">To start using APP, see [How to create and assign app protection policies](https://docs.microsoft.com/intune/app-protection-policies).</span></span>

<span data-ttu-id="fe068-105">アプリケーション保護ポリシーの要件:</span><span class="sxs-lookup"><span data-stu-id="fe068-105">Application protection policy requirements:</span></span>

- <span data-ttu-id="fe068-106">ユーザーが Intune または EMS ライセンスを持っています。</span><span class="sxs-lookup"><span data-stu-id="fe068-106">User has an Intune or EMS license.</span></span>
- <span data-ttu-id="fe068-107">ユーザーは、アプリケーション保護ポリシーの対象グループに属します。</span><span class="sxs-lookup"><span data-stu-id="fe068-107">User belongs to a group targeted by application protection policies.</span></span>
- <span data-ttu-id="fe068-108">1 人の企業ユーザーのみが、デバイス上の保護されたアプリにサインインします。</span><span class="sxs-lookup"><span data-stu-id="fe068-108">Only one corporate user is signed into protected apps on a device.</span></span>
- <span data-ttu-id="fe068-109">アプリケーションは、[Intune SDK](https://docs.microsoft.com/intune/app-sdk-get-started) を実装しています。</span><span class="sxs-lookup"><span data-stu-id="fe068-109">The application has implemented the [Intune SDK](https://docs.microsoft.com/intune/app-sdk-get-started).</span></span> <span data-ttu-id="fe068-110">SDK をサポートするアプリのリストについては、[「Microsoft Intune 保護アプリ」](https://docs.microsoft.com/intune/apps-supported-intune-apps) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fe068-110">For a list of apps that support the SDK, see [Microsoft Intune protected apps](https://docs.microsoft.com/intune/apps-supported-intune-apps).</span></span>

<span data-ttu-id="fe068-111">ポリシーは、上記の要件を満たしているユーザーが Intune SDK を有効にしたアプリにサインインすると適用されます。</span><span class="sxs-lookup"><span data-stu-id="fe068-111">Policies apply after a user who meets the above requirements signs into an Intune SDK enabled app.</span></span> <span data-ttu-id="fe068-112">ポリシーが適用されているかどうかを判断する最も簡単な方法は、ユーザーがポリシーにピンを設定することを要求することです。</span><span class="sxs-lookup"><span data-stu-id="fe068-112">The easiest way to determine if a policy is applied is by requiring that the user set a pin in the policy.</span></span> 

<span data-ttu-id="fe068-113">詳細については、以下を参照してください:</span><span class="sxs-lookup"><span data-stu-id="fe068-113">For more information, see:</span></span>

[<span data-ttu-id="fe068-114">APP/MAM のトラブルシューティングに関する FAQ</span><span class="sxs-lookup"><span data-stu-id="fe068-114">APP/MAM troubleshooting FAQ</span></span>](https://docs.microsoft.com/intune/apps/troubleshoot-mam)  

[<span data-ttu-id="fe068-115">アプリ保護ポリシーのセットアップを検証する方法</span><span class="sxs-lookup"><span data-stu-id="fe068-115">How to validate your app protection policy setup</span></span>](https://docs.microsoft.com/intune/app-protection-policies-validate)

[<span data-ttu-id="fe068-116">アプリ保護ポリシーの配布タイミングを理解する</span><span class="sxs-lookup"><span data-stu-id="fe068-116">Understand App Protection Policy delivery timing</span></span>](https://docs.microsoft.com/intune/app-protection-policy-delivery)  

[<span data-ttu-id="fe068-117">アプリ保護ポリシーを監視する方法</span><span class="sxs-lookup"><span data-stu-id="fe068-117">How to monitor app protection policies</span></span>](https://docs.microsoft.com/intune/app-protection-policies-monitor)