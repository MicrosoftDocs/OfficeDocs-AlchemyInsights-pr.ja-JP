---
title: SharePoint サイトを作成する
ms.author: kirks
author: Techwriter40
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: a4c6029c632178136396a91ba9754752dc8f7180
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/12/2019
ms.locfileid: "29932837"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="df25e-102">SharePoint サイトを作成する</span><span class="sxs-lookup"><span data-stu-id="df25e-102">Create a SharePoint site</span></span>

<span data-ttu-id="df25e-p101">サイト作成のオプションについては、[新しい SharePoint 管理センターでのサイトの管理](https://docs.microsoft.com/sharepoint/manage-site-creation )に関するページを参照してください。[チーム サイト](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) (これにより、Office 365 グループが作成されます)、または[コミュニケーション サイト](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb)を作成するよう選択します。[従来のサイト](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site)、または Office 365 グループが含まれない新しいチーム サイトを作成するには、[**その他のオプション**] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="df25e-p101">See [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation ) for site creation options. Select to create a [team site](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) (which will create an Office 365 group) or a [communication site](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb). To create a [classic site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site), or a new team site that doesn't include an Office 365 group, click **Other options**.</span></span> 
  
<span data-ttu-id="df25e-106">ヒント:</span><span class="sxs-lookup"><span data-stu-id="df25e-106">Tips:</span></span>
- <span data-ttu-id="df25e-107">*既存のサイトと同じ URL を持つサイトを作成することはできません。サイトを削除し、その URL を再利用する場合は、削除したサイトが [**削除されたサイト**] 下にまだ存在する可能性があります。削除したサイトを管理するには、[サイトの削除](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site)に関するページを参照してください。Powershell を使用してサイトを完全に削除するには、[Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) コマンドレットの例を参照してください。*</span><span class="sxs-lookup"><span data-stu-id="df25e-107">*You cannot create a site with the same URL of an existing site. If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**. To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site). To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.*</span></span>
- <span data-ttu-id="df25e-108">*ユーザーによっては、サイトを作成できない場合があります。「[SharePoint Online のサイト作成を管理する](https://docs.microsoft.com/sharepoint/manage-site-creation)」を参照してください。*</span><span class="sxs-lookup"><span data-stu-id="df25e-108">*Some users may not be able to create a site. See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).*</span></span>
- <span data-ttu-id="df25e-109">*サイトが**作成中に**予想より長く停止しているように見えることがあります。この問題が初めて発生してから 24 時間以上経過している場合は、サポート チケットを記録してください。多くの場合は、Microsoft が既に解決策に取り組んでいます。解決策の完成までには 24 時間以上の時間がかかります。*</span><span class="sxs-lookup"><span data-stu-id="df25e-109">*It's possible the site appears stuck at **Creating** longer than expected. If more than 24 hours have passed since you first saw this issue, please log a support ticket. In many cases, we're already working on a solution. Please give us at least 24 hours to complete a solution.*</span></span>
