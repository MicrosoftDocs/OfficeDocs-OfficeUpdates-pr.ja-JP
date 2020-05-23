---
title: Microsoft 365 Apps セキュリティ更新プログラムのリリース ノート
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps セキュリティ更新プログラムのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 91538ad859fe5dc3d45a73d0798ff21708f6178b
ms.sourcegitcommit: 18f8f5d6dcd9743005ae2ba87c8e9e2d9edfe8c4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/13/2020
ms.locfileid: "44211707"
---
# <a name="release-notes-for-microsoft-365-apps-security-updates"></a><span data-ttu-id="dbc33-103">Microsoft 365 Apps セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="dbc33-103">Release notes for Microsoft 365 Apps Security Updates</span></span>

<span data-ttu-id="dbc33-104">このリリース ノートには、Microsoft 365 Apps の更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="dbc33-104">These release notes provide information about security fixes that are included in updates to Microsoft 365 Apps.</span></span>

<span data-ttu-id="dbc33-105">この情報は、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版に適用されます。</span><span class="sxs-lookup"><span data-stu-id="dbc33-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="dbc33-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズチャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="dbc33-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="dbc33-107">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dbc33-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="dbc33-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="dbc33-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="dbc33-109">詳細については、 [こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2123420)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dbc33-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="dbc33-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="dbc33-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="may-12-2020"></a><span data-ttu-id="dbc33-112">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-112">May 12, 2020</span></span>
<span data-ttu-id="dbc33-113">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="dbc33-113">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="dbc33-114">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="dbc33-114">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="dbc33-115">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="dbc33-115">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="dbc33-116">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="dbc33-116">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="dbc33-117">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="dbc33-117">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="dbc33-118">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="dbc33-118">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="dbc33-120">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-120">Excel</span></span>

-   [<span data-ttu-id="dbc33-121">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="dbc33-121">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="dbc33-123">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-123">April 14, 2020</span></span>
<span data-ttu-id="dbc33-124">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="dbc33-124">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="dbc33-125">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="dbc33-125">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="dbc33-126">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="dbc33-126">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="dbc33-127">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="dbc33-127">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="dbc33-128">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="dbc33-128">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="dbc33-130">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-130">Excel</span></span>

-   [<span data-ttu-id="dbc33-131">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="dbc33-131">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="dbc33-132">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="dbc33-132">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="dbc33-133">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-133">Word</span></span>

-   [<span data-ttu-id="dbc33-134">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="dbc33-134">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="dbc33-135">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-135">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-136">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="dbc33-136">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="dbc33-137">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="dbc33-137">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="dbc33-138">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="dbc33-138">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="dbc33-140">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-140">March 10, 2020</span></span>
<span data-ttu-id="dbc33-141">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="dbc33-141">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="dbc33-142">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="dbc33-142">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="dbc33-143">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="dbc33-143">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="dbc33-144">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="dbc33-144">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="dbc33-145">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="dbc33-145">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="dbc33-147">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-147">Word</span></span>

-   [<span data-ttu-id="dbc33-148">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="dbc33-148">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="dbc33-149">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="dbc33-149">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="dbc33-150">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="dbc33-150">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="dbc33-151">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="dbc33-151">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="dbc33-153">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-153">February 11, 2020</span></span>
<span data-ttu-id="dbc33-154">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="dbc33-154">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="dbc33-155">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="dbc33-155">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="dbc33-156">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="dbc33-156">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="dbc33-157">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="dbc33-157">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="dbc33-158">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="dbc33-158">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="dbc33-160">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-160">Excel</span></span>

-   [<span data-ttu-id="dbc33-161">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="dbc33-161">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="dbc33-162">Outlook</span><span class="sxs-lookup"><span data-stu-id="dbc33-162">Outlook</span></span>

-   [<span data-ttu-id="dbc33-163">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="dbc33-163">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="dbc33-164">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-164">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-165">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="dbc33-165">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="dbc33-167">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-167">January 14, 2020</span></span>
<span data-ttu-id="dbc33-168">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="dbc33-168">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="dbc33-169">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="dbc33-169">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="dbc33-170">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="dbc33-170">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="dbc33-171">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="dbc33-171">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="dbc33-172">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="dbc33-172">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="dbc33-174">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-174">Excel</span></span>

-   [<span data-ttu-id="dbc33-175">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="dbc33-175">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="dbc33-176">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="dbc33-176">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="dbc33-177">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="dbc33-177">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="dbc33-178">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-178">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-179">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="dbc33-179">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="dbc33-181">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-181">December 10, 2019</span></span>
<span data-ttu-id="dbc33-182">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="dbc33-182">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="dbc33-183">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="dbc33-183">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="dbc33-184">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="dbc33-184">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="dbc33-185">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="dbc33-185">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-186">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-186">Excel</span></span>

-   [<span data-ttu-id="dbc33-187">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="dbc33-187">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="dbc33-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="dbc33-188">PowerPoint</span></span>

-   [<span data-ttu-id="dbc33-189">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="dbc33-189">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="dbc33-190">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-190">Word</span></span>

-   [<span data-ttu-id="dbc33-191">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="dbc33-191">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="dbc33-192">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-192">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-193">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="dbc33-193">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="dbc33-194">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="dbc33-194">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="dbc33-195">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-195">November 12, 2019</span></span>
<span data-ttu-id="dbc33-196">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="dbc33-196">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="dbc33-197">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="dbc33-197">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="dbc33-198">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="dbc33-198">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="dbc33-199">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="dbc33-199">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-200">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-200">Excel</span></span>

-   [<span data-ttu-id="dbc33-201">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="dbc33-201">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="dbc33-202">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="dbc33-202">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="dbc33-203">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-203">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-204">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="dbc33-204">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="dbc33-205">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="dbc33-205">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="dbc33-206">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-206">October 08, 2019</span></span>
<span data-ttu-id="dbc33-207">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="dbc33-207">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="dbc33-208">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="dbc33-208">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="dbc33-209">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="dbc33-209">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="dbc33-210">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="dbc33-210">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-211">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-211">Excel</span></span>

-   [<span data-ttu-id="dbc33-212">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="dbc33-212">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="dbc33-213">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="dbc33-213">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="dbc33-214">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-214">September 10, 2019</span></span>
<span data-ttu-id="dbc33-215">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="dbc33-215">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="dbc33-216">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="dbc33-216">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="dbc33-217">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="dbc33-217">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="dbc33-218">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="dbc33-218">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-219">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-219">Excel</span></span>

-   [<span data-ttu-id="dbc33-220">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="dbc33-220">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="dbc33-221">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="dbc33-221">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="dbc33-222">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-222">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-223">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="dbc33-223">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="dbc33-224">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="dbc33-224">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="dbc33-225">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-225">August 13, 2019</span></span>
<span data-ttu-id="dbc33-226">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="dbc33-226">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="dbc33-227">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="dbc33-227">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="dbc33-228">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="dbc33-228">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="dbc33-229">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="dbc33-229">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="dbc33-230">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="dbc33-230">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="dbc33-231">Outlook</span><span class="sxs-lookup"><span data-stu-id="dbc33-231">Outlook</span></span>

-   [<span data-ttu-id="dbc33-232">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="dbc33-232">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="dbc33-233">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="dbc33-233">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="dbc33-234">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="dbc33-234">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="dbc33-235">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-235">Word</span></span>

-   [<span data-ttu-id="dbc33-236">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="dbc33-236">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="dbc33-237">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="dbc33-237">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="dbc33-238">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-238">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-239">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="dbc33-239">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="dbc33-240">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-240">July 09, 2019</span></span>
<span data-ttu-id="dbc33-241">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="dbc33-241">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="dbc33-242">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="dbc33-242">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="dbc33-243">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="dbc33-243">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="dbc33-244">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="dbc33-244">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="dbc33-245">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="dbc33-245">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="dbc33-246">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-246">Excel</span></span>

-   [<span data-ttu-id="dbc33-247">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="dbc33-247">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="dbc33-248">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="dbc33-248">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="dbc33-249">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="dbc33-249">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="dbc33-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="dbc33-250">Outlook</span></span>

-   [<span data-ttu-id="dbc33-251">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="dbc33-251">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="dbc33-252">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="dbc33-252">Skype for Business</span></span>

-   [<span data-ttu-id="dbc33-253">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="dbc33-253">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="dbc33-254">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-254">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-255">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="dbc33-255">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="dbc33-256">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-256">June 11, 2019</span></span>
<span data-ttu-id="dbc33-257">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="dbc33-257">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="dbc33-258">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="dbc33-258">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="dbc33-259">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="dbc33-259">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="dbc33-260">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="dbc33-260">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="dbc33-261">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-261">Word</span></span>

-   [<span data-ttu-id="dbc33-262">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="dbc33-262">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="dbc33-263">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="dbc33-263">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="dbc33-264">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-264">May 14, 2019</span></span>
<span data-ttu-id="dbc33-265">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="dbc33-265">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="dbc33-266">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="dbc33-266">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="dbc33-267">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="dbc33-267">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="dbc33-268">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="dbc33-268">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="dbc33-269">Word</span><span class="sxs-lookup"><span data-stu-id="dbc33-269">Word</span></span>

-   [<span data-ttu-id="dbc33-270">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="dbc33-270">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="dbc33-271">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-271">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-272">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="dbc33-272">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="dbc33-273">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="dbc33-273">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="dbc33-274">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-274">April 09, 2019</span></span>
<span data-ttu-id="dbc33-275">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="dbc33-275">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="dbc33-276">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="dbc33-276">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="dbc33-277">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="dbc33-277">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="dbc33-278">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="dbc33-278">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-279">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-279">Excel</span></span>

-   [<span data-ttu-id="dbc33-280">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="dbc33-280">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="dbc33-281">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-281">Office Suite</span></span>

-   [<span data-ttu-id="dbc33-282">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="dbc33-282">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="dbc33-283">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="dbc33-283">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="dbc33-284">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="dbc33-284">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="dbc33-285">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="dbc33-285">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="dbc33-286">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="dbc33-286">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="dbc33-287">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="dbc33-287">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="dbc33-288">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-288">March 12, 2019</span></span>
<span data-ttu-id="dbc33-289">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="dbc33-289">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="dbc33-290">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-290">February 12, 2019</span></span>
<span data-ttu-id="dbc33-291">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="dbc33-291">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="dbc33-292">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="dbc33-292">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="dbc33-293">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="dbc33-293">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="dbc33-294">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="dbc33-294">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="dbc33-295">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="dbc33-295">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="dbc33-296">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-296">Excel</span></span>

-   [<span data-ttu-id="dbc33-297">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="dbc33-297">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="dbc33-298">Office スイート</span><span class="sxs-lookup"><span data-stu-id="dbc33-298">Office suite</span></span>

-   [<span data-ttu-id="dbc33-299">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="dbc33-299">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="dbc33-300">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="dbc33-300">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="dbc33-301">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="dbc33-301">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="dbc33-302">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="dbc33-302">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="dbc33-303">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="dbc33-303">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="dbc33-304">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="dbc33-304">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="dbc33-305">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-305">January 8, 2019</span></span>

<span data-ttu-id="dbc33-306">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="dbc33-306">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="dbc33-307">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="dbc33-307">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="dbc33-308">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="dbc33-308">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="dbc33-309">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="dbc33-309">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="dbc33-310">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="dbc33-310">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="dbc33-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="dbc33-311">Outlook</span></span>
-   [<span data-ttu-id="dbc33-312">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="dbc33-312">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="dbc33-313">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="dbc33-313">Word: Security updates</span></span> 
-   [<span data-ttu-id="dbc33-314">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="dbc33-314">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="dbc33-315">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="dbc33-315">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="dbc33-316">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="dbc33-316">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="dbc33-317">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="dbc33-317">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="dbc33-318">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="dbc33-318">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="dbc33-319">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-319">December 11, 2018</span></span>
<span data-ttu-id="dbc33-320">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="dbc33-320">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="dbc33-321">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="dbc33-321">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="dbc33-322">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="dbc33-322">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-323">Excel</span><span class="sxs-lookup"><span data-stu-id="dbc33-323">Excel</span></span>

-   [<span data-ttu-id="dbc33-324">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="dbc33-324">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="dbc33-325">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="dbc33-325">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="dbc33-326">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="dbc33-326">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="dbc33-327">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="dbc33-327">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="dbc33-328">Outlook</span><span class="sxs-lookup"><span data-stu-id="dbc33-328">Outlook</span></span>

-   [<span data-ttu-id="dbc33-329">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="dbc33-329">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="dbc33-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="dbc33-330">PowerPoint</span></span>

-   [<span data-ttu-id="dbc33-331">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="dbc33-331">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="dbc33-332">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="dbc33-332">November 13, 2018</span></span>
<span data-ttu-id="dbc33-333">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="dbc33-333">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="dbc33-334">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="dbc33-334">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="dbc33-335">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="dbc33-335">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="dbc33-336">Excel:</span><span class="sxs-lookup"><span data-stu-id="dbc33-336">Excel:</span></span>

-   [<span data-ttu-id="dbc33-337">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="dbc33-337">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="dbc33-338">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="dbc33-338">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="dbc33-339">Outlook:</span><span class="sxs-lookup"><span data-stu-id="dbc33-339">Outlook:</span></span>

-   [<span data-ttu-id="dbc33-340">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="dbc33-340">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="dbc33-341">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="dbc33-341">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="dbc33-342">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="dbc33-342">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="dbc33-343">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="dbc33-343">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="dbc33-344">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="dbc33-344">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="dbc33-345">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="dbc33-345">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="dbc33-346">Project:</span><span class="sxs-lookup"><span data-stu-id="dbc33-346">Project:</span></span>

-   [<span data-ttu-id="dbc33-347">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="dbc33-347">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="dbc33-348">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="dbc33-348">Skype for Business:</span></span>

-   [<span data-ttu-id="dbc33-349">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="dbc33-349">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="dbc33-350">Word:</span><span class="sxs-lookup"><span data-stu-id="dbc33-350">Word:</span></span>

-   [<span data-ttu-id="dbc33-351">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="dbc33-351">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573)
