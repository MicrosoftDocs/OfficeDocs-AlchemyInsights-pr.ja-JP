---
title: SMTP 認証の問題を解決する
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3000003"
- "5652"
ms.openlocfilehash: 814c49e8e65966a0c9f927b1f7bfb03d3dc3d637
ms.sourcegitcommit: 0e43e19448705f151846e9e9e1e0f47e12938fdf
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/15/2020
ms.locfileid: "44282090"
---
# <a name="solving-smtp-authentication-issues"></a>SMTP 認証の問題を解決する

SMTP メールを送信してクライアントまたはアプリケーションで認証しようとしたときにエラー 5.7.57 または 5.7.3 が発生した場合は、いくつかの点を確認する必要があります。

- 認証済みの SMTP 送信が、テナントまたは使用しようとしているメールボックスで無効になっている可能性があります (両方の設定を確認します)。 詳しくは、「[認証済みのクライアント SMTP 送信を有効または無効にする](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission)」をご覧ください。

- テナントで [Azure Security Defaults](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) が有効になっているかどうかを確認します。有効になっていると、基本認証 (従来の認証とも呼ばれます。これはユーザー名とパスワードを使用します) を使用した SMTP 認証は失敗します。