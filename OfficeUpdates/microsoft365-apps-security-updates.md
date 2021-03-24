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
ms.openlocfilehash: 94ea715c72eaab05a86a6c23fd3db0bca4f052f6
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169866"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="8d9ae-103">Microsoft Office セキュリティ更新プログラムのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="8d9ae-104">このリリース ノートには、Microsoft Officeの更新プログラムに含まれているセキュリティ修正プログラムに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="8d9ae-105">この情報は、エンタープライズ用Microsoft 365 アプリ、ビジネス用Microsoft 365アプリ、Office 2016 リテール (C2R)およびOffice 2019に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="8d9ae-106">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="8d9ae-107">詳細については、[こちらの記事](/DeployOffice/update-channels-changes)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-107">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>
> - <span data-ttu-id="8d9ae-108">バージョン 2004 以降の Office 365 ProPlus は Microsoft 365 Apps for enterprise に名前が変更されています。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span> <span data-ttu-id="8d9ae-109">詳細については、[こちらの記事](/deployoffice/name-change)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-109">To learn more, [read this article](/deployoffice/name-change).</span></span> <span data-ttu-id="8d9ae-110">Microsoft のドキュメントでは通常、Microsoft 365 Apps として扱います。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-110">In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (上の行は間隔を空けるために使用されているので、削除しないでください。)  

## <a name="march-09-2021"></a><span data-ttu-id="8d9ae-112">2021 年 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-112">March 09, 2021</span></span>
<span data-ttu-id="8d9ae-113">最新チャネル: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-113">Current Channel: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="8d9ae-114">月次エンタープライズ チャネル: バージョン 2101 (ビルド 13628.20528)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-114">Monthly Enterprise Channel: Version 2101 (Build 13628.20528)</span></span>  
<span data-ttu-id="8d9ae-115">月次エンタープライズ チャネル: バージョン 2012 (ビルド 13530.20628)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-115">Monthly Enterprise Channel: Version 2012 (Build 13530.20628)</span></span>  
<span data-ttu-id="8d9ae-116">半期エンタープライズ チャネル (プレビュー): バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-116">Semi-Annual Enterprise Channel (Preview): Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="8d9ae-117">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21348)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-117">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21348)</span></span>  
<span data-ttu-id="8d9ae-118">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-118">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="8d9ae-119">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="8d9ae-120">Office 2019 リテール版: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-120">Office 2019 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="8d9ae-121">Office 2016 リテール版: バージョン 2102 (ビルド 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-121">Office 2016 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="8d9ae-122">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10372.20060)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-122">Office 2019 Volume Licensed: Version 1808 (Build 10372.20060)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-124">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-124">Excel</span></span>

-   [<span data-ttu-id="8d9ae-125">CVE-2021-27054</span><span class="sxs-lookup"><span data-stu-id="8d9ae-125">CVE-2021-27054</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27054)
-   [<span data-ttu-id="8d9ae-126">CVE-2021-27057</span><span class="sxs-lookup"><span data-stu-id="8d9ae-126">CVE-2021-27057</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27057)
-   [<span data-ttu-id="8d9ae-127">CVE-2021-27053</span><span class="sxs-lookup"><span data-stu-id="8d9ae-127">CVE-2021-27053</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27053)

### <a name="powerpoint"></a><span data-ttu-id="8d9ae-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8d9ae-128">PowerPoint</span></span>

-   [<span data-ttu-id="8d9ae-129">CVE-2021-27056</span><span class="sxs-lookup"><span data-stu-id="8d9ae-129">CVE-2021-27056</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27056)

### <a name="visio"></a><span data-ttu-id="8d9ae-130">Visio</span><span class="sxs-lookup"><span data-stu-id="8d9ae-130">Visio</span></span>

-   [<span data-ttu-id="8d9ae-131">CVE-2021-27055</span><span class="sxs-lookup"><span data-stu-id="8d9ae-131">CVE-2021-27055</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27055)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-132">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-132">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-133">CVE-2021-27058</span><span class="sxs-lookup"><span data-stu-id="8d9ae-133">CVE-2021-27058</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-27058)
-   [<span data-ttu-id="8d9ae-134">CVE-2021-24108</span><span class="sxs-lookup"><span data-stu-id="8d9ae-134">CVE-2021-24108</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-24108)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-09-2021"></a><span data-ttu-id="8d9ae-136">2021 年 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-136">February 09, 2021</span></span>
<span data-ttu-id="8d9ae-137">現在のチャネル: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-137">Current Channel: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="8d9ae-138">月次エンタープライズ チャネル: バージョン 2012 (ビルド 13530.20528)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-138">Monthly Enterprise Channel: Version 2012 (Build 13530.20528)</span></span>  
<span data-ttu-id="8d9ae-139">月次エンタープライズ チャネル: バージョン 2011 (ビルド 13426.20658)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-139">Monthly Enterprise Channel: Version 2011 (Build 13426.20658)</span></span>  
<span data-ttu-id="8d9ae-140">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-140">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="8d9ae-141">半期エンタープライズ チャネル: バージョン 2008 (ビルド 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-141">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="8d9ae-142">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-142">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="8d9ae-143">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.21008)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-143">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.21008)</span></span>  
<span data-ttu-id="8d9ae-144">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-144">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="8d9ae-145">Office 2019 製品版: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-145">Office 2019 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="8d9ae-146">Office 2016 製品版: バージョン 2101 (ビルド 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-146">Office 2016 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="8d9ae-147">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10371.20060)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-147">Office 2019 Volume Licensed: Version 1808 (Build 10371.20060)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-149">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-149">Excel</span></span>

-   [<span data-ttu-id="8d9ae-150">CVE-2021-24069</span><span class="sxs-lookup"><span data-stu-id="8d9ae-150">CVE-2021-24069</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-24069)
-   [<span data-ttu-id="8d9ae-151">CVE-2021-24070</span><span class="sxs-lookup"><span data-stu-id="8d9ae-151">CVE-2021-24070</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-24070)
-   [<span data-ttu-id="8d9ae-152">CVE-2021-24067</span><span class="sxs-lookup"><span data-stu-id="8d9ae-152">CVE-2021-24067</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-24067)

[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="january-12-2021"></a><span data-ttu-id="8d9ae-154">2021 年 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-154">January 12, 2021</span></span>
<span data-ttu-id="8d9ae-155">現在のチャネル: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-155">Current Channel: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="8d9ae-156">月次エンタープライズ チャネル: バージョン 2011 (ビルド 13426.20526)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-156">Monthly Enterprise Channel: Version 2011 (Build 13426.20526)</span></span>  
<span data-ttu-id="8d9ae-157">月次エンタープライズ チャネル: バージョン 2010 (ビルド 13328.20550)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-157">Monthly Enterprise Channel: Version 2010 (Build 13328.20550)</span></span>  
<span data-ttu-id="8d9ae-158">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-158">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="8d9ae-159">半期エンタープライズ チャネル: バージョン 2008 (ビルド 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-159">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="8d9ae-160">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-160">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="8d9ae-161">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20994)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-161">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20994)</span></span>  
<span data-ttu-id="8d9ae-162">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-162">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="8d9ae-163">Office 2019 製品版: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-163">Office 2019 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="8d9ae-164">Office 2016 製品版: バージョン 2012 (ビルド 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-164">Office 2016 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="8d9ae-165">Office 2019 ボリューム ライセンス: バージョン 1808 (ビルド 10370.20052)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-165">Office 2019 Volume Licensed: Version 1808 (Build 10370.20052)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-167">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-167">Excel</span></span>

-   [<span data-ttu-id="8d9ae-168">CVE-2021-1714</span><span class="sxs-lookup"><span data-stu-id="8d9ae-168">CVE-2021-1714</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-1714)
-   [<span data-ttu-id="8d9ae-169">CVE-2021-1713</span><span class="sxs-lookup"><span data-stu-id="8d9ae-169">CVE-2021-1713</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-1713)

### <a name="word"></a><span data-ttu-id="8d9ae-170">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-170">Word</span></span>

-   [<span data-ttu-id="8d9ae-171">CVE-2021-1715</span><span class="sxs-lookup"><span data-stu-id="8d9ae-171">CVE-2021-1715</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-1715)
-   [<span data-ttu-id="8d9ae-172">CVE-2021-1716</span><span class="sxs-lookup"><span data-stu-id="8d9ae-172">CVE-2021-1716</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-1716)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-173">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-173">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-174">CVE-2021-1711</span><span class="sxs-lookup"><span data-stu-id="8d9ae-174">CVE-2021-1711</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2021-1711)


[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="december-08-2020"></a><span data-ttu-id="8d9ae-176">2020 年12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-176">December 08, 2020</span></span>
<span data-ttu-id="8d9ae-177">最新チャネル: バージョン2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-177">Current Channel: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="8d9ae-178">月次エンタープライズチャネル: バージョン 2010 (ビルド 13328.20478)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-178">Monthly Enterprise Channel: Version 2010 (Build 13328.20478)</span></span>  
<span data-ttu-id="8d9ae-179">月次エンタープライズチャネル: バージョン 2009 (ビルド 13231.20620)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-179">Monthly Enterprise Channel: Version 2009 (Build 13231.20620)</span></span>  
<span data-ttu-id="8d9ae-180">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20910)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-180">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20910)</span></span>  
<span data-ttu-id="8d9ae-181">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-181">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="8d9ae-182">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20984)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-182">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20984)</span></span>  
<span data-ttu-id="8d9ae-183">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-183">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="8d9ae-184">Office 2019 リテール版: バージョン 2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-184">Office 2019 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="8d9ae-185">Office 2016 リテール版: バージョン 2011 (ビルド 13426.20332)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-185">Office 2016 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="8d9ae-186">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10369.20032)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-186">Office 2019 Volume Licensed: Version 1808 (Build 10369.20032)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-188">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-188">Excel</span></span>

-   [<span data-ttu-id="8d9ae-189">CVE-2020-17123</span><span class="sxs-lookup"><span data-stu-id="8d9ae-189">CVE-2020-17123</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17123)
-   [<span data-ttu-id="8d9ae-190">CVE-2020-17125</span><span class="sxs-lookup"><span data-stu-id="8d9ae-190">CVE-2020-17125</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17125)
-   [<span data-ttu-id="8d9ae-191">CVE-2020-17126</span><span class="sxs-lookup"><span data-stu-id="8d9ae-191">CVE-2020-17126</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17126)
-   [<span data-ttu-id="8d9ae-192">CVE-2020-17128</span><span class="sxs-lookup"><span data-stu-id="8d9ae-192">CVE-2020-17128</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17128)
-   [<span data-ttu-id="8d9ae-193">CVE-2020-17129</span><span class="sxs-lookup"><span data-stu-id="8d9ae-193">CVE-2020-17129</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17129)
-   [<span data-ttu-id="8d9ae-194">CVE-2020-17130</span><span class="sxs-lookup"><span data-stu-id="8d9ae-194">CVE-2020-17130</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17130)

### <a name="outlook"></a><span data-ttu-id="8d9ae-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-195">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-196">CVE-2020-17119</span><span class="sxs-lookup"><span data-stu-id="8d9ae-196">CVE-2020-17119</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17119)

### <a name="powerpoint"></a><span data-ttu-id="8d9ae-197">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8d9ae-197">PowerPoint</span></span>

-   [<span data-ttu-id="8d9ae-198">CVE-2020-17124</span><span class="sxs-lookup"><span data-stu-id="8d9ae-198">CVE-2020-17124</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17124)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="november-10-2020"></a><span data-ttu-id="8d9ae-200">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-200">November 10, 2020</span></span>
<span data-ttu-id="8d9ae-201">現在のチャネル: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-201">Current Channel: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="8d9ae-202">月次エンタープライズ チャネル: バージョン 2009 (Build 13231.20514)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-202">Monthly Enterprise Channel: Version 2009 (Build 13231.20514)</span></span>  
<span data-ttu-id="8d9ae-203">月次エンタープライズ チャネル: バージョン 2008 (Build 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-203">Monthly Enterprise Channel: Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="8d9ae-204">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-204">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="8d9ae-205">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-205">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="8d9ae-206">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20974)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-206">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20974)</span></span>  
<span data-ttu-id="8d9ae-207">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-207">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="8d9ae-208">Office 2019 製品版: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-208">Office 2019 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="8d9ae-209">Office 2016 製品版: バージョン 2010 (ビルド 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-209">Office 2016 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="8d9ae-210">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10368.20035)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-210">Office 2019 Volume Licensed: Version 1808 (Build 10368.20035)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="excel"></a><span data-ttu-id="8d9ae-212">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-212">Excel</span></span>

-   [<span data-ttu-id="8d9ae-213">CVE-2020-17064</span><span class="sxs-lookup"><span data-stu-id="8d9ae-213">CVE-2020-17064</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17064)
-   [<span data-ttu-id="8d9ae-214">CVE-2020-17065</span><span class="sxs-lookup"><span data-stu-id="8d9ae-214">CVE-2020-17065</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17065)
-   [<span data-ttu-id="8d9ae-215">CVE-2020-17067</span><span class="sxs-lookup"><span data-stu-id="8d9ae-215">CVE-2020-17067</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17067)

### <a name="word"></a><span data-ttu-id="8d9ae-216">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-216">Word</span></span>

-   [<span data-ttu-id="8d9ae-217">CVE-2020-17020</span><span class="sxs-lookup"><span data-stu-id="8d9ae-217">CVE-2020-17020</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17020)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-218">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-218">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-219">CVE-2020-17062</span><span class="sxs-lookup"><span data-stu-id="8d9ae-219">CVE-2020-17062</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17062)
-   [<span data-ttu-id="8d9ae-220">CVE-2020-17063</span><span class="sxs-lookup"><span data-stu-id="8d9ae-220">CVE-2020-17063</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-17063)

[//]: # (セキュリティの詳細コンテンツを削除しないでください 終了)



## <a name="october-13-2020"></a><span data-ttu-id="8d9ae-222">2020 年 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-222">October 13, 2020</span></span>
<span data-ttu-id="8d9ae-223">最新チャネル: バージョン2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-223">Current Channel: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="8d9ae-224">月次エンタープライズ チャネル: バージョン 2008 (Build 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-224">Monthly Enterprise Channel: Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="8d9ae-225">月次エンタープライズ チャネル: バージョン 2007 (Build 13029.20708)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-225">Monthly Enterprise Channel: Version 2007 (Build 13029.20708)</span></span>  
<span data-ttu-id="8d9ae-226">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-226">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="8d9ae-227">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-227">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="8d9ae-228">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20966)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-228">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20966)</span></span>  
<span data-ttu-id="8d9ae-229">Windows 7 上の Microsoft 365アプリ: バージョン 2002 (ビルド 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-229">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="8d9ae-230">Office 2019 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-230">Office 2019 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="8d9ae-231">Office 2016 製品版: バージョン 2009 (ビルド 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-231">Office 2016 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="8d9ae-232">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10367.20048)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-232">Office 2019 Volume Licensed: Version 1808 (Build 10367.20048)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="8d9ae-234">Access</span><span class="sxs-lookup"><span data-stu-id="8d9ae-234">Access</span></span>

-   [<span data-ttu-id="8d9ae-235">CVE-2020-16957</span><span class="sxs-lookup"><span data-stu-id="8d9ae-235">CVE-2020-16957</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16957)

### <a name="excel"></a><span data-ttu-id="8d9ae-236">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-236">Excel</span></span>

-   [<span data-ttu-id="8d9ae-237">CVE-2020-16929</span><span class="sxs-lookup"><span data-stu-id="8d9ae-237">CVE-2020-16929</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16929)
-   [<span data-ttu-id="8d9ae-238">CVE-2020-16931</span><span class="sxs-lookup"><span data-stu-id="8d9ae-238">CVE-2020-16931</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16931)
-   [<span data-ttu-id="8d9ae-239">CVE-2020-16932</span><span class="sxs-lookup"><span data-stu-id="8d9ae-239">CVE-2020-16932</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16932)

### <a name="outlook"></a><span data-ttu-id="8d9ae-240">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-240">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-241">CVE-2020-16947</span><span class="sxs-lookup"><span data-stu-id="8d9ae-241">CVE-2020-16947</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16947)
-   [<span data-ttu-id="8d9ae-242">CVE-2020-16949</span><span class="sxs-lookup"><span data-stu-id="8d9ae-242">CVE-2020-16949</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16949)

### <a name="word"></a><span data-ttu-id="8d9ae-243">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-243">Word</span></span>

-   [<span data-ttu-id="8d9ae-244">CVE-2020-16933</span><span class="sxs-lookup"><span data-stu-id="8d9ae-244">CVE-2020-16933</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16933)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-245">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-245">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-246">CVE-2020-16930</span><span class="sxs-lookup"><span data-stu-id="8d9ae-246">CVE-2020-16930</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16930)
-   [<span data-ttu-id="8d9ae-247">CVE-2020-16955</span><span class="sxs-lookup"><span data-stu-id="8d9ae-247">CVE-2020-16955</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16955)
-   [<span data-ttu-id="8d9ae-248">CVE-2020-16928</span><span class="sxs-lookup"><span data-stu-id="8d9ae-248">CVE-2020-16928</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16928)
-   [<span data-ttu-id="8d9ae-249">CVE-2020-16934</span><span class="sxs-lookup"><span data-stu-id="8d9ae-249">CVE-2020-16934</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16934)
-   [<span data-ttu-id="8d9ae-250">CVE-2020-16918</span><span class="sxs-lookup"><span data-stu-id="8d9ae-250">CVE-2020-16918</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16918)
-   [<span data-ttu-id="8d9ae-251">CVE-2020-16954</span><span class="sxs-lookup"><span data-stu-id="8d9ae-251">CVE-2020-16954</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-16954)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="september-08-2020"></a><span data-ttu-id="8d9ae-253">2020 年 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-253">September 08, 2020</span></span>
<span data-ttu-id="8d9ae-254">最新チャネル: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-254">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="8d9ae-255">月次エンタープライズ チャネル: バージョン 2007 (ビルド 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-255">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="8d9ae-256">月次エンタープライズ チャネル: バージョン 2006 (ビルド 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-256">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="8d9ae-257">半期エンタープライズ チャネル (プレビュー): バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-257">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="8d9ae-258">半期エンタープライズ チャネル: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-258">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="8d9ae-259">半期エンタープライズ チャネル: バージョン 1908 (ビルド 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-259">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="8d9ae-260">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-260">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="8d9ae-261">Office 2019 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-261">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="8d9ae-262">Office 2016 製品版: バージョン 2008 (ビルド 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-262">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="8d9ae-263">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-263">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-265">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-265">Excel</span></span>

-   [<span data-ttu-id="8d9ae-266">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="8d9ae-266">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="8d9ae-267">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="8d9ae-267">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="8d9ae-268">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="8d9ae-268">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="8d9ae-269">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="8d9ae-269">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="8d9ae-270">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-270">Word</span></span>

-   [<span data-ttu-id="8d9ae-271">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="8d9ae-271">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="8d9ae-272">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="8d9ae-272">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="8d9ae-273">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-273">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-274">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="8d9ae-274">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1193)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="august-11-2020"></a><span data-ttu-id="8d9ae-276">2020 年 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-276">August 11, 2020</span></span>
<span data-ttu-id="8d9ae-277">最新チャネル: バージョン2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-277">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="8d9ae-278">月次エンタープライズ チャネル: バージョン2006 (ビルド 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-278">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="8d9ae-279">月次エンタープライズ チャネル: バージョン2005 (ビルド 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-279">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="8d9ae-280">半期エンタープライズ チャネル (プレビュー)： バージョン2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-280">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="8d9ae-281">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-281">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="8d9ae-282">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-282">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="8d9ae-283">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-283">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="8d9ae-284">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-284">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="8d9ae-285">Office 2019 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-285">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="8d9ae-286">Office 2016 製品版: バージョン 2007 (ビルド 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-286">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="8d9ae-287">Office 2019 ボリュームライセンス: バージョン 1808 (ビルド 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-287">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (セキュリティの詳細コンテンツの開始を削除しないでください)


### <a name="access"></a><span data-ttu-id="8d9ae-289">Access</span><span class="sxs-lookup"><span data-stu-id="8d9ae-289">Access</span></span>

-   [<span data-ttu-id="8d9ae-290">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="8d9ae-290">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="8d9ae-291">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-291">Excel</span></span>

-   [<span data-ttu-id="8d9ae-292">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="8d9ae-292">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="8d9ae-293">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="8d9ae-293">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="8d9ae-294">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="8d9ae-294">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="8d9ae-295">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="8d9ae-295">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="8d9ae-296">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="8d9ae-296">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="8d9ae-297">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-297">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-298">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="8d9ae-298">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="8d9ae-299">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="8d9ae-299">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="8d9ae-300">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-300">Word</span></span>

-   [<span data-ttu-id="8d9ae-301">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="8d9ae-301">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="8d9ae-302">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="8d9ae-302">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="8d9ae-303">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="8d9ae-303">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-304">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-304">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-305">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="8d9ae-305">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="8d9ae-306">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="8d9ae-306">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1563)

[//]: # (セキュリティの詳細コンテンツの終了を削除しないでください)



## <a name="july-14-2020"></a><span data-ttu-id="8d9ae-308">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-308">July 14, 2020</span></span>
<span data-ttu-id="8d9ae-309">最新チャネル: バージョン 2006 (ビルド 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-309">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="8d9ae-310">月次エンタープライズ チャネル: バージョン 2005 (ビルド 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-310">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="8d9ae-311">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-311">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="8d9ae-312">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-312">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="8d9ae-313">半期エンタープライズ チャネル： バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-313">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="8d9ae-314">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-314">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="8d9ae-315">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-315">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="8d9ae-316">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-316">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-318">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-318">Excel</span></span>

-   [<span data-ttu-id="8d9ae-319">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="8d9ae-319">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="8d9ae-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-320">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-321">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="8d9ae-321">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="8d9ae-322">Project</span><span class="sxs-lookup"><span data-stu-id="8d9ae-322">Project</span></span>

-   [<span data-ttu-id="8d9ae-323">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="8d9ae-323">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="8d9ae-324">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-324">Word</span></span>

-   [<span data-ttu-id="8d9ae-325">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="8d9ae-325">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="8d9ae-326">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="8d9ae-326">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="8d9ae-327">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="8d9ae-327">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="8d9ae-328">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="8d9ae-328">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-329">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-329">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-330">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="8d9ae-330">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1458)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="june-09-2020"></a><span data-ttu-id="8d9ae-332">2020 年 6 月 09 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-332">June 09, 2020</span></span>
<span data-ttu-id="8d9ae-333">最新チャネル: バージョン 2005 (ビルド 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-333">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="8d9ae-334">月次エンタープライズ チャネル: バージョン 2004 (ビルド 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-334">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="8d9ae-335">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-335">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="8d9ae-336">半期エンタープライズ チャネル (プレビュー)： バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-336">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="8d9ae-337">半期エンタープライズ チャネル： バージョン 1908 (ビルド 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-337">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="8d9ae-338">半期エンタープライズ チャネル： バージョン 1902 (ビルド 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-338">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="8d9ae-339">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-339">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-341">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-341">Excel</span></span>

-   [<span data-ttu-id="8d9ae-342">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="8d9ae-342">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="8d9ae-343">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="8d9ae-343">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="8d9ae-344">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-344">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-345">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="8d9ae-345">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="8d9ae-346">Project</span><span class="sxs-lookup"><span data-stu-id="8d9ae-346">Project</span></span>

-   [<span data-ttu-id="8d9ae-347">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="8d9ae-347">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-348">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-348">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-349">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="8d9ae-349">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1321)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="may-12-2020"></a><span data-ttu-id="8d9ae-351">2020 年 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-351">May 12, 2020</span></span>
<span data-ttu-id="8d9ae-352">月次チャネル: バージョン 2004 (ビルド 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-352">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="8d9ae-353">月次エンタープライズ チャネル: バージョン 2003 (ビルド 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-353">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="8d9ae-354">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-354">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="8d9ae-355">半期チャネル: バージョン 1908 (ビルド 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-355">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="8d9ae-356">半期チャネル: バージョン 1902 (ビルド 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-356">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="8d9ae-357">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-357">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-359">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-359">Excel</span></span>

-   [<span data-ttu-id="8d9ae-360">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="8d9ae-360">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0901)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="april-14-2020"></a><span data-ttu-id="8d9ae-362">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-362">April 14, 2020</span></span>
<span data-ttu-id="8d9ae-363">月次チャネル: バージョン 2003 (ビルド 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-363">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="8d9ae-364">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-364">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="8d9ae-365">半期チャネル: バージョン 1908 (ビルド 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-365">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="8d9ae-366">半期チャネル: バージョン 1902 (ビルド 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-366">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="8d9ae-367">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-367">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-369">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-369">Excel</span></span>

-   [<span data-ttu-id="8d9ae-370">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="8d9ae-370">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="8d9ae-371">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="8d9ae-371">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="8d9ae-372">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-372">Word</span></span>

-   [<span data-ttu-id="8d9ae-373">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="8d9ae-373">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-374">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-374">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-375">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="8d9ae-375">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="8d9ae-376">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="8d9ae-376">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="8d9ae-377">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="8d9ae-377">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0961)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="march-10-2020"></a><span data-ttu-id="8d9ae-379">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-379">March 10, 2020</span></span>
<span data-ttu-id="8d9ae-380">月次チャネル: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-380">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="8d9ae-381">半期チャネル (対象指定): バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-381">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="8d9ae-382">半期チャネル: バージョン 1908 (ビルド 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-382">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="8d9ae-383">半期チャネル: バージョン 1902 (ビルド 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-383">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="8d9ae-384">Windows 7 上の Microsoft 365 Apps: バージョン 2002 (ビルド 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-384">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)



### <a name="word"></a><span data-ttu-id="8d9ae-386">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-386">Word</span></span>

-   [<span data-ttu-id="8d9ae-387">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="8d9ae-387">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="8d9ae-388">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="8d9ae-388">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="8d9ae-389">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="8d9ae-389">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="8d9ae-390">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="8d9ae-390">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0851)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="february-11-2020"></a><span data-ttu-id="8d9ae-392">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-392">February 11, 2020</span></span>
<span data-ttu-id="8d9ae-393">月次チャネル: バージョン 2001 (ビルド 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-393">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="8d9ae-394">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-394">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="8d9ae-395">半期チャネル: バージョン 1908 (ビルド 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-395">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="8d9ae-396">半期チャネル: バージョン 1902 (ビルド 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-396">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="8d9ae-397">半期チャネル: バージョン 1808 (ビルド 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-397">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-399">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-399">Excel</span></span>

-   [<span data-ttu-id="8d9ae-400">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="8d9ae-400">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="8d9ae-401">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-401">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-402">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="8d9ae-402">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-403">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-403">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-404">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="8d9ae-404">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0697)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="january-14-2020"></a><span data-ttu-id="8d9ae-406">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-406">January 14, 2020</span></span>
<span data-ttu-id="8d9ae-407">月次チャネル: バージョン 1912 (ビルド 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-407">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="8d9ae-408">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-408">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="8d9ae-409">半期チャネル: バージョン 1908 (ビルド 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-409">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="8d9ae-410">半期チャネル: バージョン 1902 (ビルド 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-410">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="8d9ae-411">半期チャネル: バージョン 1808 (ビルド 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-411">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (セキュリティの詳細コンテンツを削除しないでください。開始)


### <a name="excel"></a><span data-ttu-id="8d9ae-413">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-413">Excel</span></span>

-   [<span data-ttu-id="8d9ae-414">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="8d9ae-414">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="8d9ae-415">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="8d9ae-415">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="8d9ae-416">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="8d9ae-416">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-417">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-417">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-418">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="8d9ae-418">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0652)

[//]: # (セキュリティの詳細コンテンツを削除しないでください。終了)



## <a name="december-10-2019"></a><span data-ttu-id="8d9ae-420">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-420">December 10, 2019</span></span>
<span data-ttu-id="8d9ae-421">月次チャネル バージョン 1911 (ビルド 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-421">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="8d9ae-422">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-422">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="8d9ae-423">半期チャネル: バージョン 1902 (ビルド 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-423">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="8d9ae-424">半期チャネル: バージョン 1808 (ビルド 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-424">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-425">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-425">Excel</span></span>

-   [<span data-ttu-id="8d9ae-426">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="8d9ae-426">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="8d9ae-427">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8d9ae-427">PowerPoint</span></span>

-   [<span data-ttu-id="8d9ae-428">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="8d9ae-428">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="8d9ae-429">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-429">Word</span></span>

-   [<span data-ttu-id="8d9ae-430">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="8d9ae-430">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-431">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-431">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-432">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="8d9ae-432">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="8d9ae-433">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="8d9ae-433">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="8d9ae-434">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-434">November 12, 2019</span></span>
<span data-ttu-id="8d9ae-435">月次チャネル: バージョン 1910 (ビルド 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-435">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="8d9ae-436">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-436">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="8d9ae-437">半期チャネル: バージョン 1902 (ビルド 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-437">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="8d9ae-438">半期チャネル: バージョン 1808 (ビルド 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-438">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-439">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-439">Excel</span></span>

-   [<span data-ttu-id="8d9ae-440">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="8d9ae-440">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="8d9ae-441">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="8d9ae-441">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-442">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-442">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-443">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="8d9ae-443">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="8d9ae-444">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="8d9ae-444">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="8d9ae-445">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-445">October 08, 2019</span></span>
<span data-ttu-id="8d9ae-446">月次チャネル: バージョン 1909 (ビルド 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-446">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="8d9ae-447">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-447">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="8d9ae-448">半期チャネル: バージョン 1902 (ビルド 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-448">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="8d9ae-449">半期チャネル: バージョン 1808 (ビルド 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-449">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-450">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-450">Excel</span></span>

-   [<span data-ttu-id="8d9ae-451">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="8d9ae-451">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="8d9ae-452">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="8d9ae-452">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="8d9ae-453">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-453">September 10, 2019</span></span>
<span data-ttu-id="8d9ae-454">月次チャネル: バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-454">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="8d9ae-455">半期チャネル (対象指定): バージョン 1908 (ビルド 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-455">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="8d9ae-456">半期チャネル: バージョン 1902 (ビルド 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-456">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="8d9ae-457">半期チャネル: バージョン 1808 (ビルド 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-457">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-458">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-458">Excel</span></span>

-   [<span data-ttu-id="8d9ae-459">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="8d9ae-459">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="8d9ae-460">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="8d9ae-460">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-461">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-461">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-462">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="8d9ae-462">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="8d9ae-463">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="8d9ae-463">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="8d9ae-464">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-464">August 13, 2019</span></span>
<span data-ttu-id="8d9ae-465">月次チャネル: バージョン 1907 (ビルド 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-465">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="8d9ae-466">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-466">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="8d9ae-467">半期チャネル: バージョン 1902 (ビルド 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-467">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="8d9ae-468">半期チャネル: バージョン 1808 (ビルド 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-468">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="8d9ae-469">半期チャネル: バージョン 1803 (ビルド 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-469">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="8d9ae-470">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-470">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-471">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="8d9ae-471">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="8d9ae-472">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="8d9ae-472">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="8d9ae-473">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="8d9ae-473">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="8d9ae-474">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-474">Word</span></span>

-   [<span data-ttu-id="8d9ae-475">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="8d9ae-475">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="8d9ae-476">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="8d9ae-476">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-477">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-477">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-478">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="8d9ae-478">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="8d9ae-479">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-479">July 09, 2019</span></span>
<span data-ttu-id="8d9ae-480">月次チャネル: バージョン 1906 (ビルド 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-480">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="8d9ae-481">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-481">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="8d9ae-482">半期チャネル: バージョン 1902 (ビルド 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-482">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="8d9ae-483">半期チャネル: バージョン 1808 (ビルド 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-483">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="8d9ae-484">半期チャネル: バージョン 1803 (ビルド 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-484">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="8d9ae-485">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-485">Excel</span></span>

-   [<span data-ttu-id="8d9ae-486">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="8d9ae-486">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="8d9ae-487">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="8d9ae-487">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="8d9ae-488">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="8d9ae-488">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="8d9ae-489">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-489">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-490">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="8d9ae-490">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="8d9ae-491">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="8d9ae-491">Skype for Business</span></span>

-   [<span data-ttu-id="8d9ae-492">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="8d9ae-492">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-493">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-493">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-494">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="8d9ae-494">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="8d9ae-495">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-495">June 11, 2019</span></span>
<span data-ttu-id="8d9ae-496">月次チャネル: バージョン 1905 (ビルド 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-496">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="8d9ae-497">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-497">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="8d9ae-498">半期チャネル: バージョン 1808 (ビルド 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-498">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="8d9ae-499">半期チャネル: バージョン 1803 (ビルド 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-499">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="8d9ae-500">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-500">Word</span></span>

-   [<span data-ttu-id="8d9ae-501">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="8d9ae-501">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="8d9ae-502">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="8d9ae-502">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="8d9ae-503">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-503">May 14, 2019</span></span>
<span data-ttu-id="8d9ae-504">月次チャネル: バージョン 1904 (ビルド 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-504">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="8d9ae-505">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-505">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="8d9ae-506">半期チャネル: バージョン 1808 (ビルド 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-506">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="8d9ae-507">半期チャネル: バージョン 1803 (ビルド 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-507">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="8d9ae-508">Word</span><span class="sxs-lookup"><span data-stu-id="8d9ae-508">Word</span></span>

-   [<span data-ttu-id="8d9ae-509">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="8d9ae-509">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-510">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-510">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-511">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="8d9ae-511">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="8d9ae-512">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="8d9ae-512">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="8d9ae-513">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-513">April 09, 2019</span></span>
<span data-ttu-id="8d9ae-514">月次チャネル: バージョン 1903 (ビルド 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-514">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="8d9ae-515">半期チャネル (対象指定): バージョン 1902 (ビルド 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-515">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="8d9ae-516">半期チャネル: バージョン 1808 (ビルド 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-516">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="8d9ae-517">半期チャネル: バージョン 1803 (ビルド 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-517">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-518">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-518">Excel</span></span>

-   [<span data-ttu-id="8d9ae-519">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="8d9ae-519">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-520">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-520">Office Suite</span></span>

-   [<span data-ttu-id="8d9ae-521">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="8d9ae-521">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="8d9ae-522">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="8d9ae-522">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="8d9ae-523">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="8d9ae-523">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="8d9ae-524">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="8d9ae-524">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="8d9ae-525">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="8d9ae-525">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="8d9ae-526">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="8d9ae-526">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="8d9ae-527">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-527">March 12, 2019</span></span>
<span data-ttu-id="8d9ae-528">任意のチャネルのセキュリティ更新プログラム今月はありません。</span><span class="sxs-lookup"><span data-stu-id="8d9ae-528">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="8d9ae-529">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-529">February 12, 2019</span></span>
<span data-ttu-id="8d9ae-530">月次チャネル: バージョン 1901 (ビルド 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-530">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="8d9ae-531">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-531">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="8d9ae-532">半期チャネル: バージョン 1808 (ビルド 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-532">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="8d9ae-533">半期チャネル: バージョン 1803 (ビルド 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-533">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="8d9ae-534">半期チャネル: バージョン 1708 (ビルド 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-534">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="8d9ae-535">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-535">Excel</span></span>

-   [<span data-ttu-id="8d9ae-536">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="8d9ae-536">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="8d9ae-537">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8d9ae-537">Office suite</span></span>

-   [<span data-ttu-id="8d9ae-538">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="8d9ae-538">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="8d9ae-539">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="8d9ae-539">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="8d9ae-540">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="8d9ae-540">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="8d9ae-541">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="8d9ae-541">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="8d9ae-542">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="8d9ae-542">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="8d9ae-543">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="8d9ae-543">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="8d9ae-544">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-544">January 8, 2019</span></span>

<span data-ttu-id="8d9ae-545">月次チャネル: バージョン 1812 (ビルド 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-545">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="8d9ae-546">半期対象指定チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-546">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="8d9ae-547">半期チャネル: バージョン 1808 (ビルド 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-547">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="8d9ae-548">半期チャネル: バージョン 1803 (ビルド 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-548">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="8d9ae-549">半期チャネル: バージョン 1708 (ビルド 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-549">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="8d9ae-550">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-550">Outlook</span></span>
-   [<span data-ttu-id="8d9ae-551">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="8d9ae-551">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="8d9ae-552">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8d9ae-552">Word: Security updates</span></span> 
-   [<span data-ttu-id="8d9ae-553">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="8d9ae-553">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="8d9ae-554">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="8d9ae-554">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="8d9ae-555">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8d9ae-555">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="8d9ae-556">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="8d9ae-556">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="8d9ae-557">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="8d9ae-557">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="8d9ae-558">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-558">December 11, 2018</span></span>
<span data-ttu-id="8d9ae-559">月次チャネル: バージョン 1811 (ビルド 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-559">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="8d9ae-560">半期チャネル: バージョン 1803 (ビルド 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-560">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="8d9ae-561">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-561">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-562">Excel</span><span class="sxs-lookup"><span data-stu-id="8d9ae-562">Excel</span></span>

-   [<span data-ttu-id="8d9ae-563">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="8d9ae-563">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="8d9ae-564">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="8d9ae-564">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="8d9ae-565">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="8d9ae-565">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="8d9ae-566">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="8d9ae-566">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="8d9ae-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="8d9ae-567">Outlook</span></span>

-   [<span data-ttu-id="8d9ae-568">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="8d9ae-568">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="8d9ae-569">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8d9ae-569">PowerPoint</span></span>

-   [<span data-ttu-id="8d9ae-570">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="8d9ae-570">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="8d9ae-571">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8d9ae-571">November 13, 2018</span></span>
<span data-ttu-id="8d9ae-572">月次チャネル: バージョン 1810 (ビルド 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-572">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="8d9ae-573">半期チャネル: バージョン 1803 (ビルド 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-573">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="8d9ae-574">半期チャネル (対象指定): バージョン 1808 (ビルド 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="8d9ae-574">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="8d9ae-575">Excel:</span><span class="sxs-lookup"><span data-stu-id="8d9ae-575">Excel:</span></span>

-   [<span data-ttu-id="8d9ae-576">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="8d9ae-576">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="8d9ae-577">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="8d9ae-577">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="8d9ae-578">Outlook:</span><span class="sxs-lookup"><span data-stu-id="8d9ae-578">Outlook:</span></span>

-   [<span data-ttu-id="8d9ae-579">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="8d9ae-579">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="8d9ae-580">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="8d9ae-580">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="8d9ae-581">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="8d9ae-581">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="8d9ae-582">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="8d9ae-582">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="8d9ae-583">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="8d9ae-583">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="8d9ae-584">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="8d9ae-584">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="8d9ae-585">Project:</span><span class="sxs-lookup"><span data-stu-id="8d9ae-585">Project:</span></span>

-   [<span data-ttu-id="8d9ae-586">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="8d9ae-586">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="8d9ae-587">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="8d9ae-587">Skype for Business:</span></span>

-   [<span data-ttu-id="8d9ae-588">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="8d9ae-588">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="8d9ae-589">Word:</span><span class="sxs-lookup"><span data-stu-id="8d9ae-589">Word:</span></span>

-   [<span data-ttu-id="8d9ae-590">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="8d9ae-590">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)