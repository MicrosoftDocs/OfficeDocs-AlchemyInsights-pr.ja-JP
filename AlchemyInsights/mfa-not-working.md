---
title: MFA の問題
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 2e79040c249b7825b964a19c51bcc42e5a6afb3f
ms.sourcegitcommit: 514ced512d0d7fff485b6fbf236cd27d6b4166e0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/26/2019
ms.locfileid: "35250170"
---
# <a name="issues-with-mfa"></a><span data-ttu-id="040c1-102">MFA の問題</span><span class="sxs-lookup"><span data-stu-id="040c1-102">Issues with MFA</span></span>
<span data-ttu-id="040c1-103">ユーザーが多要素認証 (MFA) を使用してログインできないかどうかを確認する方法がいくつかあります。</span><span class="sxs-lookup"><span data-stu-id="040c1-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="040c1-104">影響を受けるユーザーが Azure Active Directory ポータルでブロックされている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="040c1-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="040c1-105">そのような場合は、その特定のユーザーの認証試行が自動的に拒否されます。</span><span class="sxs-lookup"><span data-stu-id="040c1-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="040c1-106">問題を解決するには、この記事の手順を実行してください。</span><span class="sxs-lookup"><span data-stu-id="040c1-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="040c1-107">ユーザーのブロックを解除しても問題が解決しない場合や、ユーザーがブロックされていない場合は、ユーザーの MFA をリセットしてから、登録プロセスを繰り返します。</span><span class="sxs-lookup"><span data-stu-id="040c1-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="040c1-108">この記事の手順に従ってください。</span><span class="sxs-lookup"><span data-stu-id="040c1-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="040c1-109">MFA を初めて有効にして、ユーザーが Outlook や Skype などのブラウザー以外のクライアントにログインできない場合は、O365 サブスクリプションで ADAL (Active Directory 認証ライブラリ) が有効になっていない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="040c1-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="040c1-110">この場合は、Exchange Online Powershell に接続して、次のコマンドレットを実行する必要があります:   *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span><span class="sxs-lookup"><span data-stu-id="040c1-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>