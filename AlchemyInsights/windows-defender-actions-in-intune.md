---
title: Intune での Windows Defender のアクション
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1282"
- "6700008"
ms.openlocfilehash: 61a2411ce7c4578ecf2c32943c6a21edbf63eeee
ms.sourcegitcommit: e34bb95fb93250f1dc7aec6a13578bb3bb355935
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/28/2020
ms.locfileid: "45440607"
---
# <a name="windows-defender-actions-in-intune"></a><span data-ttu-id="d3717-102">Intune での Windows Defender のアクション</span><span class="sxs-lookup"><span data-stu-id="d3717-102">Windows Defender actions in Intune</span></span>

<span data-ttu-id="d3717-103">Intuneを使用して、個々のデバイスで Windows Defender のオンデマンドスキャンとウイルスシグネチャの更新をトリガーできます。</span><span class="sxs-lookup"><span data-stu-id="d3717-103">Intune can be used to trigger an on-demand scan and virus signature update for Windows Defender on individual devices.</span></span>

<span data-ttu-id="d3717-104">リモートアクションが正常にトリガーされた後、アクティビティが Windows Defender イベントログに反映されます。  </span><span class="sxs-lookup"><span data-stu-id="d3717-104">After a remote action is successfully triggered the activity is reflected in the Windows Defender event log.</span></span>

<span data-ttu-id="d3717-105">Windows のエンドポイント保護ポリシーでは、Windows Defender の追加設定機能を Intune で作成し、一連のデバイスに適用することができます。  </span><span class="sxs-lookup"><span data-stu-id="d3717-105">Windows Endpoint Protection policy allows additional settings for Windows Defender features to be created in Intune and applied to sets of devices.</span></span>

<span data-ttu-id="d3717-106">Windows Defender アクションのトリガーの詳細については、[オンデマンドの Microsoft Defender ウイルス対策スキャンを構成して実行する](https://docs.microsoft.com/windows/security/threat-protection/windows-defender-antivirus/run-scan-windows-defender-antivirus)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d3717-106">For more details on triggering Windows Defender actions, see [Configure and run on-demand Microsoft Defender Antivirus scans](https://docs.microsoft.com/windows/security/threat-protection/windows-defender-antivirus/run-scan-windows-defender-antivirus).</span></span>