---
title: 孤立したユーザーをオンプレミスサーバーから削除する
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/20/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1725"
- "9000179"
ms.openlocfilehash: 537ae7edebfa5a4ab71c2141d549d732ed4f883f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/14/2020
ms.locfileid: "47680140"
---
# <a name="delete-orphaned-user-from-on-premises-server"></a>孤立したユーザーをオンプレミスサーバーから削除する

次の手順に従い、孤立したユーザーを削除します。

1. 「[Azure Active Directory でのハイブリッド ID とは?](https://technet.microsoft.com/library/jj151771.aspx#bkmk_synchronizedirectories)」の手順に従い、ディレクトリ同期を強制します。

2. ディレクトリ同期を確認するには、「[Azure Active Directory でのハイブリッド ID とは?](https://technet.microsoft.com/library/jj151797.aspx)」を参照します。

3. 同期は正しく機能するが、Active Directory オブジェクトの削除が Azure AD に反映されない場合は、次の Windows PowerShell コマンドレット用 Azure Active Directory モジュールのいずれかを使用して、孤立したオブジェクトを手動で削除します。

    Remove-MsolContact  
    Remove-MsolGroup  
    Remove-MsolUser

    例えば、元はディレクトリ同期を使用して作成された孤立したユーザーID john.smith@contoso.com を削除するには、次のコマンドレットを実行します。

    Remove-MsolUser –UserPrincipalName John.Smith@Contoso.com