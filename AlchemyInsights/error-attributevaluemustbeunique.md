---
title: エラー AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 35eb88624a5535e136ac1d01faf8e905bf00eb45
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2021
ms.locfileid: "51813765"
---
# <a name="error-attributevaluemustbeunique"></a>エラー: AttributeValueMustBeUnique

AttributeValueMustBeUnique エラーの最も一般的な原因は、SourceAnchor (immutableId) が異なる 2 つのオブジェクトの ProxyAddresses 属性または UserPrincipalName 属性の値が同じであることです。AttributeValueMustBeUnique エラーを修正するには、次の手順を実行します。
  
1. エラーの原因になっている重複した proxyAddresses、userPrincipalName、またはその他の属性値を特定します。また、競合に関係している 2 つ以上のオブジェクトを特定します。Azure AD Connect Health for sync によって生成されるレポートが 2 つのオブジェクトの特定に役立ちます。
    
2. 重複した値を持ち続けるオブジェクトとそうでないオブジェクトを識別します。
    
3. 重複した値を持たないはずのオブジェクトから重複した値を除去します。オブジェクトの供給元になっているディレクトリで変更を加える必要があることに注意してください。競合しているオブジェクトのいずれかを削除しなければならない場合もあります。
    
4. オンプレミス AD で変更を加えた場合は、Azure AD Connect 同期にエラーを修正するための変更を指示します。
    

