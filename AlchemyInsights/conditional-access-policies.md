---
title: 条件付きアクセス ポリシー
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002357"
- "4583"
ms.openlocfilehash: 8ce41d007988f2a45f1ded385ae50ac3def97c1b
ms.sourcegitcommit: 9923ce61344e22c4490549b12f65fa2896490b1f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "43109200"
---
# <a name="conditional-access-policies"></a><span data-ttu-id="97f56-102">条件付きアクセス ポリシー</span><span class="sxs-lookup"><span data-stu-id="97f56-102">Conditional Access policies</span></span>

<span data-ttu-id="97f56-103">条件付きアクセスとは、環境内のアプリへのアクセスを特定の条件に基づいて制御する、中央の場所から管理される Azure AD の機能のことです。</span><span class="sxs-lookup"><span data-stu-id="97f56-103">Conditional Access is a capability of Azure AD that enables you to enforce controls on the access to apps in your environment, all based on specific conditions and managed from a central location.</span></span>

<span data-ttu-id="97f56-104">詳細については「[Azure AD 条件付きアクセス](https://docs.microsoft.com/azure/active-directory/conditional-access/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97f56-104">Learn more about [Azure AD Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/).</span></span>  

<span data-ttu-id="97f56-105">**注**: 2019 年 10 月 21 日以降にテナントが作成され、予期せず MFA の入力を求められた場合は、テナントで[セキュリティの既定](http://aka.ms/securitydefaults)が有効になっている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="97f56-105">**Note**: If your tenant was created after October 21st, 2019 and you're unexpectedly getting prompted for MFA, you likely have [security defaults](http://aka.ms/securitydefaults) enabled in your tenant.</span></span>

<span data-ttu-id="97f56-106">**セキュリティの既定値を管理するには**</span><span class="sxs-lookup"><span data-stu-id="97f56-106">**To Manage security defaults**</span></span>

1. <span data-ttu-id="97f56-107">グローバル管理者の資格情報を使用して、[管理センター](https://go.microsoft.com/fwlink/p/?linkid=834822)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="97f56-107">Sign in to the [admin center](https://go.microsoft.com/fwlink/p/?linkid=834822) with your Global admin credentials.</span></span>

2. <span data-ttu-id="97f56-108">[Azure Active Directory](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties) にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="97f56-108">Go to [Azure Active Directory Properties](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span></span>

3. <span data-ttu-id="97f56-109">ページの下部で、[**セキュリティの既定値の管理**] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="97f56-109">At the bottom of the page, click **Manage Security defaults**.</span></span>

4. <span data-ttu-id="97f56-110">セキュリティの既定値を有効にするには **[はい]** をクリックし、セキュリティの既定値を無効にするには **[いいえ]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="97f56-110">Click **Yes** to enable security defaults or **No** to disable security defaults.</span></span>