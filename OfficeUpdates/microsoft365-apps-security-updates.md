---
title: Microsoft Office セキュリティ更新プログラムのリリース ノート
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft Officeセキュリティ更新プログラムのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: ae1402e77905e221cbcd0a6736ad3fb4ba4d507b
ms.sourcegitcommit: db30154a1be72ca2b3b41f4dcc8ce6986834f6da
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/09/2020
ms.locfileid: "47413085"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="d69fb-103">Microsoft Office セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="d69fb-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="d69fb-104">このリリース ノートには、Microsoft Officeの更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="d69fb-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="d69fb-105">この情報は、エンタープライズ用Microsoft 365 アプリ、ビジネス用Microsoft 365アプリ、Office 2016 リテール (C2R)およびOffice 2019に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d69fb-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="d69fb-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="d69fb-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="d69fb-107">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d69fb-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="d69fb-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="d69fb-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="d69fb-109">詳細については、 [こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2123420)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d69fb-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="d69fb-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="d69fb-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="september-08-2020"></a><span data-ttu-id="d69fb-112">2020 年 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-112">September 08, 2020</span></span>
<span data-ttu-id="d69fb-113">月次エンタープライズ チャネル: バージョン 2007 (ビルド 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="d69fb-113">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="d69fb-114">月次エンタープライズ チャネル: バージョン 2006 (ビルド 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="d69fb-114">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="d69fb-115">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="d69fb-115">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="d69fb-116">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="d69fb-116">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="d69fb-117">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="d69fb-117">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="d69fb-118">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="d69fb-118">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-120">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-120">Excel</span></span>

-   [<span data-ttu-id="d69fb-121">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="d69fb-121">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="d69fb-122">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="d69fb-122">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="d69fb-123">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="d69fb-123">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="d69fb-124">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="d69fb-124">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="d69fb-125">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-125">Word</span></span>

-   [<span data-ttu-id="d69fb-126">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="d69fb-126">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="d69fb-127">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="d69fb-127">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1218)
-   [<span data-ttu-id="d69fb-128">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="d69fb-128">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1445)

### <a name="office-suite"></a><span data-ttu-id="d69fb-129">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-129">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-130">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="d69fb-130">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1458)
-   [<span data-ttu-id="d69fb-131">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="d69fb-131">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1193)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="august-11-2020"></a><span data-ttu-id="d69fb-133">2020 年 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-133">August 11, 2020</span></span>
<span data-ttu-id="d69fb-134">現在のチャネル: バージョン2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d69fb-134">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d69fb-135">月次エンタープライズ チャネル: バージョン2006 (ビルド 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="d69fb-135">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="d69fb-136">月次エンタープライズ チャネル: バージョン2005 (ビルド 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="d69fb-136">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="d69fb-137">半期エンタープライズ チャネル (プレビュー)： バージョン2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d69fb-137">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d69fb-138">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d69fb-138">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d69fb-139">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="d69fb-139">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="d69fb-140">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="d69fb-140">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="d69fb-141">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d69fb-141">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d69fb-142">Office 2019 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d69fb-142">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d69fb-143">Office 2016 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d69fb-143">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d69fb-144">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="d69fb-144">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="d69fb-146">Access</span><span class="sxs-lookup"><span data-stu-id="d69fb-146">Access</span></span>

-   [<span data-ttu-id="d69fb-147">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="d69fb-147">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="d69fb-148">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-148">Excel</span></span>

-   [<span data-ttu-id="d69fb-149">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="d69fb-149">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="d69fb-150">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="d69fb-150">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="d69fb-151">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="d69fb-151">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="d69fb-152">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="d69fb-152">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="d69fb-153">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="d69fb-153">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="d69fb-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-154">Outlook</span></span>

-   [<span data-ttu-id="d69fb-155">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="d69fb-155">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="d69fb-156">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="d69fb-156">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="d69fb-157">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-157">Word</span></span>

-   [<span data-ttu-id="d69fb-158">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="d69fb-158">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="d69fb-159">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="d69fb-159">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="d69fb-160">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="d69fb-160">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="d69fb-161">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-161">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-162">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="d69fb-162">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="d69fb-163">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="d69fb-163">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1563)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="july-14-2020"></a><span data-ttu-id="d69fb-165">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-165">July 14, 2020</span></span>
<span data-ttu-id="d69fb-166">現在のチャネル: バージョン 2006 (ビルド 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="d69fb-166">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="d69fb-167">月次エンタープライズ チャネル: バージョン 2005 (ビルド 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="d69fb-167">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="d69fb-168">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="d69fb-168">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="d69fb-169">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d69fb-169">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="d69fb-170">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d69fb-170">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="d69fb-171">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="d69fb-171">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="d69fb-172">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="d69fb-172">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="d69fb-173">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d69fb-173">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-175">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-175">Excel</span></span>

-   [<span data-ttu-id="d69fb-176">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="d69fb-176">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="d69fb-177">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-177">Outlook</span></span>

-   [<span data-ttu-id="d69fb-178">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="d69fb-178">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="d69fb-179">Project</span><span class="sxs-lookup"><span data-stu-id="d69fb-179">Project</span></span>

-   [<span data-ttu-id="d69fb-180">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="d69fb-180">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="d69fb-181">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-181">Word</span></span>

-   [<span data-ttu-id="d69fb-182">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="d69fb-182">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="d69fb-183">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="d69fb-183">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="d69fb-184">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="d69fb-184">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="d69fb-185">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="d69fb-185">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="d69fb-186">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-186">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-187">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="d69fb-187">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1458)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="june-09-2020"></a><span data-ttu-id="d69fb-189">2020 年 6 月 09 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-189">June 09, 2020</span></span>
<span data-ttu-id="d69fb-190">現在のチャネル: バージョン 2005 (ビルド 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="d69fb-190">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="d69fb-191">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="d69fb-191">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="d69fb-192">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="d69fb-192">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="d69fb-193">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="d69fb-193">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="d69fb-194">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="d69fb-194">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="d69fb-195">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="d69fb-195">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="d69fb-196">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="d69fb-196">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-198">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-198">Excel</span></span>

-   [<span data-ttu-id="d69fb-199">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="d69fb-199">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="d69fb-200">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="d69fb-200">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="d69fb-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-201">Outlook</span></span>

-   [<span data-ttu-id="d69fb-202">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="d69fb-202">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="d69fb-203">Project</span><span class="sxs-lookup"><span data-stu-id="d69fb-203">Project</span></span>

-   [<span data-ttu-id="d69fb-204">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="d69fb-204">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="d69fb-205">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-205">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-206">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="d69fb-206">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1321)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="may-12-2020"></a><span data-ttu-id="d69fb-208">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-208">May 12, 2020</span></span>
<span data-ttu-id="d69fb-209">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="d69fb-209">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="d69fb-210">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="d69fb-210">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="d69fb-211">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="d69fb-211">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="d69fb-212">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="d69fb-212">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="d69fb-213">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="d69fb-213">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="d69fb-214">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="d69fb-214">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-216">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-216">Excel</span></span>

-   [<span data-ttu-id="d69fb-217">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="d69fb-217">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="d69fb-219">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-219">April 14, 2020</span></span>
<span data-ttu-id="d69fb-220">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="d69fb-220">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="d69fb-221">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="d69fb-221">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="d69fb-222">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="d69fb-222">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="d69fb-223">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="d69fb-223">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="d69fb-224">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="d69fb-224">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-226">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-226">Excel</span></span>

-   [<span data-ttu-id="d69fb-227">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="d69fb-227">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="d69fb-228">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="d69fb-228">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="d69fb-229">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-229">Word</span></span>

-   [<span data-ttu-id="d69fb-230">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="d69fb-230">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="d69fb-231">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-231">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-232">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="d69fb-232">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="d69fb-233">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="d69fb-233">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="d69fb-234">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="d69fb-234">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="d69fb-236">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-236">March 10, 2020</span></span>
<span data-ttu-id="d69fb-237">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d69fb-237">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="d69fb-238">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d69fb-238">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="d69fb-239">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="d69fb-239">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="d69fb-240">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="d69fb-240">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="d69fb-241">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d69fb-241">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="d69fb-243">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-243">Word</span></span>

-   [<span data-ttu-id="d69fb-244">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="d69fb-244">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="d69fb-245">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="d69fb-245">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="d69fb-246">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="d69fb-246">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="d69fb-247">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="d69fb-247">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="d69fb-249">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-249">February 11, 2020</span></span>
<span data-ttu-id="d69fb-250">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="d69fb-250">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="d69fb-251">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="d69fb-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="d69fb-252">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="d69fb-252">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="d69fb-253">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="d69fb-253">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="d69fb-254">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="d69fb-254">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-256">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-256">Excel</span></span>

-   [<span data-ttu-id="d69fb-257">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="d69fb-257">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="d69fb-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-258">Outlook</span></span>

-   [<span data-ttu-id="d69fb-259">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="d69fb-259">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="d69fb-260">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-260">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-261">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="d69fb-261">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="d69fb-263">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-263">January 14, 2020</span></span>
<span data-ttu-id="d69fb-264">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="d69fb-264">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="d69fb-265">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="d69fb-265">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="d69fb-266">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="d69fb-266">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="d69fb-267">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="d69fb-267">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="d69fb-268">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="d69fb-268">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="d69fb-270">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-270">Excel</span></span>

-   [<span data-ttu-id="d69fb-271">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="d69fb-271">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="d69fb-272">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="d69fb-272">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="d69fb-273">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="d69fb-273">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="d69fb-274">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-274">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-275">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="d69fb-275">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="d69fb-277">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-277">December 10, 2019</span></span>
<span data-ttu-id="d69fb-278">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="d69fb-278">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="d69fb-279">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="d69fb-279">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="d69fb-280">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="d69fb-280">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="d69fb-281">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="d69fb-281">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-282">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-282">Excel</span></span>

-   [<span data-ttu-id="d69fb-283">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="d69fb-283">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="d69fb-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d69fb-284">PowerPoint</span></span>

-   [<span data-ttu-id="d69fb-285">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="d69fb-285">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="d69fb-286">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-286">Word</span></span>

-   [<span data-ttu-id="d69fb-287">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="d69fb-287">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="d69fb-288">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-288">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-289">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="d69fb-289">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="d69fb-290">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="d69fb-290">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="d69fb-291">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-291">November 12, 2019</span></span>
<span data-ttu-id="d69fb-292">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="d69fb-292">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="d69fb-293">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="d69fb-293">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="d69fb-294">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="d69fb-294">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="d69fb-295">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="d69fb-295">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-296">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-296">Excel</span></span>

-   [<span data-ttu-id="d69fb-297">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="d69fb-297">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="d69fb-298">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="d69fb-298">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="d69fb-299">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-299">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-300">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="d69fb-300">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="d69fb-301">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="d69fb-301">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="d69fb-302">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-302">October 08, 2019</span></span>
<span data-ttu-id="d69fb-303">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="d69fb-303">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="d69fb-304">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="d69fb-304">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="d69fb-305">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="d69fb-305">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="d69fb-306">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="d69fb-306">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-307">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-307">Excel</span></span>

-   [<span data-ttu-id="d69fb-308">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="d69fb-308">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="d69fb-309">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="d69fb-309">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="d69fb-310">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-310">September 10, 2019</span></span>
<span data-ttu-id="d69fb-311">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="d69fb-311">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="d69fb-312">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="d69fb-312">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="d69fb-313">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="d69fb-313">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="d69fb-314">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="d69fb-314">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-315">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-315">Excel</span></span>

-   [<span data-ttu-id="d69fb-316">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="d69fb-316">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="d69fb-317">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="d69fb-317">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="d69fb-318">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-318">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-319">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="d69fb-319">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="d69fb-320">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="d69fb-320">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="d69fb-321">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-321">August 13, 2019</span></span>
<span data-ttu-id="d69fb-322">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="d69fb-322">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="d69fb-323">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="d69fb-323">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="d69fb-324">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="d69fb-324">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="d69fb-325">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="d69fb-325">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="d69fb-326">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="d69fb-326">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="d69fb-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-327">Outlook</span></span>

-   [<span data-ttu-id="d69fb-328">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="d69fb-328">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="d69fb-329">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="d69fb-329">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="d69fb-330">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="d69fb-330">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="d69fb-331">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-331">Word</span></span>

-   [<span data-ttu-id="d69fb-332">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="d69fb-332">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="d69fb-333">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="d69fb-333">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="d69fb-334">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-334">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-335">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="d69fb-335">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="d69fb-336">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-336">July 09, 2019</span></span>
<span data-ttu-id="d69fb-337">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="d69fb-337">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="d69fb-338">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="d69fb-338">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="d69fb-339">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="d69fb-339">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="d69fb-340">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="d69fb-340">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="d69fb-341">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="d69fb-341">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="d69fb-342">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-342">Excel</span></span>

-   [<span data-ttu-id="d69fb-343">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="d69fb-343">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="d69fb-344">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="d69fb-344">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="d69fb-345">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="d69fb-345">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="d69fb-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-346">Outlook</span></span>

-   [<span data-ttu-id="d69fb-347">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="d69fb-347">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="d69fb-348">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="d69fb-348">Skype for Business</span></span>

-   [<span data-ttu-id="d69fb-349">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="d69fb-349">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="d69fb-350">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-350">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-351">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="d69fb-351">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="d69fb-352">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-352">June 11, 2019</span></span>
<span data-ttu-id="d69fb-353">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="d69fb-353">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="d69fb-354">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="d69fb-354">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="d69fb-355">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="d69fb-355">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="d69fb-356">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="d69fb-356">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="d69fb-357">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-357">Word</span></span>

-   [<span data-ttu-id="d69fb-358">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="d69fb-358">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="d69fb-359">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="d69fb-359">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="d69fb-360">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-360">May 14, 2019</span></span>
<span data-ttu-id="d69fb-361">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="d69fb-361">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="d69fb-362">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="d69fb-362">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="d69fb-363">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="d69fb-363">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="d69fb-364">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="d69fb-364">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="d69fb-365">Word</span><span class="sxs-lookup"><span data-stu-id="d69fb-365">Word</span></span>

-   [<span data-ttu-id="d69fb-366">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="d69fb-366">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="d69fb-367">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-367">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-368">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="d69fb-368">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="d69fb-369">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="d69fb-369">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="d69fb-370">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-370">April 09, 2019</span></span>
<span data-ttu-id="d69fb-371">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="d69fb-371">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="d69fb-372">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="d69fb-372">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="d69fb-373">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="d69fb-373">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="d69fb-374">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="d69fb-374">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-375">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-375">Excel</span></span>

-   [<span data-ttu-id="d69fb-376">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="d69fb-376">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="d69fb-377">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-377">Office Suite</span></span>

-   [<span data-ttu-id="d69fb-378">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="d69fb-378">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="d69fb-379">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="d69fb-379">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="d69fb-380">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="d69fb-380">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="d69fb-381">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="d69fb-381">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="d69fb-382">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="d69fb-382">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="d69fb-383">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="d69fb-383">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="d69fb-384">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-384">March 12, 2019</span></span>
<span data-ttu-id="d69fb-385">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="d69fb-385">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="d69fb-386">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-386">February 12, 2019</span></span>
<span data-ttu-id="d69fb-387">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="d69fb-387">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="d69fb-388">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="d69fb-388">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="d69fb-389">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="d69fb-389">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="d69fb-390">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="d69fb-390">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="d69fb-391">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="d69fb-391">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="d69fb-392">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-392">Excel</span></span>

-   [<span data-ttu-id="d69fb-393">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="d69fb-393">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="d69fb-394">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d69fb-394">Office suite</span></span>

-   [<span data-ttu-id="d69fb-395">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="d69fb-395">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="d69fb-396">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="d69fb-396">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="d69fb-397">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="d69fb-397">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="d69fb-398">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="d69fb-398">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="d69fb-399">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="d69fb-399">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="d69fb-400">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="d69fb-400">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="d69fb-401">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-401">January 8, 2019</span></span>

<span data-ttu-id="d69fb-402">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="d69fb-402">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="d69fb-403">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="d69fb-403">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="d69fb-404">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="d69fb-404">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="d69fb-405">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="d69fb-405">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="d69fb-406">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="d69fb-406">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="d69fb-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-407">Outlook</span></span>
-   [<span data-ttu-id="d69fb-408">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="d69fb-408">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="d69fb-409">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d69fb-409">Word: Security updates</span></span> 
-   [<span data-ttu-id="d69fb-410">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="d69fb-410">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="d69fb-411">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="d69fb-411">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="d69fb-412">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d69fb-412">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="d69fb-413">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="d69fb-413">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="d69fb-414">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="d69fb-414">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="d69fb-415">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-415">December 11, 2018</span></span>
<span data-ttu-id="d69fb-416">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="d69fb-416">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="d69fb-417">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="d69fb-417">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="d69fb-418">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="d69fb-418">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-419">Excel</span><span class="sxs-lookup"><span data-stu-id="d69fb-419">Excel</span></span>

-   [<span data-ttu-id="d69fb-420">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="d69fb-420">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="d69fb-421">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="d69fb-421">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="d69fb-422">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="d69fb-422">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="d69fb-423">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="d69fb-423">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="d69fb-424">Outlook</span><span class="sxs-lookup"><span data-stu-id="d69fb-424">Outlook</span></span>

-   [<span data-ttu-id="d69fb-425">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="d69fb-425">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="d69fb-426">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d69fb-426">PowerPoint</span></span>

-   [<span data-ttu-id="d69fb-427">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="d69fb-427">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="d69fb-428">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d69fb-428">November 13, 2018</span></span>
<span data-ttu-id="d69fb-429">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="d69fb-429">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="d69fb-430">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="d69fb-430">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="d69fb-431">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="d69fb-431">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="d69fb-432">Excel:</span><span class="sxs-lookup"><span data-stu-id="d69fb-432">Excel:</span></span>

-   [<span data-ttu-id="d69fb-433">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="d69fb-433">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="d69fb-434">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="d69fb-434">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="d69fb-435">Outlook:</span><span class="sxs-lookup"><span data-stu-id="d69fb-435">Outlook:</span></span>

-   [<span data-ttu-id="d69fb-436">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="d69fb-436">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="d69fb-437">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="d69fb-437">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="d69fb-438">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="d69fb-438">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="d69fb-439">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="d69fb-439">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="d69fb-440">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="d69fb-440">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="d69fb-441">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="d69fb-441">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="d69fb-442">Project:</span><span class="sxs-lookup"><span data-stu-id="d69fb-442">Project:</span></span>

-   [<span data-ttu-id="d69fb-443">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="d69fb-443">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="d69fb-444">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="d69fb-444">Skype for Business:</span></span>

-   [<span data-ttu-id="d69fb-445">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="d69fb-445">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="d69fb-446">Word:</span><span class="sxs-lookup"><span data-stu-id="d69fb-446">Word:</span></span>

-   [<span data-ttu-id="d69fb-447">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="d69fb-447">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573)
