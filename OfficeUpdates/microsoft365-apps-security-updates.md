---
title: Microsoft Office セキュリティ更新プログラムのリリース ノート
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft Officeセキュリティ更新プログラムのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: c9a4d3af52431016160bc8aa9e5f37200b90966d
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453295"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="179b8-103">Microsoft Office セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="179b8-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="179b8-104">このリリース ノートには、Microsoft Officeの更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="179b8-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="179b8-105">この情報は、エンタープライズ用Microsoft 365 アプリ、ビジネス用Microsoft 365アプリ、Office 2016 リテール (C2R)およびOffice 2019に適用されます。</span><span class="sxs-lookup"><span data-stu-id="179b8-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="179b8-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="179b8-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="179b8-107">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="179b8-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="179b8-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="179b8-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="179b8-109">詳細については、 [こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2123420)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="179b8-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="179b8-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="179b8-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="october-13-2020"></a><span data-ttu-id="179b8-112">2020 年 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="179b8-112">October 13, 2020</span></span>
<span data-ttu-id="179b8-113">最新チャネル: バージョン2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="179b8-113">Current Channel: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="179b8-114">月次エンタープライズ チャネル: バージョン 2008 (Build 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="179b8-114">Monthly Enterprise Channel: Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="179b8-115">月次エンタープライズ チャネル: バージョン 2007 (Build 13029.20708)</span><span class="sxs-lookup"><span data-stu-id="179b8-115">Monthly Enterprise Channel: Version 2007 (Build 13029.20708)</span></span>  
<span data-ttu-id="179b8-116">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="179b8-116">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="179b8-117">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="179b8-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="179b8-118">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20966)</span><span class="sxs-lookup"><span data-stu-id="179b8-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20966)</span></span>  
<span data-ttu-id="179b8-119">Windows 7 上の Microsoft 365アプリ: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="179b8-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="179b8-120">Office 2019 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="179b8-120">Office 2019 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="179b8-121">Office 2016 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="179b8-121">Office 2016 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="179b8-122">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10367.20048)</span><span class="sxs-lookup"><span data-stu-id="179b8-122">Office 2019 Volume Licensed: Version 1808 (Build 10367.20048)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="access"></a><span data-ttu-id="179b8-124">Access</span><span class="sxs-lookup"><span data-stu-id="179b8-124">Access</span></span>

-   [<span data-ttu-id="179b8-125">CVE-2020-16957</span><span class="sxs-lookup"><span data-stu-id="179b8-125">CVE-2020-16957</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16957)

### <a name="excel"></a><span data-ttu-id="179b8-126">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-126">Excel</span></span>

-   [<span data-ttu-id="179b8-127">CVE-2020-16929</span><span class="sxs-lookup"><span data-stu-id="179b8-127">CVE-2020-16929</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16929)
-   [<span data-ttu-id="179b8-128">CVE-2020-16931</span><span class="sxs-lookup"><span data-stu-id="179b8-128">CVE-2020-16931</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16931)
-   [<span data-ttu-id="179b8-129">CVE-2020-16932</span><span class="sxs-lookup"><span data-stu-id="179b8-129">CVE-2020-16932</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16932)

### <a name="outlook"></a><span data-ttu-id="179b8-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-130">Outlook</span></span>

-   [<span data-ttu-id="179b8-131">CVE-2020-16947</span><span class="sxs-lookup"><span data-stu-id="179b8-131">CVE-2020-16947</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16947)
-   [<span data-ttu-id="179b8-132">CVE-2020-16949</span><span class="sxs-lookup"><span data-stu-id="179b8-132">CVE-2020-16949</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16949)

### <a name="word"></a><span data-ttu-id="179b8-133">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-133">Word</span></span>

-   [<span data-ttu-id="179b8-134">CVE-2020-16933</span><span class="sxs-lookup"><span data-stu-id="179b8-134">CVE-2020-16933</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16933)

### <a name="office-suite"></a><span data-ttu-id="179b8-135">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-135">Office Suite</span></span>

-   [<span data-ttu-id="179b8-136">CVE-2020-16930</span><span class="sxs-lookup"><span data-stu-id="179b8-136">CVE-2020-16930</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16930)
-   [<span data-ttu-id="179b8-137">CVE-2020-16955</span><span class="sxs-lookup"><span data-stu-id="179b8-137">CVE-2020-16955</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16955)
-   [<span data-ttu-id="179b8-138">CVE-2020-16928</span><span class="sxs-lookup"><span data-stu-id="179b8-138">CVE-2020-16928</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16928)
-   [<span data-ttu-id="179b8-139">CVE-2020-16934</span><span class="sxs-lookup"><span data-stu-id="179b8-139">CVE-2020-16934</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16934)
-   [<span data-ttu-id="179b8-140">CVE-2020-16918</span><span class="sxs-lookup"><span data-stu-id="179b8-140">CVE-2020-16918</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16918)
-   [<span data-ttu-id="179b8-141">CVE-2020-16954</span><span class="sxs-lookup"><span data-stu-id="179b8-141">CVE-2020-16954</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16954)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="september-08-2020"></a><span data-ttu-id="179b8-143">2020 年 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="179b8-143">September 08, 2020</span></span>
<span data-ttu-id="179b8-144">最新チャネル: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="179b8-144">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="179b8-145">月次エンタープライズ チャネル: バージョン 2007 (ビルド 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="179b8-145">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="179b8-146">月次エンタープライズ チャネル: バージョン 2006 (ビルド 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="179b8-146">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="179b8-147">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="179b8-147">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="179b8-148">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="179b8-148">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="179b8-149">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="179b8-149">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="179b8-150">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="179b8-150">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="179b8-151">Office 2019 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="179b8-151">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="179b8-152">Office 2016 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="179b8-152">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="179b8-153">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="179b8-153">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-155">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-155">Excel</span></span>

-   [<span data-ttu-id="179b8-156">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="179b8-156">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="179b8-157">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="179b8-157">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="179b8-158">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="179b8-158">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="179b8-159">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="179b8-159">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="179b8-160">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-160">Word</span></span>

-   [<span data-ttu-id="179b8-161">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="179b8-161">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="179b8-162">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="179b8-162">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="179b8-163">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-163">Office Suite</span></span>

-   [<span data-ttu-id="179b8-164">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="179b8-164">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1193)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="august-11-2020"></a><span data-ttu-id="179b8-166">2020 年 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="179b8-166">August 11, 2020</span></span>
<span data-ttu-id="179b8-167">最新チャネル: バージョン2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="179b8-167">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="179b8-168">月次エンタープライズ チャネル: バージョン2006 (ビルド 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="179b8-168">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="179b8-169">月次エンタープライズ チャネル: バージョン2005 (ビルド 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="179b8-169">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="179b8-170">半期エンタープライズ チャネル (プレビュー)： バージョン2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="179b8-170">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="179b8-171">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="179b8-171">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="179b8-172">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="179b8-172">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="179b8-173">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="179b8-173">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="179b8-174">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="179b8-174">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="179b8-175">Office 2019 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="179b8-175">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="179b8-176">Office 2016 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="179b8-176">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="179b8-177">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="179b8-177">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="179b8-179">Access</span><span class="sxs-lookup"><span data-stu-id="179b8-179">Access</span></span>

-   [<span data-ttu-id="179b8-180">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="179b8-180">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="179b8-181">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-181">Excel</span></span>

-   [<span data-ttu-id="179b8-182">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="179b8-182">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="179b8-183">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="179b8-183">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="179b8-184">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="179b8-184">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="179b8-185">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="179b8-185">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="179b8-186">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="179b8-186">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="179b8-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-187">Outlook</span></span>

-   [<span data-ttu-id="179b8-188">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="179b8-188">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="179b8-189">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="179b8-189">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="179b8-190">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-190">Word</span></span>

-   [<span data-ttu-id="179b8-191">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="179b8-191">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="179b8-192">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="179b8-192">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="179b8-193">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="179b8-193">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="179b8-194">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-194">Office Suite</span></span>

-   [<span data-ttu-id="179b8-195">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="179b8-195">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="179b8-196">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="179b8-196">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1563)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="july-14-2020"></a><span data-ttu-id="179b8-198">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="179b8-198">July 14, 2020</span></span>
<span data-ttu-id="179b8-199">最新チャネル: バージョン 2006 (ビルド 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="179b8-199">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="179b8-200">月次エンタープライズ チャネル: バージョン 2005 (ビルド 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="179b8-200">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="179b8-201">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="179b8-201">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="179b8-202">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="179b8-202">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="179b8-203">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="179b8-203">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="179b8-204">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="179b8-204">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="179b8-205">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="179b8-205">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="179b8-206">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="179b8-206">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-208">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-208">Excel</span></span>

-   [<span data-ttu-id="179b8-209">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="179b8-209">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="179b8-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-210">Outlook</span></span>

-   [<span data-ttu-id="179b8-211">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="179b8-211">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="179b8-212">Project</span><span class="sxs-lookup"><span data-stu-id="179b8-212">Project</span></span>

-   [<span data-ttu-id="179b8-213">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="179b8-213">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="179b8-214">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-214">Word</span></span>

-   [<span data-ttu-id="179b8-215">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="179b8-215">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="179b8-216">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="179b8-216">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="179b8-217">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="179b8-217">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="179b8-218">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="179b8-218">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="179b8-219">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-219">Office Suite</span></span>

-   [<span data-ttu-id="179b8-220">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="179b8-220">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1458)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="june-09-2020"></a><span data-ttu-id="179b8-222">2020 年 6 月 09 日</span><span class="sxs-lookup"><span data-stu-id="179b8-222">June 09, 2020</span></span>
<span data-ttu-id="179b8-223">最新チャネル: バージョン 2005 (ビルド 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="179b8-223">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="179b8-224">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="179b8-224">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="179b8-225">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="179b8-225">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="179b8-226">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="179b8-226">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="179b8-227">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="179b8-227">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="179b8-228">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="179b8-228">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="179b8-229">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="179b8-229">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-231">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-231">Excel</span></span>

-   [<span data-ttu-id="179b8-232">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="179b8-232">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="179b8-233">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="179b8-233">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="179b8-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-234">Outlook</span></span>

-   [<span data-ttu-id="179b8-235">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="179b8-235">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="179b8-236">Project</span><span class="sxs-lookup"><span data-stu-id="179b8-236">Project</span></span>

-   [<span data-ttu-id="179b8-237">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="179b8-237">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="179b8-238">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-238">Office Suite</span></span>

-   [<span data-ttu-id="179b8-239">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="179b8-239">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1321)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="may-12-2020"></a><span data-ttu-id="179b8-241">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="179b8-241">May 12, 2020</span></span>
<span data-ttu-id="179b8-242">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="179b8-242">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="179b8-243">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="179b8-243">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="179b8-244">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="179b8-244">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="179b8-245">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="179b8-245">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="179b8-246">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="179b8-246">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="179b8-247">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="179b8-247">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-249">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-249">Excel</span></span>

-   [<span data-ttu-id="179b8-250">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="179b8-250">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="179b8-252">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="179b8-252">April 14, 2020</span></span>
<span data-ttu-id="179b8-253">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="179b8-253">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="179b8-254">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="179b8-254">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="179b8-255">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="179b8-255">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="179b8-256">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="179b8-256">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="179b8-257">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="179b8-257">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-259">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-259">Excel</span></span>

-   [<span data-ttu-id="179b8-260">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="179b8-260">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="179b8-261">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="179b8-261">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="179b8-262">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-262">Word</span></span>

-   [<span data-ttu-id="179b8-263">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="179b8-263">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="179b8-264">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-264">Office Suite</span></span>

-   [<span data-ttu-id="179b8-265">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="179b8-265">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="179b8-266">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="179b8-266">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="179b8-267">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="179b8-267">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="179b8-269">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="179b8-269">March 10, 2020</span></span>
<span data-ttu-id="179b8-270">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="179b8-270">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="179b8-271">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="179b8-271">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="179b8-272">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="179b8-272">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="179b8-273">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="179b8-273">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="179b8-274">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="179b8-274">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="179b8-276">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-276">Word</span></span>

-   [<span data-ttu-id="179b8-277">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="179b8-277">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="179b8-278">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="179b8-278">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="179b8-279">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="179b8-279">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="179b8-280">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="179b8-280">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="179b8-282">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="179b8-282">February 11, 2020</span></span>
<span data-ttu-id="179b8-283">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="179b8-283">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="179b8-284">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="179b8-284">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="179b8-285">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="179b8-285">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="179b8-286">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="179b8-286">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="179b8-287">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="179b8-287">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-289">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-289">Excel</span></span>

-   [<span data-ttu-id="179b8-290">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="179b8-290">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="179b8-291">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-291">Outlook</span></span>

-   [<span data-ttu-id="179b8-292">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="179b8-292">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="179b8-293">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-293">Office Suite</span></span>

-   [<span data-ttu-id="179b8-294">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="179b8-294">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="179b8-296">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="179b8-296">January 14, 2020</span></span>
<span data-ttu-id="179b8-297">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="179b8-297">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="179b8-298">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="179b8-298">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="179b8-299">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="179b8-299">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="179b8-300">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="179b8-300">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="179b8-301">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="179b8-301">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="179b8-303">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-303">Excel</span></span>

-   [<span data-ttu-id="179b8-304">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="179b8-304">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="179b8-305">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="179b8-305">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="179b8-306">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="179b8-306">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="179b8-307">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-307">Office Suite</span></span>

-   [<span data-ttu-id="179b8-308">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="179b8-308">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="179b8-310">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="179b8-310">December 10, 2019</span></span>
<span data-ttu-id="179b8-311">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="179b8-311">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="179b8-312">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="179b8-312">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="179b8-313">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="179b8-313">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="179b8-314">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="179b8-314">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-315">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-315">Excel</span></span>

-   [<span data-ttu-id="179b8-316">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="179b8-316">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="179b8-317">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="179b8-317">PowerPoint</span></span>

-   [<span data-ttu-id="179b8-318">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="179b8-318">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="179b8-319">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-319">Word</span></span>

-   [<span data-ttu-id="179b8-320">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="179b8-320">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="179b8-321">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-321">Office Suite</span></span>

-   [<span data-ttu-id="179b8-322">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="179b8-322">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="179b8-323">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="179b8-323">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="179b8-324">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="179b8-324">November 12, 2019</span></span>
<span data-ttu-id="179b8-325">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="179b8-325">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="179b8-326">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="179b8-326">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="179b8-327">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="179b8-327">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="179b8-328">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="179b8-328">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-329">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-329">Excel</span></span>

-   [<span data-ttu-id="179b8-330">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="179b8-330">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="179b8-331">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="179b8-331">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="179b8-332">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-332">Office Suite</span></span>

-   [<span data-ttu-id="179b8-333">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="179b8-333">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="179b8-334">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="179b8-334">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="179b8-335">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="179b8-335">October 08, 2019</span></span>
<span data-ttu-id="179b8-336">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="179b8-336">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="179b8-337">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="179b8-337">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="179b8-338">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="179b8-338">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="179b8-339">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="179b8-339">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-340">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-340">Excel</span></span>

-   [<span data-ttu-id="179b8-341">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="179b8-341">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="179b8-342">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="179b8-342">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="179b8-343">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="179b8-343">September 10, 2019</span></span>
<span data-ttu-id="179b8-344">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="179b8-344">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="179b8-345">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="179b8-345">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="179b8-346">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="179b8-346">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="179b8-347">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="179b8-347">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-348">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-348">Excel</span></span>

-   [<span data-ttu-id="179b8-349">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="179b8-349">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="179b8-350">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="179b8-350">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="179b8-351">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-351">Office Suite</span></span>

-   [<span data-ttu-id="179b8-352">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="179b8-352">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="179b8-353">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="179b8-353">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="179b8-354">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="179b8-354">August 13, 2019</span></span>
<span data-ttu-id="179b8-355">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="179b8-355">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="179b8-356">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="179b8-356">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="179b8-357">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="179b8-357">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="179b8-358">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="179b8-358">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="179b8-359">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="179b8-359">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="179b8-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-360">Outlook</span></span>

-   [<span data-ttu-id="179b8-361">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="179b8-361">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="179b8-362">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="179b8-362">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="179b8-363">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="179b8-363">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="179b8-364">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-364">Word</span></span>

-   [<span data-ttu-id="179b8-365">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="179b8-365">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="179b8-366">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="179b8-366">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="179b8-367">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-367">Office Suite</span></span>

-   [<span data-ttu-id="179b8-368">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="179b8-368">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="179b8-369">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="179b8-369">July 09, 2019</span></span>
<span data-ttu-id="179b8-370">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="179b8-370">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="179b8-371">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="179b8-371">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="179b8-372">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="179b8-372">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="179b8-373">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="179b8-373">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="179b8-374">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="179b8-374">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="179b8-375">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-375">Excel</span></span>

-   [<span data-ttu-id="179b8-376">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="179b8-376">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="179b8-377">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="179b8-377">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="179b8-378">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="179b8-378">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="179b8-379">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-379">Outlook</span></span>

-   [<span data-ttu-id="179b8-380">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="179b8-380">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="179b8-381">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="179b8-381">Skype for Business</span></span>

-   [<span data-ttu-id="179b8-382">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="179b8-382">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="179b8-383">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-383">Office Suite</span></span>

-   [<span data-ttu-id="179b8-384">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="179b8-384">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="179b8-385">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="179b8-385">June 11, 2019</span></span>
<span data-ttu-id="179b8-386">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="179b8-386">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="179b8-387">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="179b8-387">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="179b8-388">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="179b8-388">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="179b8-389">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="179b8-389">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="179b8-390">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-390">Word</span></span>

-   [<span data-ttu-id="179b8-391">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="179b8-391">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="179b8-392">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="179b8-392">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="179b8-393">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="179b8-393">May 14, 2019</span></span>
<span data-ttu-id="179b8-394">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="179b8-394">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="179b8-395">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="179b8-395">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="179b8-396">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="179b8-396">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="179b8-397">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="179b8-397">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="179b8-398">Word</span><span class="sxs-lookup"><span data-stu-id="179b8-398">Word</span></span>

-   [<span data-ttu-id="179b8-399">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="179b8-399">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="179b8-400">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-400">Office Suite</span></span>

-   [<span data-ttu-id="179b8-401">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="179b8-401">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="179b8-402">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="179b8-402">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="179b8-403">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="179b8-403">April 09, 2019</span></span>
<span data-ttu-id="179b8-404">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="179b8-404">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="179b8-405">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="179b8-405">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="179b8-406">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="179b8-406">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="179b8-407">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="179b8-407">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-408">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-408">Excel</span></span>

-   [<span data-ttu-id="179b8-409">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="179b8-409">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="179b8-410">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-410">Office Suite</span></span>

-   [<span data-ttu-id="179b8-411">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="179b8-411">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="179b8-412">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="179b8-412">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="179b8-413">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="179b8-413">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="179b8-414">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="179b8-414">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="179b8-415">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="179b8-415">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="179b8-416">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="179b8-416">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="179b8-417">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="179b8-417">March 12, 2019</span></span>
<span data-ttu-id="179b8-418">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="179b8-418">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="179b8-419">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="179b8-419">February 12, 2019</span></span>
<span data-ttu-id="179b8-420">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="179b8-420">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="179b8-421">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="179b8-421">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="179b8-422">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="179b8-422">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="179b8-423">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="179b8-423">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="179b8-424">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="179b8-424">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="179b8-425">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-425">Excel</span></span>

-   [<span data-ttu-id="179b8-426">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="179b8-426">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="179b8-427">Office スイート</span><span class="sxs-lookup"><span data-stu-id="179b8-427">Office suite</span></span>

-   [<span data-ttu-id="179b8-428">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="179b8-428">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="179b8-429">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="179b8-429">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="179b8-430">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="179b8-430">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="179b8-431">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="179b8-431">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="179b8-432">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="179b8-432">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="179b8-433">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="179b8-433">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="179b8-434">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="179b8-434">January 8, 2019</span></span>

<span data-ttu-id="179b8-435">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="179b8-435">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="179b8-436">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="179b8-436">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="179b8-437">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="179b8-437">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="179b8-438">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="179b8-438">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="179b8-439">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="179b8-439">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="179b8-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-440">Outlook</span></span>
-   [<span data-ttu-id="179b8-441">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="179b8-441">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="179b8-442">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="179b8-442">Word: Security updates</span></span> 
-   [<span data-ttu-id="179b8-443">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="179b8-443">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="179b8-444">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="179b8-444">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="179b8-445">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="179b8-445">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="179b8-446">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="179b8-446">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="179b8-447">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="179b8-447">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="179b8-448">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="179b8-448">December 11, 2018</span></span>
<span data-ttu-id="179b8-449">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="179b8-449">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="179b8-450">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="179b8-450">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="179b8-451">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="179b8-451">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-452">Excel</span><span class="sxs-lookup"><span data-stu-id="179b8-452">Excel</span></span>

-   [<span data-ttu-id="179b8-453">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="179b8-453">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="179b8-454">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="179b8-454">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="179b8-455">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="179b8-455">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="179b8-456">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="179b8-456">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="179b8-457">Outlook</span><span class="sxs-lookup"><span data-stu-id="179b8-457">Outlook</span></span>

-   [<span data-ttu-id="179b8-458">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="179b8-458">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="179b8-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="179b8-459">PowerPoint</span></span>

-   [<span data-ttu-id="179b8-460">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="179b8-460">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="179b8-461">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="179b8-461">November 13, 2018</span></span>
<span data-ttu-id="179b8-462">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="179b8-462">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="179b8-463">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="179b8-463">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="179b8-464">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="179b8-464">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="179b8-465">Excel:</span><span class="sxs-lookup"><span data-stu-id="179b8-465">Excel:</span></span>

-   [<span data-ttu-id="179b8-466">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="179b8-466">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="179b8-467">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="179b8-467">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="179b8-468">Outlook:</span><span class="sxs-lookup"><span data-stu-id="179b8-468">Outlook:</span></span>

-   [<span data-ttu-id="179b8-469">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="179b8-469">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="179b8-470">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="179b8-470">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="179b8-471">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="179b8-471">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="179b8-472">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="179b8-472">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="179b8-473">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="179b8-473">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="179b8-474">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="179b8-474">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="179b8-475">Project:</span><span class="sxs-lookup"><span data-stu-id="179b8-475">Project:</span></span>

-   [<span data-ttu-id="179b8-476">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="179b8-476">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="179b8-477">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="179b8-477">Skype for Business:</span></span>

-   [<span data-ttu-id="179b8-478">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="179b8-478">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="179b8-479">Word:</span><span class="sxs-lookup"><span data-stu-id="179b8-479">Word:</span></span>

-   [<span data-ttu-id="179b8-480">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="179b8-480">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573)
