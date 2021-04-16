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
ms.openlocfilehash: d48841f375a580216deb525163cc2e1b72ebd5c4
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/13/2021
ms.locfileid: "51749105"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="a717b-103">Microsoft Office セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="a717b-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="a717b-104">このリリース ノートには、Microsoft Officeの更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="a717b-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="a717b-105">この情報は、エンタープライズ用Microsoft 365 アプリ、ビジネス用Microsoft 365アプリ、Office 2016 リテール (C2R)およびOffice 2019に適用されます。</span><span class="sxs-lookup"><span data-stu-id="a717b-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="a717b-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="a717b-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a717b-107">詳細については、[こちらの記事](/DeployOffice/update-channels-changes)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a717b-107">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>
> - <span data-ttu-id="a717b-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="a717b-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span> <span data-ttu-id="a717b-109">詳細については、[こちらの記事](/deployoffice/name-change)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a717b-109">To learn more, [read this article](/deployoffice/name-change).</span></span> <span data-ttu-id="a717b-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="a717b-110">In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="april-13-2021"></a><span data-ttu-id="a717b-112">2021年 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a717b-112">April 13, 2021</span></span>
<span data-ttu-id="a717b-113">最新チャネル: バージョン 2103 (ビルド 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="a717b-113">Current Channel: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="a717b-114">月次エンタープライズ チャネル: バージョン 2102 (ビルド 13801.20506)</span><span class="sxs-lookup"><span data-stu-id="a717b-114">Monthly Enterprise Channel: Version 2102 (Build 13801.20506)</span></span>  
<span data-ttu-id="a717b-115">月次エンタープライズ チャネル: バージョン 2101 (ビルド 13628.20664)</span><span class="sxs-lookup"><span data-stu-id="a717b-115">Monthly Enterprise Channel: Version 2101 (Build 13628.20664)</span></span>  
<span data-ttu-id="a717b-116">半期エンタープライズ チャネル (プレビュー): バージョン 2102 (ビルド 13801.20506)</span><span class="sxs-lookup"><span data-stu-id="a717b-116">Semi-Annual Enterprise Channel (Preview): Version 2102 (Build 13801.20506)</span></span>  
<span data-ttu-id="a717b-117">半期エンタープライズ チャネル: バージョン 2008 (ビルド 13127.21506)</span><span class="sxs-lookup"><span data-stu-id="a717b-117">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21506)</span></span>  
<span data-ttu-id="a717b-118">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21814)</span><span class="sxs-lookup"><span data-stu-id="a717b-118">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21814)</span></span>  
<span data-ttu-id="a717b-119">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21814)</span><span class="sxs-lookup"><span data-stu-id="a717b-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21814)</span></span>  
<span data-ttu-id="a717b-120">Office 2019 リテール版: バージョン 2103 (ビルド 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="a717b-120">Office 2019 Retail: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="a717b-121">Office 2016 リテール版: バージョン 2103 (ビルド 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="a717b-121">Office 2016 Retail: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="a717b-122">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10373.20050)</span><span class="sxs-lookup"><span data-stu-id="a717b-122">Office 2019 Volume Licensed: Version 1808 (Build 10373.20050)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-124">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-124">Excel</span></span>

-   [<span data-ttu-id="a717b-125">CVE-2021-28451</span><span class="sxs-lookup"><span data-stu-id="a717b-125">CVE-2021-28451</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28451)
-   [<span data-ttu-id="a717b-126">CVE-2021-28454</span><span class="sxs-lookup"><span data-stu-id="a717b-126">CVE-2021-28454</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28454)
-   [<span data-ttu-id="a717b-127">CVE-2021-28456</span><span class="sxs-lookup"><span data-stu-id="a717b-127">CVE-2021-28456</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28456)

### <a name="outlook"></a><span data-ttu-id="a717b-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-128">Outlook</span></span>

-   [<span data-ttu-id="a717b-129">CVE-2021-28452</span><span class="sxs-lookup"><span data-stu-id="a717b-129">CVE-2021-28452</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28452)

### <a name="word"></a><span data-ttu-id="a717b-130">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-130">Word</span></span>

-   [<span data-ttu-id="a717b-131">CVE-2021-28453</span><span class="sxs-lookup"><span data-stu-id="a717b-131">CVE-2021-28453</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28453)

### <a name="office-suite"></a><span data-ttu-id="a717b-132">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-132">Office Suite</span></span>

-   [<span data-ttu-id="a717b-133">CVE-2021-28449</span><span class="sxs-lookup"><span data-stu-id="a717b-133">CVE-2021-28449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-28449)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-09-2021"></a><span data-ttu-id="a717b-135">2021 年 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a717b-135">March 09, 2021</span></span>
<span data-ttu-id="a717b-136">最新チャネル: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="a717b-136">Current Channel: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="a717b-137">月次エンタープライズ チャネル: バージョン 2101 (ビルド 13628.20528)</span><span class="sxs-lookup"><span data-stu-id="a717b-137">Monthly Enterprise Channel: Version 2101 (Build 13628.20528)</span></span>  
<span data-ttu-id="a717b-138">月次エンタープライズ チャネル: バージョン 2012 (ビルド 13530.20628)</span><span class="sxs-lookup"><span data-stu-id="a717b-138">Monthly Enterprise Channel: Version 2012 (Build 13530.20628)</span></span>  
<span data-ttu-id="a717b-139">半期エンタープライズ チャネル (プレビュー): バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="a717b-139">Semi-Annual Enterprise Channel (Preview): Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="a717b-140">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21348)</span><span class="sxs-lookup"><span data-stu-id="a717b-140">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21348)</span></span>  
<span data-ttu-id="a717b-141">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="a717b-141">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="a717b-142">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="a717b-142">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="a717b-143">Office 2019 リテール版: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="a717b-143">Office 2019 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="a717b-144">Office 2016 リテール版: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="a717b-144">Office 2016 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="a717b-145">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10372.20060)</span><span class="sxs-lookup"><span data-stu-id="a717b-145">Office 2019 Volume Licensed: Version 1808 (Build 10372.20060)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-147">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-147">Excel</span></span>

-   [<span data-ttu-id="a717b-148">CVE-2021-27054</span><span class="sxs-lookup"><span data-stu-id="a717b-148">CVE-2021-27054</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27054)
-   [<span data-ttu-id="a717b-149">CVE-2021-27057</span><span class="sxs-lookup"><span data-stu-id="a717b-149">CVE-2021-27057</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27057)
-   [<span data-ttu-id="a717b-150">CVE-2021-27053</span><span class="sxs-lookup"><span data-stu-id="a717b-150">CVE-2021-27053</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27053)

### <a name="powerpoint"></a><span data-ttu-id="a717b-151">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a717b-151">PowerPoint</span></span>

-   [<span data-ttu-id="a717b-152">CVE-2021-27056</span><span class="sxs-lookup"><span data-stu-id="a717b-152">CVE-2021-27056</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27056)

### <a name="visio"></a><span data-ttu-id="a717b-153">Visio</span><span class="sxs-lookup"><span data-stu-id="a717b-153">Visio</span></span>

-   [<span data-ttu-id="a717b-154">CVE-2021-27055</span><span class="sxs-lookup"><span data-stu-id="a717b-154">CVE-2021-27055</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27055)

### <a name="office-suite"></a><span data-ttu-id="a717b-155">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-155">Office Suite</span></span>

-   [<span data-ttu-id="a717b-156">CVE-2021-27058</span><span class="sxs-lookup"><span data-stu-id="a717b-156">CVE-2021-27058</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-27058)
-   [<span data-ttu-id="a717b-157">CVE-2021-24108</span><span class="sxs-lookup"><span data-stu-id="a717b-157">CVE-2021-24108</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-24108)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-09-2021"></a><span data-ttu-id="a717b-159">2021 年 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a717b-159">February 09, 2021</span></span>
<span data-ttu-id="a717b-160">現在のチャネル: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="a717b-160">Current Channel: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="a717b-161">月次エンタープライズ チャネル: バージョン 2012 (ビルド 13530.20528)</span><span class="sxs-lookup"><span data-stu-id="a717b-161">Monthly Enterprise Channel: Version 2012 (Build 13530.20528)</span></span>  
<span data-ttu-id="a717b-162">月次エンタープライズ チャネル: バージョン 2011 (ビルド 13426.20658)</span><span class="sxs-lookup"><span data-stu-id="a717b-162">Monthly Enterprise Channel: Version 2011 (Build 13426.20658)</span></span>  
<span data-ttu-id="a717b-163">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="a717b-163">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="a717b-164">半期エンタープライズ チャネル: バージョン 2008 (ビルド 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="a717b-164">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="a717b-165">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="a717b-165">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="a717b-166">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.21008)</span><span class="sxs-lookup"><span data-stu-id="a717b-166">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.21008)</span></span>  
<span data-ttu-id="a717b-167">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="a717b-167">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="a717b-168">Office 2019 製品版: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="a717b-168">Office 2019 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="a717b-169">Office 2016 製品版: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="a717b-169">Office 2016 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="a717b-170">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10371.20060)</span><span class="sxs-lookup"><span data-stu-id="a717b-170">Office 2019 Volume Licensed: Version 1808 (Build 10371.20060)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-172">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-172">Excel</span></span>

-   [<span data-ttu-id="a717b-173">CVE-2021-24069</span><span class="sxs-lookup"><span data-stu-id="a717b-173">CVE-2021-24069</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-24069)
-   [<span data-ttu-id="a717b-174">CVE-2021-24070</span><span class="sxs-lookup"><span data-stu-id="a717b-174">CVE-2021-24070</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-24070)
-   [<span data-ttu-id="a717b-175">CVE-2021-24067</span><span class="sxs-lookup"><span data-stu-id="a717b-175">CVE-2021-24067</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-24067)

[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="january-12-2021"></a><span data-ttu-id="a717b-177">2021 年 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a717b-177">January 12, 2021</span></span>
<span data-ttu-id="a717b-178">現在のチャネル: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="a717b-178">Current Channel: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="a717b-179">月次エンタープライズ チャネル: バージョン 2011 (ビルド 13426.20526)</span><span class="sxs-lookup"><span data-stu-id="a717b-179">Monthly Enterprise Channel: Version 2011 (Build 13426.20526)</span></span>  
<span data-ttu-id="a717b-180">月次エンタープライズ チャネル: バージョン 2010 (ビルド 13328.20550)</span><span class="sxs-lookup"><span data-stu-id="a717b-180">Monthly Enterprise Channel: Version 2010 (Build 13328.20550)</span></span>  
<span data-ttu-id="a717b-181">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="a717b-181">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="a717b-182">半期エンタープライズ チャネル: バージョン 2008 (ビルド 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="a717b-182">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="a717b-183">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="a717b-183">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="a717b-184">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20994)</span><span class="sxs-lookup"><span data-stu-id="a717b-184">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20994)</span></span>  
<span data-ttu-id="a717b-185">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="a717b-185">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="a717b-186">Office 2019 製品版: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="a717b-186">Office 2019 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="a717b-187">Office 2016 製品版: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="a717b-187">Office 2016 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="a717b-188">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10370.20052)</span><span class="sxs-lookup"><span data-stu-id="a717b-188">Office 2019 Volume Licensed: Version 1808 (Build 10370.20052)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-190">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-190">Excel</span></span>

-   [<span data-ttu-id="a717b-191">CVE-2021-1714</span><span class="sxs-lookup"><span data-stu-id="a717b-191">CVE-2021-1714</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-1714)
-   [<span data-ttu-id="a717b-192">CVE-2021-1713</span><span class="sxs-lookup"><span data-stu-id="a717b-192">CVE-2021-1713</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-1713)

### <a name="word"></a><span data-ttu-id="a717b-193">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-193">Word</span></span>

-   [<span data-ttu-id="a717b-194">CVE-2021-1715</span><span class="sxs-lookup"><span data-stu-id="a717b-194">CVE-2021-1715</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-1715)
-   [<span data-ttu-id="a717b-195">CVE-2021-1716</span><span class="sxs-lookup"><span data-stu-id="a717b-195">CVE-2021-1716</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-1716)

### <a name="office-suite"></a><span data-ttu-id="a717b-196">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-196">Office Suite</span></span>

-   [<span data-ttu-id="a717b-197">CVE-2021-1711</span><span class="sxs-lookup"><span data-stu-id="a717b-197">CVE-2021-1711</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2021-1711)


[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="december-08-2020"></a><span data-ttu-id="a717b-199">2020 年12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="a717b-199">December 08, 2020</span></span>
<span data-ttu-id="a717b-200">最新チャネル: バージョン2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="a717b-200">Current Channel: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="a717b-201">月次エンタープライズチャネル: バージョン 2010 (ビルド 13328.20478)</span><span class="sxs-lookup"><span data-stu-id="a717b-201">Monthly Enterprise Channel: Version 2010 (Build 13328.20478)</span></span>  
<span data-ttu-id="a717b-202">月次エンタープライズチャネル: バージョン 2009 (ビルド 13231.20620)</span><span class="sxs-lookup"><span data-stu-id="a717b-202">Monthly Enterprise Channel: Version 2009 (Build 13231.20620)</span></span>  
<span data-ttu-id="a717b-203">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20910)</span><span class="sxs-lookup"><span data-stu-id="a717b-203">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20910)</span></span>  
<span data-ttu-id="a717b-204">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="a717b-204">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="a717b-205">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20984)</span><span class="sxs-lookup"><span data-stu-id="a717b-205">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20984)</span></span>  
<span data-ttu-id="a717b-206">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="a717b-206">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="a717b-207">Office 2019 リテール版: バージョン 2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="a717b-207">Office 2019 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="a717b-208">Office 2016 リテール版: バージョン 2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="a717b-208">Office 2016 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="a717b-209">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10369.20032)</span><span class="sxs-lookup"><span data-stu-id="a717b-209">Office 2019 Volume Licensed: Version 1808 (Build 10369.20032)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-211">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-211">Excel</span></span>

-   [<span data-ttu-id="a717b-212">CVE-2020-17123</span><span class="sxs-lookup"><span data-stu-id="a717b-212">CVE-2020-17123</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17123)
-   [<span data-ttu-id="a717b-213">CVE-2020-17125</span><span class="sxs-lookup"><span data-stu-id="a717b-213">CVE-2020-17125</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17125)
-   [<span data-ttu-id="a717b-214">CVE-2020-17126</span><span class="sxs-lookup"><span data-stu-id="a717b-214">CVE-2020-17126</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17126)
-   [<span data-ttu-id="a717b-215">CVE-2020-17128</span><span class="sxs-lookup"><span data-stu-id="a717b-215">CVE-2020-17128</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17128)
-   [<span data-ttu-id="a717b-216">CVE-2020-17129</span><span class="sxs-lookup"><span data-stu-id="a717b-216">CVE-2020-17129</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17129)
-   [<span data-ttu-id="a717b-217">CVE-2020-17130</span><span class="sxs-lookup"><span data-stu-id="a717b-217">CVE-2020-17130</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17130)

### <a name="outlook"></a><span data-ttu-id="a717b-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-218">Outlook</span></span>

-   [<span data-ttu-id="a717b-219">CVE-2020-17119</span><span class="sxs-lookup"><span data-stu-id="a717b-219">CVE-2020-17119</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17119)

### <a name="powerpoint"></a><span data-ttu-id="a717b-220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a717b-220">PowerPoint</span></span>

-   [<span data-ttu-id="a717b-221">CVE-2020-17124</span><span class="sxs-lookup"><span data-stu-id="a717b-221">CVE-2020-17124</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17124)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="november-10-2020"></a><span data-ttu-id="a717b-223">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a717b-223">November 10, 2020</span></span>
<span data-ttu-id="a717b-224">現在のチャネル: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="a717b-224">Current Channel: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="a717b-225">月次エンタープライズ チャネル: バージョン 2009 (Build 13231.20514)</span><span class="sxs-lookup"><span data-stu-id="a717b-225">Monthly Enterprise Channel: Version 2009 (Build 13231.20514)</span></span>  
<span data-ttu-id="a717b-226">月次エンタープライズ チャネル: バージョン 2008 (Build 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="a717b-226">Monthly Enterprise Channel: Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="a717b-227">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="a717b-227">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="a717b-228">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="a717b-228">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="a717b-229">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20974)</span><span class="sxs-lookup"><span data-stu-id="a717b-229">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20974)</span></span>  
<span data-ttu-id="a717b-230">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="a717b-230">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="a717b-231">Office 2019 製品版: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="a717b-231">Office 2019 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="a717b-232">Office 2016 製品版: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="a717b-232">Office 2016 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="a717b-233">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10368.20035)</span><span class="sxs-lookup"><span data-stu-id="a717b-233">Office 2019 Volume Licensed: Version 1808 (Build 10368.20035)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="excel"></a><span data-ttu-id="a717b-235">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-235">Excel</span></span>

-   [<span data-ttu-id="a717b-236">CVE-2020-17064</span><span class="sxs-lookup"><span data-stu-id="a717b-236">CVE-2020-17064</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17064)
-   [<span data-ttu-id="a717b-237">CVE-2020-17065</span><span class="sxs-lookup"><span data-stu-id="a717b-237">CVE-2020-17065</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17065)
-   [<span data-ttu-id="a717b-238">CVE-2020-17067</span><span class="sxs-lookup"><span data-stu-id="a717b-238">CVE-2020-17067</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17067)

### <a name="word"></a><span data-ttu-id="a717b-239">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-239">Word</span></span>

-   [<span data-ttu-id="a717b-240">CVE-2020-17020</span><span class="sxs-lookup"><span data-stu-id="a717b-240">CVE-2020-17020</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17020)

### <a name="office-suite"></a><span data-ttu-id="a717b-241">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-241">Office Suite</span></span>

-   [<span data-ttu-id="a717b-242">CVE-2020-17062</span><span class="sxs-lookup"><span data-stu-id="a717b-242">CVE-2020-17062</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17062)
-   [<span data-ttu-id="a717b-243">CVE-2020-17063</span><span class="sxs-lookup"><span data-stu-id="a717b-243">CVE-2020-17063</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-17063)

[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="october-13-2020"></a><span data-ttu-id="a717b-245">2020 年 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a717b-245">October 13, 2020</span></span>
<span data-ttu-id="a717b-246">最新チャネル: バージョン2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="a717b-246">Current Channel: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="a717b-247">月次エンタープライズ チャネル: バージョン 2008 (Build 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="a717b-247">Monthly Enterprise Channel: Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="a717b-248">月次エンタープライズ チャネル: バージョン 2007 (Build 13029.20708)</span><span class="sxs-lookup"><span data-stu-id="a717b-248">Monthly Enterprise Channel: Version 2007 (Build 13029.20708)</span></span>  
<span data-ttu-id="a717b-249">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="a717b-249">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="a717b-250">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="a717b-250">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="a717b-251">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20966)</span><span class="sxs-lookup"><span data-stu-id="a717b-251">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20966)</span></span>  
<span data-ttu-id="a717b-252">Windows 7 上の Microsoft 365アプリ: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="a717b-252">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="a717b-253">Office 2019 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="a717b-253">Office 2019 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="a717b-254">Office 2016 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="a717b-254">Office 2016 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="a717b-255">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10367.20048)</span><span class="sxs-lookup"><span data-stu-id="a717b-255">Office 2019 Volume Licensed: Version 1808 (Build 10367.20048)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="a717b-257">Access</span><span class="sxs-lookup"><span data-stu-id="a717b-257">Access</span></span>

-   [<span data-ttu-id="a717b-258">CVE-2020-16957</span><span class="sxs-lookup"><span data-stu-id="a717b-258">CVE-2020-16957</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16957)

### <a name="excel"></a><span data-ttu-id="a717b-259">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-259">Excel</span></span>

-   [<span data-ttu-id="a717b-260">CVE-2020-16929</span><span class="sxs-lookup"><span data-stu-id="a717b-260">CVE-2020-16929</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16929)
-   [<span data-ttu-id="a717b-261">CVE-2020-16931</span><span class="sxs-lookup"><span data-stu-id="a717b-261">CVE-2020-16931</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16931)
-   [<span data-ttu-id="a717b-262">CVE-2020-16932</span><span class="sxs-lookup"><span data-stu-id="a717b-262">CVE-2020-16932</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16932)

### <a name="outlook"></a><span data-ttu-id="a717b-263">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-263">Outlook</span></span>

-   [<span data-ttu-id="a717b-264">CVE-2020-16947</span><span class="sxs-lookup"><span data-stu-id="a717b-264">CVE-2020-16947</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16947)
-   [<span data-ttu-id="a717b-265">CVE-2020-16949</span><span class="sxs-lookup"><span data-stu-id="a717b-265">CVE-2020-16949</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16949)

### <a name="word"></a><span data-ttu-id="a717b-266">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-266">Word</span></span>

-   [<span data-ttu-id="a717b-267">CVE-2020-16933</span><span class="sxs-lookup"><span data-stu-id="a717b-267">CVE-2020-16933</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16933)

### <a name="office-suite"></a><span data-ttu-id="a717b-268">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-268">Office Suite</span></span>

-   [<span data-ttu-id="a717b-269">CVE-2020-16930</span><span class="sxs-lookup"><span data-stu-id="a717b-269">CVE-2020-16930</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16930)
-   [<span data-ttu-id="a717b-270">CVE-2020-16955</span><span class="sxs-lookup"><span data-stu-id="a717b-270">CVE-2020-16955</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16955)
-   [<span data-ttu-id="a717b-271">CVE-2020-16928</span><span class="sxs-lookup"><span data-stu-id="a717b-271">CVE-2020-16928</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16928)
-   [<span data-ttu-id="a717b-272">CVE-2020-16934</span><span class="sxs-lookup"><span data-stu-id="a717b-272">CVE-2020-16934</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16934)
-   [<span data-ttu-id="a717b-273">CVE-2020-16918</span><span class="sxs-lookup"><span data-stu-id="a717b-273">CVE-2020-16918</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16918)
-   [<span data-ttu-id="a717b-274">CVE-2020-16954</span><span class="sxs-lookup"><span data-stu-id="a717b-274">CVE-2020-16954</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-16954)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="september-08-2020"></a><span data-ttu-id="a717b-276">2020 年 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="a717b-276">September 08, 2020</span></span>
<span data-ttu-id="a717b-277">最新チャネル: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="a717b-277">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="a717b-278">月次エンタープライズ チャネル: バージョン 2007 (ビルド 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="a717b-278">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="a717b-279">月次エンタープライズ チャネル: バージョン 2006 (ビルド 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="a717b-279">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="a717b-280">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="a717b-280">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="a717b-281">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="a717b-281">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="a717b-282">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="a717b-282">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="a717b-283">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="a717b-283">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="a717b-284">Office 2019 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="a717b-284">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="a717b-285">Office 2016 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="a717b-285">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="a717b-286">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="a717b-286">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-288">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-288">Excel</span></span>

-   [<span data-ttu-id="a717b-289">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="a717b-289">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="a717b-290">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="a717b-290">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="a717b-291">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="a717b-291">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="a717b-292">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="a717b-292">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="a717b-293">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-293">Word</span></span>

-   [<span data-ttu-id="a717b-294">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="a717b-294">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="a717b-295">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="a717b-295">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="a717b-296">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-296">Office Suite</span></span>

-   [<span data-ttu-id="a717b-297">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="a717b-297">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1193)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="august-11-2020"></a><span data-ttu-id="a717b-299">2020 年 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a717b-299">August 11, 2020</span></span>
<span data-ttu-id="a717b-300">最新チャネル: バージョン2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="a717b-300">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="a717b-301">月次エンタープライズ チャネル: バージョン2006 (ビルド 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="a717b-301">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="a717b-302">月次エンタープライズ チャネル: バージョン2005 (ビルド 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="a717b-302">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="a717b-303">半期エンタープライズ チャネル (プレビュー)： バージョン2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="a717b-303">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="a717b-304">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="a717b-304">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="a717b-305">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="a717b-305">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="a717b-306">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="a717b-306">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="a717b-307">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="a717b-307">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="a717b-308">Office 2019 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="a717b-308">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="a717b-309">Office 2016 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="a717b-309">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="a717b-310">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="a717b-310">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="a717b-312">Access</span><span class="sxs-lookup"><span data-stu-id="a717b-312">Access</span></span>

-   [<span data-ttu-id="a717b-313">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="a717b-313">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="a717b-314">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-314">Excel</span></span>

-   [<span data-ttu-id="a717b-315">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="a717b-315">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="a717b-316">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="a717b-316">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="a717b-317">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="a717b-317">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="a717b-318">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="a717b-318">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="a717b-319">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="a717b-319">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="a717b-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-320">Outlook</span></span>

-   [<span data-ttu-id="a717b-321">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="a717b-321">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="a717b-322">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="a717b-322">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="a717b-323">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-323">Word</span></span>

-   [<span data-ttu-id="a717b-324">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="a717b-324">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="a717b-325">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="a717b-325">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="a717b-326">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="a717b-326">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="a717b-327">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-327">Office Suite</span></span>

-   [<span data-ttu-id="a717b-328">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="a717b-328">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="a717b-329">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="a717b-329">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1563)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="july-14-2020"></a><span data-ttu-id="a717b-331">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a717b-331">July 14, 2020</span></span>
<span data-ttu-id="a717b-332">最新チャネル: バージョン 2006 (ビルド 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="a717b-332">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="a717b-333">月次エンタープライズ チャネル: バージョン 2005 (ビルド 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="a717b-333">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="a717b-334">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="a717b-334">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="a717b-335">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="a717b-335">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="a717b-336">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="a717b-336">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="a717b-337">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="a717b-337">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="a717b-338">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="a717b-338">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="a717b-339">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="a717b-339">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-341">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-341">Excel</span></span>

-   [<span data-ttu-id="a717b-342">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="a717b-342">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="a717b-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-343">Outlook</span></span>

-   [<span data-ttu-id="a717b-344">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="a717b-344">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="a717b-345">Project</span><span class="sxs-lookup"><span data-stu-id="a717b-345">Project</span></span>

-   [<span data-ttu-id="a717b-346">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="a717b-346">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="a717b-347">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-347">Word</span></span>

-   [<span data-ttu-id="a717b-348">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="a717b-348">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="a717b-349">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="a717b-349">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="a717b-350">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="a717b-350">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="a717b-351">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="a717b-351">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="a717b-352">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-352">Office Suite</span></span>

-   [<span data-ttu-id="a717b-353">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="a717b-353">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1458)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="june-09-2020"></a><span data-ttu-id="a717b-355">2020 年 6 月 09 日</span><span class="sxs-lookup"><span data-stu-id="a717b-355">June 09, 2020</span></span>
<span data-ttu-id="a717b-356">最新チャネル: バージョン 2005 (ビルド 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="a717b-356">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="a717b-357">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="a717b-357">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="a717b-358">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="a717b-358">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="a717b-359">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="a717b-359">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="a717b-360">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="a717b-360">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="a717b-361">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="a717b-361">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="a717b-362">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="a717b-362">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-364">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-364">Excel</span></span>

-   [<span data-ttu-id="a717b-365">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="a717b-365">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="a717b-366">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="a717b-366">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="a717b-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-367">Outlook</span></span>

-   [<span data-ttu-id="a717b-368">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="a717b-368">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="a717b-369">Project</span><span class="sxs-lookup"><span data-stu-id="a717b-369">Project</span></span>

-   [<span data-ttu-id="a717b-370">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="a717b-370">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="a717b-371">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-371">Office Suite</span></span>

-   [<span data-ttu-id="a717b-372">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="a717b-372">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-1321)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="may-12-2020"></a><span data-ttu-id="a717b-374">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a717b-374">May 12, 2020</span></span>
<span data-ttu-id="a717b-375">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="a717b-375">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="a717b-376">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="a717b-376">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="a717b-377">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="a717b-377">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="a717b-378">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="a717b-378">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="a717b-379">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="a717b-379">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="a717b-380">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="a717b-380">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-382">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-382">Excel</span></span>

-   [<span data-ttu-id="a717b-383">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="a717b-383">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="a717b-385">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a717b-385">April 14, 2020</span></span>
<span data-ttu-id="a717b-386">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="a717b-386">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="a717b-387">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="a717b-387">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="a717b-388">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="a717b-388">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="a717b-389">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="a717b-389">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="a717b-390">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="a717b-390">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-392">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-392">Excel</span></span>

-   [<span data-ttu-id="a717b-393">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="a717b-393">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="a717b-394">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="a717b-394">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="a717b-395">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-395">Word</span></span>

-   [<span data-ttu-id="a717b-396">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="a717b-396">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="a717b-397">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-397">Office Suite</span></span>

-   [<span data-ttu-id="a717b-398">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="a717b-398">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="a717b-399">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="a717b-399">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="a717b-400">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="a717b-400">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="a717b-402">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a717b-402">March 10, 2020</span></span>
<span data-ttu-id="a717b-403">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="a717b-403">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="a717b-404">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="a717b-404">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="a717b-405">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="a717b-405">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="a717b-406">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="a717b-406">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="a717b-407">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="a717b-407">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="a717b-409">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-409">Word</span></span>

-   [<span data-ttu-id="a717b-410">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="a717b-410">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="a717b-411">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="a717b-411">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="a717b-412">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="a717b-412">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="a717b-413">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="a717b-413">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="a717b-415">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a717b-415">February 11, 2020</span></span>
<span data-ttu-id="a717b-416">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="a717b-416">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="a717b-417">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="a717b-417">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="a717b-418">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="a717b-418">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="a717b-419">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="a717b-419">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="a717b-420">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="a717b-420">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-422">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-422">Excel</span></span>

-   [<span data-ttu-id="a717b-423">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="a717b-423">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="a717b-424">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-424">Outlook</span></span>

-   [<span data-ttu-id="a717b-425">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="a717b-425">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="a717b-426">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-426">Office Suite</span></span>

-   [<span data-ttu-id="a717b-427">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="a717b-427">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="a717b-429">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a717b-429">January 14, 2020</span></span>
<span data-ttu-id="a717b-430">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="a717b-430">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="a717b-431">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="a717b-431">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="a717b-432">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="a717b-432">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="a717b-433">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="a717b-433">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="a717b-434">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="a717b-434">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="a717b-436">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-436">Excel</span></span>

-   [<span data-ttu-id="a717b-437">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="a717b-437">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="a717b-438">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="a717b-438">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="a717b-439">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="a717b-439">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="a717b-440">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-440">Office Suite</span></span>

-   [<span data-ttu-id="a717b-441">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="a717b-441">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="a717b-443">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a717b-443">December 10, 2019</span></span>
<span data-ttu-id="a717b-444">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="a717b-444">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="a717b-445">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="a717b-445">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="a717b-446">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="a717b-446">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="a717b-447">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="a717b-447">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-448">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-448">Excel</span></span>

-   [<span data-ttu-id="a717b-449">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="a717b-449">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="a717b-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a717b-450">PowerPoint</span></span>

-   [<span data-ttu-id="a717b-451">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="a717b-451">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="a717b-452">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-452">Word</span></span>

-   [<span data-ttu-id="a717b-453">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="a717b-453">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="a717b-454">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-454">Office Suite</span></span>

-   [<span data-ttu-id="a717b-455">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="a717b-455">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="a717b-456">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="a717b-456">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="a717b-457">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a717b-457">November 12, 2019</span></span>
<span data-ttu-id="a717b-458">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="a717b-458">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="a717b-459">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a717b-459">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="a717b-460">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a717b-460">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="a717b-461">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="a717b-461">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-462">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-462">Excel</span></span>

-   [<span data-ttu-id="a717b-463">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="a717b-463">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="a717b-464">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="a717b-464">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="a717b-465">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-465">Office Suite</span></span>

-   [<span data-ttu-id="a717b-466">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="a717b-466">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="a717b-467">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="a717b-467">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="a717b-468">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a717b-468">October 08, 2019</span></span>
<span data-ttu-id="a717b-469">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="a717b-469">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="a717b-470">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="a717b-470">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="a717b-471">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="a717b-471">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="a717b-472">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="a717b-472">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-473">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-473">Excel</span></span>

-   [<span data-ttu-id="a717b-474">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="a717b-474">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="a717b-475">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="a717b-475">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="a717b-476">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a717b-476">September 10, 2019</span></span>
<span data-ttu-id="a717b-477">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="a717b-477">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="a717b-478">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="a717b-478">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="a717b-479">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="a717b-479">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="a717b-480">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="a717b-480">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-481">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-481">Excel</span></span>

-   [<span data-ttu-id="a717b-482">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="a717b-482">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="a717b-483">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="a717b-483">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="a717b-484">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-484">Office Suite</span></span>

-   [<span data-ttu-id="a717b-485">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="a717b-485">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="a717b-486">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="a717b-486">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="a717b-487">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a717b-487">August 13, 2019</span></span>
<span data-ttu-id="a717b-488">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="a717b-488">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="a717b-489">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="a717b-489">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="a717b-490">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="a717b-490">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="a717b-491">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="a717b-491">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="a717b-492">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="a717b-492">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="a717b-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-493">Outlook</span></span>

-   [<span data-ttu-id="a717b-494">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="a717b-494">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="a717b-495">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="a717b-495">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="a717b-496">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="a717b-496">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="a717b-497">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-497">Word</span></span>

-   [<span data-ttu-id="a717b-498">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="a717b-498">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="a717b-499">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="a717b-499">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="a717b-500">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-500">Office Suite</span></span>

-   [<span data-ttu-id="a717b-501">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="a717b-501">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="a717b-502">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a717b-502">July 09, 2019</span></span>
<span data-ttu-id="a717b-503">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="a717b-503">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="a717b-504">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="a717b-504">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="a717b-505">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="a717b-505">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="a717b-506">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="a717b-506">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="a717b-507">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="a717b-507">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="a717b-508">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-508">Excel</span></span>

-   [<span data-ttu-id="a717b-509">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="a717b-509">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="a717b-510">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="a717b-510">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="a717b-511">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="a717b-511">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="a717b-512">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-512">Outlook</span></span>

-   [<span data-ttu-id="a717b-513">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="a717b-513">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="a717b-514">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="a717b-514">Skype for Business</span></span>

-   [<span data-ttu-id="a717b-515">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="a717b-515">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="a717b-516">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-516">Office Suite</span></span>

-   [<span data-ttu-id="a717b-517">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="a717b-517">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="a717b-518">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a717b-518">June 11, 2019</span></span>
<span data-ttu-id="a717b-519">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="a717b-519">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="a717b-520">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="a717b-520">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="a717b-521">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="a717b-521">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="a717b-522">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="a717b-522">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="a717b-523">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-523">Word</span></span>

-   [<span data-ttu-id="a717b-524">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="a717b-524">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="a717b-525">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="a717b-525">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="a717b-526">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a717b-526">May 14, 2019</span></span>
<span data-ttu-id="a717b-527">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="a717b-527">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="a717b-528">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="a717b-528">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="a717b-529">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="a717b-529">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="a717b-530">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="a717b-530">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="a717b-531">Word</span><span class="sxs-lookup"><span data-stu-id="a717b-531">Word</span></span>

-   [<span data-ttu-id="a717b-532">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="a717b-532">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="a717b-533">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-533">Office Suite</span></span>

-   [<span data-ttu-id="a717b-534">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="a717b-534">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="a717b-535">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="a717b-535">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="a717b-536">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a717b-536">April 09, 2019</span></span>
<span data-ttu-id="a717b-537">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="a717b-537">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="a717b-538">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="a717b-538">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="a717b-539">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="a717b-539">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="a717b-540">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="a717b-540">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-541">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-541">Excel</span></span>

-   [<span data-ttu-id="a717b-542">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="a717b-542">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="a717b-543">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-543">Office Suite</span></span>

-   [<span data-ttu-id="a717b-544">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="a717b-544">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="a717b-545">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="a717b-545">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="a717b-546">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="a717b-546">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="a717b-547">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="a717b-547">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="a717b-548">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="a717b-548">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="a717b-549">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="a717b-549">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="a717b-550">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a717b-550">March 12, 2019</span></span>
<span data-ttu-id="a717b-551">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="a717b-551">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="a717b-552">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a717b-552">February 12, 2019</span></span>
<span data-ttu-id="a717b-553">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="a717b-553">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="a717b-554">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="a717b-554">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="a717b-555">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="a717b-555">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="a717b-556">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="a717b-556">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="a717b-557">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="a717b-557">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="a717b-558">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-558">Excel</span></span>

-   [<span data-ttu-id="a717b-559">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="a717b-559">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="a717b-560">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a717b-560">Office suite</span></span>

-   [<span data-ttu-id="a717b-561">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="a717b-561">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="a717b-562">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="a717b-562">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="a717b-563">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="a717b-563">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="a717b-564">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="a717b-564">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="a717b-565">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="a717b-565">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="a717b-566">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="a717b-566">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="a717b-567">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a717b-567">January 8, 2019</span></span>

<span data-ttu-id="a717b-568">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="a717b-568">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="a717b-569">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="a717b-569">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="a717b-570">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="a717b-570">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="a717b-571">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="a717b-571">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="a717b-572">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="a717b-572">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="a717b-573">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-573">Outlook</span></span>
-   [<span data-ttu-id="a717b-574">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="a717b-574">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="a717b-575">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a717b-575">Word: Security updates</span></span> 
-   [<span data-ttu-id="a717b-576">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="a717b-576">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="a717b-577">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="a717b-577">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="a717b-578">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a717b-578">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="a717b-579">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="a717b-579">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="a717b-580">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="a717b-580">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="a717b-581">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a717b-581">December 11, 2018</span></span>
<span data-ttu-id="a717b-582">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="a717b-582">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="a717b-583">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="a717b-583">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="a717b-584">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="a717b-584">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-585">Excel</span><span class="sxs-lookup"><span data-stu-id="a717b-585">Excel</span></span>

-   [<span data-ttu-id="a717b-586">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="a717b-586">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="a717b-587">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="a717b-587">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="a717b-588">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="a717b-588">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="a717b-589">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="a717b-589">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="a717b-590">Outlook</span><span class="sxs-lookup"><span data-stu-id="a717b-590">Outlook</span></span>

-   [<span data-ttu-id="a717b-591">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="a717b-591">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="a717b-592">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a717b-592">PowerPoint</span></span>

-   [<span data-ttu-id="a717b-593">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="a717b-593">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="a717b-594">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a717b-594">November 13, 2018</span></span>
<span data-ttu-id="a717b-595">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="a717b-595">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="a717b-596">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="a717b-596">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="a717b-597">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="a717b-597">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="a717b-598">Excel:</span><span class="sxs-lookup"><span data-stu-id="a717b-598">Excel:</span></span>

-   [<span data-ttu-id="a717b-599">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="a717b-599">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="a717b-600">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="a717b-600">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="a717b-601">Outlook:</span><span class="sxs-lookup"><span data-stu-id="a717b-601">Outlook:</span></span>

-   [<span data-ttu-id="a717b-602">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="a717b-602">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="a717b-603">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="a717b-603">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="a717b-604">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="a717b-604">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="a717b-605">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="a717b-605">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="a717b-606">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="a717b-606">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="a717b-607">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="a717b-607">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="a717b-608">Project:</span><span class="sxs-lookup"><span data-stu-id="a717b-608">Project:</span></span>

-   [<span data-ttu-id="a717b-609">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="a717b-609">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="a717b-610">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="a717b-610">Skype for Business:</span></span>

-   [<span data-ttu-id="a717b-611">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="a717b-611">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="a717b-612">Word:</span><span class="sxs-lookup"><span data-stu-id="a717b-612">Word:</span></span>

-   [<span data-ttu-id="a717b-613">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="a717b-613">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573)