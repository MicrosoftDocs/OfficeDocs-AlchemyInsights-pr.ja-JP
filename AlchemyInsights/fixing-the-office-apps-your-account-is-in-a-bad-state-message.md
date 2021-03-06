---
title: Microsoft 365 アプリのアカウントの状態が正しくありません。エラーを修正する
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: 4654b49289a455c1e6641f47fae573d2fcebc717
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2021
ms.locfileid: "51812541"
---
# <a name="fixing-the-microsoft-365-apps-your-account-is-in-a-bad-state-error"></a>Microsoft 365 アプリの「アカウントの状態が正しくありません。」エラーを修正する

このエラーを修正するには、影響を受けているコンピューター上で以下のオプションを試してみてください。

- Office アプリを開き、[**ファイル**] > [**アカウント**] > [**すべてのアカウントからサインアウト**] を選択します。 ライセンスが有効なユーザー アカウントを使用して、もう一度サインインします。 詳細については、「[Office のアカウント](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)」を参照してください。
- Windows 資格情報マネージャーを使用して、[Office の資格情報をクリア](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer)します。<br>
  **注:** Office 2016 のレジストリ パスは 16.0 に変更されています。 たとえば、\Software\Microsoft\Office\16.0\Common\Identity\
- Office 2013 を使用して Office 365 に接続している最中にエラーが発生した場合には、Office クライアントの[先進認証を有効](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication)にします。

詳細については、「[Microsoft 365、Azure、または Intune にサインインできない非ブラウザー アプリをトラブルシューティングする方法](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)」を参照してください。

