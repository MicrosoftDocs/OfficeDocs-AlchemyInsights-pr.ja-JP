---
title: グリッド内のさまざまなレコード数を示すグラフ
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/24/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5611"
- "9002930"
ms.openlocfilehash: 3d0be28c783bb129d05484565c6c2a56ac5e0acf
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/28/2020
ms.locfileid: "45440567"
---
# <a name="chart-shows-different-number-of-records-in-grid"></a><span data-ttu-id="86a5e-102">グリッド内のさまざまなレコード数を示すグラフ</span><span class="sxs-lookup"><span data-stu-id="86a5e-102">Chart shows different number of records in grid</span></span>

<span data-ttu-id="86a5e-103">**現象**</span><span class="sxs-lookup"><span data-stu-id="86a5e-103">**Symptom**</span></span>

<span data-ttu-id="86a5e-104">ダッシュボードページのグラフに、グラフ"..."をクリックし、[レコードを表示]グリッドをクリックすると、ページに移動してすべてのレコードを表示することができます。レコードの数が変わることがあります。</span><span class="sxs-lookup"><span data-stu-id="86a5e-104">For chart on dashboard page, when you click on chart "…" and click "View records", you navigate to grid page to see all the records.Sometimes, the number of records changes.</span></span>

<span data-ttu-id="86a5e-105">**原因**</span><span class="sxs-lookup"><span data-stu-id="86a5e-105">**Cause**</span></span>

<span data-ttu-id="86a5e-106">これは、元のダッシュボードページ上のグラフとグリッドのホームページのグラフのビューの違いが原因です。</span><span class="sxs-lookup"><span data-stu-id="86a5e-106">This is due to the difference of views between the chart on the original dashboard page and the chart on the grid home page.</span></span>  

<span data-ttu-id="86a5e-107">**解決方法**</span><span class="sxs-lookup"><span data-stu-id="86a5e-107">**Solution**</span></span>

1. <span data-ttu-id="86a5e-108">元のページとグリッドのビューを見て、それらが異なるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="86a5e-108">Check the view from the original page and the view in the grid to see if they are different.</span></span>
2. <span data-ttu-id="86a5e-109">元のページのビューと一致するようにグリッドのビューを変更します。</span><span class="sxs-lookup"><span data-stu-id="86a5e-109">Change the view in grid to match the view in the original page.</span></span>
3. <span data-ttu-id="86a5e-110">正しいビューが見つからない場合は、通常、アプリデザイナーでビューが有効になっていないことを意味します。</span><span class="sxs-lookup"><span data-stu-id="86a5e-110">If the correct view cannot be found, usually it means the view is not enabled in app designer.</span></span>
4. <span data-ttu-id="86a5e-111">特定のアプリのアプリデザイナーに移動して、エンティティとビューを選択し、変更を希望するビューで有効、保存、発行にチェックを入れてから閉じます。</span><span class="sxs-lookup"><span data-stu-id="86a5e-111">Go to app designer of the specific app, choose the entity and its views, check the view you want to enable, save, publish and close.</span></span>
5. <span data-ttu-id="86a5e-112">ページを更新します。</span><span class="sxs-lookup"><span data-stu-id="86a5e-112">Refresh the page.</span></span>