---
title: デバイスの書き戻し
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003257"
- "8279"
ms.openlocfilehash: f1a8dba19d220e1154549507801c813f56fe5cdd
ms.sourcegitcommit: 0470a728d184ceb89d1419f7ed57166e07bb778b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2021
ms.locfileid: "50257023"
---
# <a name="device-writeback"></a>デバイスの書き戻し

デバイスの書き戻しは、次のようなシナリオで使用します。

- [ハイブリッド証明書信頼の展開を使用した Windows Hello for Business ](https://docs.microsoft.com/windows/security/identity-protection/hello-for-business/hello-hybrid-cert-trust-prereqs#device-registration)を有効にします。
- ADFS (2012 R2 以降) で保護されたアプリケーション (証明書利用者の信頼) へのデバイスに基づく条件付きアクセスを有効にします。

    > [!NOTE]
    > デバイスの書き戻しには、Azure AD Premium のサブスクリプションが必要です。

これにより、セキュリティが強化され、アプリケーションへのアクセスが信頼されたデバイスに対してのみ許可されることが保証されます。 条件付きアクセスの詳細については、「[条件付きアクセス ポリシーを使用したリスクの管理](https://docs.microsoft.com/azure/active-directory/conditional-access/overview)」と「[Azure Active Directory Device Registration を使用したオンプレミスの条件付きアクセスの設定](https://docs.microsoft.com/azure/active-directory/devices/overview)」を参照してください。

デバイスの書き戻しの有効化に関する詳細については、「[デバイスの書き戻しを有効にする](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-device-writeback)」を参照してください。
