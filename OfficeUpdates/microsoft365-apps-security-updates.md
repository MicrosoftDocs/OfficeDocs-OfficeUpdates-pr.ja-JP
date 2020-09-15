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
ms.openlocfilehash: f8fc5a41e72074071de05ced6857e2ba1f5e7e21
ms.sourcegitcommit: 931b78282277a0d12779c6b4cae33181b4568c34
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/09/2020
ms.locfileid: "47420696"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="76f09-103">Microsoft Office セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="76f09-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="76f09-104">このリリース ノートには、Microsoft Officeの更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="76f09-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="76f09-105">この情報は、エンタープライズ用Microsoft 365 アプリ、ビジネス用Microsoft 365アプリ、Office 2016 リテール (C2R)およびOffice 2019に適用されます。</span><span class="sxs-lookup"><span data-stu-id="76f09-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="76f09-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="76f09-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="76f09-107">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="76f09-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="76f09-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="76f09-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="76f09-109">詳細については、 [こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2123420)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="76f09-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="76f09-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="76f09-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="september-08-2020"></a><span data-ttu-id="76f09-112">2020 年 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="76f09-112">September 08, 2020</span></span>
<span data-ttu-id="76f09-113">現在のチャネル: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="76f09-113">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="76f09-114">月次エンタープライズ チャネル: バージョン 2007 (ビルド 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="76f09-114">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="76f09-115">月次エンタープライズ チャネル: バージョン 2006 (ビルド 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="76f09-115">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="76f09-116">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="76f09-116">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="76f09-117">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="76f09-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="76f09-118">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="76f09-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="76f09-119">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="76f09-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="76f09-120">Office 2019 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="76f09-120">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="76f09-121">Office 2016 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="76f09-121">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="76f09-122">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="76f09-122">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-124">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-124">Excel</span></span>

-   [<span data-ttu-id="76f09-125">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="76f09-125">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="76f09-126">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="76f09-126">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="76f09-127">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="76f09-127">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="76f09-128">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="76f09-128">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="76f09-129">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-129">Word</span></span>

-   [<span data-ttu-id="76f09-130">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="76f09-130">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="76f09-131">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="76f09-131">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="76f09-132">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-132">Office Suite</span></span>

-   [<span data-ttu-id="76f09-133">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="76f09-133">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1193)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="august-11-2020"></a><span data-ttu-id="76f09-135">2020 年 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="76f09-135">August 11, 2020</span></span>
<span data-ttu-id="76f09-136">現在のチャネル: バージョン2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="76f09-136">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="76f09-137">月次エンタープライズ チャネル: バージョン2006 (ビルド 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="76f09-137">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="76f09-138">月次エンタープライズ チャネル: バージョン2005 (ビルド 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="76f09-138">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="76f09-139">半期エンタープライズ チャネル (プレビュー)： バージョン2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="76f09-139">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="76f09-140">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="76f09-140">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="76f09-141">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="76f09-141">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="76f09-142">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="76f09-142">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="76f09-143">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="76f09-143">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="76f09-144">Office 2019 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="76f09-144">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="76f09-145">Office 2016 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="76f09-145">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="76f09-146">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="76f09-146">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="76f09-148">Access</span><span class="sxs-lookup"><span data-stu-id="76f09-148">Access</span></span>

-   [<span data-ttu-id="76f09-149">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="76f09-149">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="76f09-150">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-150">Excel</span></span>

-   [<span data-ttu-id="76f09-151">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="76f09-151">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="76f09-152">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="76f09-152">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="76f09-153">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="76f09-153">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="76f09-154">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="76f09-154">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="76f09-155">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="76f09-155">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="76f09-156">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-156">Outlook</span></span>

-   [<span data-ttu-id="76f09-157">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="76f09-157">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="76f09-158">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="76f09-158">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="76f09-159">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-159">Word</span></span>

-   [<span data-ttu-id="76f09-160">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="76f09-160">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="76f09-161">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="76f09-161">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="76f09-162">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="76f09-162">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="76f09-163">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-163">Office Suite</span></span>

-   [<span data-ttu-id="76f09-164">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="76f09-164">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="76f09-165">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="76f09-165">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1563)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="july-14-2020"></a><span data-ttu-id="76f09-167">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="76f09-167">July 14, 2020</span></span>
<span data-ttu-id="76f09-168">現在のチャネル: バージョン 2006 (ビルド 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="76f09-168">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="76f09-169">月次エンタープライズ チャネル: バージョン 2005 (ビルド 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="76f09-169">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="76f09-170">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="76f09-170">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="76f09-171">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="76f09-171">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="76f09-172">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="76f09-172">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="76f09-173">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="76f09-173">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="76f09-174">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="76f09-174">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="76f09-175">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="76f09-175">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-177">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-177">Excel</span></span>

-   [<span data-ttu-id="76f09-178">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="76f09-178">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="76f09-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-179">Outlook</span></span>

-   [<span data-ttu-id="76f09-180">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="76f09-180">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="76f09-181">Project</span><span class="sxs-lookup"><span data-stu-id="76f09-181">Project</span></span>

-   [<span data-ttu-id="76f09-182">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="76f09-182">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="76f09-183">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-183">Word</span></span>

-   [<span data-ttu-id="76f09-184">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="76f09-184">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="76f09-185">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="76f09-185">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="76f09-186">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="76f09-186">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="76f09-187">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="76f09-187">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="76f09-188">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-188">Office Suite</span></span>

-   [<span data-ttu-id="76f09-189">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="76f09-189">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1458)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="june-09-2020"></a><span data-ttu-id="76f09-191">2020 年 6 月 09 日</span><span class="sxs-lookup"><span data-stu-id="76f09-191">June 09, 2020</span></span>
<span data-ttu-id="76f09-192">現在のチャネル: バージョン 2005 (ビルド 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="76f09-192">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="76f09-193">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="76f09-193">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="76f09-194">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="76f09-194">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="76f09-195">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="76f09-195">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="76f09-196">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="76f09-196">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="76f09-197">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="76f09-197">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="76f09-198">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="76f09-198">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-200">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-200">Excel</span></span>

-   [<span data-ttu-id="76f09-201">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="76f09-201">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="76f09-202">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="76f09-202">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="76f09-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-203">Outlook</span></span>

-   [<span data-ttu-id="76f09-204">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="76f09-204">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="76f09-205">Project</span><span class="sxs-lookup"><span data-stu-id="76f09-205">Project</span></span>

-   [<span data-ttu-id="76f09-206">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="76f09-206">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="76f09-207">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-207">Office Suite</span></span>

-   [<span data-ttu-id="76f09-208">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="76f09-208">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1321)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="may-12-2020"></a><span data-ttu-id="76f09-210">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="76f09-210">May 12, 2020</span></span>
<span data-ttu-id="76f09-211">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="76f09-211">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="76f09-212">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="76f09-212">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="76f09-213">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="76f09-213">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="76f09-214">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="76f09-214">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="76f09-215">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="76f09-215">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="76f09-216">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="76f09-216">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-218">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-218">Excel</span></span>

-   [<span data-ttu-id="76f09-219">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="76f09-219">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="76f09-221">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="76f09-221">April 14, 2020</span></span>
<span data-ttu-id="76f09-222">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="76f09-222">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="76f09-223">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="76f09-223">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="76f09-224">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="76f09-224">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="76f09-225">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="76f09-225">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="76f09-226">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="76f09-226">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-228">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-228">Excel</span></span>

-   [<span data-ttu-id="76f09-229">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="76f09-229">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="76f09-230">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="76f09-230">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="76f09-231">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-231">Word</span></span>

-   [<span data-ttu-id="76f09-232">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="76f09-232">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="76f09-233">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-233">Office Suite</span></span>

-   [<span data-ttu-id="76f09-234">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="76f09-234">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="76f09-235">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="76f09-235">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="76f09-236">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="76f09-236">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="76f09-238">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="76f09-238">March 10, 2020</span></span>
<span data-ttu-id="76f09-239">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="76f09-239">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="76f09-240">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="76f09-240">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="76f09-241">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="76f09-241">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="76f09-242">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="76f09-242">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="76f09-243">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="76f09-243">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="76f09-245">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-245">Word</span></span>

-   [<span data-ttu-id="76f09-246">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="76f09-246">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="76f09-247">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="76f09-247">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="76f09-248">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="76f09-248">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="76f09-249">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="76f09-249">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="76f09-251">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="76f09-251">February 11, 2020</span></span>
<span data-ttu-id="76f09-252">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="76f09-252">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="76f09-253">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="76f09-253">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="76f09-254">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="76f09-254">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="76f09-255">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="76f09-255">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="76f09-256">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="76f09-256">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-258">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-258">Excel</span></span>

-   [<span data-ttu-id="76f09-259">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="76f09-259">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="76f09-260">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-260">Outlook</span></span>

-   [<span data-ttu-id="76f09-261">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="76f09-261">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="76f09-262">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-262">Office Suite</span></span>

-   [<span data-ttu-id="76f09-263">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="76f09-263">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="76f09-265">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="76f09-265">January 14, 2020</span></span>
<span data-ttu-id="76f09-266">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="76f09-266">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="76f09-267">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="76f09-267">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="76f09-268">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="76f09-268">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="76f09-269">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="76f09-269">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="76f09-270">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="76f09-270">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="76f09-272">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-272">Excel</span></span>

-   [<span data-ttu-id="76f09-273">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="76f09-273">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="76f09-274">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="76f09-274">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="76f09-275">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="76f09-275">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="76f09-276">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-276">Office Suite</span></span>

-   [<span data-ttu-id="76f09-277">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="76f09-277">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="76f09-279">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="76f09-279">December 10, 2019</span></span>
<span data-ttu-id="76f09-280">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="76f09-280">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="76f09-281">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="76f09-281">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="76f09-282">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="76f09-282">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="76f09-283">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="76f09-283">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-284">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-284">Excel</span></span>

-   [<span data-ttu-id="76f09-285">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="76f09-285">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="76f09-286">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="76f09-286">PowerPoint</span></span>

-   [<span data-ttu-id="76f09-287">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="76f09-287">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="76f09-288">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-288">Word</span></span>

-   [<span data-ttu-id="76f09-289">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="76f09-289">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="76f09-290">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-290">Office Suite</span></span>

-   [<span data-ttu-id="76f09-291">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="76f09-291">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="76f09-292">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="76f09-292">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="76f09-293">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="76f09-293">November 12, 2019</span></span>
<span data-ttu-id="76f09-294">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="76f09-294">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="76f09-295">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="76f09-295">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="76f09-296">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="76f09-296">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="76f09-297">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="76f09-297">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-298">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-298">Excel</span></span>

-   [<span data-ttu-id="76f09-299">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="76f09-299">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="76f09-300">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="76f09-300">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="76f09-301">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-301">Office Suite</span></span>

-   [<span data-ttu-id="76f09-302">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="76f09-302">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="76f09-303">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="76f09-303">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="76f09-304">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="76f09-304">October 08, 2019</span></span>
<span data-ttu-id="76f09-305">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="76f09-305">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="76f09-306">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="76f09-306">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="76f09-307">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="76f09-307">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="76f09-308">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="76f09-308">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-309">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-309">Excel</span></span>

-   [<span data-ttu-id="76f09-310">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="76f09-310">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="76f09-311">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="76f09-311">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="76f09-312">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="76f09-312">September 10, 2019</span></span>
<span data-ttu-id="76f09-313">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="76f09-313">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="76f09-314">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="76f09-314">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="76f09-315">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="76f09-315">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="76f09-316">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="76f09-316">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-317">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-317">Excel</span></span>

-   [<span data-ttu-id="76f09-318">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="76f09-318">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="76f09-319">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="76f09-319">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="76f09-320">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-320">Office Suite</span></span>

-   [<span data-ttu-id="76f09-321">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="76f09-321">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="76f09-322">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="76f09-322">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="76f09-323">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="76f09-323">August 13, 2019</span></span>
<span data-ttu-id="76f09-324">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="76f09-324">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="76f09-325">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="76f09-325">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="76f09-326">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="76f09-326">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="76f09-327">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="76f09-327">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="76f09-328">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="76f09-328">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="76f09-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-329">Outlook</span></span>

-   [<span data-ttu-id="76f09-330">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="76f09-330">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="76f09-331">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="76f09-331">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="76f09-332">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="76f09-332">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="76f09-333">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-333">Word</span></span>

-   [<span data-ttu-id="76f09-334">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="76f09-334">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="76f09-335">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="76f09-335">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="76f09-336">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-336">Office Suite</span></span>

-   [<span data-ttu-id="76f09-337">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="76f09-337">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="76f09-338">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="76f09-338">July 09, 2019</span></span>
<span data-ttu-id="76f09-339">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="76f09-339">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="76f09-340">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="76f09-340">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="76f09-341">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="76f09-341">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="76f09-342">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="76f09-342">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="76f09-343">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="76f09-343">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="76f09-344">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-344">Excel</span></span>

-   [<span data-ttu-id="76f09-345">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="76f09-345">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="76f09-346">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="76f09-346">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="76f09-347">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="76f09-347">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="76f09-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-348">Outlook</span></span>

-   [<span data-ttu-id="76f09-349">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="76f09-349">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="76f09-350">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="76f09-350">Skype for Business</span></span>

-   [<span data-ttu-id="76f09-351">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="76f09-351">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="76f09-352">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-352">Office Suite</span></span>

-   [<span data-ttu-id="76f09-353">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="76f09-353">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="76f09-354">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="76f09-354">June 11, 2019</span></span>
<span data-ttu-id="76f09-355">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="76f09-355">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="76f09-356">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="76f09-356">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="76f09-357">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="76f09-357">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="76f09-358">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="76f09-358">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="76f09-359">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-359">Word</span></span>

-   [<span data-ttu-id="76f09-360">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="76f09-360">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="76f09-361">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="76f09-361">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="76f09-362">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="76f09-362">May 14, 2019</span></span>
<span data-ttu-id="76f09-363">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="76f09-363">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="76f09-364">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="76f09-364">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="76f09-365">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="76f09-365">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="76f09-366">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="76f09-366">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="76f09-367">Word</span><span class="sxs-lookup"><span data-stu-id="76f09-367">Word</span></span>

-   [<span data-ttu-id="76f09-368">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="76f09-368">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="76f09-369">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-369">Office Suite</span></span>

-   [<span data-ttu-id="76f09-370">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="76f09-370">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="76f09-371">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="76f09-371">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="76f09-372">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="76f09-372">April 09, 2019</span></span>
<span data-ttu-id="76f09-373">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="76f09-373">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="76f09-374">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="76f09-374">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="76f09-375">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="76f09-375">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="76f09-376">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="76f09-376">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-377">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-377">Excel</span></span>

-   [<span data-ttu-id="76f09-378">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="76f09-378">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="76f09-379">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-379">Office Suite</span></span>

-   [<span data-ttu-id="76f09-380">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="76f09-380">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="76f09-381">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="76f09-381">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="76f09-382">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="76f09-382">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="76f09-383">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="76f09-383">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="76f09-384">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="76f09-384">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="76f09-385">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="76f09-385">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="76f09-386">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="76f09-386">March 12, 2019</span></span>
<span data-ttu-id="76f09-387">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="76f09-387">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="76f09-388">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="76f09-388">February 12, 2019</span></span>
<span data-ttu-id="76f09-389">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="76f09-389">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="76f09-390">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="76f09-390">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="76f09-391">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="76f09-391">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="76f09-392">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="76f09-392">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="76f09-393">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="76f09-393">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="76f09-394">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-394">Excel</span></span>

-   [<span data-ttu-id="76f09-395">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="76f09-395">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="76f09-396">Office スイート</span><span class="sxs-lookup"><span data-stu-id="76f09-396">Office suite</span></span>

-   [<span data-ttu-id="76f09-397">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="76f09-397">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="76f09-398">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="76f09-398">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="76f09-399">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="76f09-399">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="76f09-400">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="76f09-400">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="76f09-401">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="76f09-401">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="76f09-402">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="76f09-402">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="76f09-403">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="76f09-403">January 8, 2019</span></span>

<span data-ttu-id="76f09-404">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="76f09-404">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="76f09-405">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="76f09-405">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="76f09-406">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="76f09-406">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="76f09-407">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="76f09-407">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="76f09-408">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="76f09-408">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="76f09-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-409">Outlook</span></span>
-   [<span data-ttu-id="76f09-410">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="76f09-410">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="76f09-411">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="76f09-411">Word: Security updates</span></span> 
-   [<span data-ttu-id="76f09-412">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="76f09-412">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="76f09-413">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="76f09-413">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="76f09-414">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="76f09-414">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="76f09-415">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="76f09-415">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="76f09-416">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="76f09-416">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="76f09-417">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="76f09-417">December 11, 2018</span></span>
<span data-ttu-id="76f09-418">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="76f09-418">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="76f09-419">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="76f09-419">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="76f09-420">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="76f09-420">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-421">Excel</span><span class="sxs-lookup"><span data-stu-id="76f09-421">Excel</span></span>

-   [<span data-ttu-id="76f09-422">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="76f09-422">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="76f09-423">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="76f09-423">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="76f09-424">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="76f09-424">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="76f09-425">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="76f09-425">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="76f09-426">Outlook</span><span class="sxs-lookup"><span data-stu-id="76f09-426">Outlook</span></span>

-   [<span data-ttu-id="76f09-427">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="76f09-427">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="76f09-428">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="76f09-428">PowerPoint</span></span>

-   [<span data-ttu-id="76f09-429">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="76f09-429">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="76f09-430">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="76f09-430">November 13, 2018</span></span>
<span data-ttu-id="76f09-431">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="76f09-431">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="76f09-432">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="76f09-432">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="76f09-433">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="76f09-433">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="76f09-434">Excel:</span><span class="sxs-lookup"><span data-stu-id="76f09-434">Excel:</span></span>

-   [<span data-ttu-id="76f09-435">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="76f09-435">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="76f09-436">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="76f09-436">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="76f09-437">Outlook:</span><span class="sxs-lookup"><span data-stu-id="76f09-437">Outlook:</span></span>

-   [<span data-ttu-id="76f09-438">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="76f09-438">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="76f09-439">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="76f09-439">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="76f09-440">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="76f09-440">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="76f09-441">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="76f09-441">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="76f09-442">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="76f09-442">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="76f09-443">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="76f09-443">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="76f09-444">Project:</span><span class="sxs-lookup"><span data-stu-id="76f09-444">Project:</span></span>

-   [<span data-ttu-id="76f09-445">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="76f09-445">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="76f09-446">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="76f09-446">Skype for Business:</span></span>

-   [<span data-ttu-id="76f09-447">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="76f09-447">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="76f09-448">Word:</span><span class="sxs-lookup"><span data-stu-id="76f09-448">Word:</span></span>

-   [<span data-ttu-id="76f09-449">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="76f09-449">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573)
