---
title: API アクセス許可と同意
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004343"
- "7756"
ms.openlocfilehash: c99e5e2e8fb9bcc88e5221890ed9c28ed9e7d0c8
ms.sourcegitcommit: 605a73b159d30634b064c1b63b0e734ceb3fdec8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2021
ms.locfileid: "49975113"
---
# <a name="api-permissions-and-consent"></a>API アクセス許可と同意

Microsoft ID プラットフォームと統合するアプリケーションは、ユーザーと管理者がデータへのアクセス方法を制御できる承認モデルに従います。 承認モデルの実装は、Microsoft ID プラットフォーム エンドポイントで更新されています。 これにより、アプリが Microsoft ID プラットフォームを操作する方法が変更されます。 「[Microsoft ID プラットフォーム エンドポイントのアクセス許可と同意](https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent)」は、スコープ、アクセス許可、同意など、この承認モデルの基本的な概念を網羅しています。

[Azure Active Directory (Azure AD) 同意フレームワーク](https://docs.microsoft.com/azure/active-directory/develop/consent-framework)を使用すると、マルチテナント Web およびネイティブ クライアント アプリケーションを簡単に開発できます。 これらのアプリケーションでは、アプリケーションが登録されているものとは異なる Azure AD テナントからのユーザー アカウントによるサインインが可能です。 また、独自の Web API に加えて、Microsoft Graph API (Azure AD、Intune、および Microsoft 365 のサービスにアクセスするため) やその他の Microsoft サービスの API などの Web API にアクセスする必要がある場合もあります。

