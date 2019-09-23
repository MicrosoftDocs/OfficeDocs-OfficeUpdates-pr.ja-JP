---
title: Office 365 ProPlus の既知の問題
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus の既知の問題に関する情報を提供します。
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068058"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="6f1e4-103">Office 365 ProPlus の既知の問題</span><span class="sxs-lookup"><span data-stu-id="6f1e4-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="6f1e4-104">これらの既知の問題では、月次チャネルに含まれているセキュリティ以外の更新プログラム、2019 年の Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアントおよび Office 365 Business に対する SACT および SAC の更新プログラムに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="6f1e4-105">次のテーブルでは、現在未解決の問題の概要と解決済みの問題を説明します。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="6f1e4-106">現在調査中の重要な問題に関する以下のテーブルは更新されます。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="6f1e4-107">この一覧は包括的ではありません。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="6f1e4-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="6f1e4-108">September 10, 2019</span></span>

|<span data-ttu-id="6f1e4-109">概要</span><span class="sxs-lookup"><span data-stu-id="6f1e4-109">Summary</span></span>|<span data-ttu-id="6f1e4-110">Investigating</span><span class="sxs-lookup"><span data-stu-id="6f1e4-110">Investigating</span></span>|<span data-ttu-id="6f1e4-111">Resolved</span><span class="sxs-lookup"><span data-stu-id="6f1e4-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="6f1e4-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="6f1e4-112">**Outlook**</span></span>
<span data-ttu-id="6f1e4-113">WebDAV の場所にファイルを保存できなくなるという問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="6f1e4-114">月次バージョン 1909</span><span class="sxs-lookup"><span data-stu-id="6f1e4-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="6f1e4-115">**プロジェクト**</span><span class="sxs-lookup"><span data-stu-id="6f1e4-115">**Project**</span></span>
<span data-ttu-id="6f1e4-116">次のシナリオについて考えます。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-116">Consider the following scenario.</span></span> <span data-ttu-id="6f1e4-117">プロジェクトを開きます。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-117">You open a project.</span></span> <span data-ttu-id="6f1e4-118">[ファイル] メニューをクリックして、[エクスポート] をクリックし、[PDF/XPS の作成] ボタンをクリックします。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="6f1e4-119">[参照] ダイアログ ボックス内で、ファイル名を入力して [OK] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="6f1e4-120">この場合、XPS ファイルの PDF は作成されていません。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="6f1e4-121">SAC バージョン 1902</span><span class="sxs-lookup"><span data-stu-id="6f1e4-121">SAC Version 1902</span></span>||
|<span data-ttu-id="6f1e4-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="6f1e4-122">**Word**</span></span>
<span data-ttu-id="6f1e4-123">ユーザーがファイルを開くときに発生する可能性のある問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="6f1e4-124">月次バージョン 1908</span><span class="sxs-lookup"><span data-stu-id="6f1e4-124">Monthly Version 1908</span></span>||
<span data-ttu-id="6f1e4-125">OneDrive 同期エンジンによって同期されている Office ファイルの場合は、[保存] および [名前を付けて保存] をするにあたり、プロパティの要求およびコンテンツ タイプの要件などのドキュメントのメタデータが検証されることはありません。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="6f1e4-126">SAC バージョン 1902</span><span class="sxs-lookup"><span data-stu-id="6f1e4-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="6f1e4-127">2019 年 5 月 - サンプル</span><span class="sxs-lookup"><span data-stu-id="6f1e4-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="6f1e4-128">概要</span><span class="sxs-lookup"><span data-stu-id="6f1e4-128">Summary</span></span>|<span data-ttu-id="6f1e4-129">Investigating</span><span class="sxs-lookup"><span data-stu-id="6f1e4-129">Investigating</span></span>|<span data-ttu-id="6f1e4-130">Resolved</span><span class="sxs-lookup"><span data-stu-id="6f1e4-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="6f1e4-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="6f1e4-131">**Excel**</span></span>
<span data-ttu-id="6f1e4-132">複数のビルドで解決されたサンプル -- セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなってしまう問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="6f1e4-133">SAC バージョン 1902</span><span class="sxs-lookup"><span data-stu-id="6f1e4-133">SAC Version 1902</span></span> <br> <span data-ttu-id="6f1e4-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="6f1e4-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="6f1e4-135">月次バージョン1905</span><span class="sxs-lookup"><span data-stu-id="6f1e4-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="6f1e4-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="6f1e4-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="6f1e4-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="6f1e4-137">**Word**</span></span>
<span data-ttu-id="6f1e4-138">複数のビルドで解決されたサンプル (すべてではない) -- ドキュメント プロパティのクイック パーツを有効にするときのパフォーマンスの問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="6f1e4-139">SAC バージョン 1808</span><span class="sxs-lookup"><span data-stu-id="6f1e4-139">SAC Version 1808</span></span>|<span data-ttu-id="6f1e4-140">SAC バージョン 1902</span><span class="sxs-lookup"><span data-stu-id="6f1e4-140">SAC Version 1902</span></span> <br> <span data-ttu-id="6f1e4-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="6f1e4-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="6f1e4-142">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="6f1e4-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
