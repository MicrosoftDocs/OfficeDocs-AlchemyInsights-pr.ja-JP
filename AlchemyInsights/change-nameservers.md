---
title: ネーム サーバーを変更する
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 67680a6fa514d31ccb88cc8691a199cd1f58a402
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2021
ms.locfileid: "51818617"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a>Microsoft を指すようにドメイン ネームサーバーを更新する

注: ネーム サーバーの変更は、反映されるまで最大 48 時間かかる場合があります。
  
Microsoft 365 でドメインを設定するには、レジストラーのネーム サーバーを更新する必要があります。ドメイン レジストラーでネーム サーバー レコードを作成または編集します。
  
1. ご利用のドメイン レジストラーの Web サイトにアクセスして、ネーム サーバーを編集できる領域を見つけます。
  
2. 以下の値に一致する 2 つのネーム サーバー レコードを作成または編集します。

  - ns1.bdm.microsoftonline.com

  - ns2.bdm.microsoftonline.com

3. 変更を保存します。

詳細な手順については、「[任意のドメイン レジストラーでネームサーバーを変更する](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)」も参照してください。
  