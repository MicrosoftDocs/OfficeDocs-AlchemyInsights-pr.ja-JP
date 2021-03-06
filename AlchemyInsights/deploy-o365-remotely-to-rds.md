---
title: RDS、ターミナル サーバー、または VDI で共有して使用する Microsoft 365 Apps for enterprise の展開
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: ''
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: a57be7fcf9d8236a51dc4b38e33ad1c2ac717f11
ms.sourcegitcommit: 2eab0980268e08a58014459d44a08a1cc34a17d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2021
ms.locfileid: "51200678"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>RDS、ターミナル サーバー、または VDI で共有して使用する Microsoft 365 Apps for enterprise の展開

リモート デスクトップ サービス (RDS、旧称ターミナル サービス) を使用して Microsoft 365 Apps for enterprise を展開するには:

- Microsoft 365 For Business プラン、あるいは Microsoft 365 Apps for enterprise を含む Office 365 プラン (Office 365 Enterprise E3、Enterprise E5 など) が必要です。
   > [!NOTE]
   > Microsoft 365 Apps for business と Microsoft 365 Business Standard プランには Microsoft 365 Apps for enterprise が含まれていません。
- [共有コンピューターのライセンス認証](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation)を有効にする必要があります。

> [!NOTE]
> [Microsoft サポート/回復アシスタント](https://aka.ms/SaRA_OfficeSCA_M365Portal)をダウンロードして実行することによっても、Microsoft 365 Apps for enterprise を共有コンピューターのライセンス認証モードでインストールできます。

Office 展開ツールを使用したカスタム インストールの前提条件、セットアップ手順、ガイダンスについて詳しくは、「[リモート デスクトップ サービスを使用して Microsoft 365 Apps for enterprise を展開する](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services)」を参照してください。

共有コンピューターのライセンス認証に関連するエラーを修正するには:

- 「[Microsoft 365 Apps for enterprise に対する共有コンピューターのライセンス認証に関する問題のトラブルシューティング](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation)」を参照してください。
- 「[Microsoft 365 Apps for enterprise のライセンス認証の状態をリセットする](https://go.microsoft.com/fwlink/?linkid=2109218)」を参照してください。

Microsoft 365 管理センターから Microsoft 365 Apps for enterprise を RDS にインストールする場合 (***既定のインストール設定を使用***) には、以下の手順を使用します。

1. 契約しているサブスクリプションを確認します。 「[詳細](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have)」を参照してください。
2. 必要に応じて別のサブスクリプションに切り替えます。 「[詳細](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan)」を参照してください。
3. 他の Microsoft サブスクリプションを使用して Office が RDS サーバーに既にインストールされている場合には、アンインストールします。 たとえば、[**コントロール パネル**] >  [**プログラムのアンインストール**] の順に移動して行います。 問題が発生した場合には、[Microsoft サポート/回復アシスタント](https://aka.ms/SARA-OfficeUninstall-Alchemy)を使用してアンインストールしてください。
4. RDS サーバーで、管理者アカウントを使用して Microsoft 365 管理センターにサインインし、[Microsoft 365 Apps for enterprise をインストール](https://portal.office.com/OLS/MySoftware.aspx)します。
5. Office のインストール後は、Office アプリケーションを ***開いたり、サインインしたりしないでください***。
6. RDS サーバーで、次の手順に従ってレジストリを編集し、共有コンピューターのライセンス認証を有効にします。
   1. 画面の左下隅にある Windows ボタンを右クリックし、[**実行**] を選択します。 [名前] ボックスに **regedit** と入力し、[**OK**] を選択します。
   2. レジストリ エディターがデバイスに変更を加えられるようにするかどうかを尋ねるプロンプトが表示されたら、[**はい**] を選択します。
   3. レジストリ エディターで、HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration に文字列値 **SharedComputerLicensing** を追加し、1 を設定します。
   4. RDS サーバーで ***エンド ユーザーとしてサインインし***、[共有コンピューターのライセンス認証が Microsoft 365 Apps for enterprise に対して有効になっていることを確認します](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded)。
