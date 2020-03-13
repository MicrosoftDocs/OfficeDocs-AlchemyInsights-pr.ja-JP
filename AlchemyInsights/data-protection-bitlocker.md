---
title: DataProtection - Bitlocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/30/2019
ms.locfileid: "40923551"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="200aa-102">Intune で Bitlocker 暗号化を有効にする</span><span class="sxs-lookup"><span data-stu-id="200aa-102">Enabling Bitlocker Encryption with Intune</span></span>

 <span data-ttu-id="200aa-103">Intune エンドポイント保護ポリシーを使用して、Windows デバイスの BitLocker 暗号化設定を構成できます。</span><span class="sxs-lookup"><span data-stu-id="200aa-103">Intune Endpoint Protection Policy can be used to configure Boitlocker encryption settings for Windows devices as described in : Windows10 (and later) settings to protect devices using Intune</span></span> <span data-ttu-id="200aa-104">詳細については、「[Intune を使用してデバイスを保護する Windows 10 以降の設定](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="200aa-104">For more information, see [Windows 10 (and later) settings to protect devices using Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).</span></span>
 
<span data-ttu-id="200aa-105">Windows 10 を実行する多くの新しいデバイスでは、MDM ポリシーの適用なしでトリガーされる自動 Bitlocker 暗号化をサポートしていることを、ユーザーは認識する必要があります。</span><span class="sxs-lookup"><span data-stu-id="200aa-105">You should be aware that many newer devices running Windows 10 support automatic bitlocker encryption which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="200aa-106">これは、非既定の設定が構成されている場合、ポリシーの適用に影響を与える可能性があります。</span><span class="sxs-lookup"><span data-stu-id="200aa-106">This may impact application of policy if non default settings are configured.</span></span> <span data-ttu-id="200aa-107">詳細については、次の FAQ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="200aa-107">See FAQ for more detail.</span></span>
 
<span data-ttu-id="200aa-108">Bitlocker の問題のトラブルシューティングについては、「[Microsoft Intune の BitLocker ポリシーのトラブルシューティング](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="200aa-108">For information about troubleshooting bitlocker issues, see [Troubleshoot BitLocker policies in Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).</span></span>
 
 
<span data-ttu-id="200aa-109">**FAQ**</span><span class="sxs-lookup"><span data-stu-id="200aa-109">**FAQ**</span></span>

 <span data-ttu-id="200aa-110">Q: エンドポイント保護ポリシーを使用するデバイスの暗号化をサポートする Windows のエディションはどれですか?</span><span class="sxs-lookup"><span data-stu-id="200aa-110">FAQ Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span><br>
 <span data-ttu-id="200aa-111">A: Intune エンドポイント保護ポリシーの設定は、[Bitlocker CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp) を使用して実装されています。</span><span class="sxs-lookup"><span data-stu-id="200aa-111">[](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp)A: The settings in Intune Endpoint Protection Policy  are implemented using the Bitlocker CSP.</span></span> <span data-ttu-id="200aa-112">すべての Windows のエディションまたはビルドで Bitlocker CSP をサポートしているわけではありません。</span><span class="sxs-lookup"><span data-stu-id="200aa-112">Not all editions nor builds of Windows support the Bitlocker CSP.</span></span> <br><br>
      <span data-ttu-id="200aa-113">現時点では、次の Windows エディションがサポートされています。Enterprise、Education、Mobile、Mobile Enterprise および Professional (ビルド 1809 以降)。</span><span class="sxs-lookup"><span data-stu-id="200aa-113">At this time, the following Windows editions are supported: Enterprise, Education, Mobile, Mobile Enterprise, and Professional (build 1809 and later).</span></span>
 
<span data-ttu-id="200aa-114">Q: デバイスが、暗号化方法と暗号強度 (XTS-AES-128) に対する OS の既定の設定を使用している Bitlocker で暗号化されている場合、新しい設定を使用してドライブの再暗号化を自動でトリガーできる、設定の異なるポリシーを適用することはできますか?</span><span class="sxs-lookup"><span data-stu-id="200aa-114">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128)  will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span><br>
<span data-ttu-id="200aa-115">A: いいえ。</span><span class="sxs-lookup"><span data-stu-id="200aa-115">A: No.</span></span> <span data-ttu-id="200aa-116">新しい暗号の設定を適用するには、ドライブの暗号化を最初に解除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="200aa-116">In order to apply the new cipher settings the drive must first be decrypted.</span></span><br><br>
<span data-ttu-id="200aa-117">**注**: OOBE 中に行われる Autopilot の自動暗号化を使用してデバイスが登録されている場合は、OS の既定値の代わりに使用されるポリシー ベースの設定を許可する Intune ポリシーが評価されるまで、トリガーされません。</span><span class="sxs-lookup"><span data-stu-id="200aa-117">Note For devices being enrolled with Autopilot the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated which allows the policy based settings to be used in place of the OS defaults</span></span>
 
<span data-ttu-id="200aa-118">Q: Intune ポリシーを適用した結果としてデバイスが暗号化されている場合、そのポリシーが削除されれば、デバイスの暗号は解除されますか?</span><span class="sxs-lookup"><span data-stu-id="200aa-118">Q If a device is encrypted as a result of the  application of Intune policy will it be decrypted when that policy is removed?</span></span><br>
<span data-ttu-id="200aa-119">A: 暗号化関連のポリシーを削除しても、構成されたドライブの暗号は解除されません。</span><span class="sxs-lookup"><span data-stu-id="200aa-119">A: Removal of encryption related policy does NOT result in decryption of the drives which were configured.</span></span>
 
<span data-ttu-id="200aa-120">Q: Intune コンプライアンス ポリシーで、Bitlocker が有効になっているにもかかわらず有効になっていないと表示されるのはどうしてですか?</span><span class="sxs-lookup"><span data-stu-id="200aa-120">Q: Why does Intune Compliance Policy show that my device does not have Bitlocker enabled, even though it is?</span></span><br>
<span data-ttu-id="200aa-121">A: Intune コンプライアンス ポリシーの「Bitlocker 有効」設定では、 Windows デバイス正常性構成証明 (DHA) のクライアントを利用します。</span><span class="sxs-lookup"><span data-stu-id="200aa-121">A: The "Bitlocker enabled" setting in the Intune Compliance Policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="200aa-122">このクライアントは、ブート時のデバイスの状態のみ評価します。</span><span class="sxs-lookup"><span data-stu-id="200aa-122">This client only measures device state at boot time.</span></span> <span data-ttu-id="200aa-123">そのため、Bitlocker 暗号化が完了してからデバイスが再起動されていない場合、DHA クライアント サービスでは Bitlocker をアクティブな状態として報告しません。</span><span class="sxs-lookup"><span data-stu-id="200aa-123">So if a device has not been rebooted since bitlocker encryption was completed the DHA client service will not report bitlocker as being active.</span></span>
 
 