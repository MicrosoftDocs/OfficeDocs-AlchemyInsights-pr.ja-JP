---
title: Mac または Linux への Microsoft Defender のインストールに関する問題
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6028"
- "9001222"
ms.openlocfilehash: 39f180852fd0438597fa1ce665b2703fbc7b1aa4
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539685"
---
# <a name="issues-installing-microsoft-defender-on-mac-or-linux"></a>Mac または Linux への Microsoft Defender のインストールに関する問題

**Mac**

- Microsoft Defender ATP for Mac をインストールする前に、システム要件が満たされていることを確認してください。 詳細については、[「Microsoft Defender ATP for Macのインストール方法」](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac)をご覧ください。  
- ファイル内の情報を確認します。「/Library/Logs/Microsoft/mdatp/install.log」。

**Linux**

- Linux 用の Microsoft Defender ATP をインストールする前に、システム要件が満たされていることを確認してください。 詳細については、「[Linux に MDATP をインストールする方法](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements)」を参照してください。 
- MDATPサービスが実行されていることを確認するには、[「インストールに失敗しました」](/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed)をご覧ください。  
    サービスが実行されていない場合の問題のトラブルシューティングと解決については、[「mdatpサービスが実行されていない場合のトラブルシューティングの手順」](/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running)をご覧ください。
- 製品の正常性を検証するクライアント構成を確認し、EICAR テキストファイルで検出テストを実行する手順については、[「クライアント構成」](/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration)をご覧ください。  

    **注** オンアクセスアクティビティでサポートされているファイルシステムのリストについては、[ 「Microsoft Defender ATP for Linux」](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements)をご覧ください。