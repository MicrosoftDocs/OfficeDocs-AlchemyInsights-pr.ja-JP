---
title: Intune を使用して、管理している iOS デバイスのアクティベーション ロックをバイパスする
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1277"
- "6700008"
ms.openlocfilehash: 16be4e0cd2e47fe5d5888cbbe1380774f859e4d6
ms.sourcegitcommit: 07e56267dedfc4cec1143072c791670cbf81186b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2020
ms.locfileid: "45424325"
---
# <a name="bypass-activation-lock-on-supervised-ios-devices-with-intune"></a><span data-ttu-id="c9dd7-102">Intune を使用して、管理している iOS デバイスのアクティベーション ロックをバイパスする</span><span class="sxs-lookup"><span data-stu-id="c9dd7-102">Bypass activation lock on supervised iOS devices with Intune</span></span>

<span data-ttu-id="c9dd7-103">iOS デバイスのアクティベーション ロックをバイパスする機能を利用すると、ユーザーが会社のデバイスでアクティベーション ロックを有効にして会社を去るシナリオからの回復が容易になります。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-103">The ability to bypass the activation lock on iOS devices makes it easier to recover from the scenario where a user enables activation lock on a corporate device, and then leaves the company.</span></span>

<span data-ttu-id="c9dd7-104">アクティベーション ロックをバイパスするための前提条件:</span><span class="sxs-lookup"><span data-stu-id="c9dd7-104">Pre-requisites to bypassing an activation lock include:</span></span>

- <span data-ttu-id="c9dd7-105">「監視」されているデバイスです。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-105">A device is that is "supervised."</span></span>
- <span data-ttu-id="c9dd7-106">Intune での iOS デバイス制限ポリシーを使用して、アクティベーション ロックが正常に有効になります。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-106">The activation lock is successfully enabled using iOS Device restriction policy in Intune.</span></span>

<span data-ttu-id="c9dd7-107">また、アクティベーション ロックをバイパスする場合は、次の操作を行う必要があります:</span><span class="sxs-lookup"><span data-stu-id="c9dd7-107">In addition, when bypassing an activation lock, you should:</span></span>

- <span data-ttu-id="c9dd7-108">ワイプされるデバイスを物理的に所有します。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-108">Physically possess the device being wiped.</span></span>
- <span data-ttu-id="c9dd7-109">ワイプを実行する前に、コードをコピーします。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-109">Copy the code before you issue the wipe.</span></span>

<span data-ttu-id="c9dd7-110">**注:** ワイプ コードの大文字と小文字は区別されないため、「-」文字は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-110">**Note:** The wipe code is not case sensitive, so the "-" characters are not required.</span></span>

<span data-ttu-id="c9dd7-111">詳細については、[「Intune を使用して、管理している iOS デバイスのアクティベーション ロックをバイパスする」](https://docs.microsoft.com/intune/device-activation-lock-bypass) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-111">For details, see [Bypass Activation Lock on Supervised iOS devices with Intune](https://docs.microsoft.com/intune/device-activation-lock-bypass).</span></span>

<span data-ttu-id="c9dd7-112">**FAQ**</span><span class="sxs-lookup"><span data-stu-id="c9dd7-112">**FAQ**</span></span>

<span data-ttu-id="c9dd7-113">Q: **デバイスから会社のデータを削除するためのリモート アクションを発行したところ、保留状態のままになっています。**</span><span class="sxs-lookup"><span data-stu-id="c9dd7-113">Q: **I issued a remote action to remove company data from a device, and now it’s stuck in a pending state.**</span></span>

<span data-ttu-id="c9dd7-114">A: リモートアクションを正常に完了するには、対象のデバイスがオンラインで正常である必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-114">A: For a remote action to successfully complete, the targeted device must be online and healthy.</span></span> <span data-ttu-id="c9dd7-115">次のような状況では、リモート アクションは、30 日間、またはデバイスの場合デバイスがコマンドを認識するまで、保留状態になります:</span><span class="sxs-lookup"><span data-stu-id="c9dd7-115">In the following situations, the remote action stays in a pending state for 30 days, or until the device acknowledges the command when the device:</span></span>

- <span data-ttu-id="c9dd7-116">接続がありません。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-116">Does not have connectivity.</span></span>
- <span data-ttu-id="c9dd7-117">Intune で管理状態が失われています。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-117">Loses its management status with Intune.</span></span>

<span data-ttu-id="c9dd7-118">デバイスがチェックされず、会社のデータが削除されない場合は、[削除] を選択します。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-118">If you think a device is no longer checking in, and that it won’t remove company data, select Delete.</span></span> <span data-ttu-id="c9dd7-119">削除すると、デバイスのレコードが削除され、デバイスの Intune リストに表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-119">Deleting removes the device record so that it no longer appears in the Intune list of devices.</span></span> <span data-ttu-id="c9dd7-120">デバイスをもう一度アクティブにするには、デバイスを再登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-120">For the device to become active again, its user must re-enroll the device.</span></span>

<span data-ttu-id="c9dd7-121">Q: **特定のリモート アクションを使用できないのはなぜですか?**</span><span class="sxs-lookup"><span data-stu-id="c9dd7-121">Q: **Why are certain remote actions not available for me to use?**</span></span>

<span data-ttu-id="c9dd7-122">A: すべてのプラットフォームがすべてのリモート デバイス アクションをサポートしているわけではありません。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-122">A: Not all platforms support all remote device actions.</span></span> <span data-ttu-id="c9dd7-123">次のリモート アクションはプラットフォーム固有です。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-123">The following remote actions are platform-specific.</span></span>

- <span data-ttu-id="c9dd7-124">アクティベーション ロックのバイパス (iOS のみ)</span><span class="sxs-lookup"><span data-stu-id="c9dd7-124">Bypass Activation Lock (iOS only)</span></span>
- <span data-ttu-id="c9dd7-125">新たに開始 (Windows のみ)</span><span class="sxs-lookup"><span data-stu-id="c9dd7-125">Fresh Start (Windows only)</span></span>
- <span data-ttu-id="c9dd7-126">ロスト モード (iOS のみ)</span><span class="sxs-lookup"><span data-stu-id="c9dd7-126">Lost mode (iOS only)</span></span>
- <span data-ttu-id="c9dd7-127">デバイスの検索 (iOS のみ)</span><span class="sxs-lookup"><span data-stu-id="c9dd7-127">Locate device (iOS only)</span></span>
- <span data-ttu-id="c9dd7-128">再起動 (Windows のみ)</span><span class="sxs-lookup"><span data-stu-id="c9dd7-128">Restart (Windows only)</span></span>

<span data-ttu-id="c9dd7-129">各アクションの詳細については、[「使用可能なデバイス アクション」](https://docs.microsoft.com/intune/device-management#available-device-actions) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c9dd7-129">For more details about each action, see [Available device actions](https://docs.microsoft.com/intune/device-management#available-device-actions).</span></span>