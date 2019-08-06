---
title: ワークフローが開始されていません
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: efd17c302ae6d857207e87e94d74d3794e94a83a
ms.sourcegitcommit: 204be4a6ae03700b75eae6b09b4e9ab283089fbf
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/03/2019
ms.locfileid: "36180408"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="46fb5-102">ワークフローが開始されていません</span><span class="sxs-lookup"><span data-stu-id="46fb5-102">Workflow is not starting</span></span>

- <span data-ttu-id="46fb5-103">SharePoint 2010 と SharePoint 2013 ワークフローが開始していません。</span><span class="sxs-lookup"><span data-stu-id="46fb5-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    <span data-ttu-id="46fb5-104">ワークフローが開始されていない場合、ワークフローの進行状況で断続的に遅延が発生する可能性がある一時的なサービスの問題が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46fb5-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="46fb5-105">[サービス正常性ダッシュボード](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth)をチェックして、組織が影響を受けているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="46fb5-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    <span data-ttu-id="46fb5-106">この問題が最初に発生してから24時間以上経過している場合は、サポートチケットをログに記録してください。</span><span class="sxs-lookup"><span data-stu-id="46fb5-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="46fb5-107">多くの場合、すでに解決策に取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="46fb5-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="46fb5-108">解決策を完成させるために少なくとも 24 時間を与えてください。</span><span class="sxs-lookup"><span data-stu-id="46fb5-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="46fb5-109">SharePoint 2010 のワークフローが開始時に遅延します。</span><span class="sxs-lookup"><span data-stu-id="46fb5-109">SharePoint 2010 workflows delayed on start.</span></span>

    <span data-ttu-id="46fb5-110">これは、ワークフローが大きなバッチでトリガーされた場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="46fb5-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="46fb5-111">(たとえば、一度に複数のアイテムが追加された場合)。</span><span class="sxs-lookup"><span data-stu-id="46fb5-111">(for example, when several items are added at once).</span></span>

    <span data-ttu-id="46fb5-112">ワークフローはリアルタイムで実行するように設計されていないため、遅延はデザインの動作になります。</span><span class="sxs-lookup"><span data-stu-id="46fb5-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

    <span data-ttu-id="46fb5-113">ワークフローが複雑な拡張可能なオブジェクトマークアップ言語 (XMOL) の場合、コンパイルが遅くなることがあります。</span><span class="sxs-lookup"><span data-stu-id="46fb5-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="46fb5-114">[この](https://support.microsoft.com/en-us/kb/3043697)記事を確認してください。</span><span class="sxs-lookup"><span data-stu-id="46fb5-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    <span data-ttu-id="46fb5-115">ワークフローを簡素化するか、Microsoft SharePoint 2013 ワークフロープラットフォームの種類を使用して再設計する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46fb5-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    <span data-ttu-id="46fb5-116">また、ワークフロー履歴が大きくなっている場合は、アイテムを削除するか、新しい履歴リストを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="46fb5-116">Also, if your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

    <span data-ttu-id="46fb5-117">詳細情報:[ワークフロー履歴の削除](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="46fb5-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="46fb5-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="46fb5-118">Related topics</span></span>
<span data-ttu-id="46fb5-119">SharePoint Online で Micrsoft のフローを試す必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="46fb5-119">Want to try Micrsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="46fb5-120">フローを作成する</span><span class="sxs-lookup"><span data-stu-id="46fb5-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="46fb5-121">SharePoint およびフロー</span><span class="sxs-lookup"><span data-stu-id="46fb5-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 

